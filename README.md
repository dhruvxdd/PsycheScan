Psyche Scan
Psyche Scan is a web application aimed at analyzing mental health using social data. Users can log in, participate in a psychological test called Psyche Pulse Gauge (PPG) which is an inhouse designed test, and receive mental health insights derived from the combination of this PPG test and their Tweets to ge tthe appropriate idea for thier Mental Health.

Table of Contents
Features
Installation
Usage
Files and Directories
Technologies Used
Contributing
License

Features

User Authentication:

Users can sign up for an account with a unique User ID and password.
Secure login process with credential verification.
Psyche Pulse Gauge (PPG):

Users undergo a psychological test to assess their mental health.
Results from the PPG are combined with sentiment analysis for comprehensive insights.
Sentiment Analysis:

Tweets from the user's account are processed using VADER sentiment analysis.
Average sentiment scores are calculated and visualized.
Professional Help:

Users can access information about mental health professionals in Delhi.
Remedies and Suggestions:

Provides remedies for enhancing mental health.
Offers suggestions such as a balanced diet, yoga postures, and more.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/dhruvxdd/psyche-scan.git
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Set up a MongoDB database and update the connection string in app.py.

Run the application:

bash
Copy code
python app.py
Access the application in your browser at http://localhost:8000.

Usage
Sign Up:

Create an account with a unique User ID and password. 
Log In:

Log in using your credentials.
Psyche Pulse Gauge (PPG):

Complete the PPG test for mental health evaluation.
Sentiment Analysis:

View sentiment analysis results based on your tweets.
Professional Help:

Explore options for mental health professionals in Delhi.
Remedies and Suggestions:

Access remedies and suggestions for enhancing mental well-being.
Files and Directories
app.py: Main Flask application file with routing and MongoDB integration.
backend.py: Data cleaning functions and processing for sentiment analysis.
templates/: Folder containing HTML templates for different pages.
static/: Folder containing static files such as images and stylesheets.
Technologies Used
Flask: Web framework for Python.
MongoDB: NoSQL database for storing user data.
VADER Sentiment Analysis: NLTK library for analyzing sentiment in tweets.
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

License
This project is licensed under the MIT License.
