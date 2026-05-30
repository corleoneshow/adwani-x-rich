# Update from Richie — GitHub Setup Complete

**Date:** May 30, 2026

Hey Jon — got the whole GitHub org set up properly. Here's everything that was installed and what it does for us.

---

## Apps Installed on adwani-tech org

### 1. Renovate
**What it does:** Automatically opens PRs whenever any of our dependencies are outdated or have security vulnerabilities. Zero manual work — it just runs in the background and keeps packages up to date.

### 2. GitGuardian
**What it does:** Scans every commit and PR for accidentally leaked API keys, tokens, or credentials. If anyone pushes an OpenAI key, Claude key, Google credential — anything — it catches it immediately and alerts us. Both repos are already being monitored.

### 3. Render (GitHub App)
**What it does:** Connects our GitHub repos directly to Render so we can set up auto-deploy on push to main. When the Location Agent is ready to ship, we just connect the repo and every push auto-deploys. Both `adwani-tech` and `location-agent` repos are already visible in Render.

### 4. Linear
**What it does:** Syncs GitHub issues and PRs with Linear project management. When a PR gets merged, linked issues auto-close. Good for when we start tracking A Tech product work more formally.

### 5. CodeRabbit
**What it does:** AI code reviewer — automatically reviews every PR we open, leaves line-by-line comments, catches bugs, and summarizes what changed. 14-day free trial running now (ends Jun 12), then $30/month for 1 seat. We should evaluate it before the trial ends.

---

## Security
- **GitHub 2FA** is now enabled on Richie's account (authenticator app). GitHub requires this by Jul 8, 2026 — make sure you enable it on your account too at github.com/settings/security.

---

## What You Need To Do
1. **Enable 2FA on your GitHub account** — go to github.com/settings/security before July 8, 2026
2. **Evaluate CodeRabbit** before Jun 12 — check if the reviews are useful on your PRs, then we decide if $30/month is worth it

That's it. Everything else is live and running automatically.

— Richie
