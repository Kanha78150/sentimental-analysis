# Sentiment Analysis Web Application

This project is a simple sentiment analysis web application built using Flask. It processes user input text, removes stop words and punctuation, and then analyzes the sentiment using the VADER Sentiment Analysis tool. The application displays the sentiment score and other sentiment metrics on a web page.

## Table of Contents

1. [Introduction](###Introduction)
2. [Features](###Features)
3. [Installation](###Installation)
4. [Usage](###Usage)
5. [License](###license)
6. [Contact](###contact)

### 1. Introduction

The Sentiment Analysis Web Application allows users to input a piece of text, processes it to remove stop words and punctuation, and then analyzes its sentiment using the VADER Sentiment Analysis tool. The results are displayed on the same web page, showing positive, negative, neutral scores, and a compound score.

### 2. Features

- **Text Preprocessing:** *Converts text to lowercase, removes digits, and stop words.*
- **Sentiment Analysis:** *Uses VADER Sentiment Analysis to evaluate the sentiment of the processed text.*
- **Web Interface:** *Simple and intuitive web interface for inputting text and viewing results.*

### 3. Installation
*To set up and run this project locally, follow these steps:*

1. **Clone the Repository:**
- `git clone https://github.com/Kanha78150/sentimental-analysis.git`
- `cd sentimental-analysis`

3. **Set Up a Virtual Environment:**
- `python -m venv venv`

4. **Install Dependencies:**
- `pip install -r requirements.txt`

5. **Download NLTK Data:**
- `python -m nltk.downloader stopwords`

### 4. Usage
1. **Run the Flask Application:**
- `flask run`

2. **Open in Browser:**
- [Open your web browser and go to (http://127.0.0.1:5002) to view the application.]

3. **Input Text and Analyze:**
- Enter the text you want to analyze in the provided text box.
- Click the submit button to see the sentiment analysis results.

3. **Procfile**
The project includes a Procfile for deployment using Gunicorn:
- `web: gunicorn app:app`

### 5. License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### 6. Contact
If you have any questions, issues, or suggestions, please contact:
- [Email:](bholasankarnanda123@gmail.com)
- [GitHub Issues:](https://github.com/Kanha78150)


# Thank you for using the Sentiment Analysis Web Application!
