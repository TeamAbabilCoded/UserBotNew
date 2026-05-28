# Telegram Userbot

Simple Telegram Userbot built with Python + Telethon.

## Features

* Telegram media downloader
* TikTok downloader
* YouTube video downloader
* YouTube MP3 downloader
* Alive status
* User access system
* QR Generator
* System Info

---

# Installation

## Clone Repository

```bash id="e6q14o"
git clone https://github.com/TeamAbabilCoded/UserBotNew.git
cd UserBotNew
```

---

## Install Requirements

```bash id="8l42pf"
pip install -r requirements.txt
```

---

## Install FFmpeg

### Linux

```bash id="vbjbyi"
apt install ffmpeg
```

### Windows

Download:
https://ffmpeg.org/download.html

---

# Config

Edit `config.py`

```python id="6bh8lr"
API_ID = 123456
API_HASH = "YOUR_API_HASH"
SESSION_NAME = "userbot"

OWNER_NAME = "YourName"

ALIVE_MEDIA = "assets/alive.mp4"

DOWNLOAD_DIR = "download"
```

---

# Run Userbot

```bash id="0k1rvx"
python main.py
```

First login:

* Input Telegram number
* Input OTP code
* Input 2FA password (if enabled)

Session will automatically be saved.

---

# Commands

## Download

```text id="zlt2ln"
.down
```

Reply media to download.

```text id="pv73zt"
.down link
```

Download Telegram media from link.

```text id="pwtm4v"
.tt link
```

Download TikTok video.

```text id="n8rxxm"
.yt link
```

Download YouTube video.

```text id="kixs08"
.ytmusik link
```

Download YouTube MP3.

---

# Status

```text id="n9trz9"
.alive
.ping
.sysinfo
.myplan
.id
```

---

# Tools

```text id="4wxxi9"
.qr text
.calc 1+1
.upper text
.lower text
.reverse text
.copy
.save
```

---

# Owner Commands

```text id="hh5k2f"
.makeuser id days label
.users
.broadcast text
.restart
.shutdown
```

---

# Notes

* Downloaded files are saved in `download/`
* Session file is automatically generated
* Pastebin is used for user access system

---

# Disclaimer

Use responsibly and only for content you have permission to access.
