# The Crickets — Online Publication PWA prototype

A responsive, static school-publication website for Cadi-an Elementary School.

## Included
- Home page, Feature Stories page, Editorial Cartooning page, and About page
- Responsive desktop/mobile layout using green, gold, and rural-inspired colors
- Publication logo asset
- Demo content management panel to add, edit, and delete stories or cartoons
- Browser-local persistence with `localStorage`
- PWA manifest and service worker for installability and basic offline caching

## Run locally
For a quick preview, open `index.html` in a browser. For PWA installation and service-worker behavior, serve this folder over localhost or HTTPS (service workers do not run on ordinary `file://` URLs). For example, if Python is installed:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Important limitations
- This is a front-end prototype, not a hosted production CMS. Content is stored only in the current browser and is not shared across devices or users.
- There is no authentication, database, server, analytics, or payment feature.
- Replace sample articles, dates, bylines, and illustrations with verified and approved school content before publishing.
- Poppins loads from Google Fonts when internet access is available; a system sans-serif fallback is included.
- For a production deployment, add secure administrator authentication, a server/database or approved CMS, backups, image upload validation, privacy safeguards, and an editorial approval workflow.
