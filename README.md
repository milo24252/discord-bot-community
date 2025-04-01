# Discord Bot Project

This project is a simple Discord bot designed for community engagement. It includes basic commands and event handling to interact with users.

## Features

- **Ping Command**: Responds with "Pong!" when a user types `!ping`.
- **Help Command**: Provides a list of available commands when a user types `!help`.
- **Event Handling**: Listens for messages and logs when the bot is ready.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- TypeScript (installed globally or as a project dependency)
- A Discord bot token (create a bot on the Discord Developer Portal)

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd discord-bot-project
   ```
3. Install the dependencies:
   ```
   npm install
   ```

### Configuration

1. Create a `.env` file in the root directory and add your bot token:
   ```
   DISCORD_TOKEN=your_bot_token_here
   ```

### Running the Bot

To start the bot, run the following command:
```
npm start
```

### Commands

- `!ping`: Responds with "Pong!".
- `!help`: Lists all available commands.

## Contributing

Feel free to submit issues or pull requests to improve the bot. 

## License

This project is licensed under the MIT License.