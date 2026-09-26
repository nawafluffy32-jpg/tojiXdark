# Violet Network

## Email and password accounts

Accounts use the built-in Node.js SQLite database at `data/violet.sqlite` by default. Set `VIOLET_DATABASE_PATH` to a writable persistent path when deploying the app. Passwords are stored as scrypt hashes with per-account salts; sessions use random, database-backed tokens in HttpOnly cookies. Email verification and third-party sign-in are not enabled.

Registration requires a valid email and a password between 8 and 128 characters. After signing in, players add a Java-format Minecraft username (3-16 letters, digits, or underscores). The username is stored with the account, but is not verified with Mojang.

Run locally with `npm install` and `npm run dev`.
