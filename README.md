# Archie Games site

Static site for archiegames.com.au, built 7 Oct 2026. Plain HTML and CSS, no build step.

- `index.html` – home page (Footy Coach, PairCall, studio, contact form).
- `privacy-policy/` – privacy policy for both apps. Also served at `/home/privacy-policy/` so the old Google Sites link in the app stores keeps working.
- `home/` and `home/australian-footy-coach/` – redirects from the old Google Sites URLs.
- `img/` – screenshots, key art and app icons.

Hosted on GitHub Pages from this repo. The contact form posts to FormSubmit, which relays to Alan's inbox without exposing the address.
