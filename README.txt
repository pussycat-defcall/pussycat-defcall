Pussycat Defcall - GitHub Pages website

1. Sign in at https://github.com and create a new PUBLIC repository, e.g. pussycat-defcall.
2. Upload index.html, privacy.html and style.css to the repository ROOT (not the ZIP file itself).
3. In repository Settings > Pages, choose Deploy from a branch; branch main, folder /(root); Save.
4. Wait for GitHub Pages to publish. Your URLs should look like:
   https://YOUR-GITHUB-USERNAME.github.io/pussycat-defcall/
   https://YOUR-GITHUB-USERNAME.github.io/pussycat-defcall/privacy.html
5. Check both URLs work without signing in.
6. In Google Cloud > Google Auth Platform > Branding:
   Application home page: first URL
   Application privacy policy link: second URL
   Save. Add github.io as an authorized domain ONLY if Google requires it and allows it. Do not invent domain ownership.
7. In Audience, try Publish app again. Google may require verification or additional requirements for the Google Sheets scope.
8. Once production status is confirmed, reauthorize Google on your PC to create a NEW google_token.json; upload it to Wispbyte and restart the bot.

IMPORTANT: Review the privacy policy and update any statements that do not match how your bot actually processes or stores data. Contact address currently set to larspettereinarsen@gmail.com based on your Google OAuth screenshots. Do not upload google_token.json, google_oauth.json, .env or any private credentials to GitHub.
