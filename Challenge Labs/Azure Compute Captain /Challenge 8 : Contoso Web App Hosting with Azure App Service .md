## Challenge 8 : Contoso Web App Hosting with Azure App Service

### **Lab Environment:** 
An Azure subscription with contributor rights and sample web app code.

### **Level:** Advanced 

### **Challenge Objective:**

Contoso E-commerce is a company that sells products online. They have a 
website hosted on an on-premises server, but they want to move it to Azure 
to take advantage of the cloud benefits. As an Azure administrator, your task 
is to migrate the website to Azure and make sure it is secure and scalable.
Your development has provided you the required application code and have 
tasked you to deploy this on Azure using PaaS Services.

#### Requirements:

1. Create an App Service plan named "ContosoWebPlan" in the West US 
region with a Standard tier and one instance.

1. Configure scaling settings in the App Service plan to automatically scale up to three instances when the CPU usage is above 70% for five minutes.

1. Create an App Service named "ContosoWebApp" in the same App Service plan with the following settings:
   - Runtime stack: .NET
   - Operating system: Windows
   - Region: West US

1. Deploy the Web Application Code to the newly created app service, by following FTP method. 

1. Secure the App Service by:
   - Enabling HTTPS only traffic

1. Configure backup for the App Service to back up the web app daily at 1:00 AM to a storage account named "ContosoBackupunqiuestring".

### Success Criteria:

1. App Service plan "ContosoPlan" is created with the specified settings.

1. Scaling settings are configured as described and tested by simulating high CPU usage.

1. App Service "ContosoWebApp" is created with the specified settings.

1. Custom domain names are configured as described and the website is accessible using both domain names.

1. HTTPS only traffic is enabled.

1. Backup is configured as described, and a backup is successfully created and stored in the "ContosoBackup" storage account.

### Lab Validation

Click on Validate from the **Lab Validation** tab to know if you have completed the challenge successfully.
