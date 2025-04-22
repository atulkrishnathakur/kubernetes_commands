## Minikube 
- minikube is usefull for development and local machine. If in your machine ram,processor is low then minikube is best option for kubernetes.

## Basic Structure of Kubernetes
- Pod: It is a smallest unit of kubernetes. It contain more than one container.
- Node: It is a machine where kubernetes pods run. It is a single node in minikube.
- Deployment: It manage the pods so application will run properly.
- Service: It provide network access so your applications communicate easly.

## How to install minikube
- Note: before minikube installation install the docker in your machine
```
  atul@atul-Lenovo-G570:~$ curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
```

```
  atul@atul-Lenovo-G570:~$ sudo install minikube-linux-amd64 /usr/local/bin/minikube
```

## Start minikube kubernetes with docker driver
```
atul@atul-Lenovo-G570:~$ minikube start --driver=docker

```
## verify minikube installation
```
atul@atul-Lenovo-G570:~$ minikube status
```

## Install the `kubectl`
```
atul@atul-Lenovo-G570:~$ sudo snap install kubectl --classic
```

## verify kubectl installation
```
atul@atul-Lenovo-G570:~$ kubectl version --client
```

```
atul@atul-Lenovo-G570:~$ kubectl get nodes
```

## check all pods of kubernetes
```
atul@atul-Lenovo-G570:~$ kubectl get pods --all-namespaces

```
