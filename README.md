# TOOLCOM — GitHub Pages starter

Mobile-first, fictional wallet-interface demo inspired by the reference image. It does not connect to banks or payment providers, move funds, or provide secure account login.

## Publish
1. Create a GitHub repository (for example `toolcom-demo`).
2. Upload every file and the `assets` folder, preserving folder structure.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. Open the published URL in Android Chrome and choose **Install app** or **Add to Home screen** if offered.

## Replace logos
The G / P / M marks are placeholders. Upload your own logo files in `assets/` and replace each placeholder element in `index.html` with an `<img>` tag. Keep logos clearly labelled and do not imply that any payment service is connected.

Replace `assets/toolcom-icon.svg` with your own TOOLCOM icon if desired. For broad Android compatibility, a 512×512 PNG can be used by updating the manifest icon entry.

## Important
This is frontend-only. Balances and history are sample content. There is no secure login, database, or real payment processing. Never enter real passwords, PINs, OTPs, or financial credentials.
