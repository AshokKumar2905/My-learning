# Kubernetes Services

- Expose pods to network
- Types:
  - ClusterIP: Internal access
  - NodePort: Access via node IP
  - LoadBalancer: Public access via cloud LB
- Commands:
  - `kubectl get svc`
  - `kubectl expose pod <pod-name> --type=NodePort`
