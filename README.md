# Project Cider

A fictional student programming exchange and Coming Soon teaser, built for the November 2026 CSS Technical Department assignment.

**Live website:** https://project-cider.pages.dev/

## Run locally

Use Node.js 22.23.4 or newer, as required by `package.json`.

```sh
npm ci
npm run astro -- dev --background
```

Manage the background development server with:

```sh
npm run astro -- dev status
npm run astro -- dev logs
npm run astro -- dev stop
```

Build and preview the static production output:

```sh
npm run build
npm run preview
```

The build output is `dist/`, suitable for Cloudflare Pages with framework preset **Astro** and build command `npm run build`.

## Project structure

- `src/layouts/BaseLayout.astro`: shared document, page metadata, navigation, footer, and maker credit.
- `src/pages/index.astro`: event introduction, Coming Soon announcement, and proposed activities.
- `src/pages/about.astro`: event purpose, proposed activities, and objectives.
- `src/pages/404.astro`: custom error page with a button-styled homepage link.
- `src/styles/global.css`: font, light/dark color tokens, typography, and repeated visual patterns.
- `public/fonts/`: local pixel font and attribution notes.
- `done.md`: assignment progress and verification evidence.
- `task_README.md`: original assignment instructions.

## Design and Astro concepts

The selected design uses slate and dusty violet, Minecraft Pixel headings and labels, and sans-serif paragraphs. Light and dark themes follow the device preference through `prefers-color-scheme`; no JavaScript is needed. Short link transitions are disabled when reduced motion is requested.

`BaseLayout` accepts `eventName`, `title`, and `description` props, like named function arguments. Its `<slot />` receives the content of each page. Shared rules live in `global.css`; page-specific `<style>` blocks are scoped by Astro. Navigation uses ordinary HTML links and marks the current page with `aria-current`.

The exact `<.` symbol is a subtle maker credit in the footer, not the event logo.

## Font attribution

Minecraft Pixel / Minecraft Regular is by [Pwnage_Block](https://fontstruct.com/fontstructions/show/432966), under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).

The downloaded legacy TrueType file had invalid table checksums. Its packaging was regenerated with FontTools for browser compatibility; glyph outlines were not changed. FontTools is not a project dependency. Source, license, and modification details are in [`public/fonts/LICENSE.txt`](public/fonts/LICENSE.txt).

## Manual submission

The upstream assignment repository is [CS-Society-USM/Monthly-Task-Nov-2026](https://github.com/CS-Society-USM/Monthly-Task-Nov-2026). The student will create the Pull Request personally. Include the live URL above and verify Home/About navigation and a nonexistent URL on the deployed version before submission.
