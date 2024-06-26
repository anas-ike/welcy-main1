![Readme Banner](assets/welcom.png)
![Readme Banner](assets/bey.png)
# Discord Welcome Bot

A Discord bot that sends a welcome message and an image with the background and profile picture of a user who joins the server. Built using NodeJS, runs on nodemon

## Features

- Sends a welcome message and image for new members
- Slash command to check the bot's ping and information

## Installation

1. Clone this repository.
    ```
    git clone https://github.com/anas-ike/welcy.git
    ```  
2. Install the required dependencies 
     ```
     npm install
     ```
3. Configure the bot by adding your bot token and other necessary details to the `config.js` file.
4. Run the bot using 
    ```
    node index.js
    ```
    or by using nodemon
    ```
    nodemon index.js
    ```

## Usage

Once the bot is running and connected to your server, it will automatically send a welcome message and image whenever a new member joins the server. Additionally, you can use the following slash command:

- `/ping`: Check the bot's ping and information.

## Configuration

To configure the bot, you need to provide the following details in the `config.js` file :

- `YOUR_BOT_TOKEN`: Replace with your actual bot token.
- `YOUR_CLIENT_ID`: Replace with your bot's client ID.
- `YOUR_GUILD_ID`: Replace with the ID of the guild (server) where you want to register the slash commands.
- `WELLCOME_CHANNEL_ID`: Replace with the actual channel ID for the welcome message.
- `FAREWELL_CHANNEL_ID`: Replace with the actual channel ID for the farewell message.

Rest of the configurations can be done according to your wish in the `config.js` file.

<br>

<a href="https://discord.com/invite/PqVQgXTweC">
  <img src="https://invidget.switchblade.xyz/PqVQgXTweC" alt="Discord Server">
</a>

## Dependencies

- discord.js: `^14.11.0`
- @discordjs/rest: `^1.z.1`
- discord-api-types: `^9.0.0`
- canvafy: `^7.0.4`
- nodemon: `^3.0.1`

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
