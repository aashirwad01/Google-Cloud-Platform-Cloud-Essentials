# Getting Started with Cloud Shell and gcloud
This is lab 2(Getting Started with Cloud Shell and gcloud) of quest create and manage cloud resources we are allocated 45 minutes to complete the lab.

## Understanding the terminologies

- Virtual Machine : In simple terms we can use VM's to have more thn one os on a single computer. OS within an OS. It is also used to provide computing services and storage options to anyone over cloud . So putting in perspective of cloud VM provide you an option to use a High end processor say I9(very bad example but bear it) over any machine say even if you have a Pentium processor , one can harness the power of cloud , internet and VM to get Computer with any linux image OS.
- Google Cloud Platform : It is public cloud computing services offred by Google . Like AWS and Azure another leader in IAAS services and PAAS services. Compute engine which provides virtual machine is IAAS while App engine is PAAS.
- When to use IAAS vs PAAS : IAAS is used if organization has an inhouse made app and simply need s infrastructure to host it. While PAAS is used to streamline deployment and development using services provided.
- Cloud shell : Interactive environment from google to manage cloud easily from the Web Browser.

## What did i do ?
Configured my environment to have default Zone and Project Id then created a VM instance using command line interface of Google Console of GCP platform . Gave it
- Name : Name of the VM instance

[GCP regions and zones](https://cloud.google.com/compute/docs/zones)

- series : Name of processor series
- machine type : CPU RAM 
- boot disk type : Harddisk space with Debian Server
- gcloud compute allows you to manage your Compute Engine resources in a format that's simpler than the Compute Engine API.

- instances create creates a new instance.

- gcelab2 is the name of the VM.

- The --machine-type flag specifies the machine type as n1-standard-2.

- The --zone flag specifies where the VM is created.



gcloud compute instances create gcelab2 --machine-type n1-standard-2 --zone $ZONE

#### Connected SSH to the virtual machine and checked it's status.



## This is the lab link with all the steps mentioned in it.
[Lab Link](https://google.qwiklabs.com/focuses/563?parent=catalog)
