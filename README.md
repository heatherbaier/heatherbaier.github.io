# heatherbaier.github.io

Personal academic website for Heather Baier, Assistant Professor at Arizona State University.

Built with [Academic Pages](https://github.com/academicpages/academicpages.github.io), a GitHub Pages Jekyll theme.

---

## 🚀 How to Deploy

### Step 1: Create your GitHub repository

1. Go to [github.com](https://github.com) and log in as `heatherbaier`
2. Create a **new repository** named exactly: `heatherbaier.github.io`
   - Make it **Public**
   - Do NOT initialize with a README (you already have one)

### Step 2: Upload these files

**Option A – GitHub web interface (easiest):**
1. Open your new repo on GitHub
2. Click "uploading an existing file"
3. Drag and drop ALL files/folders from this folder
4. Commit to `main` branch

**Option B – Git command line:**
```bash
cd heatherbaier.github.io
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/heatherbaier/heatherbaier.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. In your repo, go to **Settings → Pages**
2. Under "Source", select **Deploy from a branch**
3. Choose branch: `main`, folder: `/ (root)`
4. Click Save

Your site will be live at **https://heatherbaier.github.io** within a few minutes!

---

## ✏️ How to Customize

### Add your photo
Replace `images/profile.jpg` with your headshot. Keep the filename the same, or update `avatar` in `_config.yml`.

### Update your bio & links
Edit `_config.yml` — find the `author:` section and fill in:
- `email`
- `twitter`
- `googlescholar`
- `orcid`
- `linkedin`

### Add publications
Edit `_pages/publications.md` directly, following the existing format.

### Add/edit courses
Edit `_pages/teaching.md`.

### Add/edit projects
Edit `_pages/projects.md`.

### Add your CV
Place a PDF named `cv.pdf` in the `files/` folder. The About page already links to it.

---

## 📁 File Structure

```
heatherbaier.github.io/
├── _config.yml          ← Main site settings & author info
├── _data/
│   └── navigation.yml   ← Top navigation bar links
├── _pages/
│   ├── publications.md  ← Publications page
│   ├── teaching.md      ← Teaching page
│   └── projects.md      ← Projects page
├── files/
│   └── cv.pdf           ← Your CV (add this!)
├── images/
│   └── profile.jpg      ← Your headshot (add this!)
├── index.html           ← About/home page
└── Gemfile              ← Ruby dependencies (for local dev)
```

---

## 🖥️ Local Development (optional)

If you want to preview changes locally before pushing:

```bash
# Install Ruby and Bundler first, then:
bundle install
bundle exec jekyll serve
# Open http://localhost:4000
```
