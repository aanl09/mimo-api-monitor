# Mimo API Monitor

Real-time monitoring dashboard for Mimo AI API key status, model availability, and token usage.

**Live:** https://aanl09.github.io/mimo-api-monitor/

## Features

- API key validity check (active / expired / error)
- Live completion test with latency measurement
- Model availability listing
- Cumulative token usage tracking (prompt / completion / total)
- Auto-refresh every 5 minutes via GitHub Actions

## Stack

- Static HTML/CSS/JS (no build step)
- GitHub Actions cron (every 5 min) for API checks
- GitHub Pages for hosting
