# Cubic Studio Website

A static website for Cubic Studio. The site is served from `index.html`, and its logo is loaded from `cubic-studio-logo.png` in the same folder. No build step or server-side code is required.

## Publish with GitHub Pages

This repository includes a GitHub Actions workflow that publishes the static site
whenever changes are pushed to `main`.

1. Upload the contents of this folder to the root of a GitHub repository. Keep
   `index.html` and `cubic-studio-logo.png` together at the root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Push a commit to the `main` branch, or run the **Deploy to GitHub Pages**
   workflow from the **Actions** tab.
5. Once the workflow completes, open the site URL shown in the workflow summary
   or in **Settings → Pages**.

## Update the skin previews

Replace `texture.png` in the site folder with the featured buyer’s 64×64
Minecraft skin texture. The spotlight maps the base skin and outer overlay onto
a slowly rotating 3D character. Drag the preview to rotate it, or focus it and
use the arrow keys. It detects slim or classic arms from the texture when the
page loads. Update the buyer name in `index.html` each week.

The home-page hero uses `texture2.png` as its 64×64 skin atlas and has the same
layered 3D preview and rotation controls. It also detects slim or classic arms
when the page loads. Replace that file to change the hero skin.

The quote builder runs in the visitor's browser; it calculates an estimate and can copy the quote details for the visitor to send on Discord. GitHub Pages does not provide form processing or a backend.
