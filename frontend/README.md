# Frontend

Next.js frontend application for Ukkis Seuranta.

## Getting Started

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Start development server:**
   ```bash
   npm run dev
   ```
   Opens at http://localhost:3000

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Shared Code

Import shared types and constants using the path alias:

```typescript
import { Test } from '@/shared/types';
import { PAGINATION } from '@/shared/constants';
```

## Tech Stack

- Next.js 15
- React 19
- TypeScript
- Tailwind CSS
