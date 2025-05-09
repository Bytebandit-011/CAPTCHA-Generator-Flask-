<h1>Flask CAPTCHA Authentication </h1>

Overview:
This application demonstrates a simple implementation of CAPTCHA validation using Flask and Flask-Session-CAPTCHA. It provides a secure way to verify that form submissions are made by humans rather than automated bots, helping to protect your web applications from spam and abuse.

Features:<br>
1)Clean, modern UI with responsive design<br>
2)Server-side session management for enhanced security<br>
3)Customizable CAPTCHA settings (length, dimensions)<br>
4)Easy to integrate into existing Flask application<br>

The application follows this workflow:<br>
![codetoflow](https://github.com/user-attachments/assets/9e4bf516-35c6-4710-aee3-2fb714e7b92a)<br>
Configuration: Sets up Flask app, configures CAPTCHA parameters and session management<br>
Request Handling:
<br>
GET requests: Generates and displays a new CAPTCHA challenge<br>
POST requests: Validates submitted CAPTCHA against the stored value<br>
<br>
Response: Renders the form with appropriate feedback and a new CAPTCHA
<br>
Requirements
<br>
Python 3.6+
Flask
Flask-Session
Flask-Session-CAPTCHA
<br>
Installation
<br>
Clone this repository:<br>
git clone https://github.com/yourusername/flask-captcha-auth.git<br>
cd flask-captcha-auth<br>
<br>
Create and activate a virtual environment:<br>
python -m venv venv<br>
source venv/bin/activate  # On Windows: venv\Scripts\activate<br>

Install the required packages:<br>
pip install -r requirements.txt<br>


