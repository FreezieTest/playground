# music-discord-bot

<img>

<text-descr>
Discord music bot supported with Slash Commands and Requests tracking. It has clean interface and is easy to run!

## 🧑‍💻 Usage:
 - install Python
 - `git clone https://github.com/freezpmark/music-discord-bot`
 - `cd music-discord-bot`
 - `pip install -r requirements.txt`
 - `python main.py`

config change  
reqs change  
write to .env file: TOKEN=YOUR BOT TOKEN | create env file (REF!)  
google sheets setup  

## 🔥 Features:
 - enables searching and playing tracks from YouTube
 - supports playlists

## 📚 Commands
<details><summary>Click to View Commands</summary>

| Name        | Description                               | Options                                                   |
|-------------|-------------------------------------------|-----------------------------------------------------------|
| ⏸️         | Pauses the current song                    |                                                           |
| ▶️         | Resumes the current song                   |                                                           |
| ⏭️         | Skips the current song                     |                                                           |
| 🔁         | Loops the queue                            |                                                           |
| 🔂         | Loops currently playing track              |                                                           |
| 🔀         | Shuffles the queue of songs that weren't yet played           |                                        |
| `play`     | Searches and plays/adds the track into queue                  | `search`: search prompt / URL          |
| `playlist` | Allows you to pick tracks from 25 last songs in the playlist  | `playlist_url`: url of playlist        |
| `search`   | Gives you list of tracks to choose from the search prompt     |  `search`: search prompt               |
| `seek`     | Gets into certain timestamp in currently playing track        | `second`: timestamp in seconds         |
| `jump`     | Skips to a specific song in the queue       | `index`: index number in the queue                       |
| `remove`   | Removes a song from the queue               | `index`: index number in the queue                       |
| `volume`   | Changes the volume 10% is default)          | `volume`: from 1 to 100 (in %)                           |
| `clear`    | Clears the queue                            | `song`: The song number                                  |
| `history`  | Saves all requests into google sheets log   | (use prefix) `limit`: amount of msgs to take into account|
| `create_stats` | Creates stats out from the requests log | (use prefix)                                             |
</details>

## 👀 Example
<gif image>
