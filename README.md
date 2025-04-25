# Bot-davomat

A Telegram bot for attendance tracking with a backend service.

## Project Structure

- `bot/` - Telegram bot code
- `bot-backend/` - Backend service for the bot

## Setup Instructions

### Prerequisites
- Node.js
- npm/yarn

### Installation
1. Clone this repository
2. Install dependencies in both folders:
   ```
   cd bot
   npm install
   
   cd ../bot-backend
   npm install
   ```

### Configuration
1. Set up environment variables (see example .env files)

### Running the project
1. Start the backend:
   ```
   cd bot-backend
   npm start
   ```
2. Start the bot:
   ```
   cd bot
   npm start
   ```
