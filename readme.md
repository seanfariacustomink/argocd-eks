Default password of argocd

kubectl -n argo-cd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d

https://www.youtube.com/watch?v=Q44vOE1nwl0
