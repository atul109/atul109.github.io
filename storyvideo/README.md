# StoryVideo — Landing Page

Static marketing / legal site for the **StoryVideo** Android app
(`com.crazylabs.storyvideo`), ready to host on GitHub Pages.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing page with a **Get it on Google Play** button and footer links |
| `privacy.html` | Privacy Policy |
| `terms.html` | Terms of Use |
| `styles.css` | Shared styling (dark purple theme matching the app) |

## Hosting on GitHub Pages

1. Create a repo and push these files to the `main` branch (site files at the repo root).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then **Save**.
5. Your site goes live at `https://<username>.github.io/<repo>/` within a minute or two.

## Before you publish

- Confirm the Play Store URL in `index.html` matches your listing:
  `https://play.google.com/store/apps/details?id=com.crazylabs.storyvideo`
- Review the Privacy Policy and Terms of Use for legal accuracy; the contact
  email is set to `atulvasudev2008@gmail.com`.
