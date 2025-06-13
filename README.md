1. install kind (k8s in docker) which is better than minikube coz lets u create master and worker nodes
2. $ kind create cluster --name local
3. $ kind create cluster --config clusters.yml --name local
4. kind delete cluster --name local
5. ➜  ~ kubectl run nginx --image=nginx --port=80
6. ➜  ~ kubectl apply -f manifest.yml
7. ➜  ~ kubectl delete pod nginx

8. kubectl apply -f deployment-class.yml