# Pill Timer — Support Page

This small static site provides a public Support/FAQ page you can host with GitHub Pages or any static hosting provider.

How to publish (push to your new public repo):

1. In your local repo root run:

```bash
git checkout -b add/support-page
git add support-site
git commit -m "Add support-site for App Store Support URL"
# replace <GITHUB_REMOTE_URL> with your new repo HTTPS/SSH URL
git remote add origin <GITHUB_REMOTE_URL>
git push -u origin add/support-page
# Create PR in GitHub and merge to `main`, or push directly to `main`:
git push origin add/support-page:main
```

2. Enable GitHub Pages for the repository:
   - Go to the repository Settings → Pages
   - Source: `main` branch `/ (root)` or `/docs` (if you move files to `docs/`)
   - Save and wait a minute for the published URL.

3. Use the published URL as the App Store Support URL.

Notes:
- Edit `support-site/index.html` to replace contact email and links.
- If you prefer `https://<user>.github.io/<repo>/support`, move this file to `docs/support/index.html` or change Pages settings.
