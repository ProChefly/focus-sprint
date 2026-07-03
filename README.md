# Focus Sprint

A single-file Pomodoro-style focus timer. Pick a task, run a 25-minute focus sprint, take a break, repeat.

## Usage

Open `index.html` in a browser — no build step or dependencies required.

- Add a task, click it to select it as the active task, then hit **Start**.
- Each completed focus sprint is 25 minutes, followed by a 5-minute break (a 15-minute long break every 4th sprint).
- Progress (sprints, focus minutes, and day streak) is saved to `localStorage`, so it persists across reloads.

## Features

- Task list with per-task sprint counts
- Daily stats and streak tracking
- Browser notifications when a sprint or break ends
