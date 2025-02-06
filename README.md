Voice-Enabled Bank Form Application


This is a web application that enables users to fill out a bank form using voice input while providing secure user authentication. The application is built with Flask and utilizes Supabase as the backend for data storage.

📁 Project Structure

FORM/
├── .venv/                     # Virtual environment (recommended)
├── .vscode/                   # VS Code configurations
├── flask_session/             # Created through flask-session library
├── static/                    # Static files
│   ├── auth_script.js         # Authentication-related JS
│   ├── bank_script.js         # Bank form handling JS
│   └── bank_style.css         # Stylesheet for bank form
├── templates/                 # HTML templates
│   ├── auth_form.html         # User authentication page
│   └── bank_form.html         # Bank form page
├── .env                       # Environment variables (keep this secret)
├── .env.example               # Example .env file
├── app.log                    # Application logs
├── app.py                     # Main Flask application
├── README.md                  # Documentation
└── requirements.txt            # Python dependencies

🛠 Local Setup Guide

Follow these instructions to set up and run the application on your local machine.

Prerequisites

Ensure you have the following installed:

Python 3.6+ – Download from here

pip – Comes pre-installed with Python

Git – Download from here

🚀 Installation Steps

1️⃣ Clone the Repository

git clone <repository_url>
cd <project_directory>

Replace <repository_url> with the URL of your repository and <project_directory> with your project's name.

2️⃣ Set Up a Virtual Environment (Recommended)

# On macOS/Linux
python3 -m venv venv
source venv/bin/activate

# On Windows
python -m venv venv
venv\Scripts\activate

3️⃣ Install Dependencies

pip install -r requirements.txt

Additionally, install the required libraries if needed:

pip install python-dotenv bcrypt requests flask-session flask

4️⃣ Create a .env File

Create a .env file in your project’s root directory.

Add the following variables:

SECRET_KEY=<your_secret_key>
SUPABASE_URL=<your_supabase_url>
SUPABASE_KEY=<your_supabase_api_key>

Replace <your_secret_key> with a long, random string.

Replace <your_supabase_url> and <your_supabase_api_key> with your Supabase project credentials.

5️⃣ Run the Application

python app.py

The application will start on http://127.0.0.1:5000/.

6️⃣ Open in Your Browser

Go to http://127.0.0.1:5000/ to access the application.

7️⃣ Sign Up & Use the Form

Sign up with a valid email address (e.g., Gmail, Yahoo, Outlook, Hotmail, AOL, iCloud).

Log in using the same credentials.

Fill in the bank form using voice input and submit the data to the database.

📝 Notes

Ensure the .env file is added to .gitignore to prevent pushing sensitive data.

If you face any issues, ensure that Supabase is properly set up and the database tables match the required schema.

📌 Dependencies

The required dependencies are listed in the requirements.txt file. Install them using:

pip install -r requirements.txt

🏗 Supabase Setup

This application uses Supabase as the backend for storing user authentication and bank form data. Ensure that:

You have a Supabase account and project set up.

Your Supabase database has the required table structures as per the transform_payload function in app.py.

📌 Contribution Guidelines

Fork the repository and create a new branch.

Make your changes and commit them.

Push your changes to your fork.

Submit a pull request for review.

📞 Support

For any issues, feel free to raise an issue in the repository or contact the project maintainer.

GitHub Repository: Beyond-QWERTY__Form-Filling-Vernacular-Voyage-with-Voice-Versatility

Enjoy using the Voice-Enabled Bank Form Application! 🎙️💻

