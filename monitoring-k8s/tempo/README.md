# tempo
This folder is a minimal kustomize-safe placeholder for the tempo component.
It creates:
- Namespace: monitoring-tempo
- A ConfigMap `tempo-values` in that namespace as a placeholder for Helm values or kustomize overlays.

Next steps you can do (pick one):
1. Replace the files with a real Helm chart by using ArgoCD Application with `Helm` type pointed at the upstream chart and these values.
2. Add real manifests / kustomize overlays here to deploy the real services.
