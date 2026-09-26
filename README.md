# Violet Network

## Minecraft username login

Players sign in with a Minecraft username only. The name is not verified with Mojang or Microsoft, so anyone can impersonate another player. Do not use this identity for admin authorization, purchases, or ownership checks. Sessions use random database-backed tokens in HttpOnly cookies.

The built-in Node.js SQLite database is stored at `data/violet.sqlite` by default. Set `VIOLET_DATABASE_PATH` to a writable persistent path when deploying the app. Serverless hosts such as Vercel do not provide persistent local disk; use a persistent database before relying on saved player names there.

Run locally with `npm install` and `npm run dev`.
