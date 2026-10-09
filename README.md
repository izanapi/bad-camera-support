# bad camera. support pages

This is a static GitHub Pages site for the bad camera. App Store listing.

## Repository name

Recommended: `bad-camera-support`

A public repository is the simplest way to use GitHub Pages on a free account. The only public files are the support page, privacy policy, and a small home page. Do not put app source code, signing files, certificates, or private data here.

## Publish

1. On GitHub, create a **public** repository named `bad-camera-support`. Do not initialize it with a README or other files.
2. Unzip this package and upload the contents of this folder to the repository's top level. `index.html`, `Support/`, and `PrivacyPolicy/` must be at the top level.
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, then save.
4. Wait for the Pages deployment to finish. The home page will be `https://YOUR-GITHUB-NAME.github.io/bad-camera-support/`.
5. Open both page links on a phone or private browser window to confirm they are publicly readable. Replace `YOUR-GITHUB-NAME` with the actual GitHub username.
6. In App Store Connect enter:
   - Support URL: `https://YOUR-GITHUB-NAME.github.io/bad-camera-support/Support/ja.html`
   - Privacy Policy URL: `https://YOUR-GITHUB-NAME.github.io/bad-camera-support/PrivacyPolicy/ja.html`

No build step or custom domain is needed. Changes can be made by editing the files in GitHub.
