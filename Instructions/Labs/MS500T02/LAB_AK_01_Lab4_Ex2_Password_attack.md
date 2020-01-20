# Module 3 - Lab 4 - Exercise 2 - Conduct password attacks


Holly Dickson is concerned that some users in her organization may require education about secure password strategies.  In this lab you will use the Microsoft 365 Attack simulator to determine your users' susceptibility to password attacks.


### Task 1: Configure and launch a Brute Force attack

1.  Go to the Office 365 Security & Compliance center (https://protection.office.com) and login as Holly Dickson.

2.  Click **Threat management**, and then click **Attack simulator**.

3.  In the Brute Force Password (Dictionary Attack) area select the **Launch Attack** button.

4.  Name the campaign *Brute Force Test* and select **Next**.

5.  In the Target users tab click the **Address Book** button and select Lynne Robbins and then select **Next**.

6.  In the Choose attack settings area enter Pa55w.rd in The password(s) to use in the attack field and press the enter key. You can enter more than one password here if you like. We are entering Lynne's actual password on purpose. Once you have added the password select **Next**.

		**Note**: Ordinarily you would have a file that contains a list of commonly used passwords for your organization.  You would upload that file using the Upload button. 

7.  In the Confirm area select **Finish**.
    

### Task 2: Review the results

3. Go back to the Attack Simulator area of the Office 365 Security and Compliance portal.

4. In the Brute Force Password (Dictionary Attack) area click **Attack Details**.

5. The report lists the current results of the campaign including number of users targeted and success rate.  Since we entered Lynne's password the report shows "1 of 1 users compromised".
   

### Task 3: Configure and launch a Password Spray attack

1.  Go to the Office 365 Security & Compliance center (https://protection.office.com).

2.  Select **Threat management**, and then select **Attack simulator**.

3.  In the Password Spray Attack area select the **Launch Attack** button. 

4.  Name the campaign *Password Spray Test* and select **Next**.

5.  In the Target users tab click the **Address Book** button and select Lynne Robbins and select **Next**.

6.  In the Choose attack settings area type Pa55w.rd in The password(s) to use in the attack and then select **Next**.

7.  In the Confirm area select **Finish**.


### Task 4: Review the results

3. Go back to the Attack Simulator area of the Office 365 Security and Compliance portal.

4. In the Password Spray Attack area click **Attack Details**.

5. The report lists the current results of the campaign including number of users compromised.  Notice against since we entered Lynne's actual password it lists her as account as being compromised by the password spray.

 # End lab