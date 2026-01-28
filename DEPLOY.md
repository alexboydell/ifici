# IFICI Eligibility Assessor - Vercel Deployment

## Quick Deployment Steps:

### Option 1: Vercel Dashboard (Easiest)

1. **Download this folder** - You'll need both `index.html` and `vercel.json`

2. **Go to Vercel:**
   - Visit: https://vercel.com/signup
   - Sign up with GitHub (recommended) or email

3. **Deploy:**
   - Click "Add New..." → "Project"
   - Choose "Import Git Repository" OR
   - Drag the entire folder into the upload area
   - Vercel will automatically detect it's a static site

4. **Configure (Optional):**
   - Project Name: `ifici-assessor` (or your choice)
   - Root Directory: `./` (leave default)
   - Framework Preset: Other (or leave as detected)

5. **Deploy!**
   - Click "Deploy"
   - Wait ~30 seconds
   - Get your URL: `https://ifici-assessor.vercel.app` (or similar)

### Option 2: Using Vercel CLI (For Developers)

```bash
# Install Vercel CLI
npm install -g vercel

# Navigate to this folder
cd vercel-deploy

# Deploy
vercel

# Follow prompts:
# - Login with your account
# - Set up and deploy: Y
# - Link to existing project? N
# - Project name: ifici-assessor
# - Directory: ./ (current)
# - Auto-detected settings? Y

# Your site will be live!
```

### Option 3: GitHub + Vercel (Most Professional)

1. **Create GitHub repository:**
   - Go to github.com
   - Create new repository: `ifici-assessor`
   - Upload these files

2. **Connect to Vercel:**
   - Go to vercel.com/new
   - Import your GitHub repository
   - Vercel auto-deploys on every commit!

---

## After Deployment:

Your URL will be: `https://your-project-name.vercel.app`

To customize:
1. Go to your project in Vercel dashboard
2. Settings → Domains
3. Add custom domain (optional)

---

## Files Included:

- `index.html` - The complete IFICI assessment tool
- `vercel.json` - Vercel configuration (ensures proper routing)
- `DEPLOY.md` - This file

---

## Need Help?

- Vercel Docs: https://vercel.com/docs
- Support: https://vercel.com/support

Happy deploying! 🚀
