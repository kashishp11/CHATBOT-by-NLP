Project Description:
This project builds an AI-powered chatbot using Natural Language Processing (NLP) techniques. The chatbot uses Logistic Regression to classify user queries based on predefined intents, providing accurate and dynamic responses. Built with the Streamlit framework, the web-based interface is simple and interactive, offering real-time communication and a conversation history feature for a seamless user experience.

Features:
Intent Classification: Uses Logistic Regression for recognizing user intents and providing relevant responses.
Interactive Web Interface: Built with Streamlit, offering an intuitive and user-friendly chat interface.
Real-Time Conversations: Immediate replies to user queries based on intent classification.
Conversation History: Keeps a record of all chats, including user inputs, chatbot responses, and timestamps, saved in a CSV file.
Customizable Intents: The chatbot can be easily trained with new data by adding intents to the intents.json file.
Technologies Used:
NLP Libraries:
nltk for text processing (tokenization and cleaning).
sklearn for TF-IDF vectorization and intent classification using Logistic Regression.
Web Framework:
Streamlit for building an interactive and responsive UI.
Data Management:
CSV files for storing conversation logs.
JSON file for storing intents and responses.
