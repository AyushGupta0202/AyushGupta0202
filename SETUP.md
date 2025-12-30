# WEAPONIZED GITHUB PROFILE — SETUP GUIDE

## 🎯 QUICK START

This profile is a **signal weapon**. Follow these steps to activate it.

## 📋 PREREQUISITES

1. GitHub account (`AyushGupta0202`)
2. GitHub Pages enabled (for contribution snake)
3. Basic understanding of GitHub Actions

## 🚀 SETUP STEPS

### 1. Enable GitHub Pages

1. Go to repository Settings → Pages
2. Source: `Deploy from a branch`
3. Branch: `output` (will be created by workflow)
4. Save

### 2. Verify Workflows

The following workflows are included:

- **snake.yml** — Generates contribution graph snake
- **repo-score.yml** — Auto-scores repository quality
- **update-readme.yml** — Updates README metrics

### 3. Customize README

Update these placeholders in `README.md`:

- `YOUR_USERNAME` → `AyushGupta0202` (already done)
- `your@email.com` → Your actual email
- Add Wakatime username (if you use it)
- Add LeetCode username (if you use it)
- Add Codeforces username (if you use it)

### 4. First Run

Workflows will run automatically:
- **snake.yml**: Daily at midnight UTC
- **repo-score.yml**: Daily at 3 AM UTC
- **update-readme.yml**: Daily at 4 AM UTC

Or trigger manually via Actions tab.

## 🔧 CUSTOMIZATION

### Add Wakatime Stats

1. Get your Wakatime API key
2. Update README with your username:
   ```markdown
   <img src="https://github-readme-stats.vercel.app/api/wakatime?username=YOUR_WAKATIME&theme=radical" />
   ```

### Add LeetCode Stats

1. Update README:
   ```markdown
   <img src="https://leetcard.jacoblin.cool/YOUR_LEETCODE?theme=dark" />
   ```

### Add Codeforces Stats

1. Update README:
   ```markdown
   <img src="https://codeforces-readme-stats.vercel.app/api/card?username=YOUR_CODEFORCES" />
   ```

## 🎨 THEME CUSTOMIZATION

### Colors

Edit badge colors in README:
- `radical` → `dark`, `tokyonight`, `dracula`, etc.
- Badge styles: `for-the-badge`, `flat`, `flat-square`

### ASCII Logo

Generate your own at: https://patorjk.com/software/taag/

Replace the ASCII art in README.

## 📊 METRICS INTEGRATION

### Repo Scoring

The `repo-score.yml` workflow scores repos based on:
- Stars (0-20 points)
- Tests (0-25 points)
- Coverage (0-25 points)
- CI (0-15 points)
- Docs (0-15 points)

### Contribution Snake

The `snake.yml` workflow generates:
- Light theme snake
- Dark theme snake (used in README)

## 🔐 SECURITY NOTES

- Workflows use `GITHUB_TOKEN` (automatically provided)
- No secrets required for basic setup
- For external APIs (Wakatime, etc.), use GitHub Secrets

## 🚨 TROUBLESHOOTING

### Snake not appearing

1. Check GitHub Pages is enabled
2. Verify `output` branch exists
3. Check workflow ran successfully
4. Wait 5-10 minutes after first run

### Stats not updating

- GitHub Stats API caches for ~4 hours
- Force refresh by appending `?v=1` to image URLs

### Workflows failing

1. Check Actions tab for errors
2. Verify repository permissions
3. Ensure GitHub Pages is enabled

## 📈 NEXT STEPS

1. **Customize** — Make it yours
2. **Iterate** — Add your own sections
3. **Enforce** — Use PR template in your repos
4. **Dominate** — Let the profile speak for itself

## 🎯 ADVANCED FEATURES

### Custom Badges

Create custom badges at: https://shields.io/

### Dynamic Content

Use GitHub Actions to inject:
- Latest blog post
- Recent commits
- Current project status

### Multi-language Support

Add language-specific READMEs:
- `README.md` (English)
- `README.zh.md` (Chinese)
- `README.es.md` (Spanish)

---

**This profile is a weapon. Use it wisely.**

