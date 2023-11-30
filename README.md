# Next.js + Tailwind CSS + TypeScript Template for Start

## Features

This repository is battery packed with:

- ⚡️ Next.js 13 with App Router
- ⚛️ React 18
- ✨ TypeScript
- 💨 Tailwind CSS 3 — Configured with CSS Variables to extend the **primary** color
- 🃏 Jest — Configured for unit testing
- 📈 Absolute Import and Path Alias — Import components using `@/` prefix
- 📏 ESLint — Find and fix problems in your code, also will **auto sort** your imports
- 💖 Prettier — Format your code consistently
- 🐶 Husky & Lint Staged — Run scripts on your staged files before they are committed
- 🤖 Conventional Commit Lint — Make sure you & your teammates follow conventional commit
- ⏰ Release Please — Generate your changelog by activating the `release-please` workflow
- 👷 Github Actions — Lint your code on PR
- 🚘 Automatic Branch and Issue Autolink — Branch will be automatically created on issue **assign**, and auto linked on PR
- 🔥 Snippets — A collection of useful snippets
- 🗺 Site Map — Automatically generate sitemap.xml
- 📦 Expansion Pack — Easily install common libraries, additional components, and configs.

See the 👉 [feature details and changelog](https://github.com/usphantomlancer/nextjs-tailwind-typescript-template/blob/main/CHANGELOG.md) 👈 for more.

## Getting Started

### 1. Clone this template using one of the three ways

1. Use this repository as template

   **Disclosure:** by using this repository as a template, there will be an attribution on your repository.

   I'll appreciate if you do, so this template can be known by others too 😄

   ![Use as template](https://user-images.githubusercontent.com/55318172/129183039-1a61e68d-dd90-4548-9489-7b3ccbb35810.png)

2. Using `create-next-app`

   ```bash
   npx create-next-app -e https://github.com/usphantomlancer/nextjs-tailwind-typescript-template project-name
   ```

   If you still want to use **pages directory** (_is not actively maintained_) you can use this command

   ```bash
   npx create-next-app -e https://github.com/usphantomlancer/nextjs-tailwind-typescript-template/tree/pages-directory project-name
   ```

3. Using `degit`

   ```bash
   npx degit usphantomlancer/nextjs-tailwind-typescript-template YOUR_APP_NAME
   ```

### 2. Install dependencies

It is encouraged to use **yarn** so the husky hooks can work properly.

```bash
yarn install
```

### 3. Run the development server

You can start the server using this command:

```bash
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result. You can start editing the page by modifying `src/pages/index.tsx`.

### 4. Change defaults

There are some things you need to change including title, urls, favicons, etc.

Find all comments with !STARTERCONF, then follow the guide.

Don't forget to change the package name in package.json

### 5. Commit Message Convention

This starter is using [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/), it is mandatory to use it to commit changes.
