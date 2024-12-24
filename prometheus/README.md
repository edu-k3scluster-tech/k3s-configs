# How to deploy

```bash
helm upgrade --create-namespace --namespace prometheus --install prometheus prometheus-community/kube-prometheus-stack --version 67.4.0 --values kube-prometheus-stack-values.yaml
```

```bash
kubectl apply -f prometheus/ingress.yaml
```