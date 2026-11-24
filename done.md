# 🚀 CSS Tech Department — November 2026 Task Tracker

**Project:** Project Cider, Coming Soon Teaser Website  
**Tech Stack:** Astro, HTML, CSS, JavaScript, Git, GitHub, Cloudflare Pages  
**Status:** 🟡 In Progress  
**Current Focus:** Student Code Review & Manual Pull Request Submission

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

## Phase 3 — Build the Website ✅
*Goal: Create the three required pages with shared components.*

### 3.1 — Shared Layout ✅
- [x] Create `src/layouts/BaseLayout.astro`.
- [x] Add HTML boilerplate (`html`, `head`, `body`).
- [x] Add a navigation bar linking Home and About.
- [x] Add a shared footer.
- [x] Use `<slot />` to display content from individual pages.
- [x] Receive an `eventName` prop using `Astro.props`.
- [x] Display the event name dynamically in the footer.
- [x] Replace the generic browser title with an appropriate page title.

### 3.2 — Home Page ✅
- [x] Create or edit `src/pages/index.astro`.
- [x] Import and use `BaseLayout`.
- [x] Choose a fictional event name: **Project Cider**.
- [x] Add a visible "Coming Soon" message.
- [x] Practice using a JavaScript variable for the event name.
- [x] Pass `eventName` to `BaseLayout`.
- [x] Write a short, engaging event description.
- [x] Add a catchy headline or tagline.

**Project Cider's tagline:**  
*Build skills. Share what you know.*

**Event concept:**  
A proposed student-led programming exchange for practical workshops, student project sharing, and collaborative coding. Dates and programme details are not confirmed.

### 3.3 — About Page ✅
- [x] Create `src/pages/about.astro`.
- [x] Import and use `BaseLayout`.
- [x] Add an About heading and introductory text.
- [x] Explain Project Cider's purpose and concept.
- [x] Add meaningful and engaging event details.
- [x] Include a "What to Expect" subsection.
- [x] Review and improve grammatical errors.

**Proposed event activities:**
- Practical programming workshops.
- Student project sharing and constructive feedback.
- Collaborative coding and comparing approaches.

### 3.4 — Custom 404 Page ✅
- [x] Create `src/pages/404.astro`.
- [x] Add a friendly "Page Not Found" message.
- [x] Add a link returning to `/`.
- [x] Reuse `BaseLayout`.
- [x] Confirm the custom 404 page works on the deployed website.
- [x] Confirm the final page uses the intended styling.

**Milestone:** ✅ All three required pages are implemented, styled, and verified locally and on Cloudflare Pages.

## Phase 4 — Styling & Testing 🟡
*Goal: Make Project Cider presentable and functional.*

### 4.1 — Basic CSS ✅
- [x] Learn how CSS selectors, properties and values work.
- [x] Understand the purpose of `background-color`.
- [x] Understand the basics of `padding`.
- [x] Learn the basic concept of Astro scoped CSS.
- [x] Choose an initial color palette and font.
- [x] Add basic CSS styling to `BaseLayout.astro`.
- [x] Style the navigation bar.
- [x] Apply shared typography and spacing to page content.
- [x] Style the shared footer.
- [x] Introduce responsive CSS properties such as `max-width`, percentages and `clamp()`.

### 4.2 — Design Improvements 🟡
- [x] Explore websites offering ready-made UI templates and design inspiration.
- [x] Discover Astro Themes, v0 Templates and shadcn/ui Blocks.
- [x] Prepare an AI coding-agent prompt for improving Project Cider's visual design.
- [x] Choose a final visual design reference: Design C with Minecraft Pixel typography.
- [x] Implement the selected design in the existing Astro project.
- [ ] Review AI-generated changes and understand their purpose.
- [x] Finalize the visual appearance of Home, About and 404 pages.

