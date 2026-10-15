# Birthday Scrapbook 🎂📸

A small, interactive birthday website inspired by a **retro scrapbook** — a collection of little memories, warm wishes, and playful surprises.

Built with **HTML, CSS, and vanilla JavaScript**, with no backend or build step required.

## Features

- Vintage scrapbook layout with responsive Polaroid photo cards
- Click-to-view photo gallery and captions
- Interactive letter with an envelope-opening animation
- Birthday cake, candle interaction, and confetti
- Surprise gift cards
- Background music (subject to browser autoplay restrictions)
- Mobile-friendly design

## Project structure

```text
.
├── index.html          # Website layout, styles, scripts, and content
├── photos/             # Gallery images
│   ├── anh1.png
│   ├── anh2.png
│   └── anh3.png
└── music/
    └── birthday.mp3    # Background music
```

The filenames above reflect the current asset paths; update the corresponding references in `index.html` if you rename them.

## Run locally

Open `index.html` in a browser. For a closer-to-production test, run it through a local development server (for example, VS Code Live Server).

## Deploy to Netlify

This is a static website and can be deployed for free on [Netlify](https://www.netlify.com/).

### First deployment

1. Sign in to [Netlify](https://app.netlify.com/).
2. Open [Netlify Drop](https://app.netlify.com/drop), or create a new project with manual deployment.
3. Drag and drop the **project folder containing `index.html`** (not a ZIP file).
4. Wait for the deploy to finish and open the assigned `.netlify.app` URL.

### Update an existing published website

1. Edit `index.html` and/or replace assets inside `photos/` and `music/`.
2. Test the site locally and save all changes.
3. In Netlify, open **Projects → your existing project → Deploys**.
4. Use the manual deploy drag-and-drop area to upload the **entire updated project folder**.
5. Wait for the new deploy to be marked **Published** and refresh the existing website URL.

**Important:** Update through the existing project's **Deploys** page to keep the same URL. Do not create a new project just to publish changes. If the site is connected to a Git repository with automatic deployments enabled, push changes to its configured deployment branch instead.

## Customization

Edit the `CONFIG` object inside `index.html` to change captions, messages, gallery paths, and gift text. The audio source is configured separately in the HTML. Keep image and audio filenames consistent with their paths.

> **Privacy:** This repository's README intentionally omits personal details. If you publish the repository or Netlify site publicly, any names, messages, photos, and audio **inside the website files** may still be accessible. Review those files and use only media you have permission to share.

---

Made with care, a little nostalgia, and lots of confetti. ♡
