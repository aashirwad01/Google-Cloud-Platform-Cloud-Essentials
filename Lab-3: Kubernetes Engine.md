#  Kubernetes Engine
This is lab 3( Kubernetes Engine) of quest create and manage cloud resources we are allocated 30 minutes to complete the lab.
This hands-on lab shows  how deploy a containerized application with Kubernetes Engine.

## Understanding the terminologies

- Virtual Machine : In simple terms we can use VM's to have more thn one os on a single computer. OS within an OS. It is also used to provide computing services and storage options to anyone over cloud . So putting in perspective of cloud VM provide you an option to use a High end processor say I9(very bad example but bear it) over any machine say even if you have a Pentium processor , one can harness the power of cloud , internet and VM to get Computer with any linux image OS.
- Google Cloud Platform : It is public cloud computing services offred by Google . Like AWS and Azure another leader in IAAS services and PAAS services. Compute engine which provides virtual machine is IAAS while App engine is PAAS.
- When to use IAAS vs PAAS : IAAS is used if organization has an inhouse made app and simply need an infrastructure to host it. While PAAS is used to streamline deployment and development using services provided.
- Cloud shell : Interactive environment from google to manage cloud easily from the Web Browser.
- Kubernetes :It is open source platform for managing containerized applications and platforms . It runs multiple applications across multiple clusters . while Docker is to create conatiners , Kubernetes manages the containers.
- Containers : These are exectable units of software , a form of vitual os with executables , binary codes . Library to run a software application . Basically they are used to make a code device independent . The idea of code running on any computer put onto.
- Clusters : In GKE (Google Kubernetes Engine) a cluster consists of one control panel and various worker machines called nodes.
- Node : Nodes are diffrent VM compute engine instances which are created when we create a cluster in GKE
- Node Pools : Node pool is group of nodes in cluster that hae same configuration , i.e same local ssd , same cpu performance or node image .
- Load Balancing : It is a feature in Google cloud to manage traffic across VM instances , health monitoring and maintainence of VM instances.


## What did i do ?
- Set default compute zone in my case us center 1a
- created a gke cluster 
- Got authentication credentials for the cluster
- Deployed application a web page named hello server


![image](https://user-images.githubusercontent.com/47081802/136077296-1d082537-04a9-461a-961d-2edd7d63241a.png)

- Deleted the cluster





## This is the lab link with all the steps mentioned in it.
[Lab Link](https://google.qwiklabs.com/focuses/878?parent=catalog)
