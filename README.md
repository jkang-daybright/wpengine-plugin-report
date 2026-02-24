# WPEngine Plugin Report

A hosted dashboard showing plugin status across all WPEngine sites.

## 🚀 Live Site
After setup, your site will be at:
`https://<your-username>.github.io/<repo-name>/`

## Setup Instructions

### Step 1 — Create a new GitHub repo
1. Go to [github.com/new](https://github.com/new)
2. Name it something like `wpengine-plugin-report`
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload the files
Upload these 3 files to the repo root:
- `index.html`
- `.nojekyll`
- `README.md`

**Option A — Via GitHub UI (easiest):**
1. In your new repo, click **Add file > Upload files**
2. Drag and drop all 3 files
3. Click **Commit changes**

**Option B — Via Git CLI:**
```bash
git clone https://github.com/<your-username>/wpengine-plugin-report.git
cd wpengine-plugin-report
# copy the files here, then:
git add .
git commit -m "Initial plugin report"
git push origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo **Settings**
2. Click **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Set branch to **main** and folder to **/ (root)**
5. Click **Save**

### Step 4 — Visit your site
After 1-2 minutes, go to:
`https://<your-username>.github.io/wpengine-plugin-report/`

## Updating the Report
When you run a new `all-plugins.csv` export, regenerate the HTML and replace `index.html` in the repo. GitHub Pages will redeploy automatically within ~1 minute.
