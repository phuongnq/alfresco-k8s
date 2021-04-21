# alfresco-k8s

## Convert from docker-compose

```
cd docker-compose
kompose convert
```

## How to run with minikube

```
cd k8s
kubectl apply -f ./
minikube service proxy
```
