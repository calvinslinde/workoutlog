# TropicalFit

A workout tracker that installs on an iPhone home screen and works offline.

**Use it:** https://calvinslinde.github.io/workoutlog/

## What it does

- Logs exercises, sets, weight, reps, RPE, and notes.
- Rest timers that keep running in the background.
- Streaks, personal-record detection, weekly charts, and a muscle heatmap.
- An optional coach built on Google's Gemini. You paste in your own key. The coach can also read old workout logs you upload and add them to your history.
- Export to JSON or CSV.

## Setup

1. Fork or clone this repository and turn on GitHub Pages for the main branch.
2. Open the page on your iPhone in Safari, then Share and Add to Home Screen.
3. For the coach, open Settings, then AI Setup, and paste a key from aistudio.google.com.

## How it's built

Plain HTML, CSS, and JavaScript with no framework. IndexedDB for storage, a service worker for offline use, and the Screen Wake Lock API with silent audio to keep timers running in the background.

## Your data

Everything stays on your device. The coach sends your workout data to Google's Gemini only when you ask it a question or request an analysis.
