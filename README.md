# Ukkis Seuranta

A basic monorepo with frontend (Next.js) and backend (Node.js) applications.

## Project Structure

```
ukkis-seuranta/
├── frontend/           # Next.js React application
├── backend/            # Node.js backend with TypeScript
├── shared/             # Shared types and constants
├── package.json        # Root package.json with workspace scripts
└── README.md           # This file
```

## Getting Started

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Start development servers:**
   ```bash
   npm run dev
   ```
   This starts both frontend (http://localhost:3000) and backend development servers.

## Available Scripts

```bash
npm run dev             # Start both frontend and backend
npm run build           # Build both applications
npm run lint            # Lint both applications

# Individual project scripts
npm run dev:frontend    # Start frontend only
npm run dev:backend     # Start backend only
npm run build:frontend  # Build frontend only
npm run build:backend   # Build backend only
npm run lint:frontend   # Lint frontend only
npm run lint:backend    # Lint backend only
```

## Shared Code

The `shared/` directory contains TypeScript types and constants that are used by both frontend and
backend:

- Import in backend: `import { Test } from '@/shared/types';`
- Import in frontend: `import { Test } from '@/shared/types';`

## Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript, Tailwind CSS
- **Backend**: Node.js, TypeScript
- **Tools**: ESLint, Prettier, npm workspaces
