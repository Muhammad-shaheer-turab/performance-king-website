# Performance King — website

Static pages for GitHub Pages: landing page, help, about, Terms of Use,
Privacy Policy and open-source licences. No scripts, no cookies, nothing
loaded from other sites.

**Do not edit these files by hand.** They are generated from the app's
repository, so the Terms and Privacy Policy here are always the exact text the
app shows and asks people to agree to:

```bash
cd "../Performance King" && node scripts/website.mjs
```

## Publish (once)

1. Create an empty public repository named `performance-king-website` on GitHub.
2. `git remote add origin https://github.com/YOUR-USERNAME/performance-king-website.git && git push -u origin main`
3. Repository **Settings → Pages → Deploy from a branch → `main` / root → Save**.

The privacy policy is then at
`https://YOUR-USERNAME.github.io/performance-king-website/privacy.html`.
