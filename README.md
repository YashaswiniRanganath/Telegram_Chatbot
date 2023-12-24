Telegram Chatbot with OpenAI GPT-3.5-turbo
This Telegram chatbot utilizes the OpenAI GPT-3.5-turbo model to generate responses based on user input. The bot can handle both text and voice messages and responds with synthesized speech.

Prerequisites:
Python installed on your system
Telegram API token for your bot
OpenAI API key


Setup:
Clone the repository to your local machine.

git clone https://github.com/your-username/your-repository.git
cd your-repository

Install the required Python packages.:
pip install python-telegram-bot openai moviepy gtts
Obtain your Telegram API token and OpenAI API key.

Create a Telegram bot and obtain the API token.
Sign up for OpenAI and obtain your API key.
Replace "<YOUR_TELEGRAM_BOT_TOKEN>" and "<YOUR_OPENAI_API_KEY>" in the code with your actual API tokens.
Run the Telegram chatbot script.

python telegram_chatbot.py

Usage:
Text Messages: The bot responds to text messages sent to the Telegram bot. It utilizes the OpenAI GPT-3.5-turbo model to generate responses.
Voice Messages: The bot also supports voice messages. When a voice message is received, it transcribes the message, generates a response, and sends back a synthesized voice message.
How It Works
The chatbot uses the python-telegram-bot library to handle messages from Telegram users.
Text messages are processed by the text_message function, and voice messages are processed by the voice_message function.
The bot uses the OpenAI GPT-3.5-turbo model to generate responses based on the user's input.
The synthesized response is converted into an audio file using the Google Text-to-Speech (gTTS) library.
The audio file is sent back to the user as a voice message.
Important Notes
Keep your API tokens confidential. Do not share them in public repositories or with unauthorized users.
Ensure that you comply with the terms of service for both Telegram and OpenAI.
Review the OpenAI GPT-3.5-turbo documentation for additional details: OpenAI GPT-3.5-turbo Documentation
