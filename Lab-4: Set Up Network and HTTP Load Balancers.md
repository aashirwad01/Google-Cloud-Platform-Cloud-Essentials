# Set Up Network and HTTP Load Balancers
This is lab 4( Set Up Network and HTTP Load Balancers) of quest Create and Manage Cloud resources we are allocated 30 minutes to complete the lab.
This hands-on lab shows  how to set up HTTP load balancer and Networl Load Balancer and run them on Compute Engine VMs. .

## Understanding the terminologies

- Virtual Machine : In simple terms we can use VM's to have more than one os on a single computer. OS within an OS. It is also used to provide computing services and storage options to anyone over cloud . So putting in perspective of cloud VM provide you an option to use a High end processor say I9(very bad example but bear it) over any machine say even if you have a Pentium processor , one can harness the power of cloud , internet and VM to get Computer with any linux image OS.
- Google Cloud Platform : It is public cloud computing services offred by Google . Like AWS and Azure another leader in IAAS services and PAAS services. Compute engine which provides virtual machine is IAAS while App engine is PAAS.
- When to use IAAS vs PAAS : IAAS is used if organization has an inhouse made app and simply need s infrastructure to host it. While PAAS is used to streamline deployment and development using services provided.
- Cloud shell : Interactive environment from google to manage cloud easily from the Web Browser.
- Network : A collection of computers ,  servers , devices connected together an example is internet.
- web server : It is a device hosting a website it stores , processes , delivers web pages to users. The communication is done using HTTP protocol.
- Hosting : It is aprocess to of using a server to host a website 
- cloud instance : usually it's one virtual machine used to provide cloud services 
- web server instance : So this can be thought of as a single instance of webserver to host a website provided by cloud service providers . GCP , AWS , AZURE
- Traffic meaning in web terms : Means data sent and received by website . It is measured in visits by user on website. Trackers are scripts kept to see what part of website is user interacting the most in a website about prefrences and improvements in the websites.
- Google front end : It is the web server service by Google cloud . It provides correct certifications for all TLS coonections . Additionally prevents DoS attacks. It also provides domain names .
- TLS : It is the advanced improved version of security for server to server or user to server connections on network i.e internet during a data transfer . Transport Layer Security is it's full form . It provides enscription to the data being shared preventing it from being misused. These security measures are certified and GFE helps provodeing correct certifications.
- HTTP : It is protocol for communication to send , receive webpages on internet.
- Load Balancing : It is a feature in Google cloud to manage traffic across VM instances , health monitoring and maintainence of VM instances.
- Network Load balancer  : A network load balancer distributes external traffic or load among virtual machines in the same region.It works on layer 4 .
- HTTP Load balancer : External load balancer is implemented on GFE and distributes the external traffic a globally.It works on layer 7 .
- Target Pool : It defines a group of instances that should receive incoming traffic from forwarding rules
- Forwarding Rules : It is set up to allow incoming traffic and direct it from individual ports within a range to particular port on User's VM on GCP. It specofoes which target pool vm to forward a packet . Main use of this rule is in load balancer where it helps in maintaining network traffic.
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
  - global forwarding rule to route requests to proxy
- Deployed application a web page named hello server







## This is the lab link with all the steps mentioned in it.
[Lab Link](https://google.qwiklabs.com/focuses/12007?parent=catalog)
