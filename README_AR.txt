Stars Smile Excel Sync — website for Google OAuth branding
============================================================
Files:
  index.html   = Application home page
  privacy.html = Privacy policy
  terms.html   = Terms of Use
  style.css    = Styles

This is ONLY a static public-information website. It does NOT contain OAuth secrets,
claims, invoices, medical information, or live synchronization code.

Easy deployment via GitHub Pages:
1. Sign in to https://github.com and create a PUBLIC repository named
   stars-smile-excel-sync-site (or use an approved repository you control).
2. Upload index.html, privacy.html, terms.html and style.css to the repository root.
3. In repository Settings -> Pages, select Deploy from a branch -> main -> /(root), Save.
4. Wait for GitHub Pages to publish. Verify index.html and privacy.html load publicly.
5. Typical URLs (replace YOUR_GITHUB_USERNAME with the actual account):
   https://YOUR_GITHUB_USERNAME.github.io/stars-smile-excel-sync-site/
   https://YOUR_GITHUB_USERNAME.github.io/stars-smile-excel-sync-site/privacy.html
   https://YOUR_GITHUB_USERNAME.github.io/stars-smile-excel-sync-site/terms.html
6. Enter the actual publicly working links in Google Cloud > Google Auth Platform > Branding:
   Application home page, Application privacy policy link, Terms link if requested.
7. For Authorized domains, Google Cloud may require github.io and/or a verified
   custom domain depending on current console policy. If the domain cannot be
   authorized or verified in your project, use a domain you control and verify
   it through Google Search Console. A public GitHub Pages link is not a
   guarantee of approval/verification.
8. Review the privacy policy against the actual deployed script; update it if
   functionality, logging, data sharing, or retention differs.
9. Do NOT upload any Client ID, Client Secret, rclone.conf, Excel data, or patient
   information to the public repository.
10. Do not switch the running smiledrive remote until the new OAuth app has been
    tested and working. An External app in Testing may have refresh token expiry.

Important: This website cannot make the OAuth application verified automatically.
Google may still require domain ownership checks and restricted-scope verification.
