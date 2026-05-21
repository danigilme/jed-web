# jed-web

Placeholder landing for **jed.so** (the "Jed" assistant — presence project).

- Single static `index.html` served by nginx.
- Deployed as a Dokploy Application on the iOS Engine factory base server (`23.88.33.53`), domain `jed.so`, Cloudflare-proxied, Let's Encrypt via Traefik.

Build: `docker build -t jed-web . && docker run -p 8080:80 jed-web`
