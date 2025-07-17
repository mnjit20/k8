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

# Deployments 
kubectl apply -f deployment.yaml

# Delete a deployed pod 
kubectl delete pod POD_NAME -n NAMESPACE_NAME


# Check event logs for a pod to check health
kubectl describe pod POD_NAME -n NAMESPACE_NAME

# Check if deployed app is working
kubectl -n NAMESPACE_NAME

```