### 4.3 — Testing ✅
- [x] Test local navigation between Home and About.
- [x] Test the completed website at desktop width (1440px).
- [x] Test the completed website at mobile width (375px).
- [x] Confirm navigation remains accessible on smaller screens.
- [x] Confirm there is no unwanted horizontal scrolling.
- [x] Run `npm run build` successfully on the local machine.
- [x] Fix any build errors or warnings requiring attention (none reported).

**Verification:** The static production preview passed all three routes at 1440px and 375px in both system light/dark modes. Home/About links and the 404 homepage return worked. Pixel font loading, keyboard skip-link focus, and reduced-motion behavior passed. No broken assets or runtime errors were recorded.

**Milestone:** 🟡 Implementation and local verification are complete. Student review of the code remains unconfirmed.

## Phase 5 — Git & GitHub 🟡
*Goal: Submit my work using proper version control.*

### Previous Git Progress
- [x] Review changed files using `git status`.
- [x] Stage and commit earlier project work.
- [x] Push an earlier commit to my forked repository.
- [x] Prepare commit messages for the Astro structure and Project Cider content changes.

### Final Project Submission
- [x] Review the final authored changes using a selective commit draft.
- [x] Select authored website changes for the final commit.
- [x] Commit the final implementation (`5918c31`).
- [x] Push the latest changes to my fork (`main` and `feat/project-cider-pixel`).
- [ ] Personally open a Pull Request to the verified original USM CSS repository.
- [ ] Review and paste the prepared PR description, including the live URL.

**Milestone:** 🟡 Website implementation committed and pushed. Pull Request creation remains the student's responsibility.

**Commit note:** `5918c31` contains the verified website redesign. At the student's request, the favicon integration commit also includes the updated tracker and existing playground edit. The favicon update has been verified locally but has not yet been pushed or deployed.

## Phase 6 — Cloudflare Deployment ✅
*Goal: Deploy the site and experience CI/CD.*

- [x] Log in to Cloudflare.
- [x] Navigate to **Workers & Pages → Create application → Pages → Connect to Git**, or the equivalent current interface.
- [x] Connect my GitHub account and select the appropriate repository.
- [x] Configure the build settings:
  - Framework preset: `Astro`
  - Build command: `npm run build`
  - Build output directory: `dist`
- [x] Deploy Project Cider.
- [x] Obtain the public `.pages.dev` URL.
- [x] Confirm that the website is publicly accessible.

**Milestone:** ✅ Project Cider is publicly accessible through Cloudflare Pages.

**Live URL:**  
https://project-cider.pages.dev/

## Phase 7 — Final Verification & Submission 🟡
*Goal: Meet every requirement in the Definition of Done.*

- [x] Open the live website and confirm it loads correctly.
- [x] Test navigation between Home and About on the final deployed version.
- [x] Visit `/does-not-exist` and confirm my custom 404 page appears (HTTP 404).
- [x] Confirm Project Cider displays correctly on mobile.
- [ ] Push and verify the new favicon update on Cloudflare (the website redesign was already deployed and verified).
- [ ] Add the live Cloudflare Pages URL to my Pull Request.
- [ ] Verify the PR contains all required files and the deployment link.
- [x] Update this task tracker to reflect final completed work.

**Milestone:** 🟡 Website and deployment verified. The student still needs to create and verify the upstream PR.

**Live verification evidence:** The updated Home, About, and custom 404 pages passed at 1440px (dark) and 375px (light). Home/About links and the 404 return link worked. The local pixel font and signature-only footer were present. No horizontal overflow, broken assets, or runtime errors were recorded.

---

## 🏆 Final Deliverables

**Project Name:** Project Cider

**GitHub Repository:**  
https://github.com/JavanMyna/Monthly-Task-Nov-2026

**Pull Request:**  
To be created personally by the student; the assistant will not open a PR.

**Manual PR comparison:**  
https://github.com/CS-Society-USM/Monthly-Task-Nov-2026/compare/main...JavanMyna:Monthly-Task-Nov-2026:feat/project-cider-pixel?expand=1

