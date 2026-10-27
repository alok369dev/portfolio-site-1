# Alok Yadav | Portfolio

A static, single-page portfolio for Alok Yadav, Website Developer. Plain HTML, CSS and JavaScript, so there is no build step.

## Structure

```
index.html      the whole site (markup, styles, scripts)
assets/         photos and project thumbnails
vercel.json     Vercel settings (clean URLs, asset caching)
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```

## Deploy

1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New > Project** and import the repository.
3. Framework Preset: **Other**. Leave the build command and output directory empty.
4. Click **Deploy**.

## Editing

- Project cards are the `P` array near the bottom of `index.html`.
- Add live links by extending each project entry and rendering an `<a>` in the card template.
- Replace images in `assets/` and keep the same file names.
