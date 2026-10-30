# Civic

A mobile web experience for reporting public utility issues, tracking progress and confirming repairs with camera evidence.

## Run locally

Run `node preview.mjs` and open the printed address. Camera and location require HTTPS or localhost. The app uses plain HTML, CSS and JavaScript with Geist typography; no build step is required.

## Deploy

Import this repository into Vercel. Framework: Other. Output directory: `dist`. No build command is needed. `vercel.json` supplies these settings.

## Project scope

This design assignment implements the citizen experience. Reports and evidence are stored in the browser. Department updates and media analysis are simulated. Email verification uses `123456`; it does not send email. There is no municipal backend integration.

The app supports live photo/video capture, required location and landmark, report review, progress tracking, support, and citizen verification evidence.
