# Module 1 - Lab 2 - Exercise 2 - Assign Directory Roles


### Task 1:  Make a user eligible for a role


In the following task you will make  a user eligible for an Azure AD directory role.


1.  Sign in to Azure portal

1.  In the Azure Portal, click **All services** and search for and select **Azure AD Privileged Identity Management**.

     ![Screenshot](../Media/Module-1/a52510a3-b2a2-4b21-91a8-ee7f34b39a72.png)

1.  Select **Azure AD Roles**. If this is option is still greyed you may need to refresh your browser.

     ![Screenshot](../Media/Module-1/ed36b086-ae87-409f-af33-66848b3df1b9.png)
 
1.  Click **Sign up PIM for Azure AD Roles**.

     ![Screenshot](../Media/Module-1/fea44542-ff4b-4627-9700-462d39d55e76.png)


1.  Click **Sign Up** and click **Yes**.

     ![Screenshot](../Media/Module-1/d617900b-a68b-452c-867f-3f27c9e48426.png)

1.  When processing is complete **Refresh the Broswer**.

1.  Click **Roles**.

     ![Screenshot](../Media/Module-1/dde2c301-2f2e-4318-a96a-a17f3ac3b27a.png)


1.  Click **Add member** to open Add managed members.

     ![Screenshot](../Media/Module-1/12749cdd-3fcc-46c7-a544-07aabbdd84d1.png)

1.  Click **Select a role**, and click **Billing Administrator** and then click  **Select**.

     ![Screenshot](../Media/Module-1/42b809bd-9381-4d52-ae98-cb62a4c21730.png)

1.  Click **Select members**, select **Patti Fernandez** and then click **Select**.

     ![Screenshot](../Media/Module-1/923c874d-67ca-4753-9831-c801ab596ad8.png)

1.  In Add managed members, click **OK** to add the user to the role.

1.  Review the added member

     ![Screenshot](../Media/patti_billing.png)

1.  When the role is assigned, the user you selected will appear in the members list as **Eligible** for the role.


### Task 2: Make a role assignment permanent


By default, new users are only eligible for a directory role. Follow these steps if you want to make a role assignment permanent.



1.  In the Azure Portal, click **All services** and search for and select **Azure AD Privileged Identity Management**.

     ![Screenshot](../Media/Module-1/a52510a3-b2a2-4b21-91a8-ee7f34b39a72.png)

1.  Click **Azure AD roles**.

     ![Screenshot](../Media/Module-1/9914545c-313f-4c9a-84a5-d7c383c7ee37.png)

1.  Click **Members**.

     ![Screenshot](../Media/Module-1/2aedf4ab-e829-4ce3-afcc-b77048125bf9.png)

1.  Click the **Eligible** role that you want to make permanent.

     ![Screenshot](../Media/patti_billing.png)
 
1.  Click **More** and then click **Make permanent**.

     ![Screenshot](../Media/Patt_permanent.png)
 

**Results**: The role is now listed as **permanent** for Patti Fernandez.


### Task 3: Remove a user from a role


You can remove users from role assignments, but make sure there is always at least one user who is a permanent Global Administrator.



1.  In the Azure Portal, click **All services** and search for and select **Azure AD Privileged Identity Management**.

     ![Screenshot](../Media/Module-1/a52510a3-b2a2-4b21-91a8-ee7f34b39a72.png)

1.  Click **Azure AD roles**.

     ![Screenshot](../Media/Module-1/9914545c-313f-4c9a-84a5-d7c383c7ee37.png)

1.  Click **Members**.

     ![Screenshot](../Media/Module-1/2aedf4ab-e829-4ce3-afcc-b77048125bf9.png)

1.  Click a role assignment you want to remove in this case Patti Fernandez as Billing Administrator.

     ![Screenshot](../Media/Patti_remove.png)
 
1.  Click **More** and then click **Remove**.

     ![Screenshot](../Media/Remove_button.png)
 
1.  In the message that asks you to confirm, click **Yes**. The role assignment will be removed.


# Continue to exercise 3



