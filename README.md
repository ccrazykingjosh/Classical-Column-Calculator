# Column Dimension Calculator
A Django web app for analysing classical Greek columns. Input height, base 
diameter, taper ratio, and material to compute volume, mass, and moments of 
inertia. Columns are modelled as truncated cones using standard frustum geometry.
Defaults are sourced from the Parthenon, Athens (447 BC).

## Live Site
🔗 [ccrazykingjosh.pythonanywhere.com](https://ccrazykingjosh.pythonanywhere.com/)

## Features
- Compute volume, mass, and second moments of area
- Choose from Pentelic Marble, Limestone, or Granite
- Base and taper-averaged moment calculations

## Setup
1. Clone the repo
2. Install dependencies: `pip install django`
3. Make the migrations `python manage.py makemigrations`
4. Run migrations: `python manage.py migrate`
5. Start the server: `python manage.py runserver`
6. Visit `http://127.0.0.1:8000`

## Tech Stack
Python · Django · HTML/CSS/JS
