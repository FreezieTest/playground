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

| Name        | Description                               | Options                                   |
|-------------|-------------------------------------------|-------------------------------------------|
| ⏸️         | Pauses the current song                    |                                           |
| ▶️         | Resumes the current song                   | `command`: The command you want to get info  |
| ⏭️         | Skips the current song                     |          on                               |
| 🔁         | Loops the queue                            |                                           |
| 🔂         | Loops currently playing track              |                                           |
| 🔀         | Shuffles the queue of songs that were not played   |                                           |
| `play`     | Clears the queue                            |                                           |
| `playlist` | Allows you to pick tracks from 25 last songs in the playlist  |                                           |
| `search`   | Gives you list of tracks to choose from the search prompt      |                                           |
| `seek`     | Gets into certain timestamp in currently playing track        |                                           |
| `jump`     | Skips to a specific song in the queue       | `song`: The song you want to play            |
| `volume`   | Changes the volume [10% default]            |                                           |
| `remove`   | Removes a song from the queue               |                                           |
| `clear`    | Clears the queue                            | `song`: The song number                      |
| `history`  | Saves all requests into google sheets log   | have to use prefix                                          |
| `create_stats` | Creates stats out from the requests log | have to use prefix                                          |

</details>

## 👀 Example
<gif image>
