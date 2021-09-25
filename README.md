Create a Test Account
-------------
After following the instructions below, a button should appear in the List View of the Accounts module. Clicking this button will generate a new random test account in the Accounts module.


How To Use
--------
1) In Zoho CRM, navigate to *Settings -> Modules and Fields -> Accounts -> Links and Button Tab*. 

2) Click **New Button**. Name the button, then select **List View-Utility Menu** from the *Where would you like to place the button?* pick list.

3) Select **Writing Funtion** from the *What action would you like the button to perform?* pick list. 

4) Name your function. Once complete, this should naviate to the Deluge editor.

5) Open the .dg file in this repo, copy the contents, and paste it into the editor. No arguments are needed. 

6) Ensure the account_map variable contains the correct API names for your particular Account module. The fields included are Account_Name, Billing_Street, Billing_City, Billing_State, Billing_Code, Billing_Country, Website, Phone, Account_Type.

6) Click **Save** in both the editor, then in the *Create Your Button* screen.


Technologies
---------
- Deluge
