# GitHub Actions CI Method with Artifactory

## Requirements

The GitHub Actions CI Method with Artifactory will require repository or organization secrets setup before GitHub Actions can run

### Secrets Require.

##### NEXUS ENABLE
- `NEXUS_URL` - The Nexus URL
- `NEXUS_USERNAME` - Nexus username
- `NEXUS_PASSWORD` - Nexus password 

##### JFrog Enable
- `JF_ACCESS_TOKEN` - JFrog Artifactory access token
- `JF_URL` - The URL of the JFROG instance
- `JF_USERNAME` - The username for the JFROG account
- `JF_PASSWORD` - Docker access token
- `REGISTRY_NAMESPACE` - The Artifactory Repository where to upload the image
- `REGISTRY_URL` - The Registry url, usually it the JF_URL without the https

##### All the remaining
- `SONARQUBE_HOST` - The Sonarqube host url
- `SONARQUBE_TOKEN` - The Token needed to connect to Sonar
- `AWS_ACCESS_KEY_ID` - The access key
- `AWS_ENDPOINT` - The URL where to find the bucket, other wise it default to AWS
- `AWS_REGION` - The Region, in case of Noobaa anything will git
- `AWS_SECRET_ACCESS_KEY` - The secret access key
- `BUCKET_NAME` - The Bucket Name

