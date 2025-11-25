# 🚀 QUICK START: Deploy to Vercel

## Step 1: Extract the ZIP
Unzip `martykoepke-site.zip` to your desired location

## Step 2: Open in Cursor
1. Open Cursor
2. File → Open Folder
3. Select the `martykoepke-site` folder

## Step 3: Deploy to Vercel

### Method A: Vercel CLI (Fastest)
```bash
# Install Vercel CLI (one time only)
npm install -g vercel

# Navigate to project folder
cd martykoepke-site

# Deploy
vercel

# Deploy to production
vercel --prod
```

### Method B: Vercel Dashboard (No CLI needed)
1. Go to https://vercel.com
2. Sign in with GitHub/GitLab/Bitbucket
3. Click "Add New Project"
4. Import the folder (or push to GitHub first)
5. Click "Deploy"

## Step 4: Add Custom Domain
1. In Vercel dashboard, go to Project Settings → Domains
2. Add `martykoepke.com`
3. Add DNS records to your domain registrar:
   - **A Record**: `@` → `76.76.21.21`
   - **CNAME**: `www` → `cname.vercel-dns.com`

## Done! 🎉
Your site will be live at:
- Vercel URL: `your-project.vercel.app`
- Custom domain: `martykoepke.com` (after DNS propagation)

---

## Need to Update Content?
Edit `index.html` in Cursor, then run `vercel --prod` to redeploy.

## Need Help?
- Vercel Docs: https://vercel.com/docs
- DNS Help: Check your domain registrar's documentation
