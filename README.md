# Streamer Notification Discord Bot

## Overview

**StreamerBot** is a specialized Discord bot designed to track and notify users of live streams from their favorite content creators. Utilizing the Sapphire Framework, it provides an efficient and user-friendly experience.

- **Live Stream Tracking**: Monitors platforms like Twitch, YouTube, Rumble, and more.
- **Notification System**: Sends alerts when a tracked streamer goes live.
- **Streamer Management**: Add or remove streamers from the tracking list.

## Installation Instructions

1. **Clone the Repository**:

   ```sh
   git clone [Your Repository URL]
   cd [Your Repository Directory]
   ```

2. **Install Dependencies**:

   ```sh
   npm install
   ```

3. **Configure Settings**:

   - Rename `config.json.example` to `config.json`.
   - Edit `config.json` to include your bot token and any other required settings.

4. **Start the Bot**:
   ```sh
   npm start
   ```

## Usage

- Use `/help` to see available commands.
- Admin commands like `/addstreamer` and `/removestreamer` manage the streamers list.
- Utility commands such as `/liststreamers` display all tracked streamers.

## Commands

### Admin Commands

1. `addstreamer`: Adds a new streamer to the notification list.
2. `removestreamer`: Removes a streamer from the notification list.

### Utility Commands

1. `help`: Lists all available commands and their usage.
2. `liststreamers`: Shows all streamers currently being tracked.
3. `ping`: Checks the bot's response time.


## Contributing

Contributions to the StreamerBot project are welcome! Please submit pull requests or open issues to suggest improvements or report bugs.

## License

This project is licensed under the MIT License. For more details, see the [LICENSE](./LICENSE) file in the repository.