# K8S_project
## This is a Kubernates Project which containes:
- backend:
  - redis-leader deployment with a cluster ip service.
  - redis-follower deployment with a cluster ip service.
- frontend deployment with a node port service.
- ingress using nginx ingress controller.

## Note:
This project requires nginx ingress controller to setup the nginx ingress controller see the [Getting Started](https://kubernetes.github.io/ingress-nginx/deploy/) document.
