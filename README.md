# Kamensky Family Birthdays 🎂

A little web form that collects every Kamensky family member's English **and** Hebrew birthdays, so we can finally stop pretending we remembered.

- **Live form:** https://jakekam.github.io/kamensky-birthdays/
- Submissions are stored in Supabase (`birthday_submissions` table) via the `bday-capture` edge function.
- Phase 2 (planned): generate a shared "Kamensky Birthdays" Google Calendar — yearly English birthdays plus per-year Hebrew date conversions via `@hebcal/core`.

The form is a single self-contained `index.html` — no build step. Edit it directly and push to update the live site.
