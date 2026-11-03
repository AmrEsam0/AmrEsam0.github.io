# amresam0.github.io

Amr Essam's portfolio, plus public pages for the LabyrinthCode apps. Plain static HTML, no build step.

- `/` home, `/<project>/` one page per project. Theme: `assets/site.css`; images: `assets/<project>/`.
- `/egydata/`, `/omega/` are government work: name and stack only, everything else redacted.
- `stash/privacy/` and `stash/auth/` are linked from the Stash apps and keep the old `/style.css`. `stash/privacy/` is built from `Stash-mobile/PRIVACYPOLICY.md` with `pandoc -f gfm -t html`.

Local preview: `python3 -m http.server 8000`, then open http://localhost:8000.
