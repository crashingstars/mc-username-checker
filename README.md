# mc-username-checker
Private Minecraft Java username availability checker and Discord bot.
# Minecraft Username Checker

Minecraft Username Checker is a private, non-commercial Discord bot that runs locally on my personal computer.

## Purpose

The application searches for Minecraft: Java Edition usernames that may be:

- Confirmed as currently available
- Within an estimated username release or lock period
- Clean English vocabulary words
- Short or OG-style usernames
- Three-character usernames
- Four-character usernames

## Authentication

The application uses Microsoft's official browser-based OAuth authentication flow for my personal Minecraft account.

Authentication is used only to distinguish usernames that are confirmed available from usernames that simply do not have a currently assigned public Minecraft profile.

The application does not collect or store Microsoft account passwords.

## Safety and limitations

The application does not:

- Automatically claim usernames
- Automatically change Minecraft profile names
- Bypass rate limits
- Use proxies or account rotation
- Provide authentication services to other users
- Sell or share user information
- Access accounts belonging to other people

Requests are rate-limited and results are stored in a local database to reduce repeated checks.

## Data storage

Authentication tokens and configuration values are stored locally in a private `.env` file on my computer.

The `.env` file, Discord bot token, Microsoft access tokens, and refresh tokens are not included in this public repository.

## Intended users

This application is for private personal use and will only be operated by the application owner.
