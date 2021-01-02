## To install minikube:
```
brew install minikube
```
```
brew install hyperkit
```

## To start minikube:
```
minikube start --driver=hyperkit
```
#### After default hyperkit is configured
```
minikube start
```
```
minikube stop
```

## Set default hyperkit:
```
minikube config set driver hyperkit
```

## Get the minikube IP:
```
minikube ip
```
## Get minikube info
```
kubectl cluster-info
```

## Apply a k8s config file
```
kubectl apply -f <file path>
```

## print status of pods
```
kubectl get pods
```

## print status of services
```
kubectl get services
```

## Tag locally built docker image
```
docker tag <image id> <username>/<docker repo>:<desired tag>
```

## Push the docker image
```
docker push <username>/<docker repo>:<tag>
```
