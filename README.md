# web

The relialife.app front page: what ReliaLife does, ReliaBase and ReliaPro, the user
guide, release notes, and the signed-in strategy library browser.

One self-contained index.html (inline CSS and vanilla JS, no build step), served by
GitHub Pages. The strategy data is NOT in this repo: it lives in a private Supabase
storage bucket that only authenticated accounts can read. The page and its seed data
are maintained in the app repo under splash/ (see splash/README.md there).

privacy.html is the App Store-linked privacy policy - leave it in place.
