# SimplyDebug — A Hugo-Powered Tech Blog

> *Debugging Made Simple, Success Made Sure.*

A fast, SEO-optimized static tech blog built with Hugo and deployed on Cloudflare Pages. Covering topics in development, AI, and practical tech problem-solving.

🌐 **Live Site:** [blog.simplydebug.com](https://blog.simplydebug.com)

---

## PageSpeed Insights — Mobile Scores

<img width="1342" height="461" alt="image" src="https://github.com/user-attachments/assets/2f36984a-b3bd-4f78-a9ba-be52f57c8f93" />


> Scored on mobile via [Google PageSpeed Insights](https://pagespeed.web.dev/) — March 2025.

---

## Screenshot

<img width="1350" height="646" alt="image" src="https://github.com/user-attachments/assets/08474ce5-a06e-48a6-95e7-0965dfde7259" />



---

## Why Static?

In a landscape where most developers default to dynamic frameworks, I made a deliberate architectural decision to go static. The goal was simple: the fastest possible load times, maximum SEO efficiency, and near-zero infrastructure overhead.

Hugo is one of the fastest static site generators in the world — and pairing it with Cloudflare Pages means every page is served from a global CDN edge network with no server-side rendering bottlenecks. The result: a perfect 100 performance score on mobile.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Hugo | Static site generator |
| HTML / TOML | Templating and configuration |
| Niello Theme | Base theme, customized |
| Cloudflare Pages | Deployment and CDN hosting |
| Custom Domain | blog.simplydebug.com |

---

## Features

- ⚡ Perfect 100/100 Google PageSpeed score on Performance, Best Practices & SEO
- 🌍 Deployed globally via Cloudflare CDN for minimal latency
- 🔍 SEO-optimized structure with proper meta tags, categories, and tagging system
- 📱 Fully responsive design
- 🗂️ Organized by categories and tags for discoverability
- 🔎 Built-in search functionality

---

## Topics Covered

- Artificial Intelligence & Education
- Development tutorials (no-code and code)
- Practical tech troubleshooting
- AI tools and productivity

---

## What I Learned

- Hugo static site architecture and templating
- SEO fundamentals — meta structure, tagging, discoverability
- Cloudflare Pages deployment pipeline and continuous deployment from GitHub
- Performance optimization for static sites
- Managing a custom domain with DNS configuration
- The real-world trade-offs between static and dynamic web architectures

---

## Local Development

```bash
# Clone the repo
git clone https://github.com/reubenjoji/hugo-blog.git

# Navigate into the project
cd hugo-blog

# Start the local Hugo server
hugo server -D
```

> Requires [Hugo](https://gohugo.io/installation/) to be installed.

---

## Deployment

This site is deployed via **Cloudflare Pages** with automatic continuous deployment. Every push to the `main` branch triggers a new build and deploys globally within seconds.
