# Istio GitOps

GitOps-managed Istio service mesh on Kubernetes.

## Technology Stack

- Kubernetes 1.37
- ArgoCD 3.5.6
- Helm 3.22.1
- Istio 1.31.3
- Envoy Proxy

## Deployment Strategy

ArgoCD manages Istio Helm charts and Kubernetes manifests.

## Installation Order

1. Istio Base
2. Istiod
3. Istio Gateway
4. Sample microservices
5. Istio traffic and security policies
6. Observability
