# Wizard Video Builder

React/Vite wizard app for collecting product, brand, audience, and video-generation inputs.

## Run With Docker Compose

From the repository root:

```bash
docker compose up --build
```

Open:

```text
http://localhost:8080
```

Stop the container:

```bash
docker compose down
```

## Run With Docker Only

```bash
docker build -t wizard-video-builder ./tsx-preview
docker run --rm -p 8080:80 wizard-video-builder
```

Open `http://localhost:8080`.

## Run Locally Without Docker

```bash
cd tsx-preview
npm install
npm run dev -- --host 0.0.0.0
```

Vite prints the local URL, usually `http://localhost:5173`.

## Production Build Check

```bash
cd tsx-preview
npm run build
npm run lint
```

## Project Layout

```text
.
├── docker-compose.yml
├── datainput_structure.json
└── tsx-preview
    ├── Dockerfile
    ├── nginx.conf
    ├── package.json
    └── src
```
