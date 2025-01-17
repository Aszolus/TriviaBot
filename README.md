# TriviaBot Classic - Modified Edition

## Table of Contents

- [Overview](#overview)
- [Disclaimer](#disclaimer)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)
- [Contact](#contact)

## Overview

**TriviaBot Classic** is a modified version of the original [TriviaBot](https://www.curseforge.com/wow/addons/triviabot) addon for World of Warcraft Classic. This project introduces essential modifications to enhance compatibility with Blizzard’s latest API restrictions, specifically addressing issues related to automation and restricted API calls.

## Disclaimer

**TriviaBot Classic** is **not** the original creation of [Original Creator's Name](https://www.curseforge.com/wow/addons/trivia-bot). This project serves as a community-driven fork aimed at improving the addon's functionality within the constraints imposed by Blizzard’s API changes.

**All rights, trademarks, and logos belong to their respective owners.** This project is intended for personal use and modification by the WoW Classic community.

## Features

- **Manual Announcement Controls**: Removed automated chat messages to comply with Blizzard’s anti-spam policies. Now, announcements such as “Announce Winner” are triggered manually via in-game buttons.
- **Scorekeeping**: Retained the original scorekeeping logic, including tracking player speeds, win streaks, and points.

## Usage

### Starting the Trivia Game

1. **Open TriviaBot GUI**:
   - Use the designated slash command (e.g., `/triviabot`).

2. **Start the Game**:
   - Click the **Start Trivia** button to begin the game.

### Answering Questions

- **Players** can answer by typing in the designated chat channel.
- The first correct answer will be recorded, and the **Time’s Up** button will change to **Announce Winner**.

### Announcing Winners

1. **Manual Announcement**:
   - Once a correct answer is received, the **Time’s Up** button label changes to **Announce Winner**.
   - Click **Announce Winner** to publicly announce the winner (of that question).

### Additional Controls

- **Skip Question**: Allows the host to skip the current question.
- **Next Question**: Manually advances to the next question.
- **Hint**: Provides a hint for the current question.
- **Time Alert**: Sends a time warning message to players.
- **Game Scores**: Displays the current game scores.
- **All-Time Scores**: Shows the all-time leaderboard.

### Question Lists
Questions and Question lists remain unchanged from the previous version of TriviaBot.  

[LoreWalkers of Silvermoon](https://www.curseforge.com/wow/addons/lorewalkers-of-silvermoon) is a popular plugin.  You can find more listed in the original readme or even create your own.

## Contributing

Contributions are welcome! If you’d like to enhance TriviaBot Classic, please follow these steps:

1. **Fork the Repository**: Click the **Fork** button on the top right of the repository page.
2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/your-username/TriviaBotClassic.git
