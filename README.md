<h1 align="center">Nuxt 4 Starter</h1>

<p align="center">Minimal Nuxt application with Vue, TypeScript and a clean default structure.</p>

<p align="center">
  <a href="https://github.com/diogopaulino/nuxt3/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/diogopaulino/nuxt3/actions/workflows/ci.yml/badge.svg?branch=main"></a>
  <img alt="Node.js 22+" src="https://img.shields.io/badge/Node.js-22%2B-339933?logo=node.js&logoColor=white">
  <img alt="Nuxt 4" src="https://img.shields.io/badge/Nuxt-4-00DC82?logo=nuxt&logoColor=white">
</p>

## Overview

A deliberately small Nuxt 4 starter that stays close to framework conventions.

## Structure

```text
app/
└── app.vue

nuxt.config.ts
tsconfig.json
```

## Run

```bash
npm ci
npm run dev
```

Open **http://localhost:3000**.

## Quality

```bash
npm run check
```

This runs Nuxt type checking and a production build.

## Commands

| Command | Purpose |
|---|---|
| `npm run dev` | Development server |
| `npm run check` | Typecheck + production build |
| `npm run preview` | Preview the production build |
| `npm run generate` | Static generation |

## Documentation

- [Nuxt](https://nuxt.com/docs/4.x)
- [Vue](https://vuejs.org/)
