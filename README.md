# Bucket Studio

Bucket Studio is a free, local-first desktop browser for S3-compatible storage.

It gives Windows, macOS, and Linux users the same clean interface for AWS S3, Cloudflare R2, Wasabi, MinIO, and compatible providers.

Bucket Studio is currently distributed as a free beta. Source code is private during beta because the app depends on a private company UI package, but the app is designed to keep credentials on your device and connect directly to the storage endpoint you configure.

## Website

Public landing page:

https://uwanggood.github.io/bucket-studio-downloads/

## Downloads

Download the latest release from the Releases page.

| Platform | Artifact | Status |
| --- | --- | --- |
| Windows x64 | `bucket-studio-vX.Y.Z-windows-x64.zip` | Primary beta target |
| macOS | `bucket-studio-vX.Y.Z-macos.zip` | Signed/notarized builds planned |
| Linux x64 | `bucket-studio-vX.Y.Z-linux-x64.tar.gz` | AppImage/Flatpak planned after beta feedback |

Every release should include `SHA256SUMS.txt`. Verify the downloaded artifact before running it.

## Features

- Browse buckets, prefixes, and objects.
- Upload files and folders.
- Download objects, folders, or whole buckets through OS pickers.
- Generate real presigned URLs.
- Delete objects through a preview and confirmation flow.
- Connect AWS S3, Cloudflare R2, Wasabi, MinIO, or another S3-compatible endpoint.
- Store provider credentials locally using platform secure storage.

## Privacy And Security

- Credentials are stored on your device.
- Bucket Studio does not send credentials to a Bucket Studio server.
- Connections are made directly from the app to the provider endpoint you configure.
- Beta diagnostics are privacy-scrubbed and documented in `PRIVACY.md`.
- Destructive delete actions use a preview/confirmation flow.

See `PRIVACY.md` and `SECURITY.md` for details.

## Donate

Bucket Studio is free during beta. Donations help fund maintenance, signing certificates, store accounts, and cross-platform packaging.

Donation links are being prepared. Until then, feedback, issue reports, and checksum-verified beta testing help the project a lot.

## License

Bucket Studio binaries are proprietary beta software. See `LICENSE.txt`.
