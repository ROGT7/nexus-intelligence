# Nexus Intelligence

Autonomous media intelligence system with contextual discovery, content generation, and self-healing capabilities.

## Features

- Media Detective - Contextual image/video discovery from Pexels, Pixabay, Wikimedia
- YouTube Shorts Pipeline - Script to TTS to Footage to Assembly to Upload with quality checks
- Self-Healing System - Auto-repair T0/T1/T2 with test gate and rollback
- Model Router - Intelligent LLM selection (3B minimum, 3B-14B dynamic switching)
- Anti-Doublon - Perceptual hash deduplication for content

## YouTube Shorts Pipeline

1. Script generation (LLM)
2. Script sanitization (filter: IA, GPT, Ollama, LLM)
3. TTS voice generation
4. Voice verification (Whisper decode and compare)
5. Footage download (Pexels/Pixabay)
6. Video assembly (ffmpeg)
7. Pre-publish LLM check
8. YouTube upload

## Model Router

- 3B minimum for complex decisions (trading, code, reasoning)
- Dynamic 3B-14B switching based on complexity
- Performance tracking per model per task
- Cloud API fallback (Groq, OpenRouter, Gemini)

## License

MIT
