# 🚀 CSS Tech Department — November 2026 Task Tracker

**Project:** Project Cider, Coming Soon Teaser Website  
**Tech Stack:** Astro, HTML, CSS, JavaScript, Git, GitHub, Cloudflare Pages  
**Status:** 🟡 In Progress  
**Current Focus:** Styling, Website Content & Testing

## Phase 1 — Project Setup ✅
*Goal: Get an empty Astro project running locally.*

- [x] Fork the original USM CSS repository.
- [x] Clone my forked repository to my laptop.
- [x] Open the cloned repository in VS Code.
- [x] Initialize Astro using `npm create astro@latest .` and choose the **Empty** template.
- [x] Run `npm run dev` and confirm the starter website works.

**Milestone:** ✅ Astro development environment is ready.

## Phase 2 — Learn Astro Fundamentals ✅
*Goal: Understand the structure before building the website.*

- [x] Explore the `src/`, `pages/`, `layouts/`, and `public/` directories.
- [x] Understand the basic structure of `.astro` files, including frontmatter and HTML templates.
- [x] Learn how Astro file-based routing works.
- [x] Understand what layouts do and why they prevent repeated code.
- [x] Understand how `<slot />` inserts page content into a shared layout.
- [x] Understand Astro imports and reusable components.
- [x] Learn how JavaScript variables can be displayed using `{variable}`.
- [x] Understand how props pass data between Astro components.
- [x] Understand where `Astro.props` comes from.
- [x] Use JavaScript object destructuring to access props.
- [x] Learn how Astro's development server automatically updates the browser using HMR.

**Milestone:** ✅ Basic Astro fundamentals understood and applied.

## Phase 3 — Build the Website 🟡
*Goal: Create the three required pages with shared components.*

### 3.1 — Shared Layout ✅
- [x] Create `src/layouts/BaseLayout.astro`.
- [x] Add HTML boilerplate (`html`, `head`, `body`).
- [x] Add a navigation bar linking Home and About.
- [x] Add a shared footer.
- [x] Use `<slot />` to display content from individual pages.
- [x] Receive an `eventName` prop using `Astro.props`.
- [x] Display the event name dynamically in the footer.
- [ ] Replace the generic browser title with an appropriate page title.

### 3.2 — Home Page 🟡
- [x] Create or edit `src/pages/index.astro`.
- [x] Import and use `BaseLayout`.
- [x] Choose a fictional event name: **Project Cider**.
- [x] Add a visible "Coming Soon" message.
- [x] Practice using a JavaScript variable for the event name.
- [x] Pass `eventName` to `BaseLayout`.
- [ ] Write a short, engaging event description.
- [ ] Add a catchy headline or tagline.

### 3.3 — About Page 🟡
- [x] Create `src/pages/about.astro`.
- [x] Import and use `BaseLayout`.
- [x] Add an About heading and introductory text.
- [ ] Explain Project Cider's purpose and concept.
- [ ] Add meaningful and engaging event details.

### 3.4 — Custom 404 Page 🟡
- [x] Create `src/pages/404.astro`.
- [x] Add a friendly "Page Not Found" message.
- [x] Add a link returning to `/`.
- [x] Reuse `BaseLayout`.
- [ ] Confirm the custom 404 page works on the deployed website.
- [ ] Confirm it uses the intended styling.

**Milestone:** 🟡 All required page files exist and have been reviewed. Final content, styling and runtime verification remain.

## Phase 4 — Styling & Testing ⬜
*Goal: Make Project Cider presentable and functional.*

- [ ] Choose a consistent color palette and font.
- [ ] Add CSS styling to `BaseLayout.astro` or an appropriate stylesheet.
- [ ] Style the navigation bar.
- [ ] Style the homepage and Coming Soon announcement.
- [ ] Style the About and 404 pages.
- [ ] Style the shared footer.
- [ ] Make the website responsive on mobile and desktop.
- [x] Test local navigation between Home and About.
- [ ] Check the finished website at desktop and mobile widths.
- [ ] Run `npm run build` successfully.
- [ ] Fix any build errors or warnings that require attention.

**Milestone:** ⬜ Website is styled, responsive and builds successfully.

## Phase 5 — Git & GitHub 🟡
*Goal: Submit my work using proper version control.*

