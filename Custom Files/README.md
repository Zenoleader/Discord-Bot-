[![MGS GitHub Banner](https://user-images.githubusercontent.com/119907481/219827160-c69c91be-0c53-4fa0-9b97-7f649683fab4.png)](https://mountaingamingstudio.wixsite.com/mountaingaming)


# [MGS Discord Bot](https://discord.com/api/oauth2/authorize?client_id=962834876665577542&permissions=534723819584&scope=bot%20applications.commands)

[Main Page](#MGS-Discord-Bot), [Info](#INFO), [Meet the team!](#DEVELOPMENT-TEAM), [Updates](#UPDATES), [Featured Commands](#FEATURED-COMMANDS),[Links](#LINKS), [Our ToS & Privacy Policy](#MGS-GitHub-ToS), [Extra Codes](#Extra-Codes), [Game Codes](#JavaScript-Game-Codes)
------------------------------------------------------------------------------------------------------------------------------------------------------
**THIS BOT IS MADE BY Zeno#2951, Purplecake613#4099, oof.png#2521 (Mountain Gaming Studios Founders)**

In places where it says token, you need to make a secret in [replit](https://replit.com) or [visual code](https://code.visualstudio.com/) (for visual studio, you need to paste your actual token in the login. Ex: client.login("YOUR BOT TOKEN") ). Name the secret token and paste you discord bots token there. discord.js is needed to make all of this work. You can always add more commands or edit the ones already there. If any errors are found, just tell us, we don't want you guys to not understand why it didn't work.

replit: 
```js 
client.login(process.env.token);
```

visual studio: 
```js 
client.login("TOKEN");
```

* Note: We think the reason for this is for your bots safety. Visual studio is a one person platform, so your token can't rally be seen by anyone else unless you show them. Replit projects are all public, so anyone can see it (unless you pay to get it private). That's why replit created the [secret](https://docs.replit.com/programming-ide/workspace-features/storing-sensitive-information-environment-variables) tool so all your tokens or private things stay private.

**⚠️[MOUNTAIN GAMING STUDIOS](https://mountaingamingstudio.wixsite.com/mountaingaming) IS NOT RESPONSIBLE FOR ANY DATA LOSS OR BOT FRAUD. IF YOU COMMIT FRAUD, BREAK DISCORD TOS, OR FIND ANY WAY TO GET YOUR BOT BANNED OR ACCOUNT BANNED, WE ARE NOT RESPONSIBLE. TO SUM IT UP: WE ARE NOT RESPONSIBLE FOR ANYTHING YOU DO.⚠️**

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
# **INFO:**

Made with [node.js](https://nodejs.org/en/), programmed by [Mountain Gaming Studios](https://mountaingamingstudio.wixsite.com/mountaingaming), 100% safe, interaction bot. Please don't edit the code for the wrong reasons. Use this nicely. All file names are what you need to name them when creating your file. For example, if you're trying to do the [index.js](https://github.com/Zenoleader/MGS-Bot/blob/main/Main-files/index.js), you need to go to where ever you are programming and make a file called [index.js](https://github.com/Zenoleader/MGS-Bot/blob/main/Main-files/index.js). Same for everything else. You will need to download **[discord.js v13](https://v13.discordjs.guide/)**. No other version will work with the code provided. The MGS bot team uses [replit](https://replit.com) to program our bot (We recommend this if you are working with a team)! (Codes are all modified so they don't look exactly like the actual MGS commands. This is due to copying and people being lazy)

**YOU ADD ALL THE COMMANDS IN THE INDEX.JS FILE INSIDE THE SAME CLIENT:** 

```js
const Discord = require('discord.js')
//remember it's v13

const client = new Discord.Client({intents: ["GUILDS", "GUILD_MESSAGES"]}); 
//you can always add more intents

client.on("messageCreate", message => {
  if(message.content === 'hello') {
    message.channel.send("Hi.")
  }
  if(message.content === "this is the second thing") {
  message.channel.send("Ok 👌")
  }
}) 
``` 

*refer to [Example Code.js](https://github.com/Zenoleader/MGS-Bot/blob/main/Example%20Code.js) if you still don't understand.

**DOWNLOAD [DISCORD.JS](https://discord.js.org/#/): ```npm i discord.js@13.10.2```**

**⚠️ WE WILL NOT SPOON FEED YOU WITH PROGRAMMING. IF YOU DON'T UNDERSTAND SOMETHING PLEASE TRY TO FIGURE IT OUT FIRST THEN ASK US.⚠️**

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
# **DEVELOPMENT TEAM:**

**Zeno#2951**- CEO & founder of Mountain Gaming, Programs in JS & LUA, lead developer of Mountain Gaming Discord bot & FLOOR IS NEON RED on Roblox. Epic programmer🧑‍💻

**oof.png#2521**- Co-founder of Mountain Gaming, Programs in LUA, Devloper(scripter) for FLOOR IS NEON RED on Roblox. BreadMaster🍞

**Purplecake613#4099**- Co-founder of Mountain Gaming, Devloper(builder & scripter) for FLOOR IS NEON RED on Roblox and Mountain Gaming Studios Discord bot. urg burg cheese meese🧀

**ninjaxp30#4203**- Developer(builder) for FLOOR IS NEON RED on Roblox

**DannyCool65#3214**- Developer(Builder) for FLOOR IS NEON RED on Roblox

Want to join Mountain Gaming Studios? Refer to here: [MGS Applications](https://github.com/Zenoleader/MGS-Bot/blob/main/.github/Issues%20Template/Applications.md). We thank you for checking our studio out!! 👍

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
# **UPDATES**

New economy commands are now availible! We aren't done adding them, so expect more updates! This is part of the MGS v3.0.0 update!

**⚠️CUSTOM COMMANDS ARE NOT FOR THE BOT. THEY ARE FOR YOUR PERSONAL USE. REFER TO [EXTRA CODES](#Extra-Codes) TO LEARN HOW TO USE THEM.⚠️**

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
# **FEATURED COMMANDS**

Here are the featured commands of the year! We update this every year (Or month if we fell like it) so people can know which commands are best to add to their bot! If you think we need to add a different command here, just let us know!

- [8ball Cmd](https://github.com/Zenoleader/MGS-Bot/blob/main/Commands/Fun/8ball.js)
- [Ban Cmd](https://github.com/Zenoleader/MGS-Bot/blob/main/Commands/Moderation/Ban.js)
- [Kick Cmd](https://github.com/Zenoleader/MGS-Bot/blob/main/Commands/Moderation/Kick.js)
- [Slowmode Cmd](https://github.com/Zenoleader/MGS-Bot/blob/main/Commands/Moderation/slowmode.js)
- [Meme Cmd](https://github.com/Zenoleader/MGS-Bot/blob/main/Commands/Fun/meme.js)

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
# **LINKS:**

- [Support Server](https://discord.gg/zenoyt-official-server-845476765702946846)
- [Add the bot](https://discord.com/api/oauth2/authorize?client_id=962834876665577542&permissions=534723819584&scope=bot%20applications.commands)
- [FLOOR IS NEON RED (Roblox game)](https://www.roblox.com/games/7231457999/FLOOR-IS-NEON-RED)
- [top.gg](https://top.gg/bot/962834876665577542)
- [Mountain Gaming Studios (Roblox game studio)](https://www.roblox.com/groups/11791011/Mountain-Gaming-Studios)
- [Website](https://mountainggamingstudio.wixsite.com/mountaingaming)

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
# **Extra Codes**

If you've looked hard enough (Using your eyes), you will notice that there is a folder called "[Custom Files](https://github.com/Zenoleader/MGS-Bot/tree/main/Custom%20Files)". We are informing you now that those codes have **no relation to Discord bots or Discord what so ever.** These are sponsored codes that we have generously advertised for the owner of the codes ([Laylox](https://laylox.com)). We are still adding more extensions! If you would like the use them, follow the instructions bellow ⬇

1. Make sure to click Ctrl + Shift+ B to show your bookmarks bar.
2. Click on the file of which extension you want.
3. Click on whichever extension you want.
4. Then click the 2 squares to copy the code
5. Then go up to your bookmarks, right click or twofinger click, press add page, **AND ONLY CHANGE THE NAME TO WHAT YOU WANT THEN PRESS SAVE.**
6. After that, go back to that bookmark, right click or twofinger click, press edit, go to the url, and press ctrl + a, and then backspace.
7. Then press ctrl + v to paste the code and there are two scenarios that may occur. Refer to 7a. and 7b.

7a. When you paste your code, look at the beginning, you should see " javascript: "(WITHOUT THE QUOTES AND SPACES), if you do, press save, if not, refer to 7b.

7b. All you have to do is copy or type " javascript: " (WITHOUT THE QUOTES AND SPACES) in front of ALL OF THE CODE! Once that is done press save!

Want to get your own codes added? Contact us and we can discuss a partnership! Enjoy the extensions!

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
# **JavaScript Game Codes**

Just like the extra codes, we have added new programs that have **no relation to Discord Bots or Discord** at all. These are game codes that were made with code.org and provided by a the MGS Ceo, and other colleagues. We generously provided these codes so you guys could make your own games. Enjoy it.

- [Dino Game](https://github.com/Zenoleader/MGS-Bot/blob/main/JS%20Game%20codes/DinoGame.js)
- [Dino Guard](https://github.com/Zenoleader/MGS-Bot/blob/main/JS%20Game%20codes/DinoGuard.js)
- [Dino Jump](https://github.com/Zenoleader/MGS-Bot/blob/main/JS%20Game%20codes/DinoJump.js)

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
# **MGS GitHub ToS**

**1. Use of our service:** By using our codes, you agree **to not use any codes for, but not limited to: hacking, scamming, auth netting, hitting the nae nae etc.** If we feel you are violating those terms, we will remove your access from this respitory.

**2. Your privacy:** By using our codes, you accept that we take data on what you click and what is seems of intrest to you. **Your Username is shared with us, but your passwords & emails are safe to just you.** If you are here to try and hack people, not only will we remove your access, we will report you to GitHub Support.

**3. Social Media:** By using our codes, you agree that we will have to consent you on making videos, posts, pictures etc. about our sites/codes. If we feel you are violating those terms, we will remove your access from this respitory & will report you to GitHub Support. **We take social media very lightly, so you can post any time as long as you have read this.**

**4. Contact us:** Have any questions or concerns about our terms? Don't fret, just email us: [zenoytmoderator@gmail.com](https://mail.google.com/mail/u/0/?fs=1&tf=cm&source=mailto&to=zenoytmoderator@gmail.com). **Our responses could take 3-5 business days.**

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
# **MGS Bot ToS**

**1. Terms of Service:** By using the MGS bot, you agree to let the developers have access to specific data. The type of data we have is, but not limited to, **your user ID, username and tag, profile, guild IDs, and DMs with the bot.** Use of the bot is considered agreement.

**2. Access of Data:** By using the MGS bot, you agree to let the developers have access to your data. **Only the bot developers of MGS have access to your data**. We use your data to improve our bot in any way possible.

**3. Storage of Data:** By using the MGS bot, you agree to let the developers store your data. We use your data to do analytics on how the bot is doing. **If any breach of your data was made, we will notify all servers using the client.**

**4. Request Data:** By using the MGS bot, you have the right to request your data stored by MGS. You can always request your data in the support server. Your data will never be declined when requested. **You have the right to have your data removed.**

**5. Underage Users:** By using the MGS bot, you accept that you have to be 13+ or of legal age in your country to use Discord. If any reports have been made of an underage user, **we will do everything we can to delete that users' data & report that user to Discord Trust & Safety.**

**6. Questions:** Have any questions or concerns about our terms? Don't fret, just email us: [zenoytmoderator@gmail.com](https://mail.google.com/mail/u/0/?fs=1&tf=cm&source=mailto&to=zenoytmoderator@gmail.com). **Our responses could take 3-5 business days.**

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
# **MGS Bot Privacy Policy**

**1. Privacy Policy:** MGS takes your private data very seriously. To protect you, we will tell you all the information we gather from you and how we use it!

**2. Security:** The MGS development team does all they can to keep your information safe. We can't 100% guarantee that your information will be safe since the internet isn't 100% fool proof. We secure your privacy in our support server.

**3. Storage of Data:** Only the data such as your server name, a few roles, server/member ID's, & user tags **are stored permanently** until a dev deletes it or you request your data to be deleted.

**4. Changes of the Policy:** Any changes of the privacy policy will be updated and told to everyone using the bot as soon as possible. We will notify you using dm's or the "alert" command. **The policy has been in effect since 2/1/23.**

**5. Questions:** Have any questions or concerns about our policy? Don't fret, just email us: [zenoytmoderator@gmail.com](https://mail.google.com/mail/u/0/?fs=1&tf=cm&source=mailto&to=zenoytmoderator@gmail.com). **Our responses could take 3-5 business days.**

[Main Page](#MGS-Discord-Bot)

------------------------------------------------------------------------------------------------------------------------------------------------------
If any problems are found, **please join the support server, open a ticket (or use the report commands in an external server. Doesn't really matter), describe the problem, and a staff member will be with you shortly.**

![Mountain Gaming](https://user-images.githubusercontent.com/119907481/219535225-afbc528f-a45b-457c-ba10-9ca6ffd742e1.png) ![Mountain Gaming (2)](https://user-images.githubusercontent.com/119907481/219905725-3b291a15-2dce-40dc-9d82-3288d7ff374d.png)


