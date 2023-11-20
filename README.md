# Bard-Discord-AI
## Discord Bot Documentation

### Overview

This documentation provides a comprehensive guide to the Discord bot, outlining its functionalities, usage instructions, and technical details.

### Purpose

The Discord bot serves as a versatile tool for generating text, translating languages, writing creative content, and answering questions in an informative way. It seamlessly interacts with the Discord platform, allowing users to engage with the bot's capabilities through simple commands.

### Installation and Setup

#### Prerequisites:

* A Discord account
* A Bard account with __Secure-1PSID cookie value

#### Steps:

1. **Create a Discord application:**
   * Visit the Discord Developer Portal (https://discord.com/developers/docs/intro) and log in with your Discord account.
   * Click on "New Application" and provide a name for your bot application.
   * Click on the "Bot" tab and enable the "Public Bot" option (if desired).
   * Click on the "Add Bot" button and copy the generated bot token.
   * Store the bot token and Bard __Secure-1PSID cookie value in a configuration file named `config.json` using the following format:

```json
{
  "bot_token": "YOUR_BOT_TOKEN",
  "bard_cookie_value": "YOUR_BARD_COOKIE_VALUE"
}
