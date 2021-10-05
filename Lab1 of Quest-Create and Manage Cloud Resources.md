# Creating a Virtual Machine
This is lab 1(Create a Virtual Machine) of quest create and manage cloud resources we are allocated 40 minutes to complete the lab.

## Understanding the terminologies

- Virtual Machine : In simple terms we can use VM's to have more thn one os on a single computer. OS within an OS. It is also used to provide computing services and storage options to anyone over cloud . So putting in perspective of cloud VM provide you an option to use a High end processor say I9(very bad example but bear it) over any machine say even if you have a Pentium processor , one can harness the power of cloud , internet and VM to get Computer with any linux image OS.
- Google Cloud Platform : It is public cloud computing services offred by Google . Like AWS and Azure another leader in IAAS services and PAAS services. Compute engine which provides virtual machine is IAAS while App engine is PAAS.
- When to use IAAS vs PAAS : IAAS is used if organization has an inhouse made app and simply need s infrastructure to host it. While PAAS is used to streamline deployment and development using services provided.

## What did i do ?
Created a VM instance using GUI interface of GCP platform . Gave it
- Name : Name of the VM instance
- Region : It refers to region where cloud is origially located .Google has logically mapped the physical servers .
### For more information on zones and region refer this
[GCP regions and zones](https://cloud.google.com/compute/docs/zones)
- zone : the regions are further divided into logicak zones withn shared resources.
- series : Name of processor series
- machine type : CPU RAM 
- boot disk type : Harddisk space
- firewall settings :  For handling webserver to allow creating and automatic firewaal rule to allow http on port 80.

#### Connected SSH to the virtual machine then installed NGINX web server on it.



## This is the lab link with all the steps mentioned in it.
[Lab Link](https://google.qwiklabs.com/focuses/3563?parent=catalog#step4)
