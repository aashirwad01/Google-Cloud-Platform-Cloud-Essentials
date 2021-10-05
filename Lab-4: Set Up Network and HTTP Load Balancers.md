# Set Up Network and HTTP Load Balancers
This is lab 4( Set Up Network and HTTP Load Balancers) of quest create and manage cloud resources we are allocated 30 minutes to complete the lab.
This hands-on lab shows  how deploy a containerized application with Kubernetes Engine.

## Understanding the terminologies

- Virtual Machine : In simple terms we can use VM's to have more thn one os on a single computer. OS within an OS. It is also used to provide computing services and storage options to anyone over cloud . So putting in perspective of cloud VM provide you an option to use a High end processor say I9(very bad example but bear it) over any machine say even if you have a Pentium processor , one can harness the power of cloud , internet and VM to get Computer with any linux image OS.
- Google Cloud Platform : It is public cloud computing services offred by Google . Like AWS and Azure another leader in IAAS services and PAAS services. Compute engine which provides virtual machine is IAAS while App engine is PAAS.
- When to use IAAS vs PAAS : IAAS is used if organization has an inhouse made app and simply need s infrastructure to host it. While PAAS is used to streamline deployment and development using services provided.
- Cloud shell : Interactive environment from google to manage cloud easily from the Web Browser.
- Network
- HTTP
- Load Balancing
- Network load balancer vs HTTP Load balancer :
- Target Pool
- Forwarding Rules
- 


## What did i do ?
- Set default compute zone and region in my case us center 1a nd us center 1
- created multiple web server instances with single tag name so all of these acn be referenced all at once
- Configured the load balancing service 
  - Static ip address created
  - Legacy HTTP health check
  - target pool
  - added instances to target pool
  - added a forwarding rule
- Sent traffic to instances
- Created HTTP Load balancer
  - Load balancer template is created
  - instance group based on template
  - health checkup firewall rule
  - set a global external ip address
  - create backend
  - add instance group as backend to backend service
  - url map to route the requests to default backend
  - target http to route requests to url map
  - global forwarding ule to route requests to proxy
- Deployed application a web page named hello server







## This is the lab link with all the steps mentioned in it.
[Lab Link](https://google.qwiklabs.com/focuses/12007?parent=catalog)
