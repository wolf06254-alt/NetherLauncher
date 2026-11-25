# NetherLauncher website

Static landing page for NetherLauncher, deployed to GitHub Pages at
https://wolf06254-alt.github.io/NetherLauncher/.

The site source is in `site/`; relative image and stylesheet paths are compatible
with the repository's project Pages URL. The workflow at
`.github/workflows/pages.yml` publishes `site/` on pushes to `main`.

Download buttons link to the `v1.1.0` GitHub Release assets:
`NetherLauncher-1.1.0-win-x64.exe` (Windows x64 portable) and
`NetherLauncher-1.1.0-arm64.dmg` (macOS Apple silicon). The Windows build is
unsigned; the macOS build is unsigned, not notarized, and does not support Intel
Macs.

`NetherLauncher.com` is not configured. Add it as a Pages custom domain only
after confirming ownership and setting the DNS records required by GitHub.
