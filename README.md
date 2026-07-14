# avazovielts.uz

Free IELTS preparation platform for Uzbek students.

**Live site:** [avazovielts.uz](https://avazovielts.uz)

## What it does

- Full IELTS practice tests (Reading, Listening, Writing, Speaking)
- AI-powered writing feedback (Groq API)
- XP/level system and leaderboard
- User authentication with Google OAuth
- Admin panel for user management

## Tech stack

- **Frontend:** Vanilla HTML/CSS/JS (performance-first, optimized for slow connections)
- **Backend:** Cloudflare Workers
- **Database:** Cloudflare D1 (SQLite)
- **AI:** Groq API (LLaMA)
- **Hosting:** Cloudflare Pages

## Note

This repo contains the frontend only. The backend runs on Cloudflare Workers and is not public. API calls to `api.avazovielts.uz` will not work without the backend.

## Built by

[Azizbek Xusnitdinov](https://github.com/xusnitdinov) - solo project
