## Challenge 2 : Contoso – Securing Access Control

### **Lab Environment:** 
The environmet includes Brand new Azure AD tenant with an account having<br>Global Admin rights.

### **Challenge Objective:**
1. You have a new team member named “John Doe” joining your team 
  as Azure AD Administrator. Their Azure AD account is already created 
  as part of onboarding process. 
  
2. You need to assign them following permissions in most secure 
  fashion.   
   - Azure AD rights
   - Ability to Create Users
   - Ability to Create and Update Groups
   - Ability to invite Guest Users
   - Ability to reset password.
   - Ability to add application registrations.
   - Ability to manage Licenses
3. Azure Subscription
   - Must have Reader access on Azure subscription named “Test-Dev.”
   - Must be able to start/stop Virtual machines hosted in that 
   - subscriptions across all resource groups
   - Must be able to create virtual machines and dependent in a resource group named “John-Doe-Test-RG”

4. You need to ensure following guidelines while completing these 
challenges. 

   - Must follow the principal of least privilege. 
   - Permissions must not be assigned to user accounts directly.
   - Permissions must not be duplicated at various scopes. 
   - Only you, John Doe, admin@cloudlabs and cloudlabs-spn can 
       have access to Azure AD. Any other access must be removed. 
       
  ### Lab Validation

Click on Validate from the **Lab Validation** tab to know if you have completed the challenge successfully.
