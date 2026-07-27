# Sideman official site

Public static pages for App Store / Play listing links (Privacy, later Terms and marketing).

App source stays private in a separate repository. This site can grow into a fuller marketing site later without changing the Privacy URL path.

## Local preview

Open `index.html` in a browser, or:

```bash
npx --yes serve .
```

## GitHub Pages

1. Push `main` to GitHub.
2. Repo **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
3. After a minute or two, the site is at:

   - Home: `https://hubingliang.github.io/sideman-offical/`
   - Privacy (use this in App Store Connect):  
     `https://hubingliang.github.io/sideman-offical/privacy/`

## App Store

Fill **Privacy Policy URL** with the Privacy link above. Keep the copy in sync with the in-app Privacy screen when you change collection practices (analytics, IAP, accounts, etc.).

## Contact

Privacy page uses `brianhu.cn@gmail.com`. Change it in `privacy/index.html` if you prefer a dedicated inbox, and keep the in-app privacy screen aligned.
