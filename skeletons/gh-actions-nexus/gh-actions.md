# GitHub Actions CI Method with Artifactory

## Requirements

The GitHub Actions CI Method with Artifactory will require repository or organization secrets setup before GitHub Actions can run

### Secrets Require.

- `NEXUS_URL` - The Nexus URL
- `NEXUS_USERNAME` - Nexus username
- `NEXUS_PASSWORD` - Nexus password 
- `REGISTRY_NAMESPACE` - The Artifactory Repository where to upload the image
- `REGISTRY_URL` - The Registry url, usually it the JF_URL without the https
- `SONARQUBE_HOST` - The Sonarqube host url
- `SONARQUBE_TOKEN` - The Token needed to connect to Sonar
