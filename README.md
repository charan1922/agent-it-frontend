# agent-it-frontend

Frontend for the Agent IT project (Next.js + TypeScript, shadcn/ui).

## Prerequisites

- Node.js 16 or newer (check with `node -v`)
- pnpm (v7+ recommended) — install with `npm install -g pnpm` or enable via `corepack`

## Installation

1. Install dependencies:

```bash
pnpm install
```

2. If you see a message about "Ignored build scripts" or packages that require approval, run:

```bash
pnpm approve-builds
```

This allows required package build scripts (e.g. `sharp`, `msw`) to run.

## Development

Start the development server:

```bash
pnpm dev
```

Next runs on port 3000 by default. If that port is in use, Next will pick the next available port (e.g. 3001) and print the URL.

## Build & Production

Build the app for production:

```bash
pnpm build
pnpm start
```

## Troubleshooting

- If `pnpm install` fails, verify your Node and pnpm versions (`node -v`, `pnpm -v`).
- If you see warnings about ignored build scripts, run `pnpm approve-builds` as above.
- To run on a specific port: `PORT=3002 pnpm dev` (Linux/macOS) or set the `PORT` environment variable in your shell.

## Using UI components

To use the project's UI components:

```tsx
import { Button } from "@/components/ui/button";
```

## Notes

If you need help running or building the app, open an issue or ask for guidance.
