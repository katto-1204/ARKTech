# Arktech Storefront Documentation

## Overview
Arktech Storefront is a React demo app featuring product browsing, product details, cart management, and a basic account flow.

## Local Development
1) Install dependencies
- `npm install`

2) Start the dev server
- `npm start`

The app runs at http://localhost:3000.

## Build
- `npm run build`

The production build is generated in the `build` directory.

## Project Structure
- `src/components/` — UI pages and sections
- `src/CSS/` — Page-level styles
- `public/` — Static assets and HTML template

## Deployment (Vercel)
This app is compatible with Vercel’s Create React App preset.

### Option A: Vercel Dashboard
1) Push the repo to GitHub
2) Import the repo in Vercel
3) Use these settings:
   - Build Command: `npm run build`
   - Output Directory: `build`

### Option B: Vercel CLI
1) Install the CLI: `npm i -g vercel`
2) Run `vercel` and follow the prompts

### SPA Routing
A `vercel.json` file is included to ensure all routes are rewritten to `index.html`.

## Notes
- If you add environment variables later, remember to define them in Vercel project settings.
