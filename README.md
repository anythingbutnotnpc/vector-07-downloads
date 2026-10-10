# VECTOR 07 — Public download page

This folder is the static release landing page for VECTOR 07. Keep the Android source repository private if you want; create a separate **public** GitHub repository named `vector-07-downloads` for these files and the public release asset.

## Publish the page and APK

1. Create a new **public** repository on GitHub named `vector-07-downloads`.
2. Upload the contents of this folder to the repository root (`index.html`, `favicon.svg`, `.nojekyll`, `assets/`, and `README.md`). The `assets` folder contains the interface preview images.
3. In the public repository, open **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/(root)`, and save. After GitHub Pages finishes publishing, the page should be available at `https://anythingbutnotnpc.github.io/vector-07-downloads/`.
4. Open **Releases → Draft a new release** in the same public repository.
5. Create tag `v1.0.0`, title `VECTOR 07 v1.0.0 — First Public Build`, and attach the APK you downloaded from Actions. Rename the file to **exactly** `Vector-07.apk` before attaching it.
6. Publish the release. The page's Download buttons point to `https://github.com/anythingbutnotnpc/vector-07-downloads/releases/latest/download/Vector-07.apk`; the asset name and repository name must match exactly for this direct link to work.

## Updating later

For a new version, attach the new APK to a new release/tag. Keep the asset name exactly `Vector-07.apk` if you want the existing download button to continue pointing to the latest release.

## Important

The screenshots in `assets/` are UI preview images used to illustrate the design. Replace them with screenshots captured from the installed app if you want the page to show the exact current Android build. The downloadable APK must be attached to the GitHub Release; this website source folder does not include an APK binary.
