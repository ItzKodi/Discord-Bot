# DiscordJS-Bot
This project requires MongoDB to connect to the database, so make sure to get a MongoDB URI!

#### Warning
This project is made for single guild, and not a multi-guild one. I currently have a problem with Slash commands permissions, so I used role_perms property instead of them. If you have a solution, create a pull request.

# Setup the project

## Dependencies installation:
Firstly, install `package-lock.json` file:
```shell
npm init -y
```

Then install the required dependencies:

```shell
npm i discord.js@14 discord.js-v14-helper os ms uuidv4 axios mongoose
```

## Start the project:
The setup for now is for [Visual Studio Code](https://code.visualstudio.com/) users only. If you are a repl.it user and non-beginner programmer, you can read the setup below but you have to edit the Environment processing for MongoDB and the bot token.
- 1. Install [Visual Studio Code](https://code.visualstudio.com/).
- 2. Install [node.js](https://nodejs.org/en/download/).
- 3. Open command propmt and then type `node -v` and make sure that you have installed node.js version **16.9.0** or above.
- 4. [Download the project](https://github.com/ItzKodi/DiscordJs-Bot/blob/main/DiscordJS-Moderation-Bot.zip) and extract the folder from .zip folder to a normal folder.
- 5. Open the folder on a new VSCode tab.
- 6. Go to `config/main.js` and edit the properties of each file. Also make sure to check `config/data.json` because it is also a configuration file.
- 7. Open terminal and then type `node index.js` or `node .`.
- 8. Enjoy.

## Issues
If you encounter any difficulties, do not hesitate to contact me via Discord or email at contact@itzkodi.se.

**Project made with ❤ by ItzKodi#2739**
