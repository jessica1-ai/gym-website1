# Gym Website Project

This is a basic multi-page website for a gym developed using Flask, as part of the *Introduction to Computing (SE-105L)* course project.

## Project Structure

```
gym_website/
├── app.py
├── templates/
│   ├── base.html
│   ├── home.html
│   ├── about.html
│   └── membership.html
└── static/
    └── style.css
```

## Features

- Multi-page navigation (Home, About, Membership)
- Basic HTML templating using Flask and Jinja2
- Static styling with CSS

## How to Run Locally

1. Make sure you have Python installed (preferably Python 3.8 or later).
2. Install Flask:
   ```bash
   pip install flask
   ```
3. Navigate to the project directory and run the application:
   ```bash
   python app.py
   ```
4. Open your browser and go to `http://127.0.0.1:5000/` to view the site.

## Notes

This project is a basic implementation and does not use any databases or file handling. It demonstrates the use of Flask routing, templates, and static files.


