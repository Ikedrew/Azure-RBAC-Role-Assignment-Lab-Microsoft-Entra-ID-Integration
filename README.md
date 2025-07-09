# Azure-RBAC-Role-Assignment-Lab-Microsoft-Entra-ID-Integration

📌 Objective:
Demonstrate role-based access control (RBAC) in Azure by assigning the Reader role to a user created in Microsoft Entra ID, and verifying limited access permissions via portal login.

🛠️ Tools Used:
Azure Portal (Free Tier)
Microsoft Entra ID (Default Tenant)
Resource Groups
Access Control (IAM)

🪜 Steps Performed:
Created a Resource Group named Test-RG-RBAC.
Created a new Entra ID user named TestUser1.
Assigned the "Reader" role to TestUser1 at the resource group level using Azure RBAC.
Logged in as TestUser1 in a private browser to verify:
✅ Read-only visibility to the resource group.
❌ Blocked access to create or modify resources.
Confirmed assigned role using the “Check Access” feature in the IAM tab.

🖼️ Screenshots:
Resource Group Created
![image alt](https://github.com/Ikedrew/Azure-RBAC-Role-Assignment-Lab-Microsoft-Entra-ID-Integration/blob/main/README.md)
Create New User For Role Assignment
![image alt](https://github.com/Ikedrew/Azure-RBAC-Role-Assignment-Lab-Microsoft-Entra-ID-Integration/blob/main/Create%20a%20resource%20group%20-%20Microsoft%20Azure%20and%206%20more%20pages%20-%20Personal%20-%20Microsoft%E2%80%8B%20Edge%2009_07_2025%2001_54_16.png?raw=true)


RBAC Role Assigned – IAM tab with Reader role and TestUser1 selected.

Portal View as TestUser1 – read-only view.
Access Denied Attempt – error when trying to create/edit/delete.

💡 Key Takeaways:
RBAC enables precise access control without sharing privileged roles.
Reader role is ideal for audit, monitoring, or trainee accounts.
IAM + Entra ID integration makes it easy to apply least-privilege policies.
