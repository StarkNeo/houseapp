# housewebsite

# Project Description:
Web APP to get medical information in a sarcastic way like Dr. House would given.
The users will be able to ask questions about health symtomps and diseases to a an AI provided by OPENAI, which will simulate to be Dr. Gregory House a fictional protagonist of the american serie HOUSE and this ones will respond as he usually does in a sarcastic manner.

# Purpose:
The purpose of this application is for entertaniment but include a link where the users can find real medical information.

# Aknowledgements:
1. Several question options included in the list deployed in a drop down tag were gathered from EverybodyWiki Visit https://en.everybodywiki.com/List_of_diagnoses_from_House_%28TV_series%29.

# Components:
The application consists in:
* Front-end interface builded with traditional HTML,CSS,JAVASCRIPT and Flask Framework
* Back-end interface builded with Python and Flask Framework
* OPENAI API endpoints to interact with GPT 3.5 Turbo
* CSV file that contains a list of prompts to be loaded in the application

# Requirements to install and run the application
1. Install Python.
2. Clone this repository
3. Install flask
4. Navigate to housewebsite and install OPENAI Python Library with: pip install --upgrade openai
5. Setup your API Key with: setx OPENAI_API_KEY "your-api-key-here"

# How to use the project
1. Run the application with: python app.py
2. Once the application is running you can see the home page in your localhost or http://localhost:5000
3. Select the type of question you prefer, example typying text or select and option from the drop down
4. Send the question
5. The answer to your question must appears in text to be read or and audio to be listen, you can press either or both buttons.

# Documentation
* API OPENAI https://platform.openai.com/docs/api-reference/chat/create
* FLASK https://flask.palletsprojects.com/en/1.1.x/
* PYTHON https://www.python.org/downloads/

# License
This project is licensed under the MIT License - see the Licence file for details.

