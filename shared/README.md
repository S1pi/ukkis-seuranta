# Shared Code

This directory contains shared code between the frontend and backend applications.

## Contents

- `types.ts` - Shared TypeScript type definitions
- `constants.ts` - Shared constants and configuration values
- `utils.ts` - Shared utility functions

## Usage

### In Backend

```typescript
import { User, ApiResponse } from '../shared/types';
import { API_ENDPOINTS } from '../shared/constants';
import { createApiResponse } from '../shared/utils';
```

### In Frontend

```typescript
import { User, ApiResponse } from '../shared/types';
import { API_ENDPOINTS } from '../shared/constants';
import { isValidEmail } from '../shared/utils';
```

## Guidelines

- Only add code that is truly shared between frontend and backend
- Keep dependencies minimal (prefer native JavaScript/TypeScript)
- Ensure all code is environment-agnostic (works in both Node.js and browser)
- Document all exports with JSDoc comments
