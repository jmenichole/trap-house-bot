# TRAP HOUSE Discord Bot

A Discord bot for community management with focus on member engagement, moderation, and achievement tracking.

## Features

- Welcome System
  - Auto-welcome messages
  - DM rules to new members
  - Default role assignment

- Verification System
  - Reaction-based verification
  - Captcha verification option
  - Auto-role assignment

- Point & Achievement System
  - Track hits in showoff channel
  - Point-based achievements
  - Leaderboard system

- Tip Tracking
  - Monitor tip amounts
  - Track top tippers
  - Total tips calculation

- Moderation Tools
  - Channel cleaning
  - Channel lock/unlock
  - Timeout functionality
  - Warning system

## Setup

1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Copy `.env.example` to `.env` and fill in your values
4. Run the bot: `python src/bot.py`

## Configuration

Update the following values in your `.env` file:

- BOT_TOKEN: Your Discord bot token
- WELCOME_CHANNEL_ID: Channel ID for welcome messages
- SHOWOFF_CHANNEL_ID: Channel ID for tracking hits
- TIPS_CHANNEL_ID: Channel ID for tip tracking
- DEFAULT_ROLE_ID: Role ID for new members