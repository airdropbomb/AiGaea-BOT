# AI Gaea Network BOT
AI Gaea Network BOT

- Register Here : [AI Gaea Network](https://app.aigaea.net/register?ref=gaMHbVjrcOnGUL)
- Use Code: gaMHbVjrcOnGUL
- Download Extension

## Features

  - Auto Get Account Information
  - Auto Run With [Proxyscrape Free Proxy](https://proxyscrape.com/free-proxy-list) - `Choose 1`
  - Auto Run With Private Proxy - `Choose 2`
  - Auto Run Without Proxy - `Choose 3`
  - Auto Rotate Invalid Proxies - `y` or `n`
  - Auto Claim Daily Reward
  - Auto Complete Training
  - Auto Send Ping Every 10 Minutes
  - Multi Accounts With Threads

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/airdropbomb/AiGaea-BOT.git && cd AiGaea-BOT
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Configuration

### Screenshots

<div style="text-align: center;">
  <img src="image.png" alt="Image" width="500"/>
</div>

- **accounts.json:** You will find the file `accounts.json` inside the project directory. Make sure `accounts.json` contains data that matches the format expected by the script. Here are examples of file formats:
  ```json
    [
        {
            "browserId": "Your browser_id 1",
            "gaeaToken": "Your aigaea__token 1"
        },
        {
            "browserId": "Your browser_id 2",
            "gaeaToken": "Your aigaea__token 2"
        }
    ]
  ```

- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```

