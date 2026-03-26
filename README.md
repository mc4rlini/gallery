# Gallery - gallery.carlini.me

Photo gallery powered by [Hugo](https://gohugo.io/) with the [Gallery theme](https://github.com/nicokaiser/hugo-theme-gallery) by Nico Kaiser. Deployed on [Netlify](https://www.netlify.com/).

## Adding photos

1. Create a new folder in `content/` for each album (e.g., `content/my-album/`)
2. Add an `index.md` file with frontmatter:
   ```yaml
   ---
   title: "Album Title"
   description: "Album description"
   date: 2026-03-01
   ---
   ```
3. Drop your images (JPG, PNG) into the same folder
4. An image with "feature" in its name (e.g., `feature.jpg`) will be used as the album thumbnail

## Local development

```bash
hugo server -D
```

## Deploy

Push to `main` branch — Netlify builds and deploys automatically.
