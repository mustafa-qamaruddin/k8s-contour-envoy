# k8s-contour-envoy
Test Contour Envoy Ingress Controller and Reverse Proxy

Check Docs: [Docs](https://kind.sigs.k8s.io/docs/user/configuration/)
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
kind delete cluster
```
