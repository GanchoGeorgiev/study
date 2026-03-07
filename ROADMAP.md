# Web Development Study Roadmap
**Goal:** Become a job-ready frontend/fullstack developer
**Pace:** 1-2 hours/day | **Estimated duration:** ~5-6 months

---

## Glossary — Terms You'll Encounter (plain English)

| Term | What it means |
|---|---|
| **API** | A way for two programs to talk to each other. Like a waiter taking your order to the kitchen. |
| **REST API** | The most common style of API. Uses URLs and HTTP methods to read/create/update/delete data. |
| **HTTP** | The rules browsers and servers use to communicate. Every website uses it. |
| **GET / POST / PUT / DELETE** | The 4 main actions in REST: read, create, update, delete data. |
| **JSON** | The format APIs use to send data — like a JavaScript object in text form. |
| **Status code** | A number the server sends back: 200 = OK, 404 = not found, 500 = server error. |
| **Frontend** | Everything the user sees — HTML, CSS, JavaScript running in the browser. |
| **Backend** | The server-side code that handles logic, stores data, and sends responses. |
| **Database** | A structured place to store data permanently (users, posts, products, etc.). |
| **SQL** | The language used to talk to most databases: SELECT, INSERT, UPDATE, DELETE. |
| **Supabase** | A free hosted database (PostgreSQL) + auth + storage. No server needed. |
| **Authentication** | Verifying who a user is (login/signup). |
| **JWT** | A token sent after login to prove you're logged in on future requests. |
| **Deployment** | Putting your app online so other people can access it. |
| **Vercel** | A free platform to deploy Next.js apps in minutes. |

---

## How to Use This Plan
1. Work through phases **in order** — each one builds on the previous
2. Update `progress.md` after every session
3. Use Claude Code as your daily coding partner — ask it to explain, quiz you, and review your code
4. Push every project to GitHub (set up in Phase 3)

---

## Phase 1 — HTML & CSS Fundamentals
**Duration:** 3-4 weeks
**Folder:** `phase-1-html-css/`

### What You'll Learn
- How the web works (browsers, servers, HTTP basics)
- HTML: document structure, semantic tags, forms, links, images, tables
- CSS: selectors, specificity, box model, colors, fonts, flexbox, grid
- Responsive design: media queries, mobile-first approach
- Dev tools in the browser (inspect element)

### Projects
- [ ] Personal bio page (HTML only, then add CSS)
- [ ] Product landing page (flexbox layout)
- [ ] Photo gallery grid (CSS grid + responsive)

### Checkpoint — You're ready for Phase 2 when you can:
- Build a multi-section webpage from scratch without looking things up
- Center elements using flexbox and grid
- Make a page look reasonable on both mobile and desktop

---

## Phase 2 — JavaScript Fundamentals
**Duration:** 5-6 weeks
**Folder:** `phase-2-javascript/`

### What You'll Learn
- Variables (`let`, `const`), data types, operators
- Conditionals (`if/else`, `switch`)
- Loops (`for`, `while`, `forEach`)
- Functions, arrow functions, scope, closures
- Arrays and objects (the most important topic in JS)
- DOM manipulation: selecting elements, changing content, handling events
- `localStorage` — saving data in the browser
- **What an API is** — a way for programs to talk to each other over the internet
- **What REST means** — a standard set of rules for how APIs work (GET, POST, PUT, DELETE)
- **JSON format** — the language APIs use to send data back and forth
- **HTTP & status codes** — 200 OK, 404 Not Found, 500 Server Error, etc.
- `fetch()`, `async/await`, Promises — how to call APIs from JavaScript
- Reading API documentation — how to figure out any API on your own

### Projects
- [ ] Interactive quiz app (DOM + events)
- [ ] To-do list (CRUD with localStorage)
- [ ] Weather app (Fetch API + async/await with a real public API)

### Checkpoint — You're ready for Phase 3 when you can:
- Write functions that take inputs and return outputs confidently
- Manipulate the DOM to update a page dynamically
- Call a REST API, read its JSON response, and display the data on a page
- Explain what GET and POST requests are and when to use each

---

## Phase 3 — Git & GitHub
**Duration:** 1 week (run alongside Phase 2, week 3)
**Folder:** `phase-3-git/`

### What You'll Learn
- What version control is and why it matters
- `git init`, `git add`, `git commit`, `git status`, `git log`
- Branches: `git branch`, `git checkout`, `git merge`
- Remote repos: `git push`, `git pull`, `git clone`
- GitHub: profile, repositories, README files
- How to showcase your projects professionally

