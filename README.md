# Discord Bot with OpenAI Integration

## Overview

This Discord bot leverages the OpenAI API to facilitate engaging conversations within designated channels. Built using Node.js and the Discord.js library, the bot responds to user messages and maintains context throughout interactions.

## Features

- **Dynamic Message Responses:** The bot generates human-like responses based on user input and maintains context for ongoing conversations.
- **Typing Indicator:** Mimics a natural chat experience by showing a typing indicator while the bot processes responses.
- **Channel Filtering:** Configured to respond only in specified channels or when mentioned, allowing for focused discussions.
- **Error Handling:** Robust error management to handle issues with the OpenAI API gracefully.

## Technologies Used

- **Node.js**: JavaScript runtime for building the bot.
- **Discord.js**: Library for interacting with the Discord API.
- **OpenAI API**: Provides the underlying AI model for generating responses.
- **dotenv**: For managing environment variables securely.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/discord-bot.git
   cd discord-bot

2. Install the necessary packages:
   ```bash
   npm install discord.js dotenv openai
   
4. Create a .env file in the root directory and add your API keys and discord token:
   ```bash
   TOKEN=your_discord_bot_token
   OPENAI_KEY=your_openai_api_key
