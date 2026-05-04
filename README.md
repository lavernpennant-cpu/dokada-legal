# Dokada Legal AI

A demonstration AI-powered legal intake assistant built for law firms.

**Built by:** Lavern Pennant
**Contact:** lavernbygrave@gmail.com

## What this is

A live, working demonstration of AI legal intake. Visitors can chat with the assistant which captures their information, triages urgency, and prepares structured intake data — all while staying compliant with bar association rules (no legal advice, no attorney-client privilege formed, no fee quotes).

## Stack

- Static HTML landing page
- Vercel Edge Function (`/api/chat`)
- OpenAI GPT-4o-mini backend

## Deployment (Vercel)

1. Push this repo to GitHub
2. Connect to Vercel
3. Add environment variable: `OPENAI_API_KEY`
4. Deploy — Vercel auto-detects the API route

## Customization for paying clients

To customize this for a specific law firm:
1. Update `index.html` — firm name, tagline, branding
2. Update `api/chat.js` — system prompt with firm-specific details
3. Redeploy

## License

© Cornerstone Kitchen LLC dba Dokada AI. All rights reserved.
