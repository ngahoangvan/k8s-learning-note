```bash

kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
kubectl apply -f https_ingress.yaml
```

Ref:
[Argo CD official doc](https://argo-cd.readthedocs.io/en/stable/getting_started/)
[Setting up SSL for Argo CD](https://argo-cd.readthedocs.io/en/stable/operator-manual/ingress/)
[Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-deploy-to-kubernetes-using-argo-cd-and-gitops)
