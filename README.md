# NetherLauncher website

Static landing page for NetherLauncher, deployed to GitHub Pages at
https://wolf06254-alt.github.io/NetherLauncher/.

The site source is in `site/`; relative image and stylesheet paths are compatible
with the repository Pages URL. The workflow at
`.github/workflows/pages.yml` publishes `site/` on pushes to `main`.

Download buttons link to the Windows x64 portable executable
(`NetherLauncher-1.4.0-win-x64.exe`) and Apple-silicon DMG
(`NetherLauncher-1.4.0-arm64.dmg`) attached to the `v1.4.0` GitHub Release.
Version 1.4.0 keeps the launcher display name separate from the Minecraft offline nickname.

The Windows build is unsigned. The macOS build targets Apple silicon only and is
not Developer ID signed or notarized. Earlier GitHub Releases and their assets
remain available; only the current website download links point to 1.4.0.

`NetherLauncher.com` is not configured. Add it as a Pages custom domain only
after confirming ownership and setting the DNS records required by GitHub.
