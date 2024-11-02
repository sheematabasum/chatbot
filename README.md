This repository contains a Streamlit-based Chatbot built using the OpenAI API. The chatbot interface allows users to interact in real-time, generating responses using OpenAI's language model.

Features
User-friendly Chat Interface: Built with Streamlit to provide a clean, interactive experience.
Dynamic Chat History: Messages are stored in session state, preserving chat history for the duration of the session.
API Key Authentication: Users must provide an OpenAI API key to initiate interactions with the chatbot.
Installation

Clone the repository:
git clone https://github.com/sheematabasum/chatbot.git
cd streamlit-chatbot

Install required dependencies:
pip install openai streamlit

Run the application:
streamlit run app.py

Usage
Launch the app, and it will open in a new browser tab.
Enter your OpenAI API Key in the sidebar to begin interacting with the chatbot.
Type your prompt in the chat input and get responses powered by OpenAI's gpt-3.5-turbo model.

Requirements
Python 3.7+
OpenAI API key (required to interact with the OpenAI model)

Dependencies: openai, streamlit

Acknowledgments
This project is built using OpenAI's gpt-3.5-turbo model.
Developed with Streamlit for a user-friendly chat experience.

License
This project is licensed under the MIT License. See the LICENSE file for details.
