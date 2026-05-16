# Wizard Video Builder App

This is the React/Vite frontend for the wizard.

## Docker

From the repository root, use Docker Compose:

```bash
docker compose up --build
```

Then open `http://localhost:8080`.

You can also build and run this app directly:

```bash
docker build -t wizard-video-builder .
docker run --rm -p 8080:80 wizard-video-builder
```

## Local Development

```bash
npm install
npm run dev -- --host 0.0.0.0
```

Open the URL printed by Vite, usually `http://localhost:5173`.

## Checks

```bash
npm run build
npm run lint
```
