Project Description

This project is a simple banking domain chatbot that can understand user queries and respond using custom banking data. The chatbot uses SentenceTransformer embeddings and an MLP classifier to identify the intent of user questions. Based on the detected intent, the bot retrieves information from CSV files and dictionaries.

The system supports both personal banking queries (such as account balance, card details, and complaint status) and general banking queries (such as greetings, bank timings, FAQs, nearest branches, and branch manager information). For personal queries, the bot first asks for the customer’s name and validates it against the dataset before giving the answer. If the name does not exist, the bot returns an appropriate error message.

Before building the interface, the project includes:

A users.csv file containing customer details

A branch neighbors dictionary to detect nearby branches

A branch managers dictionary for manager lookup

A trained intent classifier using sentence embeddings

Chat logic that handles name requests, error handling, and dynamic responses
