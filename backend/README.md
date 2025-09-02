# Backend README

This is a simple backend service built with [Fastify](https://www.fastify.io/), using ES Modules (ESM) syntax.

## Getting Started

1. **Install dependencies:**

```bash
npm install
```

2. **Run the server:**

```bash
npm start
```

## Project Structure

- `index.js` — Main entry point
- `routes/` — API route definitions

## Scripts

- `npm start` — Start the Fastify server
- `npm run dev` — Start with auto-reload (if using nodemon)

## Requirements

- Node.js >= 16
- `"type": "module"` in your `package.json`

## Example

```js
import Fastify from "fastify";

const fastify = Fastify();

fastify.get("/", async (request, reply) => {
  return { hello: "world" };
});

fastify.listen({ port: 3000 }, (err) => {
  if (err) throw err;
  console.log("Server listening on http://localhost:3000");
});
```
