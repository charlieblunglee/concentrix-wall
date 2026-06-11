# 🏆 Concentrix Wall of Achievers

A static website for the Concentrix Wall of Achievers recognition platform. Built for GitHub Pages hosting.

## 🔐 Admin Login

- **Username:** `admin`
- **Password:** `cnx2025!`

> Change your password in Admin → Settings after first login.

## 🚀 Deploy to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) → **New repository**
2. Name it: `concentrix-wall` (or any name)
3. Set to **Public**
4. Click **Create repository**

### Step 2: Upload Files
**Option A — GitHub Web Upload:**
1. In your new repo, click **Add file → Upload files**
2. Drag the entire `concentrix-wall` folder contents
3. Commit changes

**Option B — Git CLI:**
```bash
cd concentrix-wall
git init
git add .
git commit -m "Initial deploy: Concentrix Wall of Achievers"
git remote add origin https://github.com/YOUR_USERNAME/concentrix-wall.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` → Folder: `/ (root)`
4. Click **Save**
5. Your site will be live at: `https://YOUR_USERNAME.github.io/concentrix-wall/`

## 📁 File Structure

```
concentrix-wall/
├── index.html              ← Main homepage
├── css/
│   └── style.css           ← All styles
├── pages/
│   ├── larah.html          ← Larah Sta. Maria profile
│   ├── emil.html           ← Emil Uy profile
│   └── jc.html             ← JC Boquiren profile
├── admin/
│   ├── login.html          ← Admin login
│   └── dashboard.html      ← Admin CMS
├── assets/                 ← Image data (internal)
└── README.md
```

## ✨ Features

- **Homepage** with hero, articles, and achievers wall
- **Individual profile pages** with QR codes, achievements, personal messages
- **Admin CMS** — write articles, create achiever pages, download HTML
- **QR Code generation** for each achiever profile
- **Responsive** — works on mobile and desktop
- **Session-based auth** — login protected admin panel

## 🎨 Design

- **Color palette:** Concentrix teal (#00c2b2) on dark (#0a0a0f)
- **Typography:** Rajdhani (display) + Inter (body)
- **Style:** Executive, techie, modern

