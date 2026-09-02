# Housekeeping Week — Front Office × Housekeeping Quiz

A free-to-host, mobile/desktop quiz with:
- one question per screen
- separate answer/verdict screen
- automatic scoring
- corporate-sassy reactions
- shared leaderboard via Supabase

## 1. Create the free database

Create a Supabase project, open the SQL Editor, and run `supabase_setup.sql`.

Supabase's browser JavaScript client/API can use the project's URL and anon/publishable key. Do NOT put a Supabase service_role/secret key in this website.

## 2. Add your Supabase credentials

Open `index.html` and replace:

PASTE_YOUR_SUPABASE_PROJECT_URL_HERE
PASTE_YOUR_SUPABASE_ANON_KEY_HERE

with your project's URL and browser-safe anon/publishable key.

## 3. Publish for free with GitHub Pages

Create a public GitHub repository, upload `index.html`, `supabase_setup.sql`, and this README, then enable GitHub Pages from Settings → Pages → Deploy from a branch → main → /(root).

Your site will be available at:
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/

GitHub may take a few minutes to publish changes.

## 4. Important privacy note

The leaderboard intentionally displays participant names and scores publicly. Use first names or agreed team nicknames rather than sensitive personal information.

## 5. Optional upgrades

Before launch you can add:
- hotel logo/branding
- a QR code to the final URL
- a hidden admin page
- a “Top 3” podium
- a deadline/closing date
- a one-attempt-per-person rule

The quiz content is based on the supplied Front Office & Housekeeping Quiz material.
