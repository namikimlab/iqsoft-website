# IQ Soft Website

Static company website based on `sample.html`.

## Local preview

Open `index.html` directly in a browser, or run a local static server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy on Vercel

1. Push this repository to GitHub.
2. Import the repo in Vercel.
3. Framework preset: `Other`.
4. Build command: leave empty.
5. Output directory: leave empty.
6. Deploy.

Vercel serves `index.html` at the root automatically for this static setup.
