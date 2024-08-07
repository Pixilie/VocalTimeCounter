# Vocal Time Counter

## Presentation
Introducing Vocal Time Counter, your trusty Discord companion for tracking your time spent in voice channels! This versatile bot keeps a close eye on your activity, meticulously logging every minute you spend engaged in voice conversations. Whether you're coordinating with friends or collaborating with colleagues, Vocal Time Counter ensures you stay informed about your Discord voice channel usage.

## Informations
The bot is currently on version 1.2.0 and may still have some bugs. If you have any suggestions or would like to report a bug, you can contact me through Discord (my tag is Kristen#1827) or by email at pixilietv@gmail.com. You can also join my Discord server at https://discord.gg/wcy22GAmDG to discuss the bot or share feedback.

## How to use it ?
It's very easy, there are two different commands
- ``/time``: Statistics about you
- ``/leaderboard``: Statistics about the server
- ``/delete <user>``: Delete a user or without params all the users from the database


## Add it to your server
- Clone the repository
- Create the .env file
Don't forget to add a .env file at the root of the project.
The .env file should look like this:
```env
TOKEN=your_bot_token
CLIENT_ID=your_bot_id
START_DATE=timestamp_when_the_bot_was_added_to_your_server # Use to calculate the average time spent in voice channels
SOURCE_TOKEN=logtail_key
```
- Install bun
- Run ``bun install``
- Install pm2
- Run ``pm2 start --name <name> .``
