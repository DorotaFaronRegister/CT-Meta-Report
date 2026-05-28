# Meta Ads Performance Report

A self-contained, client-side Meta Ads performance dashboard hosted on GitHub Pages.

## Setup (5 minutes)

### 1. Create a GitHub repository
- Go to [github.com](https://github.com) and sign in
- Click **New repository**
- Name it `meta-report` (or anything you like)
- Set it to **Private** (recommended — your token will be in the bookmark URL)
- Click **Create repository**

### 2. Upload the files
- Click **Add file → Upload files**
- Drag in `index.html` and `README.md`
- Click **Commit changes**

### 3. Enable GitHub Pages
- Go to **Settings → Pages**
- Under **Source**, select **Deploy from a branch**
- Choose **main** branch, **/ (root)** folder
- Click **Save**
- Wait ~60 seconds, then your site will be live at:
  `https://YOUR-USERNAME.github.io/meta-report/`

### 4. Bookmark your report URL
Add your token as a URL parameter:
```
https://YOUR-USERNAME.github.io/meta-report/?token=YOUR_SYSTEM_USER_TOKEN
```

Bookmark this URL. Every time you open it, the report auto-fetches the latest 30 days of data.

## Usage
- **Open the bookmark** → data loads automatically
- **Adjust date range** using the From/To pickers in the sidebar
- **Filter** by campaign, creative, format, copy, landing page, product, batch, or creator type
- **Switch tabs** to view performance by day, week, campaign, creative, copy, landing page, product, creative batch, or creator vs BAU
- **Click thumbnails** in the creative tab to preview images or play videos

## Security note
Your access token is stored only in your browser bookmark — it is never sent anywhere except directly to `graph.facebook.com`. GitHub Pages serves only static files and has no server-side access to your token.

For extra security, keep the repository **Private** so the `index.html` source is not publicly visible.
