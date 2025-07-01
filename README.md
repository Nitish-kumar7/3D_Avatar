# Interview Bot

## Setup

### Backend
1. `cd backend`
2. `npm install`
3. Add your API keys to `.env`
4. `npm start`

### Frontend
1. `cd frontend`
2. `npm install`
3. `npm run dev`

Open [http://localhost:3000](http://localhost:3000)

## Notes
- You need valid API keys for Google STT, OpenAI, ElevenLabs, and D-ID.
- For D-ID, you must provide a public audio URL. In production, upload the TTS audio to a public storage (e.g., S3) and pass the URL to `/api/avatar`.
- This is a minimal demo. For production, add error handling, security, and polish. 