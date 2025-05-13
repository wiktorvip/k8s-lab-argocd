# k8s-lab-argocd

```
Get password of argocd admin user:
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d

argocd login localhost:30888
argocd proj list
argocd app list


```

```
kubectl get Application -n argocd
kubectl describe Application -n argocd  apps1
kubectl describe Application -n argocd  argocd


```