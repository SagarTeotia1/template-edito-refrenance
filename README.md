# template-lab

A single-page tool that turns an Instagram, YouTube or Facebook video link into an editing template through the backend API, and lists the templates in stock.

Run it from a local server (the API only allows `http://localhost:*` origins unless the host is added to `CORS_ORIGIN`):

    python -m http.server 5180

Then open http://localhost:5180, pick the API address (`https://api.trybroll.com` or a local backend at `http://127.0.0.1:4100`), sign in, paste a link.
