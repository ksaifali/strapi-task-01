# TASK-1 – Strapi Local Setup

This repository contains a local Strapi setup completed as part of **TASK-1**.
The objective was to explore the Strapi codebase, run Strapi locally, start the Admin Panel, and create a sample content type.

---

## 📌 Objectives Completed

- Cloned the official Strapi repository for exploration
- Explored the Strapi project folder structure
- Created and ran a Strapi application locally
- Started the Strapi Admin Panel
- Created a sample content type using Content-Type Builder
- Pushed the setup to GitHub

---

## 🧩 Strapi Repository Exploration

The official Strapi repository was cloned from:

https://github.com/strapi/strapi


Key folders explored:

- `packages/` – Core Strapi framework modules
- `docs/` – Documentation source
- `scripts/` – Build and automation scripts
- `tests/` – Test suites
- `package.json` – Monorepo configuration

> Note: The Strapi core repository is a framework and does not directly run a CMS instance.

---

## 🚀 Running Strapi Locally

A Strapi application was created using the official CLI:

```bash
npx create-strapi-app my-strapi-app
cd my-strapi-app
npm run develop

Admin Panel

URL: http://localhost:1337/admin

Admin panel runs in development mode with hot reload enabled
Sample Content Type

A Single Type named About was created using the Content-Type Builder.

Fields:

title – Text

blocks – Dynamic Zone

Components used:

Rich Text

Media

Quote

Slider

This demonstrates Strapi’s support for flexible and reusable content modeling.
vailable Scripts
npm run develop   # Start Strapi in development mode
npm run start     # Start Strapi in production mode
npm run build     # Build the admin panel
npm run deploy    # Deploy the Strapi application
itHub Repository

This repository contains the complete local Strapi setup for TASK-1.

🚀 Getting Started with Strapi (Official)

Strapi comes with a full featured Command Line Interface (CLI) which lets you scaffold and manage your project in seconds.

develop

Start your Strapi application with autoReload enabled.

npm run develop
# or
yarn develop

start

Start your Strapi application without autoReload.

npm run start
# or
yarn start

build

Build your admin panel.

npm run build
# or
yarn build
