# Quran Scroll website

Static site for https://quranscrollapp.com/ (SMS waitlist landing page, Privacy Policy and Terms of Service for the Quran Scroll iOS app). The domain is registered at Porkbun; DNS points at GitHub Pages (four A + four AAAA records on the apex, `www` CNAME to basimibsies09.github.io) and `CNAME` in this folder sets the custom domain. The old github.io URL redirects here.

Source of truth is the `site/` folder of the private `ScrollTheQuran` repo. Deploy by pushing that folder to the public `quran-scroll-site` repo (GitHub Pages serves `main` at `/`):

```bash
git subtree push --prefix site https://github.com/BasimIbsies09/quran-scroll-site.git main
```
