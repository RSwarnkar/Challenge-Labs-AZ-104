## Challenge 9 : Contoso Virtual Network Implementation & Security

### **Lab Environment:** 
An Azure subscription with contributor rights. 

### **Level:** Intermediate 

### **Challenge Objective:**

#### Requirement:
Contoso Corp is a multinational company that specializes in the 
development of cutting-edge technologies. The company has recently 
expanded its operations to the cloud and has migrated several critical 
applications to Azure. As a result, they need a highly secure and resilient 
virtual network infrastructure to support their cloud-based applications.

#### Challenge:
Your task is to design and configure a highly secure and resilient virtual 
network infrastructure for Contoso Corp. The virtual network should have the 
following requirements:

1. The virtual network named “primary-vnet” in East US region should be 
divided into two subnets: one for the primary-application and another 
for the primary-database. The application subnet should have a CIDR 
block of 10.0.0.0/24, and the database subnet should have a CIDR 
block of 10.0.1.0/24. The VNET CIDR must support adding atleast 60 
subnets in future with /24 range.

1. The virtual network named “secondary-vnet” in West US region should 
be divided into two subnets: one for the secondary-application and 
another for the secondary-database. The application subnet should 
have a CIDR block of 10.20.0.0/24, and the database subnet should 
have a CIDR block of 10.20.1.0/24. The VNET CIDR must support adding 
atleast 60 subnets in future with /24 range. 

1. Virtual machines between secondary-database and primary-database
must be able to communicate with each other over private IPs 
without going through public IP address. 

1. Virtual machines in primary-vnet must not be allowing RDP 3389 port 
from any source. You must implement an alternate method for RDP 
which does not require exposing RDP 3389 port, both internally and 
externally. 

1. The virtual machines in the primary-application subnet must be able 
to access a blog storage account named “appstorageuniquestring” 
securely by private network without going through internet. 

1. The virtual network should have a network security group (NSG) 
associated with the all subnets. The NSG should have the any rules 
except than required for this setup.

### Success Criteria:
1. The virtual network should be configured according to the requirements listed above.

1. The virtual network peering should be established successfully, and the primary-vnet should be accessible from the secondary-vnet

1. Virtual machines in the application subnet should be accessible via RDP through the Bastion host.

1. The private endpoint for Azure Storage should be accessible from the virtual machines in the application subnet.

1. The NSG should be configured correctly, with minimum rules.

 > All above listed requirements must be met.

### Lab Validation

Click on Validate from the **Lab Validation** tab to know if you have completed the challenge successfully.
