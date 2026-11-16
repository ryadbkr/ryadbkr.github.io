# ryadbkr.github.io — Ink Learning Studios

Served by GitHub Pages at https://ryadbkr.github.io/

| Path | What | Used by |
|---|---|---|
| `/` (`index.html`) | Studio page listing the games | Store "website" fields |
| `/app-ads.txt` | AdMob authorised sellers (publisher `pub-9769492867230987`) | AdMob crawler — **must stay at the root** |
| `/privacy.html` | Flags Ink privacy policy | Flags Ink Play listing — **do not move** |
| `/flags-ink/` | Flags Ink page | studio page |
| `/Zipstache/` | Zipstache page | studio page, Zipstache footer links |
| `/Zipstache/privacy.html` | Zipstache privacy policy (EN/FR) | Play listing + in-app link (`SettingsScreen.PRIVACY_POLICY_URL`) — **do not move** |
| `/Zipstache/delete.html` | Zipstache account deletion (EN/FR) | Play Console › Data safety › Delete account URL — **do not move**. Linked only from the privacy page (end), never from the home pages |
| `/rawabit/privacy.html` | Rawabit al-Kalimat (روابط الكلمات) privacy policy (AR/EN/FR) | Play listing + in-app link (`Sheets.PRIVACY_URL`) — **do not move** |
| `/rawabit/delete.html` | Rawabit al-Kalimat: how to delete your data (AR/EN/FR) | Play Console › Data safety › delete data URL — **do not move** |
| `/qasim/privacy.html` | Redirect to `/rawabit/privacy.html` (the app's working name before 16 Nov 2026) | nothing — kept so an old link still lands |
| `/Zipstache/site.css`, `pistache.webp` | Shared style and art of the Zipstache pages | |

Rules
- URLs given to Google (privacy, delete, app-ads.txt) never move. Paths are case-sensitive (`Zipstache`).
- This repo is the only copy of these pages: edit here, not in the app repos.
- A change in what an app collects or deletes updates its privacy page, its delete page and the Play
  Console data safety form together, with a new "Updated" date.
