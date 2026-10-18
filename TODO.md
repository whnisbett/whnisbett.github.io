# Site tasks

Live at https://whnisbett.github.io. Repo deploys on push to `main`.

## Decide
- [x] Home page layout: Readme style (minimum was the runner-up)
- [x] Font: Figtree
- [ ] Custom domain, or stay on whnisbett.github.io
- [ ] Which painting(s) to use, and where they live (writing page, about page)
- [ ] Site name in the tab: "William Nisbett" or "Billy Nisbett"

## Write
- [x] Home bio (draft D, wry; confirm Texas/Singapore/Mandarin facts and point "Read this first" at a real post)
- [ ] About page: longer bio, the "this site" colophon, what the paintings are
- [ ] Projects page: fill in real projects with links (Quill, store-state tool, resume pipeline, plus side projects)
- [ ] Reading page: real list with one line each
- [ ] First post (src/content/writing/*.md)
- [ ] Two or three more posts so the writing page has a "Start here" list that means something

## Assets
- [x] Photo for the home page
- [ ] Favicon (public/favicon.svg is Astro's default)

## Build
- [x] Astro scaffold, pages, writing collection, RSS
- [x] GitHub Pages deploy via Actions, Node 22
- [x] Light mode only
- [x] Apply the chosen layout and font
- [x] Background: iron-filings dipole field with click waves (src/components/Field.astro)
- [ ] Open Graph / Twitter meta tags in Base.astro so links unfurl
- [ ] 404 page (src/pages/404.astro)
- [ ] Sitemap (@astrojs/sitemap) once there's a final domain
- [ ] Code block styling check once a post has code in it
- [ ] Check phone width on a real phone

## Later, maybe
- [ ] Newsletter or "get posts by email" link
- [ ] Tags page if the post count grows
- [ ] "Now" page
