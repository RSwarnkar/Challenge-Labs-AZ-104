## Challenge 4 : Contoso Web Application Deployment

### **Lab Environment:** 

1. This lab consists of an Azure subscription and a contributor-permitted resource group called **Challenge4-SUFFIX**.

2. You need to use the **Challenge4-SUFFIX** resource group through out the challenge.

3. To access the Azure portal, open a new browser tab, go to **[Azure Portal](https://portal.azure.com)**, and log in with the Azure credentials provided on the **Environment details** page. 


### **Level:** Advanced 

### **Challenge Objective:**

#### Contoso is a web application development company that needs to deploy a new web application in Azure. The web application has the following requirements:

1. The application must run on a Windows Server 2019 virtual machine.

1. The virtual machine must have 2 cores and 8 GB RAM.

1. The virtual machine must have a data disk with a size of 128 GB.

1. The virtual machine must be deployed to the East US region.

1. The virtual machine must be part of a virtual network with an address space of 10.0.0.0/16 and a subnet with an address space of 10.0.0.0/24.

1. The virtual machine must be accessible from the internet via port 80.
 
1. The Virtual machine must be part of an Availability set with 3 fault domain and 10 update to plan for future high availability. 

1. IIS with default page must be accessible.

#### Your team's challenge is to deploy this web application in Azure by using an ARM template/Azure Portal. This should include the following resources:

1. A virtual network along with other required network depdencies. 

1. A virtual machine with the specified configuration.

1. A network security group with required rules.

1. Any other dependent Azure resource, scripts etc required to meet the 
goal.

### Success Criteria:

1. The web application must be accessible from the internet via port 80.

1. The virtual machine must have the specified configuration.

1. The virtual machine must be deployed using ARM template. 

1. There should not be any other port open except required. 

1. IIS must be installed using VM Extension.

### Lab Validation

Click on Validate from the **Lab Validation** tab to know if you have completed the challenge successfully.
