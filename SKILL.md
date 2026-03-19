---
name: discover-free-apis
description: Automatically find and catalog free API endpoints for AI models (LLMs, image generation, embeddings, etc.). Searches popular providers, open source projects, and API directories for free tiers. Use when the user needs free AI model API access for testing, prototyping, or low-volume usage.
metadata:
  display-name: Discover Free AI APIs
  enabled: "true"
  version: "1.0"
---

# Discover Free AI APIs

## When to Use

Activate when the user asks for:
- Free AI model APIs
- Free LLM API access
- No-cost AI inference
- Free tier AI providers
- Open source model APIs
- Free image generation APIs
- Free embedding APIs
- Testing/prototyping AI without payment

## Steps

### Phase 1: Search Multiple Sources in Parallel

Open hidden tabs and search these sources simultaneously:

1. **GitHub Awesome Lists**
   - Search: awesome free ai api
   - URL: https://github.com/search?q=awesome+free+ai+api&type=repositories

2. **Reddit Communities**
   - r/LocalLLaMA - search "free api"
   - r/MachineLearning - search "free tier"

3. **Provider Directories**
   - Hugging Face Inference API docs
   - Replicate pricing page
   - Together AI pricing
   - Groq pricing
   - Cohere free tier
   - AI21 Labs
   - Mistral AI

4. **Aggregator Sites**
   - theresanaiforthat.com
   - ai.google.dev/models
   - openrouter.ai

5. **Open Source Projects**
   - Ollama API docs
   - LM Studio API docs
   - llama.cpp server
   - text-generation-webui

### Phase 2: Extract API Information

For each provider found, extract:
- Provider name
- Models available (model IDs/names)
- Free tier limits (requests/day, tokens, rate limits)
- API endpoint URL
- Authentication method (API key, none, etc.)
- Documentation link
- Registration required? (yes/no)
- Notes (restrictions, features, etc.)

### Phase 3: Categorize by Use Case

Group findings into:
- Chat/Completion APIs (LLMs for text generation)
- Image Generation (Stable Diffusion, DALL-E alternatives)
- Embeddings (text embeddings for RAG)
- Code/Programming (code completion, analysis)
- Speech/Audio (TTS, STT)
- Vision (image understanding, OCR)
- Self-Hosted Options (run locally, no API needed)

### Phase 4: Verify and Format

Create a structured markdown report (see example in repo).

### Phase 5: Save and Deliver

1. Save the report to: {workspace}/free-ai-apis-{timestamp}.md
2. Present key findings to user
3. Offer to open top 3 provider signup pages

## Tips

- Free tiers change frequently — always verify current limits
- Some providers require credit card even for free tier
- Self-hosted options (Ollama, LM Studio) are truly free but require local GPU
- Rate limits often more restrictive than volume limits
- Consider latency — free tiers may be slower
- Check terms of service for commercial use restrictions