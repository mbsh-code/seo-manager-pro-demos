# 🌐 SEO Manager Pro – Demo Collection

This repository contains working demos for [`seo-manager-pro`](https://www.npmjs.com/package/seo-manager-pro), a lightweight JavaScript SEO utility for dynamically managing meta tags, titles, canonical URLs, and structured data.

---

## 📦 What is `seo-manager-pro`?

A tiny, framework-agnostic library that updates SEO-related data on the fly.  
Supports:

- Title & meta tags
- Open Graph & custom meta
- Canonical links
- JSON-LD structured data (Product, Article, FAQPage)
- Robots rules

---

## 🚀 Available Demos

| Demo Type     | Framework      | Preview / Usage |
|---------------|----------------|------------------|
| Angular       | Angular 15+     | [`angular-demo/`](./angular-demo) |
| React         | React 18 + React Router | [`react-demo/`](./react-demo) |
| JavaScript    | Vanilla JS + HTML | [`js-demo/`](./js-demo) |

Each folder contains a minimal project showing how to integrate and use the package effectively.

---

## 📂 Folder Structure

```
seo-manager-pro-demos/
├── angular-demo/    → Angular SPA with dynamic SEO
├── react-demo/      → React app with routing and SEO
├── js-demo/         → Pure HTML + JS usage
└── README.md        → You're here!
```

---

## ✨ Get Started

Install the package via npm:

```bash
npm install seo-manager-pro
```

Use in your project:

```ts
import { SeoManagerPro } from 'seo-manager-pro';

SeoManagerPro.updateSeo({
  title: 'My Page Title',
  description: 'My awesome description.',
  canonicalUrl: 'https://example.com/page',
  schema: [
    {
      type: 'Article',
      data: {
        headline: 'My Article',
        author: 'Me'
      }
    }
  ]
});
```

---

## 📬 Feedback / Contribute

Got an idea or found an issue?  
Open a GitHub issue or start a discussion — contributions welcome!

---

**Author**: [MohammadBagher Sharifi / GitHub](https://github.com/mbsh-code)  
**NPM Package**: [`seo-manager-pro`](https://www.npmjs.com/package/seo-manager-pro)
