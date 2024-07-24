# TonGoldMiner

💬 You can reach me through a bot connected via Telegraph! 💬


💰 The cost of this bot is 3 tons. 💰


📧 For inquiries, contact me at [@Gerfesto](https://t.me/gerfesto_bot). 📧

# Use Python 3.11 or 3.10

## Features

| Feature              | Supported |
|----------------------|:---------:|
| Auto mining          |     ✅     |
| Purchase raccoons/cats |     ✅     |
| Support tdata / pyrogram .session / telethon .session |     ✅     |
| Sends error message to Telegram |     ✅     |

## .env File Settings

| Setting                  | Description                                                                                               |
|--------------------------|-----------------------------------------------------------------------------------------------------------|
| **API_ID / API_HASH**    | Platform data to launch the Telegram session from _(default - Android)_                                    |
| **BUY_MINER**            | Should the bot buy miners at all? _(True / False)_                                                         |
| **BUY_MINER_NUMBERS**    | How many miners your bot will buy and will not purchase more  _(e.g., 2)_                                 |
| **REF_ID**               | Your referral code that comes after ?start=                                                               |
| **UPGRADE_MINER**        | Should your miners be upgraded? _(True / False)_                                                          |
| **UPGRADE_MAX_LEVEL_MINER** | Up to what level should we upgrade them? _(e.g., 10)_                                                 |
| **UPGRADE_STORAGE**      | Should your treasury be upgraded? _(True / False)_                                                        |
| **UPGRADE_MAX_LEVEL_STORE** | Up to what level should we upgrade it? _(e.g., 10)_                                                  |
| **MIN_SAVE_COIN**        | Minimum coin amount to keep in your balance _(e.g., 10000)_                                              |
| **SLEEP_TIME**           | Delay in seconds when the minimum coin is reached  _(e.g., [3500,3600])_                                 |
| **LOGGER_FORMAT**        | String variable determining the console output format _(e.g., "{time:YYYY-MM-DD HH:mm:ss} {message}")_    |
| **USE_PROXY_FROM_FILE**  | Use proxy from `bot/proxies.txt` _(True / False)_                                                        |

## Installation
# Linux and MacOS
```
~/TonGoldMiner >>> python3 -m venv venv
~/TonGoldMiner >>> source venv/bin/activate
~/TonGoldMiner >>> pip3 install -r requirements.txt
~/TonGoldMiner >>> cp .env-example .env
~/TonGoldMiner >>> nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
~/TonGoldMiner >>> python3 main.py

# Windows

~/TonGoldMiner >>> python -m venv venv
~/TonGoldMiner >>> venv\Scripts\activate
~/TonGoldMiner >>> pip install -r requirements.txt
~/TonGoldMiner >>> copy .env-example .env
~/TonGoldMiner >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/TonGoldMiner >>> python main.py
```
