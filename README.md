# discord.sh CLI
discord.sh is a command-line tool that allows you to manage your Discord bot and perform various actions, such as logging in, viewing servers, and sending messages. This tool provides a simple and convenient interface for interacting with your bot.

## Installation
To install discord.sh CLI, you need to have Node.js and npm installed on your machine. Then, you can install the package globally using the following command:

```shell
npm install -g discord.sh
```

## Usage
To use discord.sh CLI, simply run the following command in your terminal:

```shell
discord.sh
```

This will display a list of available commands and options that you can choose from. Select a command by typing the corresponding number and pressing Enter.

## Login
The `Login` command allows you to log in to your Discord bot by providing the bot token. If you haven't logged in yet, this command will prompt you to enter your bot token. Once logged in, you can perform other actions with your bot.

## Servers
The `Servers` command allows you to view the servers that your bot is added to. Selecting this command will display a list of servers, and you can choose a server to perform further actions, such as leaving the server, getting server information, or managing the server.

## Send
The `Send` command enables you to send messages to specific channels in your servers. Selecting this command will guide you through a series of prompts to select the target guild and channel, and choose the type of message to send (text message, embed, or button).

## Configuration
discord.sh CLI uses environment variables to store the bot token. If you haven't logged in yet, the tool will prompt you to enter the token and store it as an environment variable. Subsequent runs of the CLI will use the stored token automatically.

## Dependencies
discord.sh CLI relies on the following npm packages:

- axios: for making HTTP requests to the Discord API
- prompts: for interactive prompts with the user
- colors: for coloring console output
- cli-table: for generating tables in the console
- terminal-image: for displaying images in the console
<br>**These dependencies are automatically installed when you install discord.sh CLI.**

## License
This project is licensed under the MIT license. See the LICENSE file for more details.


Thank you for using discord.sh CLI! If you have any questions or encounter any issues, please feel free to reach out.
