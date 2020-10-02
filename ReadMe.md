# React injectable ts boilerplate

Purpose of this repo is to have a boilerplate for creating React app in typescript,
which can be injected into any `html` via `<script>` tag and modifying element id in `index.tsx`.

# Why?
Imagine website, not able to be fully made in React or you have an existing site, cms, etc. where you just need to add a simple reactive form.

Create multiple microfrontends on static website, which can't be one SPA.

# Usage

- Create react apps as you are used to (in typescript, tho)
- After building just inject the script into the `html` - Example html is `public/index.html`
- Build:
  - `yarn webpack-prod` for minified production build
  - `yarn webpack-dev` for development build
  - `yarn webpack-errors` display details about errors
