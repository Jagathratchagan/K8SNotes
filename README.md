# K8SNotes
My Kubernetes Notes


# Install Kubernetes Dashboard
$ kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.7.0/aio/deploy/recommended.yaml 
$ kubectl get all -n kubernetes-dashboard

$ kubectl edit service/kubernetes-dashboard 
Add note port (32321) and chagne type to type: **NodePort**

$ kubectl get svc 

http://<NodeIp>:<dashboard port>

$ vim k8s-serviceaccount.yml 







