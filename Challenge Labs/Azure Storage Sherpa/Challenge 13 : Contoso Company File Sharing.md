## Challenge 13 : Contoso Company File Sharing 

### **Contoso Environment:** 

1. The Contoso environment consists of an Azure **subscription** with **contributor** permissions and a pre-provisioned resource group.

1. To access the Azure portal, open a private/incognito window in your browser and navigate to **[Azure Portal](https://portal.azure.com)**.

1. On the **Sign in to Microsoft Azure** tab you will see a login screen, enter the following email/username and then click on **Next**. 
   * Email/Username: <inject key="AzureAdUserEmail"></inject>
   
     ![](media/email1.png "Enter Email")
     
1. Now enter the following password and click on **Sign in**.
   * Password: <inject key="AzureAdUserPassword"></inject>
   
     ![](media/password2.png "Enter Password")
     
1. If you see the pop-up **Stay Signed in?**, click No.

1. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.
   
1. Now you will see Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.

    ![](media/select-rg.png "Resource groups")
   
1. Confirm you have a resource group **Challenge13** present as shown in the below screenshot. You need to use the **Challenge13** resource group through out this challenge.

    ![](media/challenge13-rg.png "Resource groups")

### **Level:** Intermediate 

### **Challenge Objective:**

Contoso Company is looking to migrate their on-premises file server to Azure. Your challenge is to create an Azure File Share and configure access to it.

#### Challenge Tasks and Success criterias:

1. Create an Azure File Share.

1. Configure access to the Azure File Share using Azure Active Directory authentication.

1. Verify that the Azure File Share is accessible by the Contoso Company users.

### Lab Validation

1. After completing the challenge, you need to visit the **Lab Validation (1)** tab and click on the **VALIDATE (2)** button under Actions to perform the validation steps. Verify that you have met the success criteria of the challenge. 

    ![](media/challenge13-v1.png "Validation")

1. If the validation status displays **Success** for all the validation steps, **congratulations!** This means that you have successfully completed the challenge. 

     ![](media/challenge13-v2.png "Validation")
     
1. If the validation status displays **Fail**, **don't worry!** This could mean that you did not perform the challenge correctly.

     ![](media/challenge13-v3.png "Validation")

1. Hover your mouse over the `i` **(1)** icon to see the error message and determine the root cause of the failure. Based on the error message, revisit the challenge as necessary, and redo the validation by clicking on the **VALIDATE (3)** button again.
      
     ![](media/challenge13-v4.png "Validation") 

1. If you are still having trouble, you can reach out to the support team via `labs-support@spektrasystems.com` for further assistance. The support team is available to help you to troubleshoot and resolve any technical issues or validation issues that may arise while the lab environment is live.
