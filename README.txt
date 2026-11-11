NOVA AI STUDIO — COMPLETE STARTER APP

WHAT WORKS
- Responsive dashboard for phones and computers.
- Live AI chat, once a Gemini API key is configured.
- AI advertisement script generation.
- AI-generated ad copy (headline, spoken script, caption).
- Image-to-video: creates a short animated WebM clip from an uploaded image in the browser, with a slow zoom and text overlay.
- The API key is kept on the server, not in the web page.

IMPORTANT VIDEO LIMITATION
The image-to-video tool makes a simple animated clip from a still picture. It does not generate new AI footage, talking people, or realistic scenes. A separate video-generation provider and API integration would be needed for that.

RUN LOCALLY
1. Install Node.js 18 or newer.
2. Extract this ZIP.
3. Open a terminal in the extracted nova_ai_studio_complete folder.
4. Run: npm start
5. Open: http://localhost:3000

CONNECT AI
1. Ask a parent/guardian to help review the AI provider's age rules and account terms before creating any developer account or API key.
2. In Google AI Studio, obtain a Gemini API key if eligible. Check current free-tier limits and terms first.
3. Copy .env.example to .env.
4. Put your key after GEMINI_API_KEY= in .env.
5. Restart the app.

This starter uses Node's built-in server and fetch; no npm packages are required.
Do not share your API key or upload it to public code repositories.
The free tier has limits and provider terms can change. Requests may be subject to rate limits or service availability.
