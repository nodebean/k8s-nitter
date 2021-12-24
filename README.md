## Kubernetes Nitter Example

### Purpose

Put Nitter into a personal kubernetes cluster with an nginx sidecar

### Details
|File  |  |
|--|--|
|deployment.yaml|A nitter container and an nginx container with a volume mount and volume for the config  |
|service.yaml|service configuration|
|ingress.yaml|generic ingress configuration with tls |
|configmap-nginx.yaml|the configuration for the configmap that defines the mounted nginx.conf|
|configmap-nitter.yaml|the configuration for the configmap that defines the mounted nitter.conf| 
