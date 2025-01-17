
This `README.md` file contains information on setting up, running, and understanding the project. Let me know if you need any adjustments!

# AI Chat Assistant with OpenAI GPT

This Python project uses OpenAI's GPT model (GPT-3.5 or GPT-4) to create a conversational assistant that can answer questions and assist with various tasks based on user input.

## Features

- Interact with the GPT model via a chat interface.
- Dynamically append user input to the conversation and receive a relevant AI-generated response.
- Configurable model and parameters (temperature, max tokens, etc.) for fine-tuning behavior.
- Utilizes environment variables to securely handle API keys.

## Prerequisites

Before running the script, ensure you have the following prerequisites:

- Python 3.6 or higher
- An OpenAI API key (sign up at https://beta.openai.com/signup/ if you don't have one)
- Python libraries: `openai` and `python-dotenv`

## Setup and Installation

### 1. Clone the Repository (or Copy the Files)

You can clone the repository using:

```bash
git clone https://github.com/RunInnova/ChatBot.git

Alternatively, just copy the provided Python script into your project directory.

2. Install Dependencies

```bash
pip install openai python-dotenv


3. Set Up the .env File
In the root directory of the project, create a .env file and add your OpenAI API key like so:

```bash
OPENAI_API_KEY=your-api-key-here


4. Run the Script
Once the setup is complete, run the script:

```bash
python Chatbot.py


```bash
5. Interact with the AI
The AI will prompt you for input. Type your message and the AI will respond based on the conversation context. To exit the chat, simply type "exit."

Example Interaction

Welcome to the AI Chat Assistant!
Type 'exit' to end the chat.

You: How can I create an API in Python?
AI: To create an API in Python, you can use frameworks such as Flask or FastAPI. Both provide easy ways to create REST APIs and handle HTTP requests.
...

-----------------------------------------------------------
Code Overview
openai: This library is used to interact with the OpenAI API and send requests to the GPT model.
dotenv: Used to load the OpenAI API key from the .env file for security.
messages: A list of messages that make up the conversation. Each message has a role (system, user, or assistant) and the content of the message.
chat_with_ai: The function that sends the conversation to the OpenAI API and receives the AI's response.
GPT_MODEL: The OpenAI GPT model being used (either "gpt-3.5-turbo" or "gpt-4").


License
This project is open-source, and you are welcome to modify or use it for personal or commercial purposes. However, ensure you comply with OpenAI's API usage terms.







