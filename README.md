# k8s-lab-argocd

```
Get password of argocd admin user:
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d


kubectl port-forward -n argocd service/argocd-server 67684:80

argocd login 127.0.0.1:argocd_port_here
argocd proj list
argocd app list


```

```
kubectl get Application -n argocd
kubectl describe Application -n argocd  apps1
kubectl describe Application -n argocd  argocd


```