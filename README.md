# fsProject

Minimal full-stack TypeScript scaffold with:

- `client`: React + TypeScript + Vite + Redux Toolkit + React Router
- `server`: Node.js + Express + TypeScript (REST-style health endpoint)

## Prerequisites

- Node.js 18+
- npm

## Install dependencies

From the repository root:

```bash
npm install
npm install --workspace client
npm install --workspace server
```

## Run in development

Run both client and server:

```bash
npm run dev
```

Run only client:

```bash
npm run client:dev
```

Run only server:

```bash
npm run server:dev
```

## Build

Build both projects:

```bash
npm run build
```

## API health check

Server endpoint:

- `GET /api/health`

Response:

```json
{
  "success": true,
  "message": "Server is running"
}
```
