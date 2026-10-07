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

## Suggested 3-minute demo

1. Start on **Command Center**. Point out the four live stats, House Captain, countdown, leaderboard, Danger Zone, tasks and announcement feed.
2. Click **Contestants**. Show the 10-person roster. Give Arjun +25 and -25 once; explain that the leaderboard follows the same state.
3. Grant **Kabir** immunity. Try to nominate him again: the UI blocks it. This demonstrates the immunity rule.
4. Nominate **Riya**. Open **Danger Zone** and show that she appears there immediately.
5. Open **House Control** and switch captain to **Riya**. The captain badge moves everywhere.
6. Open **Tasks**, create “Midnight kitchen check” for a contestant, then mark it complete. The task board updates.
7. Start the timer, pause it, then reset it. Use a 5-minute preset for a quicker live demonstration.
8. Broadcast “Housemates, report to the activity area in five minutes.” Show the message in the broadcast log.
9. Return to **Danger Zone** and evict a nominee. The active count and leaderboard update, proving eviction is wired into the central state.
10. End on **Command Center** and summarize: “Every operational action here is tied to one House state, so the dashboard updates across views instead of being a collection of fake screens.”

## Visual direction

The UI deliberately avoids the usual generic dashboard look. It uses a restrained black/graphite control-room aesthetic, mono labels for system information, sharp panels, small status tags, limited accent colors, and tight spacing.
