# 🎭 Odd One Out - Landing Page

This is the landing page for the Odd One Out multiplayer party game.

## 📁 Files

- `index.html` - Main landing page with game description
- `privacy-policy.html` - Privacy Policy
- `terms-of-service.html` - Terms of Service

## 🚀 Setup Instructions

### Step 1: Create GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create account)
2. Click the **+** button → **New repository**
3. Name it: `oddoneout` (or any name you like)
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Files

1. Click **uploading an existing file**
2. Drag and drop all 3 HTML files
3. Click **Commit changes**

### Step 3: Enable GitHub Pages

1. Go to **Settings** tab
2. Click **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Under "Branch", select **main** and **/ (root)**
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 4: Get Your URLs

Your site will be available at:
- **Homepage:** `https://YOUR_USERNAME.github.io/oddoneout/`
- **Privacy Policy:** `https://YOUR_USERNAME.github.io/oddoneout/privacy-policy.html`
- **Terms:** `https://YOUR_USERNAME.github.io/oddoneout/terms-of-service.html`

### Step 5: Verify Domain in Google Search Console

1. Go to [Google Search Console](https://search.google.com/search-console)
2. Click **Add property**
3. Choose **URL prefix**
4. Enter: `https://YOUR_USERNAME.github.io/oddoneout/`
5. Choose **HTML file** verification method
6. Download the verification file (e.g., `google1234567890abcdef.html`)
7. Upload it to your GitHub repository
8. Click **Verify** in Search Console

### Step 6: Update OAuth Consent Screen

1. Go to [Google Cloud Console](https://console.cloud.google.com)
2. Navigate to **APIs & Services** → **OAuth consent screen**
3. Update:
   - **Homepage:** `https://YOUR_USERNAME.github.io/oddoneout/`
   - **Privacy Policy:** `https://YOUR_USERNAME.github.io/oddoneout/privacy-policy.html`
   - **Terms of Service:** `https://YOUR_USERNAME.github.io/oddoneout/terms-of-service.html`
4. Save and submit for verification

## ⚠️ Important

Remember to update the "Play Now" button link in `index.html` with your actual Google Apps Script URL!

Look for this line and replace with your URL:
```html
<a href="https://script.google.com/a/macros/umindanao.edu.ph/s/YOUR_SCRIPT_ID/exec" class="play-btn">
```

## 📧 Contact

Developer: Don Inciso
Email: e.inciso.471453@umindanao.edu.ph
