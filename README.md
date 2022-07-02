# Create Chrome Extension (.crx)

[![npm](https://img.shields.io/npm/v/create-chrome-ext?logo=npm)](https://www.npmjs.com/package/create-chrome-ext)
[![npm-download](https://img.shields.io/npm/dw/create-chrome-ext)](https://www.npmjs.com/package/create-chrome-ext)
![GitHub Language Count](https://img.shields.io/github/languages/count/guocaoyi/create-chrome-ext)
[![npm publish](https://github.com/guocaoyi/create-chrome-ext/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/guocaoyi/create-chrome-ext/actions/workflows/npm-publish.yml)

> Next generation chrome extension generater

- ⚡️ Lightning Fast HMR(use vite2)
- 🗂 Multiple Framework Support
- 📦 Optimized Builds
- 📚 Documentation

## Installing

> Node >= 14.18.0

```bash
# with npm
λ npm create chrome-ext@latest

# or with pnpm
λ pnpm create chrome-ext

# or with yarn
λ yarn create chrome-ext

# or with npx
λ npx create-chrome-ext
```

## Usage

You can also directly specify the project name and the template you want to use via additional command line options. For example, to scaffold a Vite + Svelte project, run:

```bash
# npm 6.x
λ npm create chrome-ext@latest my-crx-app --template svelte-js

# or npm 7+, extra double-dash is needed:
λ npm create chrome-ext@latest my-crx-app -- --template react-ts

# or yarn
λ yarn create chrome-ext my-crx-app --template vue-ts

# or pnpm
λ pnpm create chrome-ext my-crx-app --template vanilla-ts
```

You can also generator the project with `crx` cli.
run:

```bash
λ npm install create-chrome-ext --global

# and then
λ crx my-crx-app
# or
λ crx my-crx-app --template preact-js
# or use create-chrome-exe (global env)
λ create-chrome-ext my-crx-app
```

## Supported Templates

framework presets include:

- [React](https://reactjs.org/)
- [Vue](https://vuejs.org/)
- [Svelte](https://svelte.dev/)
- [Solid](https://www.solidjs.com/)
- [Preact](https://preactjs.com/)
- [Lit](https://lit.dev/)
- [Vanilla](http://vanilla-js.com/)

languages presets include:

- JavaScript
- TypeScript

## Preview

![crx-run](./docs/crx-run.png)
![crx-install](./docs/crx-install.png)
![crx-build](./docs/crx-build.png)
![crx-preview](./docs/crx-preview.png)
