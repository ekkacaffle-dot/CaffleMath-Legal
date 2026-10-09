# FreeCal Maths & Scientific — Legal & Support

Public legal and support pages for FreeCal Maths & Scientific (formerly Caffle Math), a free offline basic and scientific calculator. The repository was renamed from CaffleMath-Legal to FreeCalMaths-Legal, then to FreeCalMaths-Scientific-Legal.

- [Privacy Policy](privacy.html)
- [Terms & Conditions](terms.html)
- [Support](support.html)

Support: **ekka.caffle@gmail.com**. Effective date: **October 9, 2026**.

These static pages require no npm dependencies, external fonts, JavaScript, analytics, or contact form. They support mobile screens and system light/dark appearance.

## Enable GitHub Pages

The files are committed in this repository. To publish the website:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then **Save**.
4. Wait for the Pages deployment to finish. Enable **Enforce HTTPS** when available.
5. Open each page and verify it before using the URLs in App Store Connect.

Expected URLs after deployment:

- https://ekkacaffle-dot.github.io/FreeCalMaths-Scientific-Legal/
- https://ekkacaffle-dot.github.io/FreeCalMaths-Scientific-Legal/privacy.html
- https://ekkacaffle-dot.github.io/FreeCalMaths-Scientific-Legal/terms.html
- https://ekkacaffle-dot.github.io/FreeCalMaths-Scientific-Legal/support.html

Committing the files does not automatically enable GitHub Pages. Keep Apple's Standard EULA in App Store Connect; these app-specific terms supplement it.

The calculator also includes its legal and support content offline.

## Update the pages

In the full FreeCal Maths & Scientific app project, edit `src/content/legal.json` or `src/content/legal.css`, then run:

```bash
npm run legal:build
```

Copy the regenerated files from `legal-site/` into this repository and commit the changes. Ship an app update when its bundled legal content changes.
