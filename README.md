# Sideman official site

Public static pages for App Store / Play listing links (Privacy, Terms, Support, and a light marketing home).

App source stays private in a separate repository. This site can grow into a fuller marketing site later without changing the Privacy / Terms URL paths.

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
   - Privacy (App Store Connect **Privacy Policy URL**):  
     `https://hubingliang.github.io/sideman-offical/privacy/`
   - Terms (EULA / Terms of Use if asked):  
     `https://hubingliang.github.io/sideman-offical/terms/`
   - Support (App Store Connect **Support URL**):  
     `https://hubingliang.github.io/sideman-offical/support/`

## Keep in sync with the app

English copy on these pages should match the in-app Privacy / Terms screens in the Sideman app (`src/i18n/messages.ts`). Update both when collection practices change (analytics, IAP details, accounts, etc.).

The public Privacy page may keep a short **Children** section that is not shown in-app; everything else should stay aligned.

## Contact

Privacy, Terms, and Support use `brianhu.cn@gmail.com`. Change it here and in the app if you prefer a dedicated inbox.
