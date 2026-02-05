# ARKTECH

A modern React storefront demo with product listings, product details, cart management, and a simple account flow. Built with Create React App and React Router.

## Table of Contents
- [Features](#features)
- [Screens](#screens)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Scripts](#scripts)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Deployment (Vercel)](#deployment-vercel)
- [Troubleshooting](#troubleshooting)
- [Documentation](#documentation)

## Features
- Product listing and details
- Cart add/update/remove flow
- Simple login/register/profile screens
- Responsive layout and carousels
- Client-side routing with React Router

## Screens
- Home
- Products
- Product Details
- Cart / Empty Cart
- Place Order
- Our Team
- Login / Register / Profile

## Tech Stack
- React 19, React Router
- Create React App
- Swiper / React Slick
- Axios

## Getting Started
1) Install dependencies
	- `npm install`
2) Run the app
	- `npm start`

The app runs at http://localhost:3000.

## Scripts
- Start dev server: `npm start`
- Build for production: `npm run build`
- Run tests: `npm test`

## Project Structure
- `src/` — app entry and routing
- `src/components/` — UI pages and sections
- `src/CSS/` — page-level styles
- `public/` — static assets and HTML template

## Configuration
This project uses Create React App defaults. If you add environment variables later, prefix them with `REACT_APP_` and restart the dev server.

## Deployment (Vercel)
This project is ready for Vercel out of the box. A Vercel config is included to enable SPA routing.

### Quick Deploy
1) Push this repo to GitHub
2) Import it in Vercel
3) Use the defaults:
	- Build Command: `npm run build`
	- Output Directory: `build`

## Troubleshooting
If you see a blank page after deploy, ensure the `vercel.json` rewrite is present and that the output directory is set to `build`.

## Documentation
See [docs/README.md](docs/README.md) for extended setup and deployment notes.
