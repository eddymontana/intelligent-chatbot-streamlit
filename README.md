# intelligent-chatbot-streamlit
Developed an intelligent, interactive chatbot using Python, Streamlit, and NLP techniques (TF-IDF, Logistic Regression). This conversational AI accurately identifies user intent and provides relevant, dynamic responses, showcasing fundamental machine learning and web application development skills.


Intelligent Conversational AI Chatbot
Project Overview
This project features an intelligent, interactive chatbot built using Python, designed to understand user intent and provide relevant, predefined responses. It leverages fundamental Natural Language Processing (NLP) techniques and a machine learning model to classify user queries, making it a robust example of a basic conversational AI application. The chatbot is presented through an intuitive web interface powered by Streamlit.

Features
Intent Recognition: Classifies user input into predefined categories (e.g., greetings, questions about finance, requests for help).

Dynamic Responses: Provides appropriate and varied responses based on the recognized intent.

Simple & Intuitive UI: User-friendly web interface built with Streamlit for easy interaction.

Scalable Intent System: Easily expandable by adding more intents and patterns to the intents data structure.

Technologies Used
Python: The core programming language.

Streamlit: For creating the interactive web application interface.

scikit-learn:

TfidfVectorizer: For converting text data into numerical features (TF-IDF).

LogisticRegression: For the machine learning model used in intent classification.

NLTK (Natural Language Toolkit): Used for text processing functionalities (punkt tokenizer).

Setup and Installation
Follow these steps to get the chatbot running on your local machine.

Prerequisites
Python 3.8+ installed on your system.

pip (Python package installer)

Installation Steps
Clone the Repository (if applicable):
If you've cloned this repository from GitHub, navigate to the project directory:

cd your-repo-name # e.g., cd intelligent-chatbot-streamlit

If you just have the my_chatbot.py file, ensure your terminal is in the directory where this file is saved.

Install Required Libraries:
Open your terminal or command prompt and run the following command to install all necessary Python packages:

pip install streamlit scikit-learn nltk

Download NLTK Data:
The script automatically attempts to download the punkt tokenizer. Ensure you have an active internet connection when running the app for the first time if this data is not already present.

How to Run the Chatbot
Once the setup is complete, you can launch the Streamlit application:

Navigate to the Project Directory:
Open your terminal or command prompt and change your current directory to where your my_chatbot.py file is located.

# Example for Windows
cd C:\Users\YourUsername\Downloads\my_chatbot_project
# Example for macOS/Linux
cd ~/Downloads/my_chatbot_project

(C:\Users\user\Downloads\my_chatbot).

Launch the Streamlit App:
Run the following command:

streamlit run my_chatbot.py

Access the App:
Your default web browser should automatically open a new tab displaying the chatbot interface, typically at http://localhost:8501. If it doesn't, copy and paste the "Local URL" provided in your terminal into your browser.

Usage
Interact with the chatbot by typing your messages into the "You:" input field and pressing Enter. The chatbot will process your input, identify the intent, and provide a relevant response in the "Chatbot:" area.

Example Interactions:

"Hi" / "Hello" / "How are you"

"Thank you" / "Thanks a lot"

"What can you do?" / "Who are you?"

"How can I make a budget?"

"What is a credit score?"

"Bye" / "See you later"

![image](https://github.com/user-attachments/assets/91fe2d75-036d-4900-a909-f25453327f23)

![image](https://github.com/user-attachments/assets/847c5086-f3b7-42fc-b354-8b62e74ec86a)



Project Structure
my_chatbot.py: The main Python script containing all the chatbot logic, NLP model training, and Streamlit application code.

Future Enhancements (Optional)
More Intents and Responses: Expand the chatbot's knowledge base with more diverse topics and detailed responses.

Context Management: Implement a way for the chatbot to remember previous turns in the conversation for more natural dialogue.

External API Integration: Connect to external services (e.g., weather APIs, news APIs) to provide real-time information.

Error Handling: Add more robust error handling for unexpected inputs.

Advanced NLP Models: Explore using deep learning models (e.g., BERT, GPT-like models) for more sophisticated intent recognition and response generation.

License
This project is open-sourced under the MIT License. See the LICENSE file for more details. (You might need to create a LICENSE file in your repository if you want to include one).









