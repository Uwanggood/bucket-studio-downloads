# Privacy

Bucket Studio is a local-first desktop application for S3-compatible storage.

## Credentials

Provider credentials are stored on your device using platform secure storage where available. Bucket Studio does not send access keys, secret keys, session tokens, bucket names, endpoints, or object paths to a Bucket Studio server.

The app connects directly from your computer to the S3-compatible endpoint you configure, such as AWS S3, Cloudflare R2, Wasabi, MinIO, or a compatible private endpoint.

## Diagnostics And Updates

Beta builds may use Sentry for crash and error diagnostics when diagnostics are enabled at build time. Diagnostic events are configured to avoid storage credentials, secret keys, session tokens, bucket names, endpoints, object paths, presigned query strings, request bodies, screenshots, and default personally identifiable information.

Bucket Studio also checks the public update manifest at `latest.json` to learn whether a newer release is available. The update manifest does not require storage credentials.

## Local Files

Bucket Studio accesses local files only when you choose files or folders to upload, choose a destination for downloads, or use a feature that explicitly asks for local filesystem access.

## Support

If you report a bug, avoid sharing credentials, presigned URLs, private endpoints, object names, or logs that contain sensitive information.
