# Personal site

Readme-style single-column site built with [Astro](https://astro.build), deployed to GitHub Pages on every push to `main`.

```
src/pages/index.astro        home: photo, bio, links
src/pages/writing/           index (featured above all) and post pages
src/pages/{projects,reading,about}.astro
src/content/writing/*.md     posts; frontmatter fields under "Write a post" below
src/layouts/Base.astro       <head>, font link, background field
src/components/Field.astro   the cursor-magnet background; delete the <Field /> line in Base.astro to turn it off
src/styles/global.css        all styling; colours and font are CSS variables at the top
public/images/               me.jpg (home photo)
```

## Run

```sh
npm install
npm run dev       # http://localhost:4321
npm run build     # static output in dist/
```

## Write a post

Add `src/content/writing/my-post.md` with `title` and `date`. Set `featured: true` to pin it under "Start here". Remove `draft: true` to publish. The filename is the URL slug.

## Change the font

Edit `--font` in `src/styles/global.css` and the Google Fonts `<link>` in `src/layouts/Base.astro`.
