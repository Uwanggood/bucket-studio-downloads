# Privacy

Bucket Studio is a local-first desktop application for S3-compatible storage.

## Credentials

Provider credentials are stored on your device using platform secure storage where available. Bucket Studio does not send access keys, secret keys, session tokens, bucket names, endpoints, or object paths to a Bucket Studio server.

The app connects directly from your computer to the S3-compatible endpoint you configure, such as AWS S3, Cloudflare R2, Wasabi, MinIO, or a compatible private endpoint.

## Telemetry

Telemetry is not enabled during beta.

If telemetry, crash reporting, or update checks are added later, they should be documented here and should not include storage credentials.

## Local Files

Bucket Studio accesses local files only when you choose files or folders to upload, choose a destination for downloads, or use a feature that explicitly asks for local filesystem access.

## Support

If you report a bug, avoid sharing credentials, presigned URLs, private endpoints, object names, or logs that contain sensitive information.
