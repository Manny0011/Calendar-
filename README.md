# Orbit Planner 2.0 🌌

A responsive, animated space-themed planner built with HTML, CSS and vanilla JavaScript.

## Features
- Daily, weekly and monthly calendar views
- Add, edit, complete and delete tasks
- Task date, time, priority, category, notes and reminders
- Weekly/monthly goals with progress steps
- Search and filters
- LocalStorage persistence
- Installable PWA with dedicated 192px/512px app icons and favicon
- Notification settings: task reminders, daily pending-task digest, goal deadlines, weekly recap
- Test notification button
- Offline shell caching

## Run locally
Serve this folder through a local web server (PWA and notifications need `localhost` or HTTPS):
- VS Code: install/use Live Server and open `index.html`
- Or run `python -m http.server 8000` inside this folder, then open `http://localhost:8000`

## Install on Android
1. Upload this folder to an HTTPS static host (for example GitHub Pages or Netlify).
2. Open the HTTPS website in Chrome on Android.
3. Use Chrome menu → **Install app** or **Add to Home screen**. The dedicated PNG app icons are configured in the manifest.

## Notification limitation
The app can schedule reminders while Orbit is open and browser notifications are permitted. Static websites cannot guarantee scheduled notifications after the browser/app is fully closed. That requires a push-notification backend/service and user permission.

## Data
Tasks, goals and notification preferences are stored in this browser's LocalStorage. Clearing browser site data will remove them. This starter does not sync between devices.
