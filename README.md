
# BoomBot

BoomBot is a Discord bot used for personal use. The bot can play music on any Discord Server.

# Install

Download the `main.py` file, and install the dependencies:
```
- discord
- dotenv
- yt_dlp
```

You also need to install `ffmpeg` (Linux only, can run using `ffmpeg.exe` on Windows).

# Configuration

You'll need a Discord Bot with all access, and the matching Token.

Create a `.env` file next to the `main.py`, set as follow:
```
DISCORD_TOKEN="<Your Discord Token>"
```
You'll also need to add the bot to the server of your choice.

# Start the bot

Run:
```bash
python3 main.py
```

# Commands

## Join the channel

You must be in a vocal channel before. Type `!join` for the bot to join your channel.

## Play a music

`!play_song <url to the YouTube video>`

## Stop the music

`!pause`

## Resume the music

`!resume`

## Leave the channel

`!leave`