### Previous Git Progress
- [x] Review changed files using `git status`.
- [x] Stage and commit earlier project work.
- [x] Push an earlier commit to my forked repository.

### Final Project Submission
- [ ] Review the latest Project Cider changes using `git status`.
- [ ] Stage the updated website files.
- [ ] Commit the latest implementation.
- [ ] Push the latest changes to my fork.
- [ ] Open a Pull Request to the correct original USM CSS repository.
- [ ] Write a short PR description explaining what I built.

**Milestone:** ⬜ Latest website changes pushed and Pull Request created.

## Phase 6 — Cloudflare Deployment 🟡
*Goal: Deploy the site and experience CI/CD.*

- [x] Log in to Cloudflare.
- [ ] Navigate to **Workers & Pages → Create application → Pages → Connect to Git**, or the equivalent current interface.
- [ ] Connect my GitHub account and select the appropriate repository.
- [ ] Configure the build settings:
  - Framework preset: `Astro`
  - Build command: `npm run build`
  - Build output directory: `dist`
- [ ] Deploy Project Cider.
- [ ] Obtain the public `.pages.dev` URL.

**Milestone:** ⬜ Project Cider is publicly accessible.

## Phase 7 — Final Verification & Submission ⬜
*Goal: Meet every requirement in the Definition of Done.*

- [ ] Open the live website and confirm it loads correctly.
- [ ] Test navigation between Home and About on the deployed site.
- [ ] Visit `/does-not-exist` and confirm my custom 404 page appears.
- [ ] Confirm Project Cider displays correctly on mobile.
- [ ] Add the live Cloudflare Pages URL to my Pull Request.
- [ ] Verify the PR contains all required files and the deployment link.
- [ ] Update this task tracker to reflect the final completed work.

**Milestone:** ⬜ November CSS task completed! 🎉

---

## 🏆 Final Deliverables

**Project Name:** Project Cider

**GitHub Repository:**  
https://github.com/JavanMyna/Monthly-Task-Nov-2026

**Pull Request:**  
Pending creation.

**Live Website:**  
Pending Cloudflare Pages deployment.

## 🌱 Optional Improvements
*Only attempt these after meeting all mandatory requirements.*

- [ ] Add subtle animations or hover effects.
- [ ] Add a custom Project Cider favicon.
- [ ] Improve page metadata and SEO.
- [ ] Make page titles dynamic using layout props.
- [ ] Explore reusable Astro components beyond layouts.
- [ ] Explore Astro's scoped CSS.
- [ ] Test automatic redeployment by pushing a small update.

## 📝 Learning Reflection

**Things I learned:**

1. **Astro file-based routing:** Files inside `src/pages/` automatically generate website routes, such as `index.astro` for `/` and `about.astro` for `/about`.
2. **Reusable layouts:** `BaseLayout.astro` can provide shared HTML structure, navigation and footer. The `<slot />` element allows individual pages to insert their own content.
3. **Astro Props:** Components can receive data through `Astro.props`, similar to receiving function arguments in Python. JavaScript destructuring can extract these values.
4. **Frontmatter:** JavaScript inside `---` runs during Astro's rendering process rather than automatically in the visitor's browser.
5. **Hot Module Replacement (HMR):** Changes made in VS Code can appear automatically in the browser while the Astro development server is running.

**Problems I encountered:**
- Had difficulty remembering basic HTML structure and navigation syntax after relying heavily on AI-generated code.
- Initially didn't know how to create navigation links.
- Didn't initially understand where `Astro.props` came from.
- Accidentally shared Windows `.url` shortcuts instead of actual `.astro` files for code review.

**How I solved them:**
- Reused existing HTML boilerplate and learned the purpose of the relevant elements.
- Learned to use `<nav>` and `<a href="">` to create navigation links.
- Learned that `Astro.props` is supplied automatically by Astro to components.
- Uploaded the actual `.astro` source files for review.
- Practiced writing and modifying code manually rather than generating the entire website with AI.

**Concepts I want to explore next:**
- Astro scoped CSS and responsive styling.
- Dynamic page titles and component props.
- Static site generation and production builds.
- GitHub Pull Requests.
- Cloudflare Pages deployment and CI/CD.

---

**Final Status:** 🟡 In Progress

**Next Action:** Finish Project Cider's event content, then begin CSS styling and responsive design.