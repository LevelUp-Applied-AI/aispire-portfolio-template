# AI.SPIRE Portfolio Site Template

A starter template for your professional portfolio site, built with GitHub Pages and Jekyll (Cayman theme). This site will grow throughout the AI.SPIRE program as you add projects from each module.

---

## Quick Start

1. **Click "Use this template"** (green button, top right) then **"Create a new repository"**
2. **Name your repo** one of:
   - `your-github-username.github.io` — this enables GitHub Pages automatically at `https://your-username.github.io/`
   - `portfolio` — you will need to enable Pages manually (see step 4)
3. **Set visibility to Public** (required for GitHub Pages free tier)
4. **Enable GitHub Pages** (skip this step if you used the `.github.io` naming):
   - Go to your repo Settings tab then Pages
   - Under "Source," select **Deploy from a branch**
   - Set Branch to **main**, folder to **/ (root)**
   - Click **Save**
5. **Wait 1-2 minutes**, then visit your site:
   - If you named it `your-username.github.io`: visit `https://your-username.github.io/`
   - If you named it `portfolio`: visit `https://your-username.github.io/portfolio/`

---

## Customizing Your Site

1. **Edit `_config.yml`:** Change `title` to your name and `description` to your tagline
2. **Edit `index.md`:** Replace the placeholder name, write your About section, and fill in your project entries
3. **Commit and push** — your site updates automatically in 1-2 minutes

---

## Adding Projects

After each module, add your new project to the appropriate phase section in `index.md`. Each entry should include a descriptive title, one sentence about what you built, a link to your GitHub repo, and 2-3 skill tags.

For advanced projects (RAG systems, deployed APIs, capstone), you can create a dedicated detail page in the `projects/` folder. See `projects/sample-project.md` for the template.

---

## File Structure

```
your-portfolio/
├── _config.yml                  ← Site title, description, and theme
├── _layouts/
│   └── default.html             ← Page layout (customized from Cayman theme)
├── index.md                     ← Your portfolio content — edit this
├── projects/
│   └── sample-project.md        ← Template for project detail pages (optional)
├── .gitignore                   ← Keeps build artifacts out of your repo
├── LICENSE                      ← Educational use license
└── README.md                    ← This file (not displayed on the site)
```

---

## License

This repository is provided for educational use only. See [LICENSE](LICENSE) for terms.

You may clone and modify this repository for personal learning and practice, and reference code you wrote here in your professional portfolio. Redistribution outside this course is not permitted.
