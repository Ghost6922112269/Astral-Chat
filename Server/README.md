# Server stuff

## How to use-
To use, first run `node index.js` in this folder, this starts the main server that handles the sending of text/other data to TERA and your discord bot. 
Next, navigate to the discord folder and run `npm i` to install the required dependencies, then edit the included config.json file to include your discord bots [token](https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token) and the [channel ID](https://support.discordapp.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-) of the channel you want the bot to talk in. To run the discord bot, after this, run `node discord.js`.

Then, just simply tell your friends to add the IP and port (by default the IP of the server running the files and the port 3454) to their Astral-Chat config files that are generated after they first run the game with the module(not the server one). Changes will take effect after they restart proxy/log-out to the server select screen and back.
