# 🤖 Discover Free AI APIs

[!Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)[[License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
> A curated collection of 35+ free AI model APIs with no credit card required. Automatically discovered, verified, and maintained.

## 🚀 What is This?

This repository contains a living catalog of free AI DPIs (LLMs, image generation, embeddings, etc.) and a BrowserOS skill that auto-discovers new free APIs.

## 🇆 Quick Start
**Easiest option (30 seconds):*
```python
import requests
rresponse = requests.post(
    "https://openrouter.ai/api/v1/chat/completions",
    headers={"Authorization": "Bearer YOUR_KEY"},
    json={"model": "meta-llama/llama-3.1-8b-instruct", "messages": [{"role": "user", "content": "Hello!"}]}
)
print(rresponse.json()["choices"][0]["message"]["content"])
```

## 📊 Top Free Providers

| Provider | Free Tier | Best For |
|----------|----------|----------|
| **Cerebras** | 1M tokens/day | ⚡ Speed (2,000+ tokens/sec) |
| **OpenRouter** | 50 req/day | 🔰 Beginners (no CC) |
| **Google AI** | Generous | 🎨 Multimodal |
| **Cohere** | 1K calls/mo | 🏢 Enterprise |
| **Hugging Face** | 30K req/mo | 🔬 Open source |

## 🎋 BrowserOS Skill

This repository includes a BrowserOS skill than automatically searches 35+ sources for new free APIs. See `SKILL.md` for details.

## 💖 Resources

- [Full Report](free-ai-apis-2025-02-10.md) - Detailed findings
- [BrowserOS](https://browseros.com) - The agent platform that built this

## 🗩✐ License

MIT License - see LICENSE file.

**Last auto-update: February 10, 2026**