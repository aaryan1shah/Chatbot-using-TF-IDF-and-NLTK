# Chatbot-using-TF-IDF-and-NLTK

This code is a simple chatbot implemented in Python using natural language processing techniques. The chatbot takes input from the user in the form of text and responds accordingly.

# Prerequisites
Before running the code, make sure you have the following libraries installed:

* numpy
* sklearn
* nltk
* gradio
You can install these libraries using pip command in your terminal.

# How to Run the Code
* Open the terminal and navigate to the directory where the code is saved.
* Run the command python chatbot.py
* The chatbot will launch in the terminal and you can start chatting with it.

# How the Code Works
The code reads in a text file called 'chatbot.txt' and preprocesses it using natural language processing techniques such as tokenization and lemmatization.

The chatbot responds to the user's input using cosine similarity between the user's input and the preprocessed text. If the user's input matches a greeting in the GREETING_INPUTS list, the chatbot responds with a greeting from the GREETING_RESPONSES list. If the user's input does not match a greeting, the chatbot finds the most similar sentence from the preprocessed text and responds with it.

The chatbot is also implemented with a Gradio interface, which allows the user to interact with the chatbot using a web interface.
