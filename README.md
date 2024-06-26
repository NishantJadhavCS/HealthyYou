***HealthyYou***
HealthyYou is a health and fitness app featuring a nutritional tracker, health calculators, calories burnt tracker and personalized exercise plans based on muscle groups.

*Running the Project*

To run the project, follow these steps:

1. Make sure you have Python and Django installed on your system. You can check if you have Django installed by running the following command:
   
django-admin --version

If you don't have Django installed, you can install it using following command:

pip install django

2. Clone the repository to your local machine. You can clone the repository using the following command:
   
git clone https://github.com/NishantJadhavCS/HealthyYou

4. Navigate to the root directory of the project in the terminal or command prompt.
   
cd HealthyYou

5. Activate the virtual environment. The command to activate the virtual environment depends on your operating system. On Windows, you can run:
venv\Scripts\activate

6. Create a database for your project. The database name, and password should be replaced in the DATABASES setting in the settings.py file. (I have used MySQL)

7. Obtain API Keys from https://api-ninjas.com/api. Create a new account and get copy your API Key.

Replace the 'YOUR_API_KEY' in accouts/views.py with your personal API Key.

8. Create an Email ID from where you wish to send email to the user once logged in. Create a new Google account or use existing account for this.
To allow Django to access your email id follow the below steps:

Go to the "Less secure apps" section in the Google Account settings. You can find it by going to the Google Account page at https://myaccount.google.com/ and clicking on "Security" in the left-hand menu. Then, click on "Less secure app access" in the "Signing in to Google" section.

Turn on the "Allow less secure apps" option. This will allow Django to authenticate with the SMTP server using your Gmail account.

Then enter your own 'EMAIL_HOST' and 'EMAIL_HOST_PASSWORD'.

*IF YOU DONT WISH TO SEND EMAILS AFTER USER SIGN IN JUST DELETE THE CODES WITH THE FOLLOWING COMMAND:*

#SENDING EMAILS TO USER

To run the project on development server run the following command:

python manage.py runserver

For any further query email me at nishantjadhav.cs@gmail.com
