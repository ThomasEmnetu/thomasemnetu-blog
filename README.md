# Gradient.

A personal blog exploring the intersection of design and AI.

**Live site:** [thegradient.ink](https://thegradient.ink)

## About

Gradient. is where I write about the evolving relationship between humans, technology, and how we interact. Topics include multi-agent systems, design thinking, AI ethics, and the future of software development.

## Tech Stack

- **Static Site Generator:** [Hugo](https://gohugo.io/)
- **Theme:** [PaperMod](https://github.com/adityatelange/hugo-PaperMod)
- **Hosting:** GitHub Pages
- **Domain:** thegradient.ink

## Local Development

```bash
# Clone with submodules (theme)
git clone --recurse-submodules https://github.com/ThomasEmnetu/thegradient-blog.git

# Navigate to project
cd thegradient-blog

# Run local server
hugo server -D
```

Site will be available at `http://localhost:1313`

## Deployment

Pushes to `main` trigger automatic deployment via GitHub Actions:
1. Hugo builds the site
2. Built files deploy to `gh-pages` branch
3. GitHub Pages serves from `gh-pages`

## Project Structure

```
├── content/posts/     # Blog posts (Markdown)
├── static/images/     # Images and assets
├── assets/css/        # Custom CSS overrides
├── themes/PaperMod/   # Theme (git submodule)
├── hugo.yaml          # Site configuration
└── .github/workflows/ # CI/CD pipeline
```

## Author

**Thomas Emnetu**  
[Twitter](https://x.com/Thomasemn) · [LinkedIn](https://linkedin.com/in/thomasemnetu)

---

*Design thinker. AI tinkerer.*
