# Jenna
![Not my art lol](https://cdn.discordapp.com/attachments/729757758332862535/737422906774126663/03387e22311e8dab20cd3eb23f212283_1.png)
* [Link to artwork](https://www.pinterest.com/pin/629870697860898632/?nic_v1=1a2e%2Bc%2F8ybPI%2B6IHEwuxBwDXGMn2MUvzKt5a6CCAagOFO3Zz%2BgWykMAID0rvU82eo2)
#### The Ultimate Extensive Discord Bot tailored to Self-Botting and Group Chats
* Updated Regularly
* Created by jam#3515 or jamxu88 on github
* Lightweight, easy to host and setup
* Made in Discord.js
## Dependencies
* [NodeJS and NPM](https://nodejs.org/en/) (Distrubuted Together)
* [Discord.js](https://www.npmjs.com/package/discord.js) (Version 11.5 or earlier for self-bots, self-bots are depreciated in version 11.6 and later)
* [Fetch](https://www.npmjs.com/package/fetch)
* [Math.js](https://www.npmjs.com/package/mathjs)
* [Cheerio](https://www.npmjs.com/package/cheerio)
* [Request](https://www.npmjs.com/package/request)
* [Oxford Dictionary API](https://www.npmjs.com/package/oxford-dictionary-api) (Not known to function, used in under development non-functional define command)
* Optional: [Git](https://git-scm.com/downloads)- Git makes everything easier to do with their CLI
* Optional: [PM2](https://www.npmjs.com/package/pm2)- Git makes everything easier to do with their CLI
## Features 
* Weather Command (US Zipcodes)
* GC/Server Logging
* Mock Case
* Embeded Messages
* Dice Roll
* Random Number Generator
* Rock, Paper, Scissors
* Magic 8 Ball (Ask Jenna)
* Calculator
* Some hidden features ;)
## Under Development
* Fighting Game
* Dictionary Command
* Google Search/Image Search (Basically an entire freaking browswer in Discord)
## Known Issues (Self-Bot)
* Bot crashes upon Group Chat name change or picture change (TypeError: channelClass is not a constructor)
* Bot crashes when attempting to send a direct message to non-friend users (DiscordAPIError: Cannot send messages to this user)
## Known General Issues
* Random unhandled error events, usually network related- this issue can be solved by hosting the bot on [PM2](https://github.com/Unitech/pm2)
## Installation
* First, Download jconfig.json and jenna.js
* Next, you need to configure jconfig.json
  * I can't tell you to self-bot... so uh head over to https://discord.com/developers/ and make a new application and bot
![Discord Developer Portal](https://cdn.discordapp.com/attachments/729757758332862535/737415172259577987/QAAAABJRU5ErkJggg.png)
  * Create a bot ![Bot Creation](https://cdn.discordapp.com/attachments/729757758332862535/737422656046891053/unknown.png)
  * Where it says `token:` in jconfig.js, enter the token within the quotes.
  * Right now, the `dictID` and `dictAppKey` are not needed.
  * `logServerID` should be the channel ID of where you want logged messages to go. To get the channel ID, make sure you're in developer mode ![dev mode](https://cdn.discordapp.com/attachments/729757758332862535/737415741627957306/unknown.png) and right click on the channel and press **Copy ID**
  * `jennaID` should be the Client ID found in your Developer Application ![Dev App](https://cdn.discordapp.com/attachments/729757758332862535/737422836712603698/unknown.png)
* Now you're ready to begin the hosting process. Install the [dependencies](https://github.com/jamxu88/jenna#dependencies).
* Make sure jenna.js, jconfig.json, and your node modules are in the same folder
* For PM2- `pm2 start jenna.js`
* For Stock Node- `node jenna.js`
* **And you're done!**
