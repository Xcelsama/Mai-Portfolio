# Excel Amadi | Portfolio

My personal portfolio: graphic designer and self-taught full-stack developer from Port Harcourt, Nigeria. It shows my three crafts (design, code and video), my projects, my creative work and how to reach me.

Built with plain HTML, CSS and a little JavaScript. No framework, no build step, no dependencies.

## Pages

| Page | File | What it holds |
| --- | --- | --- |
| Home | `html/index.html` | Hero, stats, the three crafts, About, Skills, selected projects, creative preview, contact |
| Projects | `html/projects.html` | Flagship projects, other projects and experiments |
| Creative | `html/creative.html` | Posters and flyers, photo gallery, video, AI work |
| Contact | `html/contact.html` | Email, profiles and other ways to reach me |

## Folder structure

```
My-Portfolio/
├── html/        index, projects, creative, contact
├── css/
│   └── styles.css   all styling for every page
├── js/
│   └── loader.js    the X loading animation
├── images/
│   ├── favicon.svg
│   ├── og.jpg           link-preview image
│   ├── asson-poster.jpg
│   └── shots/           project screenshots
├── files/
│   └── Excel-Amadi-CV.pdf
└── tools/
    └── screenshots.mjs  makes project screenshots
```

## Run it locally

No install needed. Either:

- Open `html/index.html` in a browser, or
- Use the **Live Server** or **Live Preview** extension in VS Code and open `html/index.html`.

## Deploy

It is a static site, so it works on Vercel, Netlify or GitHub Pages.

The home page lives at `html/index.html`, not in the project root. Pick one:

- Add a root `index.html` that redirects to `html/index.html`, or
- Move the files up one level and fix the `../` paths.

## Before you go live

- [ ] **Link previews:** in each page's `<head>`, delete the comment marks around the `og:url`, `og:image` and `twitter:card` tags and replace `YOUR-DOMAIN` with your real address. WhatsApp needs full `https://` links.
- [ ] **Age:** add it in the About facts list in `index.html` (the commented-out row), if you want it shown.
- [ ] **Courses:** add the course title and year for CIL Academy in the Training list.
- [ ] **Portrait:** swap the X mark in the About section for a real photo (instructions are in a comment in `index.html`).
- [ ] **Gallery preview:** three tiles load images from the Excel's Gallery site. If you delete a post there, remove its tile here.

## Update the content

- **Add a project:** copy an `<article class="project-card">` block in `projects.html`. Flagships go in the "Flagship projects" grid.
- **Change the stats:** edit the `.proof` list in the hero of `index.html`.
- **Change a craft tile:** edit the `.crafts` list under the hero of `index.html`.
- **Colours and fonts:** all in the `:root` variables at the top of `css/styles.css`.
- **Screenshots:** run `node tools/screenshots.mjs` from this folder. It needs Google Chrome and an internet connection, and saves 1280x720 shots to `images/shots/`.

## Design notes

- Dark theme, blue accent, Space Grotesk for headings, Inter for body text, JetBrains Mono for small labels.
- Responsive down to phones, with visible keyboard focus, a skip link and reduced-motion support.

## Links

- GitHub: [Xcelsama](https://github.com/Xcelsama)
- LinkedIn: [Excel Hephzibah Amadi](https://www.linkedin.com/in/excel-hephzibah-amadi-5733b4298)
- TikTok: [@xcel_sama](https://www.tiktok.com/@xcel_sama)
- Email: ms.excel.amadi@gmail.com

## Licence

Code is free to read and learn from. Please don't copy the design, text, posters or photos without asking.