# 💧 Lifeline Packaged Drinking Water — Website

A complete, single-file website for Lifeline Packaged Drinking Water with customer ordering, UPI payment, screenshot upload, and admin order management.

## Files
- `index.html` — The entire website (one file, no build step needed)

## How to Host on GitHub Pages (Free)

### Step 1 — Create a GitHub Account
Go to [github.com](https://github.com) and sign up for a free account if you don't have one.

### Step 2 — Create a New Repository
1. Click the **+** button (top right) → **New repository**
2. Name it: `lifeline-water` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 3 — Upload the File
1. On your new repository page, click **uploading an existing file**
2. Drag and drop `index.html` into the upload area
3. Scroll down and click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repository → **Settings** tab
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: **main** and folder: **/ (root)**
5. Click **Save**

### Step 5 — Access Your Website
After 1–2 minutes, your site will be live at:
```
https://YOUR-USERNAME.github.io/lifeline-water/
```

That's it! Share this link with your customers.

---

## Login Credentials

| Role | Email | Password |
|------|-------|----------|
| Admin | admin@lifeline.com | admin123 |
| Demo Customer | raj@example.com | raj123 |

**Change these immediately** — see "Customising" below.

## Customising Before Launch

Open `index.html` in any text editor (Notepad, VS Code, etc.) and change:

1. **UPI ID** — search for `lifeline.water@paytm` and replace with your actual UPI ID
2. **Phone number** — search for `+91 98765 43210` and replace
3. **Email** — search for `lifeline.water@gmail.com` and replace
4. **Admin password** — search for `admin123` and replace with something strong
5. **FSSAI licence number** — search for `12315004000753` and replace with yours

## Features
- Public browsing without login
- Customer registration with auto Client ID (C-001, C-002…)
- Product ordering with +/- quantity selector
- UPI QR code payment screen
- Payment screenshot upload
- 6-step delivery tracking (Order Placed → Delivered)
- Admin: verify payments, set delivery time, manage orders
- Admin: full client list with order history
- PDF invoice download (auto-generated, no server needed)
- All data saved in browser localStorage
