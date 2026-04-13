# Customer accounts

A customer record in the Stripe for Salesforce app represents your customers. This record can be used to create, update, edit and track customer information.

## **Create a new customer record in the Stripe app and send data**

Here we will discuss how to add a new customer record and send the record information from Salesforce to Stripe.

To create a **New** customer record in the Stripe for Salesforce app. First go to the Account tab and find the **New** action button, select the Person Account record type you have configured. Then fill in the information form fields and click save.

![CustomerAccounts1](assets\Customer-Accounts1.png)

![CustomerAccounts2](assets\Customer-Accounts2.png)
*New Person Account record form fields*

Your page will refresh with the newly created customer record, where you can see all the information you previously added. The Stripe for Salesforce application will then sync with Stripe to create and send the customer details.

![CustomerAccounts3](assets\Customer-Accounts3.png)
*New customer record*

## **Sync patient data to Stripe**

Here we will discuss how to send an existing customer record from Salesforce to Stripe.&#x20;

This is normally done automatically through the integration, but if you need to do this manually please follow these instructions.

To send this customer information to Stripe, click on the **Send Customer** action button. And, if you want to pull any data manually from Stripe, click on the **Sync Stripe.** Once the request has been sent to Stripe or from Stripe, you will then be shown a completion message once the flow is complete.

![CustomerAccounts4](assets\Customer-Accounts4.png)
*Customer record > Send customer data to Stripe* 

![CustomerAccounts5](assets\Customer-Accounts5.png)
*Customer record > Sync customer data from Stripe*

![CustomerAccounts6](assets\Customer-Accounts6.png)
*Customer record > send data to stripe completion message*

## **Verify that patients are available in Stripe.**

Here we will discuss how to verify the customer record has synced correctly with Stripe.

Go to your customers area on Stripe. Next, search for the customer you need.

![CustomerAccounts7](assets\Customer-Accounts7.png)
*Stripe Dashboard > Customers*

Go to the left hand side of the window and view the details dropdown. Here you should see a customer ID number and this will match the record you see in Salesforce.

![CustomerAccounts8](assets\Customer-Accounts8.png)
*Stripe Dashboard > Customers > Details: Stripe ID*

![CustomerAccounts9](assets\Customer-Accounts9.png)
*Customer record > Stripe ID*
