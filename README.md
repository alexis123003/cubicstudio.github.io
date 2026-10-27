# Cubic Studio Website

A static website for Cubic Studio. The site is served from `index.html`, and its logo is loaded from `cubic-studio-logo.png` in the same folder. No build step or server-side code is required.

## Publish with GitHub Pages

1. Create a GitHub repository and upload the files in this folder to the repository root. Keep `index.html` and `cubic-studio-logo.png` together at the root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then select **Save**.
5. Once the deployment completes, open the URL shown in the Pages settings.

The quote builder runs in the visitor's browser; it calculates an estimate and can copy the quote details for the visitor to send on Discord. GitHub Pages does not provide form processing or a backend.
