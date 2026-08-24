# Focus Timer (포커스 타이머)

A minimal, single-file Pomodoro-style focus timer with a task list, built with vanilla HTML/CSS/JS — no build step, no dependencies.

## Features

- **Timer modes** — 25-minute focus session, 5-minute short break, 15-minute long break
- **Circular progress ring** that fills as time elapses
- **Session tracking** — counts completed focus sessions per day (persisted in `localStorage`)
- **Task list** — add, complete, and delete tasks (persisted in `localStorage`)
- **Browser tab notification** — page title changes when a session ends

## Usage

Just open `index.html` in a browser — no installation or server required.

```bash
open index.html   # macOS
start index.html  # Windows
```

## Tech

Plain HTML, CSS, and JavaScript in a single file. State is kept in `localStorage` under the `focusTimer.*` keys, so your tasks and session count persist across visits.