### Tasks
- [ ] Create a GitHub account
- [ ] Push all Phase 1 and 2 projects to GitHub
- [ ] Write a good README for each project

---

## Phase 4 — React
**Duration:** 5-6 weeks
**Folder:** `phase-4-react/`

### What You'll Learn
- Why React exists (component-based UI)
- JSX syntax
- Components, props, and state
- `useState` and `useEffect` hooks
- Handling events and forms in React
- Lists and conditional rendering
- React Router (multiple pages in a single-page app)
- Fetching data in React

### Projects
- [ ] Counter and form components (learning exercises)
- [ ] Notes / bookmark app (state management)
- [ ] Movie / book search app (API + React Router)

### Checkpoint — You're ready for Phase 5 when you can:
- Build a multi-page React app that fetches and displays real data
- Understand the component lifecycle and when to use `useEffect`

---

## Phase 5 — TypeScript
**Duration:** 2-3 weeks
**Folder:** `phase-5-typescript/`

### What You'll Learn
- Why TypeScript exists (catching errors before running code)
- Basic types: `string`, `number`, `boolean`, `array`, `object`
- Interfaces and type aliases
- Function types and return types
- Generics (basics)
- Using TypeScript in a React project

### Tasks
- [ ] Rewrite one of your Phase 4 projects in TypeScript
- [ ] Build a small new component using TypeScript from scratch

---

## Phase 6 — Next.js + Backend + Databases
**Duration:** 5-6 weeks
**Folder:** `phase-6-nextjs/`

### What You'll Learn

#### Next.js
- What Next.js adds on top of React
- File-based routing (pages and app router)
- Server-Side Rendering (SSR) vs Static Site Generation (SSG) vs Client-Side Rendering
- Image optimization and metadata (SEO basics)
- Deploying to Vercel (free hosting)

#### Building Your Own API (Backend)
- What a backend is: the server that stores and manages data
- Next.js API routes — write backend code inside your Next.js project
- Handling GET, POST, PUT, DELETE requests in your own API
- What middleware is and how to use it
- Authentication basics: sessions, JWTs, cookies

#### Databases with Supabase
- **What a database is** — a structured place to store data permanently
- **SQL basics** — SELECT, INSERT, UPDATE, DELETE (the language databases speak)
- **What Supabase is** — a free, hosted PostgreSQL database with a nice dashboard
- Tables, rows, columns — how data is organized
- Connecting your Next.js app to Supabase
- Querying data from your app: read, write, update, delete
- Supabase Auth — built-in user login/signup (no code needed)
- Supabase Storage — uploading images and files

### Projects
- [ ] Personal portfolio site (your main public project, deployed to Vercel)
- [ ] Blog with markdown or Supabase as the content source
- [ ] Fullstack app with auth + database: task manager, budget tracker, recipe app, etc.

### Checkpoint — You're ready for job hunting when you can:
- Build and deploy a fullstack Next.js app with a real database (Supabase)
- Handle user login and protect routes that require authentication
- Explain the difference between frontend, backend, and database
- Build your own REST API and document what each endpoint does

---

## Phase 7 — Job Preparation (Ongoing from Phase 4+)
**Folder:** `phase-7-job-prep/`

### Tasks
- [ ] Portfolio site live on Vercel with 3+ projects
- [ ] GitHub profile polished (pinned repos, good READMEs, profile README)
- [ ] Resume: 1 page, focused on projects and skills
- [ ] LinkedIn profile updated
- [ ] LeetCode: solve 20-30 easy problems in JavaScript
- [ ] Practice explaining your projects out loud (mock interviews)

### Skills to highlight on resume/LinkedIn
- HTML, CSS, JavaScript, TypeScript
- React, Next.js
- Git, GitHub
- REST APIs, async JavaScript
- Vercel, Supabase (or similar)

---

## Tech Stack Summary

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3, Flexbox, Grid |
| Logic | JavaScript (ES6+) |
| Types | TypeScript |
| UI Library | React |
| Framework | Next.js |
| Version Control | Git + GitHub |
| Backend/DB | Next.js API routes + Supabase |
| Deployment | Vercel |

---

## Your Daily Workflow
1. Open `progress.md` — check what you did yesterday
2. Open the current phase folder and continue from where you left off
3. Code for 1-2 hours — build something, don't just watch/read
4. When stuck, ask Claude Code: `What does X mean?` or `Review my code`
5. Log what you did in `progress.md`
