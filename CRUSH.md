# mtremsal.github.io Development Guide

This document provides instructions for developing and maintaining this website.

## Stack

- **Framework**: [Astro](https://astro.build/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Deployment**: GitHub Pages

## Development

- **Run development server**: `npm run dev`
- **Build for production**: `npm run build`
- **Preview production build**: `npm run preview`

## Content

- **Pages**: New pages can be added as `.md` or `.astro` files in the `src/pages` directory.
- **Blog Posts**: Create new blog posts by adding `.md` files to the `src/content/work` directory.
- **Links**: The main page links are in `src/pages/index.astro`.

## Deployment

Changes pushed to the `main` branch are automatically deployed to GitHub Pages using the `.github/workflows/deploy.yml` workflow.

## Pre-commit Checklist

Before committing any changes, please run a local build to ensure everything is working correctly:

`npm run build`

If the build fails, please fix the issues before committing.