**PR branches:** Base `CS-Society-USM/Monthly-Task-Nov-2026:main`; head `JavanMyna/Monthly-Task-Nov-2026:feat/project-cider-pixel`. No existing upstream PR by this account was found during the submission check.

**Live Website:**  
https://project-cider.pages.dev/

## 🌱 Optional Improvements
*Only attempt these after meeting all mandatory requirements.*

- [x] Add subtle hover transitions that respect reduced motion.
- [x] Add a custom Project Cider favicon, Apple touch icon, and named web manifest; verify all supplied icon dimensions and successful local responses.
- [x] Improve page metadata with page-specific titles and descriptions.
- [x] Make page titles dynamic using layout props.
- [ ] Explore reusable Astro components beyond layouts.
- [ ] Learn more about Astro's scoped CSS.
- [x] Test automatic redeployment with a new GitHub push and verify the result.

## 📝 Learning Reflection

**Things I learned:**

1. **Astro file-based routing:** Files inside `src/pages/` automatically generate website routes.
2. **Reusable layouts:** `BaseLayout.astro` provides shared HTML structure, navigation and footer. The `<slot />` element allows individual pages to insert their own content.
3. **Astro Props:** Components receive data through `Astro.props`, similar to receiving function arguments in Python.
4. **Frontmatter:** JavaScript inside `---` runs during Astro's rendering process rather than automatically in the browser.
5. **Hot Module Replacement (HMR):** Changes made in VS Code can appear automatically in the browser while the development server is running.
6. **CSS Fundamentals:** CSS selectors target HTML elements, while properties and values control their appearance.
7. **Astro Scoped CSS:** Styles defined inside an Astro component are scoped to that component by default. Global selectors can be used when necessary.
8. **Cloudflare Pages:** A static Astro website can be built and deployed through Cloudflare Pages.

**Implementation notes to review:**
- Shared CSS variables define the slate/violet palette; `prefers-color-scheme` switches themes without JavaScript.
- Minecraft Pixel is self-hosted with CC BY-SA 3.0 attribution; paragraphs use a readable sans-serif font.
- The `<.` mark is a footer maker credit, not event branding.
- Page-specific styles remain scoped; shared typography and reusable visual patterns live in `src/styles/global.css`.
- `aria-current`, visible focus outlines, a skip link, and a button-styled 404 return link support accessible navigation.
- These explanations have been provided; understanding is not marked complete until the student confirms their review.

**Problems I encountered:**
- Had difficulty remembering basic HTML structure and navigation syntax after relying heavily on AI-generated code.
- Initially didn't know how to create navigation links.
- Didn't initially understand where `Astro.props` came from.
- Accidentally shared Windows `.url` shortcuts instead of actual `.astro` files.
- Felt confused when transitioning from Astro fundamentals to CSS.
- Needed to balance learning concepts properly with completing the assignment efficiently.

**How I solved them:**
- Reused existing HTML boilerplate and learned the purpose of relevant elements.
- Learned to use `<nav>` and `<a href="">` to create navigation links.
- Learned that `Astro.props` is automatically supplied by Astro.
- Uploaded the actual `.astro` source files for review.
- Started CSS learning with a simple background-color change before adding more styling.
- Switched to completion-focused development when time became a constraint.
- Explored website templates and prepared an AI-agent prompt for the remaining design work.

**Concepts I want to explore next:**
- Responsive design and Flexbox.
- Dynamic page titles and component props.
- Static site generation and production builds.
- GitHub Pull Requests.
- Automatic deployment and CI/CD.
- AI-assisted frontend development without losing understanding of the code.

---

**Final Status:** 🟡 In Progress

**Next Actions:**
1. Review the changed code and confirm understanding.
2. Push the favicon integration and tracker commit when ready.
3. Personally create the upstream Pull Request with the live URL.
4. Verify the PR contains the required files and deployment link, then complete the submission checkboxes.