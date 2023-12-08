# GitHub Actions CI Method with Artifactory

## Requirements

The GitHub Actions CI Method with Artifactory will require repository or organization secrets setup before GitHub Actions can run

### Secrets Require.

- `JF_ACCESS_TOKEN` - JFrog Artifactory access token
- `JF_URL` - The URL of the JFROG instance
- `REGISTRY_NAMESPACE` - The Artifactory Repository where to upload the image
- `REGISTRY_URL` - The Registry url, usually it the JF_URL without the https

