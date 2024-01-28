# BCDV4032-Lab-4-
Commands used 

minikube start

minikube dashboard( changed port visibility) 

run all yaml files
kubectl apply -f . 

or 

kubectl apply -f ganache-deployment.yaml
kubectl apply -f ganache-service.yaml

kubectl apply -f backend-deployment.yaml
kubectl apply -f backend-service.yaml

kubectl apply -f frontend-deployment.yaml
kubectl apply -f 
frontend-service.yaml

kubectl apply -f loadbalancing.ingress.yaml
kubectl apply -f storagep.pvc.yaml
kubectl apply -f scaling.hpa.yaml 


minikube tunnel (another terminal)
