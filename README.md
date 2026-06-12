# Tourism in SA

A responsive Django web application that showcases tourism in Saudi Arabia through city-based pages, attractions, cultural highlights, media galleries, and useful travel content.

## Live Website

[https://tourism-in-sa-production-069d.up.railway.app/](https://tourism-in-sa-production-069d.up.railway.app/)

## Overview

Tourism in SA is a Django project built to present the beauty, history, and travel appeal of Saudi Arabia in a clean and interactive way. The website focuses on major destinations such as Riyadh, Abha, Mekkah, and AlUla, with dedicated pages for each city and a consistent responsive design.

## Features

- Built with Django
- Uses templates and template inheritance
- Dynamic URLs for city pages
- Static files integration for styling and assets
- Homepage plus at least 6 pages
- Responsive layout for mobile, tablet, and desktop
- Light and dark mode support
- Uniform and coherent UI design
- City pages with attractions, brief history, events, images, and embedded media

## Pages

- Home page
- About page
- Cities listing page
- Riyadh page
- Abha page
- Mekkah page
- AlUla page

## Tech Stack

- Python
- Django
- HTML
- CSS
- Bootstrap
- JavaScript

## Project Structure

```bash
tourism-in-sa/
├── manage.py
├── project/
├── app/
├── templates/
├── static/
└── README.md
```

## Key Functionality

### Home Page
- Catchy tourism-focused hero section
- Wide featured image
- General introduction to tourism in Saudi Arabia
- Quick links to city pages

### City Pages
Each city page includes:
- A title and catchy phrase
- A short introduction
- Top attractions
- Image gallery or carousel
- Embedded video
- Brief history or timeline
- Major events

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
```

2. Move into the project folder:
```bash
cd tourism-in-sa
```

3. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate
```

On Windows:
```bash
venv\Scripts\activate
```

4. Install dependencies:
```bash
pip install -r requirements.txt
```

5. Apply migrations:
```bash
python manage.py migrate
```

6. Run the development server:
```bash
python manage.py runserver
```

7. Open in browser:
```bash
http://127.0.0.1:8000/
```

## Learning Goals

This project was built to practice:
- Django project structure
- URL routing
- Template inheritance
- Responsive frontend design
- Static file management
- Building multi-page web applications

## Notes

- Developer-focused academic project built with Django
- Designed around Saudi tourism and destination discovery
- Suitable as a portfolio project for demonstrating full-stack fundamentals

## Author

Abdulmjeed Bojeir

## License

This project is for educational and portfolio purposes.
