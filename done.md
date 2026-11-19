# 🚀 CSS Tech Department — November 2026 Task Tracker

**Project:** Coming Soon Teaser Website  
**Tech Stack:** Astro, Git, GitHub, Cloudflare Pages  
**Status:** 🔴 Not Completed

## Phase 1 — Project Setup
*Goal: Get an empty Astro project running locally.*

- [x] Fork the original USM CSS repository.
- [x] Clone my forked repository to my laptop.
- [x] Open the cloned repository in VS Code.
- [x] Initialize Astro using `npm create astro@latest .` and choose the **Empty** template.
- [x] Run `npm run dev` and confirm the starter website works.

**Milestone:** Astro development environment is ready.

## Phase 2 — Learn Astro Fundamentals
*Goal: Understand the structure before building the website.*

- [x] Explore the `src/`, `pages/`, `layouts/`, and `public/` directories.
- [ ] Understand how `.astro` files combine HTML, CSS, and JavaScript.
- [ ] Learn how Astro file-based routing works.
- [ ] Understand what layouts do and why they prevent repeated code.

**Milestone:** I understand how to organize a basic Astro website.

## Phase 3 — Build the Website
*Goal: Create the three required pages with shared components.*

### 3.1 — Shared Layout
- [ ] Create `src/layouts/BaseLayout.astro`.
- [ ] Add HTML boilerplate (`html`, `head`, `body`).
- [ ] Add a navigation bar linking Home and About.
- [ ] Add a shared footer.
- [ ] Use `<slot />` to display content from individual pages.

### 3.2 — Home Page
- [ ] Create or edit `src/pages/index.astro`.
- [ ] Import and use `BaseLayout`.
- [ ] Add a fictional event name and catchy headline.
- [ ] Write a short event description.
- [ ] Add a visible "Coming Soon" message.

### 3.3 — About Page
- [ ] Create `src/pages/about.astro`.
- [ ] Use `BaseLayout`.
- [ ] Explain the fictional event's purpose and concept.
- [ ] Add engaging event details.

### 3.4 — Custom 404 Page
- [ ] Create `src/pages/404.astro`.
- [ ] Add a friendly "Page Not Found" message.
- [ ] Add a button or link returning to `/`.
- [ ] Confirm it uses the intended styling.

**Milestone:** All three required pages are implemented.

## Phase 4 — Styling & Testing
*Goal: Make the website presentable and functional.*

- [ ] Choose a consistent color palette and font.
- [ ] Style the navigation bar, main content, and footer.
- [ ] Make the website responsive on mobile and desktop.
- [ ] Verify Home → About → Home navigation.
- [ ] Run `npm run build` successfully.

**Milestone:** Website works locally and builds without errors.

## Phase 5 — Git & GitHub
*Goal: Submit my work using proper version control.*

- [ ] Review changed files using `git status`.
- [ ] Stage and commit completed work.
- [ ] Push changes to my forked GitHub repository.
- [ ] Open a Pull Request to the original USM CSS repository.
- [ ] Write a short PR description explaining what I built.

**Milestone:** Pull Request is created.

## Phase 6 — Cloudflare Deployment
*Goal: Deploy the site and experience CI/CD.*

- [ ] Log in to Cloudflare.
- [ ] Navigate to **Workers & Pages → Create application → Pages → Connect to Git**.
- [ ] Connect my GitHub account and select the forked repository.
- [ ] Configure the build settings:
  - Framework preset: `Astro`
  - Build command: `npm run build`
  - Build output directory: `dist`
- [ ] Deploy and obtain my `.pages.dev` URL.

**Milestone:** Website is publicly accessible.

## Phase 7 — Final Verification & Submission
*Goal: Meet every requirement in the Definition of Done.*

- [ ] Open the live website and confirm it loads correctly.
- [ ] Test navigation between Home and About.
- [ ] Visit `/does-not-exist` and confirm my custom 404 page appears.
- [ ] Add the live Cloudflare Pages URL to my Pull Request.
- [ ] Verify the PR contains all required files and the deployment link.

**Milestone:** November CSS task completed! 🎉

---

## 🏆 Final Deliverables

**GitHub Repository:**  
`https://github.com/USERNAME/REPOSITORY`

**Pull Request:**  
`https://github.com/ORIGINAL-REPO/pull/NUMBER`

**Live Website:**  
`https://PROJECT-NAME.pages.dev`

## 🌱 Optional Improvements
*Only attempt these after meeting all mandatory requirements.*

- [ ] Add subtle animations or hover effects.
- [ ] Add a custom favicon.
- [ ] Improve page metadata and SEO.
- [ ] Learn how Astro components can be reused.
- [ ] Test automatic redeployment by pushing a small update.

## 📝 Learning Reflection

**Three things I learned:**
1.
2.
3.

**Problems I encountered:**
-

**How I solved them:**
-

**Concepts I want to explore next:**
-

---

**Final Status:** ⬜ Not Started / 🟡 In Progress / ✅ Completed