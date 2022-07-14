</p>
<h1 align="center">
  <b>Pirate BOT</b>
</h1>


## Features

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Index
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel
- [x] Spelling Check Feature
## Variables

Read [this](https://telegram.dog/AdvBotUpdates/18) before you start messing up with your edits.

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `PICS`: Bot starting image
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [MESSAGE](https://telegram.dog/AdvBotUpdates/18)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com).
* `COLLECTION_NAME`: Name of the collections. Defaults to Telegram_files. If you are using the same database, then use different collection name for each bot. Not required

### Optional Variables
* `AUTH_USERS` : The Username or ID. Separate multiple users by space. If no need this function please empty the option
* `AUTH_CHANNEL` : The ID of Force Sub Channel. If no need this function please empty the option


## Deploy
You can deploy this bot anywhere.

<details><summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?/template=http://github.com/Sajeevbkk/AutoSearch">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/Teampir/d-n-1-f
# Install Packages
pip3 install -U -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>


## Commands
```
• /stats - to get status of files in db.
* /filter - add manual filters
* /filters - view filters
* /connect - connect to PM.
* /disconnect - disconnect from PM
* /del - delete a filter
* /delall - delete all filters
* /deleteall - delete all index(autofilter)
* /delete - delete a specific file from index.
• /users - to get list of my users and ids.
• /chats - to get list of the my chats and ids 
• /index  - to add files from a channel
```
## Support
[![telegram badge](https://img.shields.io/badge/Telegram-Group-30302f?style=flat&logo=telegram)](https://telegram.dog/AdvBotUpdates)
[![telegram badge](https://img.shields.io/badge/Telegram-Channel-30302f?style=flat&logo=telegram)](https://telegram.dog/AdvBotUpdates)

## Thanks to 
 - Thanks To Dan For His Awesome [Library](https://github.com/pyrogram/pyrogram)
 - Thanks To Mahesh For His Awesome [Media-Search-bot](https://github.com/Mahesh0253/Media-Search-bot)
 - Thanks To [Trojanz](https://github.com/trojanzhex) for Their Awesome [Unlimited Filter Bot](https://github.com/TroJanzHEX/Unlimited-Filter-Bot) And [AutoFilterBoT](https://github.com/trojanzhex/auto-filter-bot)
 - Thanks To All Everyone In This Journey
