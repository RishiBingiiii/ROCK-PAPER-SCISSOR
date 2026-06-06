# 🪨 Rock · Paper · Scissors — Tkinter GUI

## Files
```
rps_game/
├── game.py       ← main application
├── scores.json   ← auto-created on first run (persistent stats)
└── README.md
```

## Requirements
Python 3.x (Tkinter is included in the standard library — no pip installs needed)

## Run
```bash
python game.py
```

## Features
| Feature | Details |
|---|---|
| 🎮 GUI | Dark-themed Tkinter window |
| 🪨📄✂️ Emoji display | Big emoji show both moves each round |
| 🏆 Match modes | Best of 3 / 5 / 7 — switch anytime |
| 📊 Match scoreboard | Live round tracker inside each match |
| 💾 Persistent stats | All-time wins/losses/draws saved to `scores.json` |
| 🔄 Reset | One-click wipe of all-time stats |

## How to Play
1. Select a match mode (Best of 3/5/7) at the top
2. Click **🪨 Rock**, **📄 Paper**, or **✂️ Scissors**
3. First to reach the target wins — a popup announces the result
4. Hit **Play Again** for a new match or **Quit** to exit

## Next Steps (from the roadmap)
- **Version 3**: Add a smart AI that tracks your move history
- **Version 5**: Stats dashboard with Pandas + Matplotlib charts
- **Version 6**: Add images/animations to the Tkinter GUI
- **Version 7-8**: Export `scores.json` into a dataset for ML experiments

