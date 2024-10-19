# Flask Email Sender

A simple Flask app to send emails using Google SMTP.

## Features
- Send emails via a web form
- Uses Google SMTP for email delivery
- Input validation for email fields
- 
## Technologies Used

- **Flask**: A lightweight WSGI web application framework in Python.
- **SQLite3**: A lightweight database for storing email logs (if implemented).
- **HTML/CSS**: For the frontend user interface.
- **SMTP**: For sending emails.
 
## Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/PatanThaseen/FlaskEmailSender.git
   cd FlaskEmailSender
   
## Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

## Install dependencies:
pip install -r requirements.txt

## Update email settings in config.py:
MAIL_USERNAME = 'your_email@gmail.com'
MAIL_PASSWORD = 'your_password'

## Run the app:
python app.py
Open your web browser and go to http://127.0.0.1:5000.
Fill in the form to send an email.
