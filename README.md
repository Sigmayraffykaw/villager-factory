# Grand Villager Factory — BruhWiks

A static website for planning a huge Minecraft Java 1.21.11 villager factory castle.

## Preview
The website includes a Three.js concept preview, department descriptions, a rough materials estimator, and build guidance.

**Important:** The 3D preview is an illustration of the planned castle, not a validated block-for-block schematic. The downloadable .litematic is not included yet; it should only be linked after it is validated in Litematica and tested in-game.

## GitHub Pages
This repository is set up for GitHub Actions deployment. In **Settings → Pages**, choose **GitHub Actions** as the build and deployment source.

Custom domain: `factory.bruhwiks.com`

In Cloudflare DNS, create a CNAME record:
- Type: CNAME
- Name: factory
- Target: Sigmayraffykaw.github.io
- Proxy status: DNS only while verifying Pages/HTTPS (recommended during setup)

Then in GitHub **Settings → Pages → Custom domain**, set `factory.bruhwiks.com`. Once DNS and certificate provisioning finish, enable Enforce HTTPS.

## Files
- `index.html` — complete static site and 3D viewer
- `CNAME` — custom domain
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow
