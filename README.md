# Ctruh_backend
Task Management Backend System
This is the backend system for the Task Management application. It provides the necessary API endpoints to manage tasks.

Prerequisites
Python 3.6 or higher
Django 3.0 or higher
Django REST Framework 3.12 or higher
drf-yasg 1.20 or higher (for API documentation)

Setup
1. Clone the repository to your local machine:
   git clone https://github.com/PranitaR12/Ctruh_backend.git
2. Navigate to the project directory:
   cd Ctruh_beckend
3. Create a virtual environment:
   python3 -m venv env
4. Activate the virtual environment:
   .\env\Scripts\activate
   For macOS/Linux:
   env/bin/activate
5. Install the project dependencies:
   pip install -r requirements.txt
6. Run database migrations:
   python manage.py migrate
7. (Optional) Load sample data (for testing or demonstration purposes):
   python manage.py loaddata sample_data.json
   
Configuration
1. Open the task_management/settings.py file.
2. Configure the database settings, such as the DATABASES dictionary, to match your database setup.
3. Configure any other settings specific to your deployment environment, if needed.

Run the Backend
To run the backend system, follow these steps:

Make sure the virtual environment is activated.

Start the development server:

python manage.py runserver
The backend server should now be running locally at http://localhost:8000/.

API Documentation
The API endpoints and their usage are documented using Swagger UI.

Start the development server if it's not running already:

python manage.py runserver
Access the Swagger documentation at: http://localhost:8000/swagger/

Usage
Use an HTTP client (e.g., cURL, Postman) or a front-end application to interact with the API endpoints.
Include an authentication token in the request headers for authenticated endpoints.
Testing
To run the automated tests for the backend system, use the following command:

python manage.py test

Contributing
Fork the repository.
Create a new branch for your feature/fix:
git checkout -b my-feature-branch
Commit your changes and push to the branch:
git commit -m "Add my feature"
git push origin my-feature-branch
Submit a pull request with your changes for review.
License
This project is licensed under the MIT License. See the LICENSE file for details.
