# Ansible-k8s
**Welcome to 1 click Kubernetes World** , Lets take a sneek peak on how we can install Kubernetes multi-master cluster using Ansible .


<img width="36" alt="kube" src="https://user-images.githubusercontent.com/99710234/154669206-f2927d33-db97-43ac-b8e5-1340692767d6.png"> <img width="37" alt="docker" src="https://user-images.githubusercontent.com/99710234/154669208-eeab2758-d86d-438b-a566-071690820a6a.png"> <img width="109" alt="flannel" src="https://user-images.githubusercontent.com/99710234/154669213-e7153a7e-14b8-4959-8761-9a300348f074.png">

______________________________________________________________________________________________

**Pre-Requesties**

Ubuntu Server image 20.04 for master and worker nodes .
https://releases.ubuntu.com/20.04/ubuntu-20.04.3-live-server-amd64.iso

**We are building the Kubernetes cluster on basis of following compeonents**

1) Ubuntu server 20.04 LTS Versions 
2) Containerd as runtime
3) Kubernetes orchestration of course :)
4) Kubernetes Dashboard
5) Flanneld for Networking
6) Calico for network policy management 
7) Prometheus Monitoring
8) Grafana for Metrics

**Requirements before Deploy**

Get your server's ready with unique ip and set hostnames as specified (or as your wish) .
 * k8s-control1.example.com
 * k8s-control2.example.com
 * k8s-worker1.example.com
 * k8s-worker2.example.com
 
  ** Make sure interenet is accesibe to all the systems's .
  
  **Instaltaion Steps**
  Step 1 
  Download Git Deploy folder to all four instance .
  Wget -p https://github.com/kubernetes-quickdeploy/kubernetes/tree/main/deploy

 
 
  



 
