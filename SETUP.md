# Quick Setup Guide

## Files You Have

- **index.html** - Your entire portfolio website (all-in-one file)
- **README.md** - Project information
- **.gitignore** - Git configuration
- **SETUP.md** - This file

## Step-by-Step Instructions

### Step 1: Create GitHub Account & Repository

1. Go to [github.com](https://github.com)
2. Click **Sign up**
3. Create account with your email
4. Click **Create repository** (or the + icon → New repository)
5. Name it: `username.github.io` (use your actual GitHub username)
   - Example: if your username is "alex", name it `alex.github.io`
6. Click **Create repository**

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop `index.html`, `README.md`, and `.gitignore` into the upload area
3. Click **Commit changes**
4. Wait 30 seconds...
5. Your site is now live at `https://username.github.io`

**Option B: Using Git Command Line (Advanced)**

```bash
# Clone your repository
git clone https://github.com/username/username.github.io.git
cd username.github.io

# Copy files into folder
# (Copy index.html, README.md, .gitignore here)

# Push to GitHub
git add .
git commit -m "Add game design portfolio"
git push origin main
```

### Step 3: Connect Your Custom Domain

1. Go to your GitHub repo → Settings → Pages
2. Under "Custom domain", enter your domain (e.g., `myportfolio.com`)
3. Click **Save**
4. You'll see instructions for DNS configuration
5. Log into your domain registrar (GoDaddy, Namecheap, etc.)
6. Update DNS records to point to GitHub Pages:
   - Add CNAME record pointing to `username.github.io`
   - Or add A records (GitHub will provide exact values)
7. Wait 5-30 minutes for DNS to update
8. Your site will be at `https://myportfolio.com`

## Customizing Your Portfolio

Edit `index.html` with any text editor:

- **Line 112**: Update your name/title
- **Line 118-120**: Update hero subtitle
- **Line 167-174**: Update project descriptions
- **Line 311**: Update email link (change `your-email@example.com`)

Save and push changes to GitHub - your site updates automatically!

## Need Help?

- GitHub Pages docs: https://docs.github.com/en/pages
- Domain setup: Contact your domain registrar's support

---

That's it! You now have a professional game design portfolio! 🎮
