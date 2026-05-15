# LLM Gateway — API Router Dashboard

> Next-level LLM API key management & routing dashboard

## Overview

A premium, fully-responsive single-page dashboard for managing multiple LLM provider API keys, monitoring usage, and routing requests — all from one unified interface.

## Features

- **Multi-Provider Support** — OpenAI, Anthropic, Google Gemini, DeepSeek, Mistral AI, Xiaomi MiMo
- **API Key Management** — Add, view, delete keys with labels per provider
- **Real-time Monitoring** — Total requests, active keys, error rate, latency stats
- **Usage Analytics** — Interactive bar chart (7D / 30D views) powered by Chart.js
- **Live Activity Feed** — Recent request logs with method, route, status code
- **Provider Status** — Visual health indicators per provider with usage bars
- **Dark Premium UI** — Glassmorphism design, smooth animations, gradient accents
- **Fully Responsive** — Desktop sidebar → mobile top navigation, fluid grids
- **Zero Backend Required** — Static HTML, deploy anywhere (GitHub Pages, Vercel, S3)

## Tech Stack

| Component | Technology |
|-----------|-----------|
| HTML/CSS | Custom dark theme with glassmorphism |
| Framework | Tailwind-like utility design (pure CSS) |
| Charts | Chart.js 4.x |
| Icons | Inline SVG |
| Fonts | Inter (Google Fonts) |
| Runtime | Zero dependencies — single `.html` file |

## Usage

1. Open `index.html` in any browser
2. Navigate via sidebar: Dashboard → Providers → API Keys → Logs
3. Click **"Add Key"** to register a new API key
4. Click **"Add Provider"** to connect a new LLM service
5. Monitor usage stats and activity feed in real-time

## Deploy

```bash
# Serve locally
python3 -m http.server 8080

# Or upload index.html to any static host
# GitHub Pages, Vercel, Netlify, Cloudflare Pages, S3
```

## Why This Project

Built as part of the Xiaomi MiMo 100T Creators Program — demonstrates practical AI infrastructure tooling with modern web design. The gateway concept is production-ready for developers who manage multiple LLM API keys across different providers.

---

**Author:** Akbarrrsw
**Built with:** Pure HTML/CSS/JS + Chart.js
