# music-discord-bot

!!!<img>!!!

Discord music bot supported with Slash Commands and Requests tracking. It has clean interface and is easy to run!  
Also has the main template function that I use in my personal bot.

In config.json you can set these parameters:
 - timezone (for request tracking)
 - bots_settings["glados"]:
   - activity (defines the status of the bot)
   - cog_blacklist (defines which cogs should be ignored)
   - prefix (for commands that deal with request tracking)

You have to create .env file in the root directory and set these variables:
 - GOOGLE_CREDENTIALS
 - SERVER_ID
 - glados_TOKEN
 - glados_ID

```bash
TOKEN="." # Your bot token
PREFIX="!" # Your prefix
OWNER_IDS="859640640640640640, 859640640640640640" # Your ID
CLIENT_ID="960072976412340254" # Your bot client ID
GUILD_ID="859640640640640640" # Your server ID (if you want to use it for a single server)
PRODUCTION="true" # "true" for production
DATABASE_URL="mongodb+srv://Blacky:xxxxxxxxxxxx" # Your MongoDB URL
LAVALINK_URL="lava.moebot.xyz:443" # Your lavalink url
LAVALINK_AUTH="youshallnotpass" # Your lavalink password
LAVALINK_NAME="Blacky" # Your lavalink name
LAVALINK_SECURE= "true" # true for secure lavalink
```

```
TOKEN="." # Your bot token
PREFIX="!" # Your prefix
OWNER_IDS="859640640640640640, 859640640640640640" # Your ID
CLIENT_ID="960072976412340254" # Your bot client ID
GUILD_ID="859640640640640640" # Your server ID (if you want to use it for a single server)
PRODUCTION="true" # "true" for production
DATABASE_URL="mongodb+srv://Blacky:xxxxxxxxxxxx" # Your MongoDB URL
LAVALINK_URL="lava.moebot.xyz:443" # Your lavalink url
LAVALINK_AUTH="youshallnotpass" # Your lavalink password
LAVALINK_NAME="Blacky" # Your lavalink name
LAVALINK_SECURE= "true" # true for secure lavalink
```

google sheets setup:

## 🧑‍💻 Usage:
 - install Python
 - `git clone https://github.com/freezpmark/music-discord-bot`
 - `cd music-discord-bot`
 - `pip install -r requirements.txt`
 - `python main.py`


## 🔥 Features:
 - enables searching and playing tracks from YouTube
 - supports playing playlist or picking tracks from it
 - real-time audio player that is being updated before every track
 - button interactivity with the audio player
 - track request tracking system integrated with google sheets
 - track request summarization over certain periods of time

## 📚 Commands
<details><summary>Click to View Commands</summary>

| Name        | Description                               | Options                                                   |
|-------------|-------------------------------------------|-----------------------------------------------------------|
| ⏸️         | Pauses the current song                    |                                                           |
| ▶️         | Resumes the current song                   |                                                           |
| ⏭️         | Skips the current song                     |                                                           |
| 🔁         | Loops the queue                            |                                                           |
| 🔂         | Loops currently playing track              |                                                           |
| 🔀         | Shuffles the queue of songs that weren't yet played          |                                         |
| `play`     | Searches and plays/adds the track into queue                  | `search`: search prompt / URL          |
| `playlist` | Allows you to pick tracks from 25 last songs in the playlist  | `playlist_url`: url of playlist        |
| `search`   | Gives you list of tracks to choose from the search prompt     | `search`: search prompt                |
| `seek`     | Gets into certain timestamp in currently playing track        | `second`: timestamp in seconds         |
| `jump`     | Skips to a specific song in the queue       | `index`: index number in the queue                       |
| `remove`   | Removes a song from the queue               | `index`: index number in the queue                       |
| `volume`   | Changes the volume (10% is default)         | `volume`: from 1 to 100 (in %)                           |
| `clear`    | Clears the queue                            | `song`: The song number                                  |
| `history`  | Saves all requests into google sheets log   | (use prefix) `limit`: amount of msgs to take into account|
| `create_stats` | Creates stats out from the requests log | (use prefix)                                             |
</details>

## 👀 Example
!!!<gif>!!!

config change  
reqs change  
