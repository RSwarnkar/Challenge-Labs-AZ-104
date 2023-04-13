## Challenge 4 : Contoso Web Application Deployment

### **Lab Environment:** 
Brand new Azure AD tenant with an Azure Subscription with Contributor rights.  

### **Level:** Advanced 

### **Challenge Objective:**

#### Contoso is a web application development company that needs to deploy a new web application in Azure. The web application has the following requirements:

• The application must run on a Windows Server 2019 virtual machine.

• The virtual machine must have 2 cores and 8 GB RAM.

• The virtual machine must have a data disk with a size of 128 GB.

• The virtual machine must be deployed to the East US region.

• The virtual machine must be part of a virtual network with an address space of 10.0.0.0/16 and a subnet with an address space of 10.0.0.0/24.

• The virtual machine must be accessible from the internet via port 80.
 
• The Virtual machine must be part of an Availability set with 3 fault domain and 10 update to plan for future high availability. 

• IIS with default page must be accessible.

#### Your team's challenge is to deploy this web application in Azure by using an ARM template. The ARM template should include the following resources:

• A virtual network along with other required network depdencies. 

• A virtual machine with the specified configuration.

• A network security group with required rules.

• Any other dependent Azure resource, scripts etc required to meet the 
goal.

### Success Criteria:

• The web application must be accessible from the internet via port 80.

• The virtual machine must have the specified configuration.

• The virtual machine must be deployed using ARM template. 

• There should not be any other port open except required. 

• IIS must be installed using VM Extension.

### Lab Validation

Click on Validate from the **Lab Validation** tab to know if you have completed the challenge successfully.
