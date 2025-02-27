# Flask Web Application Report

## Overview
This project implements a **Flask Web Application** with multiple routes for serving HTML pages and handling form submissions. It demonstrates basic **WSGI application structure**, **HTML rendering**, and **form handling**.

## Features
- **Homepage (`/`)**: Displays a simple welcome message.
- **Index Page (`/index`)**: Serves an `index.html` template.
- **About Page (`/about`)**: Serves an `about.html` template.
- **Form Page (`/form`)**: Handles GET and POST requests for user input.
- **Submit Page (`/submit`)**: Processes form submissions.

## Technologies Used
- **Flask**: Lightweight web framework for Python.
- **Jinja2**: Template engine for rendering HTML pages.
- **HTML & CSS**: Basic front-end structure.

## Implementation Details
- **Flask is initialized** using `Flask(__name__)`.
- **Templates (`.html` files)** are rendered using `render_template()`.
- **Form Handling**:
  - Uses `request.form[]` to retrieve submitted data.
  - Returns a response with the user's input.
- **Static Files Support**: CSS and JavaScript files are loaded using `url_for('static', filename='...')`.

## Installation & Usage
### **Setup Instructions**
1. **Install Flask**:
   ```bash
   pip install flask
   ```
2. **Run the Application**:
   ```bash
   python app.py
   ```
3. **Access the Web Pages**:
   - Open `http://127.0.0.1:5000/` in a browser.
   - Navigate to `/index`, `/about`, `/form`, and `/submit`.

## Future Enhancements
- Integrate a **database** to store form submissions.
- Implement **user authentication**.
- Deploy on a cloud platform (AWS, Heroku).

## Conclusion
This Flask application serves as a foundation for **dynamic web development**, incorporating both **backend logic** and **HTML rendering**. It can be expanded into a more complex system with additional functionalities.

