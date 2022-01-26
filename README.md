# Kubernetes SDN-based CNI (KSC)
Customized CNI based on the [K-vswitch](https://github.com/k-vswitch/k-vswitch)

## Features

- OVS based overlay networking
- Multiple NICs for pods

## Deployment 
```shell
curl -LO https://raw.githubusercontent.com/nephilimboy/k-vswitch/master/deployment/k-vswitch-latest.yaml
nano k-vswitch-latest.yaml  # edit the first ConfigMap on this file based on your cluster configuration
kubectl apply -f k-vswitch-latest.yaml
```

## TODO
- Custom flow rules installation using API


