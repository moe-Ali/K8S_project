# K8S_project
## This is a Kubernates Project which containes:
- backend:
  - redis-leader deployment with a ClusterIP service.
  - redis-follower deployment with a ClusterIP service.
- frontend deployment with a NodePort service.
- ingress using nginx ingress controller.

## Note:
This project requires nginx ingress controller to set up the nginx ingress controller, see the [Getting Started](https://kubernetes.github.io/ingress-nginx/deploy/) document.
