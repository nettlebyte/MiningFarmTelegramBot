# Mining Farm Telegram Bot

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![aiogram](https://img.shields.io/badge/aiogram-3.13.1-2CA5E0?logo=telegram&logoColor=white)](https://docs.aiogram.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A Telegram group bot featuring a virtual mining farm simulator. Build your own mining operation, upgrade equipment, earn in-game currency, compete with other players, and join clans.

## Features

- **Mining System** — Build, manage, and upgrade your virtual mining farm.
- **Equipment Shop** — Purchase hardware and manage your inventory.
- **Wallet & Bank** — Manage virtual USD and BTC balances.
- **Player Transfers** — Send in-game currency to other players.
- **Clans** — Create clans, invite members, and manage a shared treasury.
- **Leaderboards** — Compete with other players and track rankings.
- **Player Profiles** — View player statistics and progress.
- **Admin Panel** — Manage players, the in-game economy, and bot operations.
- **Database Backups** — Optional automatic SQLite backups.

## Requirements

- Python 3
- Telegram Bot Token

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nettlebyte/MiningFarmTelegramBot.git
   cd MiningFarmTelegramBot
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the project directory:

   ```env
   BOT_TOKEN=your_bot_token
   ADMIN_ID=0
   DB_BACKUP_CHAT_ID=0
   SOUNDCLOUD_CLIENT_ID=
   JAMENDO_CLIENT_ID=
   ```

4. Start the bot:

   ```bash
   python main.py
   ```

## Main Commands

| Command | Description |
|---|---|
| `/start` | Start the bot |
| `/mining` | Open the mining farm |
| `/shop` | Open the equipment shop |
| `/inventory` | View inventory |
| `/wallet` | Open wallet |
| `/profile` | View player profile |
| `/leaders` | View leaderboard |
| `/clan` | View clan information |
| `/wiki` | Browse the equipment encyclopedia |
| `/help` | Show available commands |

## Technologies

- Python
- aiogram 3
- SQLite
- Requests
- python-dotenv

## Notes

- Designed for Telegram groups and supergroups.
- Some commands require a subscription to the news channel.
- The database is created automatically on first launch.
- BTC and USD are virtual in-game currencies, not real cryptocurrency transactions.

## License

This project is licensed under the [MIT License](LICENSE).
