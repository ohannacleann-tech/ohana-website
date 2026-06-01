# OHANA Clean Solutions — Website

Premium residential cleaning website for Silicon Valley & Bay Area.  
Version: **v12** | Stack: Static HTML/CSS/JS · Leaflet.js · WhatsApp Booking

---

## File Structure

```
/
├── index.html              ← Rename ohana-v12.html to this before deploy
├── vercel.json             ← Vercel deployment config
├── README.md               ← This file
├── 1000344482.jpg          ← OHANA logo
├── 1000345724.jpg          ← Hero background (real client home)
├── 1000342922.jpg          ← Bathroom after
├── 1000342926.jpg          ← Bathroom before
├── 1000344494.jpg          ← Window before
├── 1000344496.jpg          ← Window after
├── 1000344498.jpg          ← Stove after
├── 1000344500.jpg          ← Stove before
├── 1000344502.jpg          ← Bedroom after
├── 1000344509.jpg          ← Bedroom before
```

---

## Deploy to Vercel

### Step 1 — Rename main file
Rename ohana-v12.html to index.html

### Step 2 — Create GitHub repository
1. Go to github.com/new
2. Name: ohana-clean-solutions
3. Private repository
4. Create repository

### Step 3 — Push files to GitHub
```bash
git init
git add .
git commit -m "OHANA v12 production"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ohana-clean-solutions.git
git push -u origin main
```

### Step 4 — Connect to Vercel
1. Go to vercel.com → Add New Project
2. Import ohana-clean-solutions repo
3. Framework Preset: Other
4. Root directory: /
5. Deploy

### Step 5 — Custom Domain
In Vercel > Project Settings > Domains:
- Add ohanacleansolutions.com
- Add www.ohanacleansolutions.com
- Follow DNS instructions

---

## Stripe Deposit — Current Flow

The booking flow works as follows:
1. Client completes the 5-step quote calculator
2. Reserve My Spot opens WhatsApp with full quote summary
3. OHANA confirms appointment via WhatsApp
4. OHANA sends a Stripe payment link for $50 deposit via WhatsApp

To create your Stripe deposit link:
- Go to stripe.com/payment-links
- Create a product called "OHANA Cleaning Reservation Deposit" at $50
- Copy the link
- Paste it into WhatsApp messages manually until automation is set up

---

## Version History

v10 — Original site
v11 — P1 fixes: WhatsApp handoff, image 404s, coverage div bug, mobile padding
v12 — Full audit: real hero photo, hero metrics, Stripe flow clarification, SEO meta, JSON-LD schema, lazy loading, mobile tap targets, safe-area-inset, duplicate review data cleanup
