# Paradise: 
##### Yet another discord.js bot
Current version: v0.5.6testing (development version.)

Paradise is a utility and moderation bot written for Discord using [discord.js](https://github.com/discordjs/discord.js)
This is still heavily in development with a huge lack of features as we write a lot of the server-side for now. Bare with us. 
We're looking for beta servers with significant server populations, contact Paradaux#2864 for more information.

# Requirements

In order to host this bot yourself you'll need the following node.js packages which can be installed by simply running `npm install` once you've cloned the repository:

 - [discord.js](https://github.com/discordjs/discord.js) - v11.3.2 (stable)
 - [enmap](https://github.com/eslachance/enmap) - v3.0.4
 - [moment](https://github.com/moment/moment/) - v2.22.2
 - [reaction-core](https://github.com/Mundayne/reaction-core) - v2.2.0
 - [mongoose](https://mongoosejs.com/) - v5.5.3
 
 Developed using the following global packages
- [nodemon](https://github.com/remy/nodemon) - v1.18.3
- [forever](https://github.com/foreverjs/forever) - v0.15.3

# Installation / Setting it up

Before you can begin using this bot you will need to register your bot with the discord api via the developers portal available [here](https://discordapp.com/developers/applications/me) 

Following on from that you'll need to invite your bot by creating an invite link using this format `https://discordapp.com/oauth2/authorize?client_id=INSERT_CLIENT_ID_HERE&scope=bot&permissions=2146958839` and inserting the client id you got from discord within that link. 

Inside of the developers portal you will also need to make sure you create a bot user account, you do this by clicking into the application you've made and going into the bot tab. 

Now clone the repository and place the token you get on that page into /data/config.json.example in the token field then rename config.json.example to simply config.json 

Now you need to grab the dependancies using `npm install` inside of the main directory of the bot

Now you've set it all up and just need to start the bot by using `node start main.js`

## Contributors 

Here's a list of our current, active contributors:

- [ParadauxDev](https://github.com/ParadauxDevelopment) 


## Planned Features

| user        | feature                     | eta  |
|-------------|-----------------------------|------|
| ParadauxDev | basic moderation system     | v1.0 |
| ParadauxDev | basic administration system | v1.0 |
| ParadauxDev | fun commands                | v1.0 |

## Command List

Commands are currently being worked on, but currently the focus is on the back-end handling for each command. (i.e database storage for our moderation system.)

| Command | Argument(s)          | Notes                                     | Example Usage         |
|---------|----------------------|-------------------------------------------|-----------------------|
| ;help   |                      | Shows help regarding added commands       | ;help                 |
| ;warn   | add-remove-check     | Warning system to aid in chat moderation. | ;warn add @Paradaux   |
| ;mute   | <usr> <time> <reasion| Placeholder command, For now.             | ;mute                 |

