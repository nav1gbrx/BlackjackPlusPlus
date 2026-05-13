# Blackjack Casino Game

Blackjack Casino is a single-player Blackjack game built with Python and Tkinter.

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
