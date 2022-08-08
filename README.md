# k8s-contour-envoy
Test Contour Envoy Ingress Controller and Reverse Proxy

```
brew install kind
kind create cluster --config=config.yaml
kubectl cluster-info --context kind-kind
kind export logs
kubectl cluster-info dump
kubectl apply -f iac.yaml 
kubectl get pods -A       
kubectl get services -A   
curl 127.0.0.1
```
