# KubernetesFinalTask
![image](https://user-images.githubusercontent.com/66691418/205509301-c77e153b-ad1d-4365-98ee-1402a9685019.png)

 Task Information : 
 Please use your last two homework assignments:
- The YNET news: Reads the “Breaking News” from YNet news service.
- The Bitcoin app: Presents the Current BitCoin Price, And the Average Price for the last 10 minutes and stores the price in a Redis Database..
-  Dockerize your YNET and Bitcoin applications.
- bitcoin : ![image](https://user-images.githubusercontent.com/66691418/205509669-59977a23-502f-4da3-90c8-b83f546f2802.png)
- Ynet : 
-  Create Kubernetes manifests (Deployment and service).
-  Deploy on your minikube.
-  Deploy/Enable Ingress Controller on your cluster.
-  Create an ingress that directs the traffic to the correct service:
http://…/ynet → ynet service.
http://…/bitcoin → bitcoin service.
Access from browser:
 - http://localhost/bitcoin
 ![image](https://user-images.githubusercontent.com/66691418/205510580-34a6f6fe-7368-440b-9d0e-aaf14e6c5cec.png)

 - http://localhost/ynet
 ![image](https://user-images.githubusercontent.com/66691418/205509516-5bd96751-8d56-463d-bed7-7af968d8b129.png)


⚡Run With Minikube:
- Clone the project : git clone https://github.com/mariamqais29/KubernetesFinalTask.git
- project directory: cd KubernetesFinalTask 
- minikube start 
- minikube addons enable ingress 
- kubectl apply -f
- minikube tunnel 
