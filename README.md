# ClipForge AI — Creator Studio

A premium Next.js starter for a YouTube-to-clips studio. The current version is a frontend prototype: clip cards and scores are sample data, and media processing/rendering is not connected yet.

## Run locally

Requirements: Node.js 18.17+ (Node 20 recommended).

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Deploy

Import this repository into Vercel and deploy as a Next.js project. No environment variables are required for the frontend prototype.

## Planned processing backend

Add a job API and background worker using FFmpeg/ffprobe, timestamped transcription, highlight ranking, subtitle generation, output validation, and object storage. Support only videos the user owns or is authorized to process; don't bypass platform access controls. Never commit API keys.
