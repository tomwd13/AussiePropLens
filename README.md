# AussiePropLens 🏡

AI-powered property deal intelligence for Australian investors.

## Files
- `index.html` — Landing page
- `residential.html` — Residential analyser ($20/mo tier)
- `commercial.html` — Commercial analyser ($120/mo tier)
- `institutional.html` — Institutional analyser ($120/mo tier)
- `vercel.json` — Routing config

## Deploy in 10 minutes

### Step 1 — GitHub
1. Go to github.com → sign up free
2. Click "New repository" → name it `aussieproplens` → Public → Create
3. Click "Add file" → "Upload files"
4. Drag all 5 files in → click "Commit changes"

### Step 2 — Vercel
1. Go to vercel.com → sign up with GitHub
2. Click "Add New Project" → select `aussieproplens`
3. Click Deploy — live in 60 seconds
4. Your URL: aussieproplens.vercel.app

### Step 3 — Custom domain (optional)
1. Buy aussieproplens.com.au on namecheap.com (~$20/yr)
2. Vercel dashboard → Settings → Domains → add your domain
3. Follow Vercel's DNS instructions

### Step 4 — Payments
1. Go to stripe.com → create free account
2. Products → Add Product:
   - "AussiePropLens Residential" — $20/month recurring
   - "AussiePropLens Commercial" — $120/month recurring
   - "AussiePropLens Institutional" — $120/month recurring
3. Each generates a Payment Link — paste into the pricing buttons in index.html

## Costs
| Item | Cost |
|------|------|
| Vercel hosting | Free |
| GitHub | Free |
| Domain | ~$20/yr |
| Stripe | 0% until you earn |
| Claude API | ~$0.01 per analysis |

**Total upfront: $20**
