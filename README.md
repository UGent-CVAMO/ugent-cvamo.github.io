# CVAMO Website

Website for the research group **Cost and Value Analytics, Models & Optimization (CVAMO)**  
Ghent University – Faculty of Economics and Business Administration.

Live site: https://cvamo.ugent.be redirects to https://ugent-cvamo.github.io/

## Overview

This repository contains the source code of the CVAMO website, built with [Astro](https://astro.build) and deployed via GitHub Pages.

The site provides information on:
- Research activities and publications
- Team members
- Industry collaboration
- Contact information

## Development

Install dependencies:

```sh
npm install
```

## Start local development server:

```sh
npm run dev
```

## Build the site:

```sh
npm run build
```

## Preview production build:

```sh
npm run preview
```

## Deployment

The website is automatically deployed to GitHub Pages via GitHub Actions on every push to the main branch.

## Structure

```
src/
├── layouts/      # Page layouts
├── pages/        # Route-based pages
├── components/   # Reusable components
public/           # Static assets (images, logos, etc.)
```

## Notes

The site follows a UGent-inspired layout and styling.

Designed to be lightweight, maintainable, and responsive.

Content is intentionally kept simple (no CMS).

## License

Internal use – CVAMO / Ghent University
