# heldoc-web (deploy)

Veřejný deploy webu Heldoc na **app.heldoc.cz** (GitHub Pages).

Obsahuje jen **sestavený výstup** (`dist`) — zdrojové kódy žijí v privátním
monorepu [`sevela/heldoc`](https://github.com/sevela/heldoc) ve složce `web/`.
Aktualizace: `cd web && npm run build` a obsah `web/dist` + `CNAME` nahrát sem.

Žádná tajemství — publishable klíč Supabase je veřejný, data chrání RLS za přihlášením.
