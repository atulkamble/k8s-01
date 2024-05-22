# k8s-01
Syntax for Service and Deployment

Clone this repo
```
git clone https://github.com/atulkamble/k8s-01.git
cd k8s-01
```
```
// apply files to kubenetes cluster
kubectl apply -f .\deployment.yaml
kubectl get deployments
kubectl apply -f service.yaml
kubectl get services
kubectl get pods
kubectl describe pod my-deployment-cfb4dd9fc-skdz2
kubectl scale deployment my-deployment --replicas=5
kubectl get pods
kubectl scale deployment my-deployment --replicas=3
kubectl get pods
```
