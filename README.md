# Nextcloud-deployment-in-Kubernetes
next cloud app using postgrsql and redis

Requirements

install docker and minikube 

Deployment

$ kubectl apply -f pvc.yaml

$ kubectl apply -f maria.yaml

$ kubectl apply -f redis.yaml

$ kubectl apply -f nextcloud.yaml


$ kubectl apply -f ingress.yaml

$ minikube service app

url
http://192.168.49.2:30005/apps/dashboard/
