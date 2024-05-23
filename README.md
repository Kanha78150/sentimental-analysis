# Sentiment Analysis Web Application

This project is a simple sentiment analysis web application built using Flask. It processes user input text, removes stop words and punctuation, and then analyzes the sentiment using the VADER Sentiment Analysis tool. The application displays the sentiment score and other sentiment metrics on a web page.

## Table of Contents

1. [Introduction](Introduction)
2. [Features](###features)
3. [Installation](###installation)
4. [Usage](###usage)
5. [Configuration](###configuration)
6. [Contributing](###contributing)
7. [License](###license)
8. [Contact](###contact)

### Introduction

The Sentiment Analysis Web Application allows users to input a piece of text, processes it to remove stop words and punctuation, and then analyzes its sentiment using the VADER Sentiment Analysis tool. The results are displayed on the same web page, showing positive, negative, neutral scores, and a compound score.

### Features

- **Text Preprocessing:** *Converts text to lowercase, removes digits, and stop words.*
- **Sentiment Analysis:** *Uses VADER Sentiment Analysis to evaluate the sentiment of the processed text.*
- **Web Interface:** *Simple and intuitive web interface for inputting text and viewing results.*

### Installation
*To set up and run this project locally, follow these steps:*

1. **Clone the Repository:**
   git clone https://github.com/Kanha78150/sentimental-analysis.git
   *cd sentimental-analysis*

**Set Up a Virtual Environment:**
`python -m venv venv`

**Install Dependencies:**
`pip install -r requirements.txt`

**Download NLTK Data:**
`python -m nltk.downloader stopwords`

### Usage
*Run the Flask Application:*
`flask run`

**Open in Browser:**
Open your web browser and go to ```http://127.0.0.1:5002``` to view the application.

**Input Text and Analyze:**
*Enter the text you want to analyze in the provided text box.
*Click the submit button to see the sentiment analysis results.

**Procfile**
The project includes a Procfile for deployment using Gunicorn:
`web: gunicorn app:app`

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Contact
If you have any questions, issues, or suggestions, please contact:

**Email:** ```bholasankarnanda123@gmail.com```
**GitHub Issues:** ```https://github.com/Kanha78150/sentimental-analysis```

# Thank you for using the Sentiment Analysis Web Application!
