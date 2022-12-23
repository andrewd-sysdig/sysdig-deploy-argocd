# sysdig-deploy-argocd

Requires ArgoCD 2.6.0+ for the new feature that allows values.yaml to come from a different repo than the chart


```
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/v2.6.0-rc1/manifests/install.yaml
```
