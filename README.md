# Complete Django App with Heroku Deployment

🚀 Welcome to the Complete Django App with Heroku Deployment repository! This repository contains a fully functional Django web application along with instructions for setting up the project and deploying it to Heroku.

## Project Overview

This Django app is equipped with multiple ORM calls and provides a set of APIs. The app comes with a Postman collection for testing the APIs. Whether you're a developer looking to explore Django or someone interested in deploying a Django project on Heroku, this repository has got you covered!

## Setup Instructions

Follow these steps to set up the Django project:

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   ```

2. **Install Dependencies:**
   Navigate to the project directory and install dependencies from `requirements.txt`:
   ```bash
   cd Complete-Django-App-With-Heroku-Deployment
   pip install -r requirements.txt
   ```

3. **Run Migrations:**
   Apply database migrations to set up the initial database schema:
   ```bash
   python manage.py migrate
   ```

4. **Create Superuser:**
   Create a superuser to access the Django admin panel:
   ```bash
   python manage.py createsuperuser
   ```

5. **Run the Development Server:**
   Start the Django development server:
   ```bash
   python manage.py runserver
   ```

6. **Explore the APIs:**
   Use the provided Postman collection to test the APIs and interact with the application.

## Heroku Deployment

To deploy the Django app on Heroku, follow these additional steps:

1. **Create a Heroku Account:**
   If you haven't already, sign up for a free account on [Heroku](https://www.heroku.com/).

2. **Install Heroku CLI:**
   Install the Heroku Command Line Interface (CLI) by following the instructions on the [Heroku Dev Center](https://devcenter.heroku.com/articles/heroku-cli).

3. **Login to Heroku:**
   Log in to your Heroku account using the CLI:
   ```bash
   heroku login
   ```

4. **Initialize a Git Repository:**
   Initialize a Git repository if you haven't already:
   ```bash
   git init
   ```

5. **Create a Heroku App:**
   Create a new Heroku app:
   ```bash
   heroku create
   ```

6. **Deploy to Heroku:**
   Deploy the code to Heroku:
   ```bash
   git push heroku master
   ```

7. **Run Migrations on Heroku:**
   Run database migrations on the deployed Heroku app:
   ```bash
   heroku run python manage.py migrate
   ```

8. **Create a Superuser on Heroku:**
   Create a superuser on the deployed Heroku app:
   ```bash
   heroku run python manage.py createsuperuser
   ```

9. **Open the App:**
   Open the deployed app in your browser:
   ```bash
   heroku open
   ```

## 🎉 Happy Coding!

Congratulations! You now have a fully functional Django app deployed on Heroku. Explore the app, test the APIs, and feel free to customize it further according to your needs. Happy coding! 🚀




Common solutions:
    ALLOWED_HOSTS = ['*'] - modify this in settings.py of crud
    cf login
NT user ( not the email , just the user,)
NT password
choose the org
choose the space
cf push app name ( be in the same dir and push the app)
