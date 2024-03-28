# Minimal Astro Blog Template

## ✨ Features

- `Tailwind CSS` for styling responsive ui
- `MDX` to write blog posts
- `rehype-pretty-code` for styling code

## ⚒️ Integrations

- [`@astrojs/Tailwind`](https://docs.astro.build/en/guides/integrations-guide/tailwind/)
- [`@astrojs/MDX`](https://docs.astro.build/en/guides/integrations-guide/mdx/)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
src
 ┣ assets
 ┣ components
 ┣ content
 ┃ ┣ blog
 ┃ ┗ config.ts
 ┣ layouts
 ┣ pages
 ┃ ┣ blog
 ┃ ┃ ┗ [slug].astro
 ┃ ┗ index.astro
 ┗ env.d.ts
```

- write a blog post: use `src/content/blog`
- update `front matter` for post: use `src/content/config.ts`
- add components: use `src/components`

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
