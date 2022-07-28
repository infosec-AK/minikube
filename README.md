# minikube

I deployed a MongoDB database and a web application which connected to the database using ConfigMap and Secret.
And made it accessible from the browser.

Setup minikube on my homelab.

$ minikube start --driver docker

$ minikube status

$ kubectl apply -f mongo-config.yaml

$ kubectl apply -f mongo-secret.yaml

$ kubectl apply -f webapp.yaml

$ kubectl apply -f mongo.yaml 

$ kubectl get all

$ kubectl get svc

$ minikube ip
