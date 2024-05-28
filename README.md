Recipe Blog Website
Welcome to the Recipe Blog Website, a web application designed for food enthusiasts to share, discover, and manage their favorite recipes. This application is built using Flask, a lightweight WSGI web application framework for Python.

Table of Contents
Features
Installation
Usage
Technologies Used

Features
User Authentication: Secure registration and login functionality.
Password Encryption: Enhanced security for user passwords using bcrypt.
Email Notifications: Send confirmation and password reset emails.
Recipe Management: Create, read, update, and delete recipes.
User Profiles: Manage personalized user profiles.
Search Functionality: Efficient recipe search by name or ingredients.
Installation
To set up the project locally, follow these steps:

Prerequisites
Ensure you have the following installed:

Python 3.8 or higher
Flask and related extensions:
Flask-Mail
itsdangerous
Flask-SQLAlchemy
Flask-Bcrypt
Flask-Login
Jinja2
MarkupSafe
Steps
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/recipe-blog.git
cd recipe-blog
Create and Activate a Virtual Environment:

bash
Copy code
python3 -m venv venv
source venv/bin/activate
Install Required Packages:

bash
Copy code
pip install -r requirements.txt
Configure Environment Variables:
Create a .env file in the root directory and add the following:

plaintext
Copy code
SECRET_KEY='your_secret_key'
SQLALCHEMY_DATABASE_URI='sqlite:///site.db'
MAIL_SERVER='smtp.googlemail.com'
MAIL_PORT=587
MAIL_USE_TLS=1
MAIL_USERNAME='your_email@example.com'
MAIL_PASSWORD='your_email_password'
Run the Application:

bash
Copy code
flask run
Usage
After starting the application, it can be accessed at http://127.0.0.1:5000. The following functionalities are available:

Register an Account: Create a new user account.
Log In: Access existing user accounts.
Manage Recipes: Create, edit, view, and delete recipes.
Explore Recipes: Browse recipes shared by other users.
Search Recipes: Find recipes by name or ingredients.
Profile Management: Update user profile details.

We welcome contributions to this project. Please feel free to submit issues or pull requests. Thank you for your interest and happy coding!
