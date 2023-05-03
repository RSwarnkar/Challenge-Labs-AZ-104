## Challenge 17 : Contoso Disaster Recovery Plan

### **Contoso Environment:** 

1. The Contoso environment consists of an Azure **subscription** with **contributor** permissions, a pre-configured Contoso virtual machine with the name **Contosovm<inject key="DeploymentID" enableCopy="false"/>**, and a resource group with the name **Challenge17-<inject key="DeploymentID" enableCopy="false"/>**.

1. To access the Azure portal, open a private/incognito window in your browser and navigate to **[Azure Portal](https://portal.azure.com)**.

1. On the **Sign in to Microsoft Azure** tab you will see a login screen, enter the following email/username and then click on **Next**. 
   * Email/Username: <inject key="AzureAdUserEmail"></inject>
   
     ![](media/image7.png "Enter Email")
     
1. Now enter the following password and click on **Sign in**.
   * Password: <inject key="AzureAdUserPassword"></inject>
   
     ![](media/image8.png "Enter Password")
     
1. If you see the pop-up **Stay Signed in?**, click No

1. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.
   
1. Now you will see Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.

    ![](media/select-rg.png "Resource groups")
   
1. Confirm you have a resource group **Challenge17-<inject key="DeploymentID" enableCopy="false"/>** present as shown in the below screenshot. You need to use the **Challenge16-<inject key="DeploymentID" enableCopy="false"/>** resource group through out the challenge.

    ![](media/Rg.png "Resource groups")

### **Level:**  Intermediate 

### **Challenge Objective:**

#### Contoso wants to ensure that its critical workloads are protected against any potential disasters. As an Azure Administrator, you have been tasked with setting up a disaster recovery plan for Contoso's virtual machines. The requirements are as follows:

1.  Create an Azure Site Recovery (ASR) vault to replicate Contoso's virtual machines to a secondary region.
 
1.  Configure replication for a virtual machine to the secondary region.

1.  Test the replication by performing a planned failover of the virtual machine to the secondary region.

1.  Perform a unplanned failover of the virtual machine to the secondary region in the event of a disaster.

### Success Criteria:

1.  The ASR vault is successfully created.

1.  The virtual machine is successfully replicated to the secondary region.

1.  The planned failover operation is successful and the virtual machine is running in the secondary region.

### Lab Validation

1. After completing the challenge, you need to visit the **Lab Validation (1)** tab and click on the **VALIDATE (2)** button under Actions to perform the validation steps. Verify that you have met the success criteria of the challenge. 

    ![](media/validate01.png "Validation")

1. If the validation status displays **Success** for all the validation steps, **congratulations!**. This means that you have successfully completed the challenge. 

     ![](media/validate02.png "Validation")
     
1. If the validation status displays **Fail**, **don't worry!** This could mean that you did not perform the challenge correctly.

     ![](media/validate03.png "Validation")

1. Hover your mouse over the `i` **(1)** icon to see the error message and determine the root cause of the failure. Based on the error message, revisit the challenge as necessary, and redo the validation by clicking on the **VALIDATE (3)** button again.
      
     ![](media/validate04.png "Validation") 

1. If you are still having trouble, you can reach out to the support team via `labs-support@spektrasystems.com` for further assistance. The support team is available to help you to troubleshoot and resolve any technical issues or validation issues that may arise while the lab environment is live.




