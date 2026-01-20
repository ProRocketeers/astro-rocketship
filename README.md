# Astro Rocketship

A minimal Astro landing page for testing deployments.

## Development

```bash
bun install
bun run dev
```

Dev server runs at `http://localhost:4321`

## Build

```bash
bun run build
```

Static output goes to `./dist/`

## Docker

Build and run:

```bash
docker build -t astro-rocketship .
docker run -p 1337:80 astro-rocketship
```

Site available at `http://localhost:1337`
