
## to deploy the deployment, simplely run following:
kubectl apply -f deployment.yaml

## for minikube running on VM, because it's using NAT network, need a port forwarding
kubectl port-forward service/hello-python-service2 7080:6000
