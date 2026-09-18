# BRIOnline Travel

**BRIOnline = Book. Reserve. Itineraries Online Travel**

A GitHub-ready travel search frontend designed to connect to a server-side travel API proxy.

## Why a backend/proxy?
Never expose Travelpayouts/API credentials in browser JavaScript. Put secrets in environment variables on the server.

## Structure
- `public/` — browser UI
- `api/` — serverless API endpoints
- `src/` — application source/config
- `.env.example` — environment variable template

## Deploy
This project is designed for Vercel/Netlify-style serverless deployment. GitHub Pages can host the static UI, but API secrets require a separate backend.

## Environment
Copy `.env.example` to `.env.local` for local development and set your API credentials.

> The included WordPress ZIP is kept as a reference for the Travelpayouts integration. This starter does not copy WordPress-specific code into the frontend.
