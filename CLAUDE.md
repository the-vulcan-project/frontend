# Frontend

Next.js frontend application with TypeScript and Tailwind CSS.

## Stack

- **Framework**: Next.js (latest, App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Runtime**: Node 22 LTS

## Commands

- `npm run dev` — run dev server with hot reload
- `npm run build` — production build
- `npm start` — serve production build
- `npm run lint` — run ESLint

## Project Structure

- `src/app/` — App Router pages and layouts
- `src/app/globals.css` — global styles and Tailwind imports
- `public/` — static assets

## Conventions

- Use App Router (`src/app/`) with server components by default
- Add `"use client"` directive only when client interactivity is needed
- Style with Tailwind utility classes
- App runs on port 3000, served behind nginx at `/`
- Backend API is accessible via `/api/*` through nginx reverse proxy
