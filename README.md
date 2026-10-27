# holegar.github.io

My portfolio site, published with GitHub Pages. Every commit to `main` updates the live site within a minute or two.

## What's here

| File or folder | What it is |
|---|---|
| `index.html` | The homepage |
| `style.css` | Shared styling for every page. Change it once and every page updates |
| `images/` | Photos and images |
| `images/projects/` | Diagrams and screenshots for project pages |
| `projects/project-template.html` | A blank project page to copy |
| `stats/` | A private visitor stats page. Not linked from the site |

## Add your photo

1. Use a square photo, at least 336 × 336 pixels, under 300 KB.
2. Name it exactly `sam.jpg` (lowercase) and upload it into `images/`.
3. Commit. It appears top right on desktop and above your name on a phone.

Until the file exists, the photo space stays hidden, so nothing looks broken.

## Add a project page

1. Copy `projects/project-template.html` and rename the copy, for example `projects/cdc-demo.html`. Use lowercase and hyphens.
2. Replace every `[bracketed]` placeholder and delete any section you don't need.
3. Put its images in `images/projects/`, named to match, for example `cdc-demo-diagram.png`.
4. On `index.html`, find the project under "Public projects I'm building". Turn its name into a link to `projects/cdc-demo.html` and remove the "In progress" label.
5. Commit to `main`.

The template itself isn't linked from the homepage, so it won't show up for visitors.

## Visitor stats

Visits are counted by [GoatCounter](https://www.goatcounter.com/), which uses no cookies. Every page has one script line just before `</body>`. Pages copied from the template already have it.

To see the numbers, open [holegar.github.io/stats/](https://holegar.github.io/stats/) or the GoatCounter dashboard at holegar.goatcounter.com.

- The stats page asks for a GoatCounter API key the first time. Create one that can only read statistics. It's saved in that browser only, so never put it in this repo: everything here is public.
- Tick "Don't count my own visits" on the stats page in each browser you use, so your own visits stay out of the numbers.

## If something doesn't appear

- File names are case sensitive. `Sam.JPG` and `sam.jpg` are different files.
- Seeing the old version? Hard refresh with Ctrl+F5, or Cmd+Shift+R on a Mac.
- Check the Actions tab. A green tick on "pages build and deployment" means it's live.
