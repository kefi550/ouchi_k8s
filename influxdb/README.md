```
kubectl apply -f influx-auth-sealed.yaml
# sealed secretが必要
helmfile apply
```

```
helmfile destroy
# pv, pvc, sealed-secretが残る
```

