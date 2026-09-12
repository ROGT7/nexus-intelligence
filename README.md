# Nexus Intelligence

Autonomous media intelligence system for content discovery, contextual media search, and automated video production.

## Features

- **Media Detective** — Scans Google Trends, Reddit, Hacker News, RSS feeds for viral topics
- **Contextual Media Search** — Pexels API + Pixabay API + Bing Images for licensed, attributable media
- **Video Pipeline** — Script generation → TTS → footage assembly → FFmpeg → YouTube upload
- **Pre-Publish Quality Check** — Script sanitizer + Whisper voice decoder + LLM content analysis
- **Evolutionary Trading** — Genetic algorithm strategy discovery with walk-forward validation

## Architecture

```
Topic Discovery → Media Search → Script Generation → TTS → Video Assembly → Quality Check → Upload
```

### Media Sources
- Pexels API (images + videos HD/4K, licensed)
- Pixabay API (images + videos, no attribution required)
- Bing Images (fallback)
- Google Trends, Reddit, HN, RSS feeds

### Quality Pipeline
1. Script sanitizer filters sensitive words
2. Whisper speech-to-text verifies generated audio matches script
3. LLM analyzes content before publication

## Tech Stack
- Python 3.11
- Ollama (local LLM, 3B-14B models)
- Edge-TTS (free Microsoft Neural voices)
- Pexels/Pixabay APIs
- FFmpeg
- YouTube Data API v3
- Whisper (speech-to-text)

## Results
- 55.8% win rate on multi-coin backtest (BTC 67.6%)
- Automated media discovery across 5+ sources
- Pre-publish quality gate operational

## License
Proprietary — Nexus Intelligence
