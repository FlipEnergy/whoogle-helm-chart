[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/flipenergy)](https://artifacthub.io/packages/search?repo=flipenergy)
# Helm chart for deploying Whoogle to K8s

Bare bones helm chart for deploying [Whoogle Search](https://github.com/benbusby/whoogle-search) to k8s.

see [values.yaml](whoogle/values.yaml) for configurations.

Install using Helm v3:

```
helm repo add flipenergy https://flipenergy.github.io/k8s-homelab/
helm install my-release flipenergy/whoogle
```
