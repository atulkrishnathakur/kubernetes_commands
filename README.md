## Minikube 
- minikube is usefull for development and local machine. If in your machine ram,processor is low then minikube is best option for kubernetes.

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
