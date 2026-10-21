# SSIS-PORTAL - Web Deployment

This repository connects the San Simon Integrated School (SSIS) Portal to a clean, custom URL hosted for free on **Vercel** via GitHub.

---

## 🚀 Quick Setup (3 Minutes)

### Step 1: Upload to GitHub
1. Create a new GitHub repository (e.g., `ssis-portal`).
2. Upload the contents of this folder (`index.html`, `vercel.json`, `README.md`, etc.) to your repository.

### Step 2: Deploy to Vercel
1. Go to [vercel.com](https://vercel.com) and log in with your GitHub account.
2. Click **"Add New..."** > **"Project"**.
3. Import your `ssis-portal` repository.
4. Keep the default settings and click **Deploy**.

### Step 3: Change / Customize Your URL
1. Once deployed, Vercel gives you an immediate URL like:
   `https://ssis-portal.vercel.app`
2. To customize the name:
   - Go to **Project Settings** > **Domains**.
   - Edit the domain to whatever name you want (e.g., `ssis-portal-aringay.vercel.app`).
   - You can also attach an official school domain (e.g., `portal.sansimonis.edu.ph`) if you have one.

---

## 🔒 Security & Data Integrity
- **Zero Breakage**: Google Sheets backend connections, live weather, PIN verification, and staff directory continue to function through Google Apps Script.
- The root `index.html` loads the portal in a full-screen, responsive frame seamlessly under your custom Vercel address.
- Original Google Apps Script files are backed up in the `/gas` directory.
