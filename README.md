# Kubernetes - K8
IaC (Infrastructure as Code) or GitOps

# Commands list
```bash
# start minikube
minikube start

# get cluster information
kubectl cluster-info

# get namespaces
kubectl get namespaces

# get pods which was created with minikube. -A is for listing pods for all the namespaces
kubectl get pods -A

# get services
kubectl get services -A

# Create namespace
kubectl apply -f namespace.yaml

# Delete namespace
kubectl delete -f namespace.yaml

```
