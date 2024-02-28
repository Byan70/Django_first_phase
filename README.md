# Django Project Starter

Welcome to your Django project! This repository contains the code for your web application built using Django.

![](https://i.morioh.com/200618/ffcb5207.jpg)

## Getting Started

1. **Prerequisites**:
   - Make sure you have **Python** installed (preferably version 3.6 or higher).
   - Install **Django** by running: `pip install django`.

2. **Clone the Repository**:
   - Clone this repository to your local machine:
     ```
     git clone https://github.com/Byan70/Django_first_phase.git
     ```

3. **Setup Virtual Environment** (optional but recommended):
   - Create a virtual environment to isolate your project dependencies:
     ```
     python -m venv venv
     source venv/bin/activate  # On Windows: venv\Scripts\activate
     ```

4. **Install Dependencies**:
   - Install the required packages listed in `requirements.txt`:
     ```
     pip install -r requirements.txt
     ```

5. **Run Migrations**:
   - Apply database migrations:
     ```
     python manage.py migrate
     ```

6. **Create a Superuser**:
   - Create an admin user to access the Django admin panel:
     ```
     python manage.py createsuperuser
     ```

7. **Run the Development Server**:
   - Start the development server:
     ```
     python manage.py runserver
     ```

8. **Access the Application**:
   - Open your web browser and visit: `http://127.0.0.1:8000/`
   - Log in to the admin panel at: `http://127.0.0.1:8000/admin/`

## Project Structure

- Describe the structure of your project here (e.g., apps, templates, static files).

## Key Concepts Covered

- **Django Setup**: Installation and project creation.
- **Django First Project**: Basic project setup.
- **Django Template Language (DTL)**: Creating dynamic HTML templates.
- **Adding Two Numbers in Django**: Implementing a simple view.
- **GET vs. POST**: Understanding HTTP methods.
- **Model-View-Template (MVT)**: Django's architecture.
- **Static Files in Django**: Serving CSS, JavaScript, and images.
- **Passing Dynamic Data in HTML**: Using context variables.
- **If Statements**: Conditional logic in templates.
- **Object-Relational Mapper (ORM)**: Interacting with databases.
- **PostgreSQL and PgAdmin Setup**: Configuring your database.
- **Models and Migrations**: Defining data models and applying changes.
- **Django Re-Migration**: Handling model modifications.
- **Admin Panel**: Managing data through the Django admin.
- **Adding and Fetching Data from the Database**: CRUD operations.
- **User Registration**: Implementing user sign-up.
- **Passing Messages**: Flash messages for user feedback.
- **User Login and Logout**: Authentication functionality.

## Author
**Achieng Brian**