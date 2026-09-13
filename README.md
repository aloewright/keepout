# Keepout for Android

Official signed Android downloads for [Keepout](https://keepout.app). This repository contains download information only; Keepout's source code is not published here.

## Install with ObtainX

1. In ObtainX, choose **Add App** and enter **https://github.com/aloewright/keepout**.
2. Turn on **Include prereleases** while Keepout is in beta.
3. Add the app, then download and install its APK. No GitHub account or token is needed for this public source.

Already tracking the private `aloewright/txt` URL? Replace that source with the URL above. Do not uninstall Keepout: removing the app deletes its device-bound vault keys and local data.

Prefer a direct download? Open [Releases](https://github.com/aloewright/keepout/releases) and select the APK attached to the newest release. Android may ask you to allow installation from your browser or ObtainX.

## Compatibility and verification

- Android 9 or later; ARM64 phones (including Pixel) and x86_64 devices.
- Package: `pm.keepout`.
- Releases use the same signing identity as earlier Keepout Android beta packages, so they can update an existing installation in place.
- Each release includes its APK SHA-256 checksum. Signing certificate SHA-256: `0ca4c1563aaa7d9c2a663156543078f4983bd89a74b6da207290e89847336ee4`.

Keepout is currently a prototype/beta. Release notes distinguish tested behavior from remaining device-specific checks.

[Support](https://keepout.app) · [Privacy](https://keepout.app/privacy) · [Terms](https://keepout.app/terms)
