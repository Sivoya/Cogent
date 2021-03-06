![](https://i.imgur.com/lwD2EOn.png)

<p align="center">
    <img src="https://img.shields.io/github/release/VenkSociety/Cogent.svg">
    <img src="https://img.shields.io/github/license/VenkSociety/Cogent.svg">
    <img src="https://img.shields.io/github/issues/VenkSociety/Cogent.svg">
    <img src="https://img.shields.io/github/issues-pr/VenkSociety/Cogent.svg">
    <img src="https://img.shields.io/github/repo-size/VenkSociety/Cogent.svg">
</p>

## A light-weight modular Discord bot built with DiscordJS.

### Features
- Currency system
- Fun games and commands
- Moderation and logging
- Helpful community and quality support

### Installation:
A couple of dependencies you will need:
[NodeJS](https://nodejs.org/en/download/) - A JavaScript runtime, it also has NPM built-in. 

Once NodeJS is installed, install the npm dependencies. For example; the code below will install the `discord.js` package.

- ```npm install discord.js```

Do this for each package in [package.json](https://github.com/VenkSociety/Cogent/blob/master/package.json#L18).

Now that the hard part is over, installation is a simple as a couple of clicks *(and patience depending on your internet speed)*. Simply download the latest release .zip from [here](https://github.com/VenkSociety/Cogent/releases), extract and run **_run.bat_** and you're done, it's that easy!

### Configuration:
By default, the only thing you will need to edit in **_config.json_** is the bot's token. If you're not sure on how to get a bot token, you can follow the [tutorial](https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token) made by our friends over at [Reactiflux](https://www.reactiflux.com/).

    {
    "bot_name": "Cogent",
    "prefix": "/",
    "token": "SEE-ABOVE-IF-NOT-SURE",

    "loaded_msg": "Bot loaded.",
    "active_msg": "Cogent | /help",
    "error_msg": "There was an error trying to use that command.",
    
    "default_role": "welcome",
    "mod_role": "Moderator",
    "log_channel": "logs",
    "welcome_channel": "general"
	}

Optionally, you can edit the other stuff too. If you're not sure what an option means, feel free to take a peak [here](https://github.com/VenkSociety/Cogent/wiki/Config.js).

### Commands:
A full list of commands and how to use them can be found [here](https://github.com/VenkSociety/Cogent/wiki/Commands) as well as a guide to making your own commands.

### Contributing guidelines:
Due to the extremely long amount of text, you can find information on editing files, pull requests, merge requests and issues [here](https://github.com/VenkSociety/Cogent/wiki/Contributing-Guidelines).

### Don't want to host the bot yourself?
We have a public instance of the bot which you can add to your Discord [here](https://discordapp.com/oauth2/authorize?client_id=492871769485475840&scope=bot&permissions=1506142455).

### Didn't answer your question?
Why not join the [official Cogent Bot Discord](https://discord.gg/3hbeQgY)? With lots of things to do and loads of members to chat with, it's one of the most friendly places on the internet... sorta.
