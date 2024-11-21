# おうちk8s
## k3dでclusterを作る

```
k3d cluster create -c k3d_config.yaml
```

## helmfileで諸々作る

- sealed-secret
- influxdb

```
helmfile apply
```
