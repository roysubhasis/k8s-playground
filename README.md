# k8s-playground
Study k8s

Some sample commands below.

## Create ngnix pod using kubectl
`kubectl apply -f <yaml file name>`

## Get Pods
`kubectl get pods`

## Describe pod
`kubectl describe pod <pod_name>`

## Delete pod
`kubectl delete pod <pod_name>`

## Create depolyment using kubectl
`kubectl create deployment hello-minikube --image=k8s.gcr.io/echoserver:1.10`

## Run image/pod on fly using kubectl
`kubectl run nginx --image=nginx`

## kubectl create replication controller
`kubectl create -f rc-definition.yml`

## kubectl get replication controller
`kubectl get replicationcontroller`

## kubectl delete replication controller
`kubectl delete rc <relication-controller-name>`

## kubectl get replicaset
kubectl get replicaset
