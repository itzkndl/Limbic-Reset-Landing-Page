# Limbic Reset — GitHub Pages

Marketing site for [Limbic Reset](https://limbicreset.netlify.app).

## Before you deploy — update these 3 things in index.html:

**1. Your Netlify URL** (search `limbicreset.netlify.app`, replace with your real URL)

**2. Gumroad product links** (after creating products on gumroad.com):
- `YOUR_MONTHLY_ID` → your $5/month membership link
- `YOUR_QUARTERLY_ID` → your $15/quarter membership link
- `YOUR_6MONTH_ID` → your $25/6-month membership link
- `YOUR_ANNUAL_ID` → your $45/year membership link

**3. Donation links:**
- `YOUR_KOFI_NAME` → your Ko-fi username
- `YOUR_BMAC_NAME` → your Buy Me a Coffee username

## Enable GitHub Pages
Settings → Pages → Deploy from branch → main → / (root) → Save

## Enable Giscus comments
1. Make this repo Public
2. Settings → Features → enable Discussions
3. Go to giscus.app, fill in your repo, copy the script
4. Paste the script in index.html where it says "PASTE YOUR GISCUS SCRIPT HERE"
