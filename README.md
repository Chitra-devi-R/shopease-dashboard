# ShopEase - E-Commerce Admin Dashboard

A professional dashboard prototype for an e-commerce application, built using
basic HTML tags and CSS as part of a Full Stack assignment.

## Before You Push: Personalize It
Open `index.html` and replace:
- `Your Name Here` (appears twice — header and footer)
- `Your Register Number Here`
- Optionally change the logo image, contact details, and social links.

## Files
- `index.html` — main dashboard page
- `style.css` — styling

## Step 1: Initialize Git and Push to GitHub

Open a terminal inside this project folder and run:

```bash
git init
git add .
git commit -m "Initial commit: ShopEase dashboard"
```

Now create a new empty repository on GitHub (no README/license, since you already have files):
1. Go to https://github.com/new
2. Name it e.g. `shopease-dashboard`
3. Click **Create repository** (don't initialize with any files)

Then connect and push your local project:

```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/shopease-dashboard.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

## Step 2: Deploy on Vercel

1. Go to https://vercel.com and sign in (you can sign in with your GitHub account).
2. Click **Add New... → Project**.
3. Select the `shopease-dashboard` repository you just pushed.
4. Framework preset: choose **Other** (this is a static HTML site, no build step needed).
5. Click **Deploy**.
6. After a few seconds, Vercel gives you a live URL like:
   `https://shopease-dashboard.vercel.app`

## Step 3: Submit for Evaluation

For your assignment submission, include:
- **GitHub Repository Link:** `https://github.com/YOUR_USERNAME/shopease-dashboard`
- **Vercel Live URL:** `https://shopease-dashboard.vercel.app`

## Notes for Future Edits

Any time you change `index.html` or `style.css`, redeploy by running:

```bash
git add .
git commit -m "Update dashboard content"
git push
```

Vercel automatically redeploys on every push to the `main` branch — no need to
repeat the Vercel setup steps.
