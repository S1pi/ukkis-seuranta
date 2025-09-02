# Ukkis Seuranta

A monorepo with frontend (Next.js) and backend (Express.js) applications.

## Project Structure

```
ukkis-seuranta/
├── frontend/           # Next.js React application
├── backend/            # Node.js backend (Fastify - to be added)
├── package.json        # Root package.json with workspace scripts
├── tsconfig.json       # TypeScript configuration
├── eslint.config.mjs   # ESLint configuration
├── .prettierrc         # Prettier configuration
└── .editorconfig       # Editor configuration
```

## Getting Started

1. **Install dependencies:**

   ```bash
   npm install
   cd frontend && npm install
   cd ../backend && npm install
   ```

2. **Start development servers:**
   ```bash
   # From root directory
   npm run dev
   ```
   This starts both frontend (http://localhost:3000) and backend (http://localhost:3001)

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

## Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript, Tailwind CSS
- **Backend**: Node.js, TypeScript (Fastify to be added later)
- **Tools**: ESLint, Prettier, EditorConfig
