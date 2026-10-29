# Quran Scroll website

Static site for https://basimibsies09.github.io/quran-scroll-site/ (Privacy Policy and Terms of Service for the Quran Scroll iOS app).

Source of truth is the `site/` folder of the private `ScrollTheQuran` repo. Deploy by pushing that folder to the public `quran-scroll-site` repo (GitHub Pages serves `main` at `/`):

```bash
git subtree push --prefix site https://github.com/BasimIbsies09/quran-scroll-site.git main
```
