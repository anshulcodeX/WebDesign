# Gather event discovery website

Gather is a responsive event discovery and registration website built with HTML5, CSS3, and vanilla JavaScript. It demonstrates a polished event listing experience with practical search, filtering, event details, and a registration flow.

## Features

- Responsive layouts for mobile, tablet, and desktop
- Search events by title, category, venue, area, and description
- Filter by Music, Food & drink, Wellness, and Creative
- Event detail dialogs with date, time, venue, description, and registration action
- Registration form validation for name, email, and phone number
- Confirmation dialog and localStorage registration management
- Light and dark themes, plus a mobile navigation menu

## Run locally

Open `index.html` in a modern browser. The event photos and web fonts are loaded from Unsplash and Google Fonts, so those visual assets need an internet connection. All site behavior runs in the browser; no server or build step is required.

## Deploy

This is a static site. To publish with GitHub Pages, push this folder to a GitHub repository, open **Settings → Pages**, choose the `main` branch and `/ (root)` (or the folder containing `index.html`), then save. For Netlify or Vercel, import the repository and use the project folder as the site root; no build command is needed and the publish directory is `.`.

## Project files

- `index.html` — semantic page structure and dialogs
- `styles.css` — visual design and responsive breakpoints
- `script.js` — event data, rendering, filtering, validation, dialogs, and local storage

## Notes

Event details are sample content for the project demo. Registrations are stored only in the current browser's local storage and are not sent to a server. Replace the sample event data and connect a secure backend before using this as a live booking service.
