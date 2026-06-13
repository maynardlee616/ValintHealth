# Valint Health — Landing Page

Simple coming-soon landing page for [valinthealth.com](https://www.valinthealth.com).

## Files

```
├── index.html   # The entire page — HTML, CSS, and JS in one file
└── logo.png     # Valint Health logo mark
```

## No build step required

Plain HTML and CSS. No frameworks, no npm, no dependencies beyond a Google Fonts request.

## Deploying to GitHub Pages

1. Push both files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Set source to `main` branch, `/ (root)` folder.
4. Your page goes live at `https://<username>.github.io/<repo>/`.

For the custom domain `www.valinthealth.com`:
- Add a `CNAME` file to the repo root containing: `www.valinthealth.com`
- In your DNS provider, add a `CNAME` record pointing `www` → `<username>.github.io`

## Things to update

- [ ] Replace `info@valinthealth.com` with your real contact email (appears in 3 places)
- [ ] Update the tagline and description copy in `index.html`
- [ ] Add a `favicon.ico` and `<link rel="icon">` in `<head>` when ready
