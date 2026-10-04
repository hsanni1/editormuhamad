# EditorMuhamad · Motion Designer

Portfolio site for EditorMuhamad, a motion designer who does brand animation, 3D and video edits.

**Live:** https://editormuhamad.vercel.app

## Sections

- **Hero:** intro and headline
- **Work:** recent projects as video tiles with cover images
- **Why:** reasons to work together
- **About:** background and tools (After Effects, Premiere Pro, Blender, Cinema 4D, Figma, CapCut)
- **Clients:** brands worked with
- **Contact:** call to action with links to Telegram and X

## Tech

A single static page: plain HTML, CSS and JavaScript in `index.html`. It has no build step and no dependencies. The only external resource is the Inter font from Google Fonts.

```
index.html        page markup, styles and scripts
images/           photos, client logos, tool icons
videos/           work videos (work-0X.mp4) and their covers (cover-0X.png)
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

The site is hosted on Vercel as a static site. To deploy from this folder:

```sh
vercel --prod
```
