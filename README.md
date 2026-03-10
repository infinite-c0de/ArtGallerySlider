# Democratization of Mental Wellness Foundation (DMWF) Website

Public-facing nonprofit website built with Next.js (App Router), React, TypeScript, and Tailwind CSS.

## Tech Stack

- Next.js 15
- React 18
- TypeScript
- Tailwind CSS
- Radix UI primitives and `shadcn/ui`-style components

## Prerequisites

- Node.js 18+ (LTS recommended)
- npm

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm run dev
   ```
3. Open [http://localhost:3000](http://localhost:3000).

## Available Scripts

- `npm run dev` - Start the local development server.
- `npm run build` - Build the production bundle.
- `npm run start` - Start the production server after build.
- `npm run lint` - Run ESLint.

## Project Structure

- `app/` - Next.js App Router pages and layout.
- `components/` - Shared and page-specific React components.
  - `components/landing/` - Homepage sections.
  - `components/fund/` - Donation/funding sections.
  - `components/ui/` - Reusable UI primitives.
- `hooks/` - Custom React hooks.
- `lib/` - Utilities and shared helpers.
- `styles/` - Global stylesheet assets.

## Main Routes

- `/` - Homepage
- `/about`
- `/campaign`
- `/contact`
- `/fiscal-sponsorship`
- `/founder`
- `/founding-partners`
- `/fund-a-mind`
- `/get-involved`
- `/governance`
- `/media`
- `/mission`
- `/pilot`
- `/privacy`

## Development Notes

- Global app metadata and root layout live in `app/layout.tsx`.
- The homepage is composed from modular sections in `components/landing/`.
- No local environment variables are currently required by checked-in code.

## Deployment

This project can be deployed to any Node-compatible host. Vercel is the most direct option for Next.js apps.

Typical deployment flow:

1. `npm run build`
2. `npm run start` (or deploy via platform build pipeline)
