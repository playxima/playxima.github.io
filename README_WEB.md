# XIMA Web Edition (Multi-page)

Complete website edition of the book split into sections for easier reading:

- `index.html`
- `fundamentos.html`
- `mecanicas.html`
- `estrategia.html`
- `practica.html`
- `styles.css`

## Run locally

```bash
cd "/Users/awrjorge/Downloads/XIMA_How_to_reach_the_top"
python3 -m http.server 8080
```

Open: `http://localhost:8080`

## Push to GitHub

```bash
cd "/Users/awrjorge/Downloads/XIMA_How_to_reach_the_top"
git init
git add .
git commit -m "Add XIMA multi-page website"
git branch -M main
git remote add origin https://github.com/YOUR_USER/YOUR_REPO.git
git push -u origin main
```

## Publish with GitHub Pages

1. Go to `Settings > Pages`.
2. In `Build and deployment` choose:
   - Source: `Deploy from a branch`
   - Branch: `main` and `/root`
3. Save and wait for the public URL.
