# Customer accounts

A customer record in the Stripe for Salesforce app represents your customers. This record can be used to create, update, edit and track customer information.

## **Create a new customer record in the Stripe app and send data**

Here we will discuss how to add a new customer record and send the record information from Salesforce to Stripe.

To create a **New** customer record in the Stripe for Salesforce app. First go to the Account tab and find the **New** action button, select the Person Account record type you have configured. Then fill in the information form fields and click save.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2Fglkkxgf66Faur0xMXFeo%2FCustomer_Accounts_NEW1.png?alt=media&#x26;token=bcd4058c-a520-434d-b0fc-6e3c80a5734a" alt=""><figcaption><p>Account object > Account records list view > New action button </p></figcaption></figure></div>

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2F6v9umuy0hRguYF5mpweo%2FCustomer_Accounts_NEW2.png?alt=media&#x26;token=4c3cdeee-0789-4778-8e86-3d58df9f6640" alt=""><figcaption><p>New Person Account record form fields</p></figcaption></figure></div>

Your page will refresh with the newly created customer record, where you can see all the information you previously added. The Stripe for Salesforce application will then sync with Stripe to create and send the customer details.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FnX8K4xBA9de6upTwBtxc%2FCustomer_Account_NEW3.png?alt=media&#x26;token=f6de2d8f-d6f1-4128-8b1c-742424d05a46" alt=""><figcaption><p>New customer record</p></figcaption></figure></div>

## **Sync patient data to Stripe**

Here we will discuss how to send an existing customer record from Salesforce to Stripe.&#x20;

This is normally done automatically through the integration, but if you need to do this manually please follow these instructions.

To send this customer information to Stripe, click on the **Send Customer** action button. And, if you want to pull any data manually from Stripe, click on the **Sync Stripe.** Once the request has been sent to Stripe or from Stripe, you will then be shown a completion message once the flow is complete.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FwhtVnMVfGzt0T99M6jKo%2FCustomer_Account_NEW4-SendDataToStripe.png?alt=media&#x26;token=d7c1f22a-7289-419d-bc27-4c7529009f7c" alt=""><figcaption><p>Customer record > Send customer data to Stripe </p></figcaption></figure></div>

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FHFvBveGD6UUoLpAUW910%2FScreenshot%202023-11-07%20at%2009.42.58.png?alt=media&#x26;token=63d63404-542a-4b41-893f-b4a12f22beb3" alt=""><figcaption><p>Customer record > Sync customer data from Stripe</p></figcaption></figure></div>

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FHABI2ROy3dXdyWNoPCBv%2FCustomer_Account_NEW5-Senddatatostripeflownotif.png?alt=media&#x26;token=5ff119c5-2670-4c72-bcc7-5db4a87419c6" alt=""><figcaption><p>Customer record > send data to stripe completion message</p></figcaption></figure></div>

## **Verify that patients are available in Stripe.**

Here we will discuss how to verify the customer record has synced correctly with Stripe.

Go to your customers area on Stripe. Next, search for the customer you need.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FLAHjVrEMJHvI5KzdgH1b%2FCustomer_Account_Customer_syncing1.png?alt=media&#x26;token=d93ee8c4-879f-41b4-891d-670d3819858a" alt=""><figcaption><p>Stripe Dashboard > Customers</p></figcaption></figure></div>

Go to the left hand side of the window and view the details dropdown. Here you should see a customer ID number and this will match the record you see in Salesforce.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FHLcBSwcMMbWvBk8XICwD%2FScreenshot%202023-11-02%20at%2017.19.21.png?alt=media&#x26;token=56ab4e4c-7894-418c-86e1-861dfedf9ef3" alt=""><figcaption><p>Stripe Dashboard > Customers > Details: Stripe ID </p></figcaption></figure></div>

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2Fztm5DlcWygSLeVh9Ld6P%2FScreenshot%202023-11-07%20at%2009.46.18.png?alt=media&#x26;token=9f158024-b1a2-49d1-8ac2-1e169da9887b" alt=""><figcaption><p>Customer record > Stripe ID</p></figcaption></figure></div>
