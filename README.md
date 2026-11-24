# aetos-releases

Public auto-update feed for the [Aetos 5.3](https://github.com/haganahzion/aetos) desktop app.

The Aetos desktop app (Electron + electron-updater) checks this repo's Releases
for `latest.yml` and the Windows installer. The app repo (`aetos`) is private, so
the installer and update metadata are mirrored here, where the installed app can
reach them without a token.

Releases are published automatically by the `Desktop release` workflow in the
`aetos` repo when a `desktop-v*` tag is cut (requires the `RELEASES_TOKEN` secret).
