# Brew Haven — Seasonal Campaign

Selected scenario: **Option 1 — Coffee Shop / Brew Haven**. Four original layout files and PNG exports promote the Pumpkin Spice Latte using an intentionally warm, cozy palette (#F5E7D1, #D96F2A, #2B170E).

## Live website (GitHub Pages ready)

`index.html` and `styles.css` form a responsive, dependency-free landing page. To deploy it, create or use a GitHub repository, upload this whole folder, then choose **Settings → Pages → Deploy from a branch → main / root**. GitHub will publish a URL of the form `https://USERNAME.github.io/REPOSITORY/`.

| Asset | Dimensions |
| --- | ---: |
| `exports/instagram-post.png` | 1080 × 1080 px |
| `exports/landing-page-banner.png` | 1600 × 900 px |
| `exports/newsletter-header.png` | 600 × 200 px |
| `exports/banner-ad.png` | 336 × 280 px |

## Design files

`designs/*.svg` are **self-contained** — the coffee photo is embedded (base64) inside each file, so the image always shows no matter where/what app opens it (Inkscape, browser, GitHub preview). Text is converted to vector paths, so `designs/*.svg` renders **pixel-identical** to `exports/*.png`. Editable copies with live text are kept in `designs/editable/` (those reference `../assets/` and need the `assets` folder next to `designs`).

## Image credit

The campaign photography is **not AI-generated**. It uses *“A cup of coffee sitting on top of a wooden tray”* by Raymond Petrik, free under the [Unsplash License](https://unsplash.com/photos/a-cup-of-coffee-sitting-on-top-of-a-wooden-tray-6tcybUwV-kY). The photo is retained locally as `assets/pumpkin-latte-unsplash.jpg`; original graphic layouts are in `designs/`.
