# 建置順序

```
    kubectl apply -f crd.yaml
    kubectl apply -f rbac.yaml
    kubectl apply -f config.yaml
    kubectl apply -f deploy.yaml
    kubectl apply -f dashboard.yaml
```