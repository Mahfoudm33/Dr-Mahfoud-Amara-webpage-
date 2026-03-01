# Dr. Mahfoud Amara — Academic Website

Static HTML/CSS/JS academic website for Dr. Mahfoud Amara, Associate Professor in Sport Management & Social Sciences, Qatar University.

## Deploying to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in (or create an account)
2. Click **"New repository"**
3. Name it: `mamara-website` (or any name you prefer)
4. Set it to **Public**
5. Do NOT check "Add README" (you'll upload files directly)
6. Click **"Create repository"**

### Step 2: Upload the Files
**Option A — Simple drag-and-drop (recommended for beginners):**
1. In the empty repository page, click **"uploading an existing file"**
2. Drag ALL files and folders from this zip into the browser window:
   - `index.html`
   - `publications.html`
   - `world-cup-2022.html`
   - `conferences.html`
   - `research.html`
   - `phd-supervision.html`
   - `media.html`
   - `contact.html`
   - `assets/` folder (with all CSS, JS, and image files)
3. Scroll down, write a commit message like "Initial upload"
4. Click **"Commit changes"**

**Option B — Using GitHub Desktop (easier visual tool):**
1. Download [GitHub Desktop](https://desktop.github.com/)
2. Clone your repository
3. Copy all website files into the cloned folder
4. Commit and push

### Step 3: Enable GitHub Pages
1. In your repository, go to **Settings** → **Pages** (left sidebar)
2. Under "Source", select **"Deploy from a branch"**
3. Branch: **main** | Folder: **/ (root)**
4. Click **Save**
5. Wait 1–2 minutes, then your site will be live at:
   `https://YOUR-USERNAME.github.io/mamara-website/`

### Step 4: Add Your Profile Photo
1. Place your photo file in the `assets/img/` folder
2. Name it: `profile.jpg`
3. Commit and push — the homepage will automatically display it

### Optional: Custom Domain
If you want a custom URL (e.g., `mahfoudamara.com`):
1. Buy a domain from a registrar (Namecheap, Google Domains, etc.)
2. In repository Settings → Pages → Custom domain, enter your domain
3. Follow GitHub's DNS configuration instructions

## File Structure
```
mamara-website/
├── index.html              ← Homepage
├── publications.html       ← Full publications list
├── world-cup-2022.html     ← Qatar 2022 research
├── conferences.html        ← Conference presentations
├── research.html           ← Research projects & funding
├── phd-supervision.html    ← PhD students & examinations
├── media.html              ← Media coverage (EN/FR/AR)
├── contact.html            ← Contact & academic profiles
├── README.md               ← This file
└── assets/
    ├── css/
    │   └── style.css       ← All styling
    ├── js/
    │   └── main.js         ← Navigation, animations
    └── img/
        └── profile.jpg     ← YOUR PHOTO (add this file)
```

## Updating Content
All content is in plain HTML. To update:
- Open the relevant `.html` file in any text editor (Notepad, VS Code, etc.)
- Find the section you want to edit
- Make changes
- Save and upload to GitHub (it re-deploys automatically in ~1 minute)

## Design
- **Colors:** Qatar University Deep Maroon (#6D1D2A) + Gold (#C9A84C) on Warm Ivory
- **Fonts:** Cormorant Garamond (display) + DM Sans (body) from Google Fonts
- **Features:** Responsive mobile layout, scroll animations, back-to-top button, fixed navigation, print-friendly styles
