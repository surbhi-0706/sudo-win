# Big Boss — Tech House Command Center

A single-file, demo-ready control dashboard for the Tech House challenge. It runs with no backend and no install step.

## Run

Open `index.html` directly in a browser, or serve the folder with any static server. Example:

```bash
python -m http.server 4173
```

Then visit `http://localhost:4173`.

## What is implemented

### Mandatory
- Contestant management with 10 prepared contestants, names, teams, points, status.
- Live leaderboard sorted by score.
- Task management with assignment modal and live completion state.
- Point system with +25 / -25 controls.
- Captaincy with instant captain switching.
- Nominations with immunity protection.
- Immunity grants and automatic nomination removal when immunity is granted.
- Danger Zone showing current nominees.
- Big Boss announcements with broadcast log.
- Task timer with start, pause, reset, and 5/15/30 minute presets.
- Live house statistics: active count, top scorer, completed tasks, nominees.
- Eviction flow with confirmation; evicted contestants disappear from active leaderboard.

### Bonus touches
- LocalStorage persistence — refresh the page and state remains.
- Contestant profile drawer.
- Fast-actions control strip.
- Show/hide evicted contestants.
- Demo reset button to restore the prepared scenario.
- Responsive layout for tablet/mobile.
- Live clock and live feed indicator.
- Toast confirmations for important actions.
- Preloaded scenario that makes the dashboard immediately demoable.




