## Challenge 17 : Contoso Disaster Recovery Plan

### **Lab Environment:**

1. This lab consists an Azure subscription with contributor permissions, a pre-configured virtual machine, and a resource group with the name **Challenge17-<inject key="DeploymentID" enableCopy="false"/>**.

2. You need to use the **Challenge17-<inject key="DeploymentID" enableCopy="false"/>** resource group through out the challenge.

3. To access the Azure portal, open a new browser tab, go to **[Azure Portal](https://portal.azure.com)**, and log in with the Azure credentials provided on the **Environment details** page.

### **Level:**  Intermediate 

### **Challenge Objective:**

### Contoso wants to ensure that its critical workloads are protected against any potential disasters. As a Azure Administrator, your team has been tasked with setting up a disaster recovery plan for Contoso's virtual machines. The requirements are as follows:

1.  Create an Azure Site Recovery (ASR) vault to replicate Contoso's virtual machines to a secondary region.
 
1.  Configure replication for a virtual machine to the secondary region.

1.  Test the replication by performing a planned failover of the virtual machine to the secondary region.

1.  Perform a unplanned failover of the virtual machine to the secondary region in the event of a disaster.

### Success Criteria:

1.  The ASR vault is successfully created.

1.  The virtual machine is successfully replicated to the secondary region.

1.  The planned failover operation is successful and the virtual machine is running in the secondary region.

1.  The unplanned failover operation is successful and the virtual machine is running in the secondary region.

1.  The backup reports show that the virtual machine is protected by the ASR vault and is fully recoverable in the event of a disaster.

### Lab Validation

Click on Validate from the **Lab Validation** tab to know if you have completed the challenge successfully.


