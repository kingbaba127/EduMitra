# EduMitra Full Project

Mobile-friendly full-stack free learning platform starter.

## Included
- Student registration/login and dashboard
- Course catalogue and recorded lesson links
- PDF library with admin upload
- Online mock tests with automatic scoring
- Leaderboard
- Live-class schedule using external meeting links
- Study streak (recorded when a student submits a test)
- Completion certificate generator (print/save as PDF)
- Dark mode
- AI assistant integration through an optional server-side OpenAI-compatible API
- Admin panel for courses, lessons, PDFs, tests, live classes and users

## Run
Requires Node.js 20+ and a host that supports persistent storage.
1. Copy `.env.example` to `.env`.
2. Change `SESSION_SECRET`, `ADMIN_EMAIL`, and `ADMIN_PASSWORD`.
3. Run `npm install`
4. Run `npm start`
5. Open `http://localhost:3000`

Admin is seeded on first server start using the .env values. The example credentials are placeholders; change them before deployment.

## Important
This is a functional starter, not a production-scale PW replacement. Live classes are meeting links (Google Meet/Zoom etc.), not built-in video streaming. The AI feature needs an API provider and key configured on the server; never put keys in browser code. Certificates are completion acknowledgements, not accredited/government qualifications. Use only course videos and PDFs you own or have permission to distribute. Before public launch, add email verification, password reset, CSRF protection, privacy/terms pages, backups and a security review. Use a host with persistent disk for `data/` and `uploads/`.
