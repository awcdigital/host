# Python Script Hosting Bot

A Telegram bot to host and manage Python scripts.

## Deployment on Render.com

1. Fork this repository
2. Create a new Render.com account
3. Click "New" -> "Web Service"
4. Connect your GitHub account
5. Select this repository
6. In settings:
   - Name: `python-script-bot`
   - Region: Choose closest
   - Branch: `main`
   - Runtime: Python 3
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `python main.py`
7. Add environment variables:
   - `TELEGRAM_TOKEN`: Your bot token from @BotFather
   - `ADMINS`: Your admin user ID (comma separated if multiple)
8. Click "Create Web Service"

## Features
- Host Python scripts
- Start/stop scripts
- Admin controls
- Script status monitoring
