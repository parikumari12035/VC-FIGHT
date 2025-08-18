<h1 align="center">🎶 VC UserBot</h1>

<p align="center">
  <b>A Powerful Telegram Voice Chat UserBot</b><br>
  Built with ❤️ using <a href="https://github.com/pyrogram/pyrogram">Pyrogram</a> + <a href="https://github.com/pytgcalls/pytgcalls">PyTgCalls</a>  
</p>

---

## ✨ Features
- 🎧 Join Group & Channel Voice Chats  
- 🎵 Play Music via Name/URL  
- ⏹ Stop / ⏭ Skip Songs  
- ⚡ Easy Setup — Just add your String Session  
- ☁️ Works 24/7 on **Heroku**  

---

## 🎵 Commands

| Command | Description |
|---------|-------------|
| `.join` | Join Group Voice Chat |
| `.cjoin` | Join Channel Voice Chat |
| `.play [song/url]` | Play song in Group VC |
| `.cplay [song/url]` | Play song in Channel VC |
| `.stop` | Stop current song |
| `.skip` | Skip current song |
| `.leave` | Leave VC |

---

## 🚀 Deployment

### 🔹 Heroku (One-Click Deploy)

<p align="center">
  <a href="https://heroku.com/deploy">
    <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy on Heroku"/>
  </a>
</p>

---

### 🔹 Local Deploy
```bash
git clone https://github.com/YourUser/VCUserBot
cd VCUserBot
pip install -r requirements.txt
python3 -m vcuserbot
