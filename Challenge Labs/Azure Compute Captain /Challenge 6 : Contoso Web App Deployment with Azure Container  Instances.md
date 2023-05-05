## Challenge 6 : Contoso Web App Deployment with Azure Container Instances

### **Contoso Environment:** 

1. The Contoso environment consists of an Azure **subscription** with **contributor** permissions and a pre-provisioned resource group with the name **Challenge6-<inject key="DeploymentID" enableCopy="false"/>**.

1. To access the Azure portal, open a private/incognito window in your browser and navigate to **[Azure Portal](https://portal.azure.com)**.

1. On the **Sign in to Microsoft Azure** tab you will see a login screen, enter the following email/username and then click on **Next**. 
   * Email/Username: <inject key="AzureAdUserEmail"></inject>
   
     ![](media/image7.png "Enter Email")
     
1. Now enter the following password and click on **Sign in**.
   * Password: <inject key="AzureAdUserPassword"></inject>
   
     ![](media/image8.png "Enter Password")
     
1. If you see the pop-up **Stay Signed in?** click No.

1. If you see the pop-up **You have free Azure Advisor recommendations!**, close the window to continue the lab.

1. If a **Welcome to Microsoft Azure** popup window appears, click **Maybe Later** to skip the tour.
   
1. Now you will see Azure Portal Dashboard, click on **Resource groups** from the Navigate panel to see the resource groups.

    ![](media/select-rg.png "Resource groups")
   
1. Confirm you have a resource group **Challenge6-<inject key="DeploymentID" enableCopy="false"/>** present as shown in the below screenshot. You need to use the **Challenge6-<inject key="DeploymentID" enableCopy="false"/>** resource group through out the challenge.

    ![](media/challenge06-rg.png "Resource groups")

### **Level:** Intermediate 

### **Challenge Objective:**

Contoso wants to deploy a web application using Azure Container Instances. The application should be accessible over the internet, and create an email notification alert based on Memory usage.

### Success Criteria:

1. The web application is accessible over the internet.

1. The email notification alert should be configured based on Memory usage of the container instance.

1. The public IP address and DNS name are configured correctly.

1. The web application works as expected.

1. The application must use default nginx as web server and use the public container image. 

### Lab Validation

1. After completing the challenge, you need to visit the **Lab Validation (1)** tab and click on the **VALIDATE (2)** button under Actions to perform the validation steps. Verify that you have met the success criteria of the challenge. 

    ![](media/challenge06-v1.png "Validation")

1. If the validation status displays **Success** for all the validation steps, **congratulations!** This means that you have successfully completed the challenge. 

     ![](media/challenge06-v2.png "Validation")
     
1. If the validation status displays **Fail**, **don't worry!** This could mean that you did not perform the challenge correctly.

     ![](media/challenge06-v3.png "Validation")

1. Hover your mouse over the `i` **(1)** icon to see the error message and determine the root cause of the failure. Based on the error message, revisit the challenge as necessary, and redo the validation by clicking on the **VALIDATE (3)** button again.
      
     ![](media/challenge06-v4.png "Validation") 

1. If you are still having trouble, you can reach out to the support team via `labs-support@spektrasystems.com` for further assistance. The support team is available to help you to troubleshoot and resolve any technical issues or validation issues that may arise while the lab environment is live.
