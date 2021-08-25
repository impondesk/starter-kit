docker build -t bpa/node-server .    

docker run -p 3000:3000 bpa/node-server

http://bpa.io:3000/api/master



kubectl create -f k8s-definition.yaml 

kubectl get all


# minikube start --vm=true
# minikube addons enable ingress


