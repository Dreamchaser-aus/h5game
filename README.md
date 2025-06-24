# HTML5 Dice Game (Flask)

This is a simple Flask web app to play a dice game against the computer. You must bind your Telegram user ID before playing.

## Features

- Login page to bind user ID
- Dice vs system (win/loss logic with +10/-5 points)
- User point and play tracking
- Game logs stored to PostgreSQL
- Deployment-ready on Railway

## Running Locally

```bash
pip install -r requirements.txt
python main.py
```

## Railway Deployment

1. Upload the folder to Railway as a new Python project.
2. Add a PostgreSQL database and set the following environment variable:
   - `DATABASE_URL`
3. Optionally add `SECRET_KEY` to secure sessions