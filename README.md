# Abir Messenger Bot 🤖🇧🇩

A fun and interactive Facebook Messenger bot built in Python using `fbchat`. Supports Bengali replies, group commands like `.kiss`, `.hug`, `.kill`, `.hack`, and more!

---

## ✨ Features

- `.kiss @user` – Send a funny kiss with GIF and mention 💋  
- `.hug @user` – Send a warm hug 🤗  
- `.kill @user` – Playfully kill a user 💀  
- `.hack @user` – Fake hack simulation 👾  
- `.bot` – Bot will reply in Bangla 🧠  
- Mention support: Bot will mention user back  
- All commands respond in Bangla with emojis and GIFs

---

## ⚙️ Setup Instructions

1. Clone this repo or download the ZIP:

    ```bash
    git clone https://github.com/tor-username/messenger-bot.git
    cd messenger-bot
    ```

2. Install required package:

    ```bash
    pip install fbchat
    ```

3. Fill up the `config.json` file like this:

    ```json
    {
      "email": "your_facebook_email",
      "password": "your_password",
      "admins": ["your_facebook_numeric_id"]
    }
    ```

4. Run the bot:

    ```bash
    python bot.py
    ```

---

## 🧠 Admin Features

Only users in `admins` list can add/edit commands by editing `all_commands.py` inside `commands/`.

---

## 🛡️ License

This project is licensed under the **MIT License** – use freely and modify with love.

---

## ❤️ Made With

Built by **Abir** a.k.a the chillest botmaster from BD 😎
