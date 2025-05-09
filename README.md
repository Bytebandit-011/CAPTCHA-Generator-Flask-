<h1>Flask CAPTCHA Authentication </h1>

Overview:
This application demonstrates a simple implementation of CAPTCHA validation using Flask and Flask-Session-CAPTCHA. It provides a secure way to verify that form submissions are made by humans rather than automated bots, helping to protect your web applications from spam and abuse.

Features:
1)Clean, modern UI with responsive design
2)Server-side session management for enhanced security
3)Customizable CAPTCHA settings (length, dimensions)
4)Easy to integrate into existing Flask application

The application follows this workflow:

Configuration: Sets up Flask app, configures CAPTCHA parameters and session management
Request Handling:

GET requests: Generates and displays a new CAPTCHA challenge
POST requests: Validates submitted CAPTCHA against the stored value


Response: Renders the form with appropriate feedback and a new CAPTCHA

Requirements

Python 3.6+
Flask
Flask-Session
Flask-Session-CAPTCHA

Installation

Clone this repository:
git clone https://github.com/yourusername/flask-captcha-auth.git
cd flask-captcha-auth

Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install the required packages:
pip install -r requirements.txt


![codetoflow](https://github.com/user-attachments/assets/9e4bf516-35c6-4710-aee3-2fb714e7b92a)
