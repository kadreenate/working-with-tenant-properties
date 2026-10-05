# working-with-tenant-properties
Lab 2 on [Microsoft Entra ID](entra.microsoft.com)

**Step 1: Create the custom domain**

Log in to Microsoft Entra ID as a Global administrator. In the left navigation, under Entra ID, select Domain names. In the Custom domain name page, select + Add custom domain. In the Custom domain name field, create a custom subdomain for the lab tenant by putting sales in front of the onmicrosoft.com domain name. Note: After entering an .onmicrosoft.com domain, a restriction message appears indicating that managing onmicrosoft.com domains is restricted in Microsoft Entra ID. Select the Microsoft 365 Admin Center link shown in the message to complete this action: 

<img width="1198" height="646" alt="image" src="https://github.com/user-attachments/assets/2159c7d9-fff3-41b5-bbe5-240f7a274e10" />

On the Microsoft 365 Admin Center, in the Domains page, select Add domain to add the subdomain. Enter the subdomain name sales.tenantname.onmicrosoft.com into the dialog. Remember to replace tenantname with the name of your tenant. Select the "Use this domain" button at the bottom of the screen.

<img width="1591" height="1120" alt="image" src="https://github.com/user-attachments/assets/fa2c7d9e-45e3-4089-bb4a-a160a184c92f" />

Select the Close button when the next screen opens up. For this lab, I didn't set up the DNS.

<img width="1412" height="853" alt="image" src="https://github.com/user-attachments/assets/eb526e03-8fe5-4c8c-8fdd-860a986451bf" />

**Step 2: Changing the tenant display name**

In the left navigation, select Overview under the Entra ID menu, then select Properties. Change the Tenant Properties for the Name and Technical contact in the dialog.
Name: Contoso Marketing; Technical contact: your Global admin account. Select Save to update the tenant properties, as shown below: 

<img width="1198" height="887" alt="image" src="https://github.com/user-attachments/assets/3d932615-71e9-43c1-9337-a9f73c707ef2" />

You will notice the name change immediately after the save is complete. To copy the tenant ID, go to Overview under Entra ID on the left menu > Properties > Tenant ID

**Step 3: Adding internal policies and privacy info**

Microsoft strongly recommends adding global privacy contact and organization's privacy statement, so internal employees and external guests can review policies. To add privacy info, go to Properties and fill the Global privacy contact and Privacy statement URL, as shown in the image below: 

<img width="1176" height="573" alt="image" src="https://github.com/user-attachments/assets/aeb80695-d245-49d6-ac75-0d4e20ea5a94" />

To check your privacy statement, go to Microsoft Entra admin dashboard (on the upper right corner, click on your username and select "view account" from the dropdown). 

On the left hand menu, select Data and Privacy under My Account > Under Organization's notice select the View item next to Contoso Marketing organizational privacy statement. A new browser tab will open with the Privacy PDF file you linked to displayed.
