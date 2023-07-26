# Falcify Workshop Chatbot

![Falcify Workshop Chatbot](path/to/your/chatbot-image.png)

**Falcify** is an AI-powered chatbot built using **Rasa** to assist participants with workshop-related queries and issues. It is integrated with **Telegram**, making it easy for users to interact with the chatbot directly from the Telegram app.

## Features

- Answer common workshop queries
- Provide information about workshop dates, timings, and venue
- Help with registration and guidelines
- Provide feedback and certificate information

## Requirements

Before running the Falcify chatbot, make sure you have the following installed:

- Python 3.6 or higher
- Rasa 2.0 or higher
- Telegram app for interacting with the bot

## Usage

To interact with the Falcify chatbot, follow these steps:

1. Open the **Telegram** app on your device.

2. Search for the bot using the username `@Falcify_bot`.

3. Start a conversation by sending a message to the bot.

## Installation and Setup

To run the Falcify chatbot locally, follow the instructions below:

### Clone the repository:
   ```shell
   git clone https://github.com/yourusername/falcify-workshop-chatbot.git
   ```
### Change into the project directory:
   ```shell
   cd falcify-workshop-chatbot
   ```
### Install the required Python packages using pip:
   ```shell
   pip install -r requirements.txt
   ```
### Train the Rasa chatbot:
   ```shell
   rasa train
   ```
### Start the Rasa action server:
   ```shell
   rasa run actions
   ```
### Run the Rasa chatbot server:
   ```shell
   rasa run --enable-api --cors "*"
   ```
## Contribution
Contributions are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
