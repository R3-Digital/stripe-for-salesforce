# Charges

The charge object represents a single attempt to move money into your Stripe account. A PaymentIntent confirmation is the most common way to create Charges. The Charge object includes information relating to the amount, currency, customer, and payment method.&#x20;

Using Stripe for Salesforce app to sync your charges from Stripe to Salesforce, keeps track of all charges, transactions and statuses inside your Salesforce org.

## **Charges in the Stripe for Salesforce app**

Charges are read-only records that are provided to the user to highlight every individual transaction.&#x20;

You can find the Charges located under the **Charge** object in the Stripe for Salesforce application. The Charge's list view, provides information such as the ***SCR-xxxxxx*** (*Stripe Charge record name*), the amount, the amount refunded, the transaction description, the status and the charge creation date and time.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2Fog3uyiH1CIo82DpunHeE%2FScreenshot%202023-11-06%20at%2014.46.14.png?alt=media&#x26;token=38faa25b-a40c-49c5-b055-6dbec693ca38" alt=""><figcaption></figcaption></figure></div>

Clicking on the name of one of the charge opens up the record for further inspection.&#x20;

In the record we see the similar information as the list view but also information about the transaction amounts, any further Stripe IDs for reference, and any relevant records of refunds.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2Ftbt7qn5OHNUfhmj0XDCH%2FScreenshot%202023-11-06%20at%2014.46.39.png?alt=media&#x26;token=75b332fd-805b-4ff1-86b4-0b572792239c" alt=""><figcaption></figcaption></figure></div>

## Sync Charges from Stripe

If you need to manually sync your payment intents from Stripe, without waiting for the webhooks to automatically complete that, you will need to navigate to the charge record and locate and click the action button **Charge**. This will pull the data from Stripe to your Salesforce org.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FYomoo5BJC6R0s2YkI69C%2FScreenshot%202023-11-06%20at%2014.46.39.png?alt=media&#x26;token=1fbb30a4-eb32-4a11-8676-9809294db648" alt=""><figcaption></figcaption></figure></div>

## Charges Statuses

In the table below you will see a list of statuses used by the Stripe for Salesforce application and Stripe regarding charges, as well as a description of the status.&#x20;

| Charge Status | Description                                                                                                                                                                                                                                     |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `Succeeded`   | <p>A charge status of s<code>ucceeded</code> occurs when a transaction instance has added funds to your account.<br><br>Or refunds, once the refund has been processed and left your account and reached the customer's payment instrument.</p> |
| `Pending`     | A charge status of `pending` occurs when there is a delay to the capturing of funds or releasing the funds for refunds.                                                                                                                         |
| `Failed`      | A charge of status of `failed` occurs when the transaction has failed, been cancelled or interrupted.                                                                                                                                           |
