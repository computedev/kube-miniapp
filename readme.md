#### K8s manifest files 
* mongo-configmap.yml
* mongo-secret.yml
* mongo.yml
* webapp.yaml

##### start Minikube and check status
    minikube start --vm-driver=hyperkit 
    minikube status
##### Minikube node's ip address
    minikube ip

##### basic info about k8s components
    kubectl get node
    kubectl get pod
    kubectl get svc
    kubectl get all

##### get extended info about components
    kubectl get pod -o wide
    kubectl get node -o wide

##### get detailed info about a specific component
    kubectl describe svc {svc-name}
    kubectl describe pod {pod-name}

##### get application logs
    kubectl logs {pod-name}
    
##### stop your Minikube cluster
    minikube stop

<br />


