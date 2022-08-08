# k8s-contour-envoy
Test Contour Envoy Ingress Controller and Reverse Proxy

```
kind create cluster --config=config.yaml
kubectl cluster-info --context kind-kind
kind export logs
kubectl cluster-info dump

```
