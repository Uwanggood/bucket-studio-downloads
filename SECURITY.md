# Security

Bucket Studio handles storage credentials, so security reports are welcome.

## Reporting A Vulnerability

Please report suspected vulnerabilities privately when possible.

Use GitHub private vulnerability reporting if it is enabled for this repository. If it is not available yet, open a public issue with only a high-level description and no secrets, credentials, private endpoints, object names, presigned URLs, or exploit details.

Include:

- Bucket Studio version.
- Operating system and version.
- A short description of the issue.
- Steps to reproduce, if safe to share.
- Any relevant logs with credentials and private endpoints removed.

Do not post exploitable security issues publicly before a fix is available.

## Security Model

- Credentials are intended to stay on the local device.
- The app signs S3-compatible requests locally.
- The app connects directly to the configured storage endpoint.
- Destructive delete operations should require preview and explicit confirmation.
- Release artifacts should be published with SHA256 checksums.

## Supported Versions

During beta, only the latest published release is supported for security fixes.
