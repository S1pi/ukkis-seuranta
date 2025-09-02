# Shared

Shared TypeScript types and constants used by both frontend and backend.

## Usage

Import from both frontend and backend using the path alias:

```typescript
// Import types
import { Test } from '@/shared/types';

// Import constants
import { PAGINATION, VALIDATION } from '@/shared/constants';
```

## Files

- `types.ts` - Shared TypeScript type definitions
- `constants.ts` - Shared constants and configuration values

## Adding New Shared Code

1. Add your types to `types.ts`
2. Add your constants to `constants.ts`
3. Both frontend and backend will automatically have access via `@/shared/*` imports
