# Simple Flask App in K8s

This is to demonstrate deploying a flask app container in kubernetes cluster locally via minikube

### Prerequisite

- Docker
- Kubectl
- Minikube
- VirtualBox

### Quickstart

- Clone the repo
- Create a kubernetes cluster

```
> minikube start
```

- Apply all k8s config

```
> kubectl apply -f k8s-config
```

- Enable Ingress

```
> minikube addons enable ingress
```

- List the cluster ip

```
> minikube ip
```

- Access the app in the browser using cluster ip in `http://{minikube-ip}`
