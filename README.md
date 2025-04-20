# 📚 TrendFurnace Blog (Jekyll + GitHub Pages)

This is your fully automated, real-content publishing blog using Jekyll and GitHub Pages.

## ✅ How It Works

- All blog posts are stored in `_posts/` as `.md` files
- Each post is auto-rendered into its own page using the `_layouts/post.html` template
- GitHub Pages hosts the blog for free using Jekyll

---

## 🛠 Setup Instructions

### 1. Clone this Repo

```bash
git clone https://github.com/YOUR-USERNAME/trendfurnace-blog.git
cd trendfurnace-blog
```

### 2. Add a Blog Post

- Save your Markdown file as `_posts/YYYY-MM-DD-title-of-post.md`
- Example:

```markdown
---
title: 'NBA Playoffs 2025'
date: 2025-04-21
---

The NBA Playoffs are heating up...
```

### 3. Push Your Content

```bash
git add .
git commit -m "Add blog post"
git push
```

### 4. Enable GitHub Pages

- Go to the repo → Settings → Pages
- Source: `main` branch
- Folder: `/ (root)`
- Save → Your blog will be live at:

```
https://your-username.github.io/trendfurnace-blog/
```

---

## 💡 Notes

- Your homepage is `index.md`
- Blog layout lives in `_layouts/post.html`
- Site config is in `_config.yml`
- `.nojekyll` prevents GitHub from blocking Jekyll processing

---

Built for speed, simplicity, and monetization 🔥
