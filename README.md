# C06_DewanshWarjurkar_assignment3

# Flask & Django with Docker Compose

## Overview
This project demonstrates how to create and containerize web applications using Flask and Django, managed with Docker Compose.

## Flask Application
- A simple Flask web application with:
  - A homepage displaying "Hello, World!"
  - A form to accept a user's name and age, returning a greeting message
  - Basic error handling for invalid inputs

## Django Application
- A basic Django project with:
  - A homepage displaying a list of items stored in a database
  - An admin panel to add and modify items
  - A form on the homepage to add a new item

## Setup & Run
### Prerequisites
- Install Docker
- Install Docker Compose

### Running with Docker Compose
1. Clone the repository:
   git clone https://github.com/SRCEM-AIML/C06_DewanshWarjurkar_assignment3.git
   cd C06_DewanshWarjurkar_assignment3
2. Build and start the containers:
   docker-compose up --build
3. Access the applications:
   - Flask app: http://localhost:5000
   - Django app: http://localhost:8000

### Running Containers Individually
#### Flask
1. Build the Flask image:
   docker build -t flask_app ./flask_app
2. Run the Flask container:
   docker run -p 5000:5000 flask_app

#### Django
1. Build the Django image:
   docker build -t django_app ./django_app
2. Run the Django container:
   docker run -p 8000:8000 django_app

## Docker Hub & GitHub
- **GitHub Repository:** [GitHub Repo](https://github.com/SRCEM-AIML/C06_DewanshWarjurkar_assignment3.git)
- **Docker Hub:**
  - [Django App](https://hub.docker.com/repository/docker/dewanshhh24/django_app/general)
  - [Flask App](https://hub.docker.com/repository/docker/dewanshhh24/flask_app/general)



