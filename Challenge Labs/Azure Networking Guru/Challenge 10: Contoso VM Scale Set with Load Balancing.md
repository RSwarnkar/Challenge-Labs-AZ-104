## Challenge 10: Contoso VM Scale Set with Load Balancing

### **Lab Environment:** 
An Azure subscription with contributor rights.  

### **Level:** Expert 

### **Challenge Objective:**

Contoso has a web application that needs to be deployed across multiple 
virtual machines to handle high traffic loads. Your team's challenge is to 
deploy the web application in a VM scale set in Azure. The web application 
has the following requirements:

1. The application must run on Windows Server 2019 virtual machine using Scale Set. 

1. The virtual machines must have 2 cores and 4 GB RAM

1. The virtual machines must be deployed to the East US region

1. The virtual machines must be part of a virtual network with an address space of 10.0.0.0/16 and a subnet with an address space of 10.0.0.0/24.

1. A load balancer with an inbound NAT rule for port 80

1. A VM scale set with the required configuration.

1. Must be able to survive datacenter level failure. 

  > Your challenge is to deploy the web application in a VM scale set by using an ARM template or Azure Portal.

### Success Criteria:

1. The web application must be accessible from the internet via port 80 and must distribute load. 

1. The VM scale set must have the specified configuration.

1. Load Balancing must be functional.

1. Application must be highly available.

1. The virtual machines must not be directly accessible from the internet via port 80 or any other port. 

### Lab Validation

Click on Validate from the **Lab Validation** tab to know if you have completed the challenge successfully.
