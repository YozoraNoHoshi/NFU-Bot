# NFU's Custom Discord Bot


Source code for my private discord's bot. 

This bot runs on Node.js, and is assumed you are using npm as your package manager.

The bot requires a postgreSQL database named `nfubot` for calling emojis. You may change the database name in either a `.env` file or in `config.ts`.   

### Installation
---
Clone the repository:
`git clone git@github.com:YozoraNoHoshi/NFU-Bot.git`

Install Packages:  
`npm install  `


### Running a local copy
---

To run a copy of this bot, you will require your own Discord bot - see [Discord's Developer Portal](https://discordapp.com/developers/applications/).   
**Store your bot's token and client id somewhere, you will need it later.**   
Once you have created a bot, place the bot's token in a `.env` file in the root directory of the project.
> token='YOUR BOT TOKEN HERE'

Add the bot to your discord server using this url: 
>https://discordapp.com/oauth2/authorize?client_id=BOTCLIENTID&scope=bot&permissions=370752  

Replace the `client_id` with your bot's `client_id`.

**Start the bot with  `npm start`**     
If the bot starts successfully, you should see 
>Drain your glass!   

in the console.
