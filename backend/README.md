# Backend

Node.js backend application for Ukkis Seuranta.

## Getting Started

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Start development server:**

   ```bash
   npm run dev
   ```

3. **Build for production:**

   ```bash
   npm run build
   ```

4. **Start production server:**
   ```bash
   npm start
   ```

## Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build the application for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

## Shared Code

Import shared types and constants using the path alias:

```typescript
import { Test } from '@/shared/types';
import { PAGINATION } from '@/shared/constants';
```

## Project Structure

```
backend/
├── src/
│   └── index.ts         # Application entry point
├── dist/                # Compiled JavaScript (generated)
├── package.json         # Dependencies and scripts
└── tsconfig.json        # TypeScript configuration
```

## Tech Stack

- Node.js
- TypeScript
