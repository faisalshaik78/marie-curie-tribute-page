# Marie Curie Tribute Page

A responsive tribute page built with HTML5 and CSS3 (no JavaScript).

## Project structure

```
tribute-page/
├── index.html   # page structure and content
├── style.css    # all styling
└── README.md
```

## Run locally

1. Download or clone the folder.
2. Open `index.html` in any browser. No build step or install needed.

An internet connection is needed for the Google Fonts and the portrait image.

## Features

- Page title with subject name and one-line tagline
- Prominent portrait (public domain, Wikimedia Commons)
- Four-paragraph original biography
- Timeline (ordered list) and achievement cards
- Distinct quote block
- Three background colours: dark green-black, pale paper, copper
- Two font styles: Fraunces (serif, headings and bio), IBM Plex Sans (body)
- Responsive layout (CSS Grid, `auto-fit` cards, mobile breakpoint at 760px)
- Keyboard focus styles and reduced-motion support

## Design tokens

| Name   | Value     | Use                         |
|--------|-----------|-----------------------------|
| night  | `#0e1d1b` | hero and timeline background |
| glow   | `#9fe8c8` | accents, inspired by radium's glow |
| paper  | `#eef2ec` | light sections              |
| copper | `#b8693d` | quote block, card borders   |

## Sources

- Facts paraphrased from [Britannica](https://www.britannica.com/biography/Marie-Curie) and [Wikipedia](https://en.wikipedia.org/wiki/Marie_Curie)
- Image: [Marie Curie c1920.jpg](https://commons.wikimedia.org/wiki/File:Marie_Curie_c1920.jpg), Wikimedia Commons (public domain)
- Fonts: Fraunces and IBM Plex Sans via Google Fonts

## Customising

- Change the subject: edit the text in `index.html` and the image `src`.
- Change colours: edit the variables in `:root` at the top of `style.css`.
- If the image fails to load, download it from Commons, save it in the folder and set `src="marie-curie.jpg"`.

## Deploy (GitHub Pages)

1. Push the folder to a GitHub repository.
2. Settings → Pages → select the `main` branch, root folder → Save.
3. Your page goes live at `https://<username>.github.io/<repo>/`.
