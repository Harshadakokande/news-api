News App Using API in Python

This is a simple Python news application that fetches the latest news articles using an online news API. The user can search for news by entering a keyword and the app will display the latest related articles along with their links. This project helps beginners understand how APIs work and how to handle JSON data in Python.

Project Description

The News App connects to the NewsAPI service and retrieves real time news data. It sends a request to the API based on the keyword entered by the user and receives the response in JSON format. The app then extracts the news titles and URLs and displays them in a readable format.

This project is completely beginner friendly and runs in the terminal.

Technologies Used

Python programming language
Requests library for API calls
NewsAPI for news data
JSON for data exchange

Project Structure

main.py
README.md

How to Run the Project

First make sure Python is installed on your system.

Install the required library using this command
pip install requests

Create a free account on the NewsAPI website and generate an API key.

Open the main.py file and replace the API key with your own key.

Run the program using the command
python main.py

Enter the topic you want news about when prompted.

How the Application Works

The program asks the user to enter a news topic.
It sends a request to the NewsAPI with the given keyword.
The API returns news data in JSON format.
The program reads the JSON response and extracts article titles and links.
The results are displayed one by one in the terminal.

Learning Outcome

This project helps in understanding how to use APIs in Python.
It teaches how to send HTTP requests and receive responses.
It explains how JSON data is parsed and used.
It improves basic Python programming skills.

Future Enhancements

Add category based news filtering
Create a graphical interface
Add error handling for no results
Allow saving news articles to a file

Author

Harshada Kokande
Final Year B Tech Computer Science and Engineering AI ML
