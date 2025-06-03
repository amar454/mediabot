# mediabot

A simple, easy to configure, and minimal Discord bot with 

## Summary of features

- Download, play, and save songs via simple Discord commands.
- Easily change the command prefix, which is ! by defualt.
- Songs are saved to the hosting computer, and can be managed via Disocrd commands.
- Admin role permissions are required for certain tasks and the role name may be changed.
- Logs each command to terminal and logging file.
- Member leave/join logs.
- Low memory overhead.

---

## Requirements/dependencies

- Python 3.8+
- `discord.py` 
- `pytube`
- `ffmpeg` (add to path)

# Installation & Setup

1. Clone the repository with `git clone https://github.com/amar454/mediabot.git`, and then type `cd mediabot` to chnage to the repository directory.

2. Install ffmpeg at https://ffmpeg.org/download.html 

3. Install dependencies with `pip install -r requirements.txt`.

4. If bot_data.json doesn't exist, create it using `touch 

```json
{
  "admin_role_name": "Admin",
  "prefix": "!"
}
```

5. Edit `'key'` in the line `client.run('key')` with your Discord Bot API token. You need to get this yourself from the Discord developers portal.

6. Run the bot with `python bot.py`.

--- 

