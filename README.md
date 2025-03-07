# Chatbot_using_NLP_AICTE_Cycle
Training for the project on implementation of chatbot using  NLP


Description
This project implements a simple chatbot using Natural Language Processing (NLP) techniques with nltk, scikit-learn, and streamlit for the user interface. The chatbot is designed to recognize user input patterns and provide appropriate responses based on predefined intents.

Features
Recognizes and responds to greetings, farewells, and common user queries.
Utilizes nltk for tokenization and text preprocessing.
Uses scikit-learn for text vectorization and classification.
Provides an interactive, web-based interface with streamlit.
Easily extendable to support additional intents and responses.
Requirements
Ensure Python is installed (Python 3.13 recommended). Install the necessary dependencies before running the chatbot:


pip install nltk scikit-learn streamlit


How It Works
The chatbot is trained on predefined intents (e.g., greetings, farewells, budgeting).
It uses TF-IDF vectorization to process and analyze user input.
Logistic Regression is used to classify user queries.
Responses are selected randomly from predefined responses based on classification results.
Running the Chatbot
Ensure all dependencies are installed, then start the chatbot using:


streamlit run chatbot.py
This will launch a web-based interface where users can interact with the chatbot.


Example Interactions
User: Hello
Bot: Hi there!

User: How can I make a budget?
Bot: A good budgeting strategy is the 50/30/20 rule...

Supported Intents
The chatbot currently supports the following intents:

Greeting – Responds to "Hi", "Hello", etc.
Goodbye – Recognizes farewells.
Thanks – Acknowledges gratitude.
About – Provides chatbot information.
Help – Offers assistance.
Age – Responds to age-related queries.
Weather – Provides basic weather information.
Budgeting – Offers budgeting advice.
Credit Score – Explains credit scores and how to check them.


Notes
The chatbot currently works with predefined responses.
Streamlit provides a simple UI for easy interaction.
Future updates may include more advanced NLP techniques and real-time API integrations.


Future Improvements
✅ Expand the dataset with more intents and responses.
✅ Integrate real-time data APIs (e.g., live weather updates).
✅ Improve the model using deep learning techniques.
✅ Implement a feedback system to enhance chatbot accuracy.
