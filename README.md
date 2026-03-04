# PitchCraft AI

> Generate a complete, investor-ready business plan in 30 seconds with AI.

🔗 **[pitchcraftai.app](https://pitchcraftai.app)**

## What is PitchCraft AI?

PitchCraft AI is a SaaS tool that uses GPT-4o to generate professional business plans from a simple idea description. Each plan includes:

- ✅ Executive Summary
- ✅ Market Analysis (TAM/SAM/SOM)
- ✅ Competitive Analysis
- ✅ Business Model & Unit Economics
- ✅ 3-Year Financial Projections
- ✅ Go-to-Market Strategy
- ✅ 12-Slide Pitch Deck (Kawasaki/Sequoia method)
- ✅ Viral Content (LinkedIn, Twitter, Email)

## Pricing

| Plan | Price | Included |
|------|-------|----------|
| Free | €0/month | 3 plans, GPT-4o mini |
| Starter | €9/month | 10 plans, PDF export |
| Pro | €29/month | 100 plans, GPT-4o, API |

## API

Pro users get REST API access:

```bash
curl -X POST https://pitchcraftai.app/api/v1/generate \
  -H "X-API-Key: your_key" \
  -H "Content-Type: application/json" \
  -d '{"idea": "An AI tool that generates business plans", "industry": "SaaS"}'
