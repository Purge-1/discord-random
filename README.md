# discord-random

- Package [V1](https://www.npmjs.com/package/something-random-on-discord) Was By CTK WARRIOR#7923 ([Discord Server](https://discord.gg/7efH8yYpqK))
- Current : Something Random On Discord V2 (Status: Working)

### Example
```js
//Discord.js Bot - discord.js.org - npm i discord.js
const Discord = require("discord.js"), Random = require("discord-random");
const client = new Discord.Client();

client.on("ready", () => console.log("Bot Is Ready With Something Random On Discord V2 💙"));

client.on("message", async message => {
    if (message.content.toLowerCase() === "meme") {
        const Meme = await Random.GetMeme();
        return message.channel.send(Meme);
    };
});

client.login("Put Your Epic Bot Token Here!");
```
![](https://cdn.discordapp.com/attachments/763294769974607912/763295959761289246/unknown.png)

### Why discord-random?

- Fast & Many Functions
- Quick Updates


- Thank You For Reading & Using [This Package](https://www.npmjs.com/package/discord-random) ;)
