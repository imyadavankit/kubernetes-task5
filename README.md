# Kubernetes Task 5

## What I Did:
1. Installed Minikube, Docker, and kubectl on Windows
2. Created a Kubernetes cluster locally
3. Deployed an Nginx web application using YAML files
4. Exposed the application using a LoadBalancer service
5. Scaled the deployment from 2 to 4 pods
6. Verified everything using kubectl commands

## Files:
- `deployment.yaml` - Defines the application deployment
- `service.yaml` - Exposes the application to the network

## Commands Used:
- `minikube start --driver=docker`
- `kubectl apply -f deployment.yaml`
- `kubectl apply -f service.yaml`
- `kubectl get pods`
- `kubectl get services`
- `kubectl scale deployment my-web-app --replicas=4`
- `minikube service my-web-service --url`
