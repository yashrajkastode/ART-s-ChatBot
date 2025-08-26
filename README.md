# ART-s-ChatBot
Project Description:
ART's ChatBot is a web-based conversational AI application built using Streamlit and powered by the Google Gemini-Pro model. This project provides a user-friendly interface for interacting with an AI assistant, allowing users to ask questions or engage in conversations in real-time. The application leverages the Gemini-Pro API for natural language processing and maintains a chat history for seamless interactions.
Key Features

Interactive Chat Interface: A clean and centered Streamlit interface for chatting with the AI.
Gemini-Pro Integration: Utilizes Google's Gemini-Pro model for intelligent and context-aware responses.
Chat History: Persists conversation history within the session for a continuous chat experience.
Environment Configuration: Securely loads API keys using python-dotenv for easy configuration.
Customizable UI: Configured with a custom page title, favicon, and layout for an enhanced user experience.

Technologies Used

Python: Core programming language.
Streamlit: Framework for building the web-based UI.
Google Gemini-Pro API: Provides the AI model for generating responses.
python-dotenv: Manages environment variables for secure API key handling.

How It Works

The application initializes a Streamlit session and configures the Gemini-Pro model using an API key stored in a .env file.
Users input their queries via a chat input field.
The app sends the user's message to the Gemini-Pro model and displays the AI's response.
Chat history is maintained and displayed for each session, with roles translated between Gemini-Pro ("model") and Streamlit ("assistant") terminology.

Setup Instructions

Clone the Repository:
git clone https://github.com/yashrajkastode/ART-s-ChatBot.git
cd ART-s-ChatBot


Install Dependencies:
pip install -r requirements.txt


Set Up Environment Variables:

Create a .env file in the project root.
Add your Google API key: GOOGLE_API_KEY=your-api-key-here.


Run the Application:
streamlit run main.py


Open the provided local URL (e.g., http://localhost:8501) in your browser to interact with the chatbot.


Requirements

Python 3.8+
Streamlit
google-generativeai
python-dotenv

Usage

Enter a question or message in the chat input field.
The AI will respond instantly, and the conversation history will be displayed above the input field.
Continue the conversation as needed within the same session.

Future Enhancements

Add support for multi-modal inputs (e.g., images or files).
Implement user authentication for personalized chat sessions.
Enhance UI with custom themes and styling.
Add error handling for API rate limits and invalid inputs.

License
This project is licensed under the MIT License.
