# Blackjack Casino Game

Blackjack Casino is a single-player Blackjack game built with Python and Tkinter.

## Game Overview

Welcome to Blackjack++, a modernized and progression-based version of the classic casino card game Blackjack. This game enhances the traditional experience through unlockable powerups, strategic gameplay mechanics, persistent progression, sound effects, and an interactive graphical user interface. Designed not only for entertainment but also to demonstrate practical Object-Oriented Programming concepts, Blackjack++ showcases modular class design, game state management, file handling, and GUI integration using Python. This game is a Finals Project of the 1st year students in Angeles University Foundation under the course of Computer Engineering for their Object-Oriented Programming subject to be submitted to Jeremy A. Tecson.

## Gameplay

How To Play:

Each player starts with two cards and tries to get a hand value as close to 21 as possible without going over. Number cards keep their value, face cards are worth 10, and Aces can count as either 1 or 11 depending on the hand. On your turn, choose to Hit to draw another card or Stand to keep your current total and end your turn. After all players finish, the dealer reveals their cards, and the hand closest to 21 without busting wins the round.

## The Twist:

As players earn more money, they unlock special powerups such as Lucky Draw, Peek, Swap, and Bust Shield, each giving unique advantages or risks during gameplay. Only one powerup can be used per round, and once activated, it enters a 3-round cooldown before it can be used again.

Power-ups Rules:
Lucky Draw improves your next Hit by increasing the chance of drawing cards that bring you closer to 21. 
Peek reveals the Dealer’s hidden card range (low 2–6, mid 7–9, or high 10–Ace). 
Swap lets you exchange hands with the Dealer, but it’s risky and can backfire. 
Bust Shield raises the bust limit from 21 to 24 for one round only.




## What is included

- `mlaknyak.py` - the main game source code
- `dist/mlaknyak.exe` - packaged Windows executable
- `card_draw.wav` (optional) - card draw sound effect file
- `payout.wav` (optional) - generated payout sound file

## Requirements

- Windows
- Python 3.14+ for running from source
- `pygame` is optional for sound support
- `Pillow` is required for the GUI background image effects

## Running from source

1. Open PowerShell in the game folder.
2. Run:
   ```powershell
   python mlaknyak.py
   ```

## Running the executable

1. Open `dist` folder.
2. Run `mlaknyak.exe`.

## Packaging into an executable

The game was packaged using PyInstaller.

To rebuild the executable, use:

```powershell
python -m pip install pyinstaller
python -m PyInstaller --onefile --windowed mlaknyak.py
```

The generated executable will appear in the `dist` folder.

## Notes

- If `pygame` is installed and sound files are present, the game plays card and payout sounds.
- If sound is unavailable, the game still runs normally.
- Save and load progress using the in-game buttons.


## File Access

- Total file size exceeded 25MB, therefore it cannot be uploaded into repository.
- Access files here in Google Drive: https://drive.google.com/drive/folders/1wYOsEz2SaUpOkg_njF2-MfwEaC-VkcY_?usp=sharing
