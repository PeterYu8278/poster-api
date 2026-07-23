# Poster API Gateway v4
1. Copy `.env.example` to `.env` and replace placeholders.
2. Run `npm install` then `npm test` and `npm start`.
3. Deploy behind HTTPS.
4. Replace `https://YOUR_API_BASE_URL` in the GPT Action schema.
5. In GPT Builder Action Authentication choose API Key, header `Authorization`, value `Bearer YOUR_GATEWAY_API_KEY`.

Never expose provider keys in GPT Builder. The included image generation endpoint is intentionally a 501 placeholder until you connect your chosen paid provider.
