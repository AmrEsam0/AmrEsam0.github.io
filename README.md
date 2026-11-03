# amresam0.github.io

Amr Essam's portfolio, plus public pages for the LabyrinthCode apps. Plain static HTML, no build step.

- `/` home, `/<project>/` one page per project. Theme: `assets/site.css`; images: `assets/<project>/`.
- `/egydata/`, `/omega/` are government work: name and stack only, everything else redacted.
- `<app>/privacy/` pages are linked from the apps and store listings. `stash/privacy/` wraps `pandoc -f gfm -t html Stash-mobile/PRIVACYPOLICY.md` in the site theme; `stash/auth/` (Chrome sign-in redirect) keeps the old `/style.css`.

Local preview: `python3 -m http.server 8000`, then open http://localhost:8000.
