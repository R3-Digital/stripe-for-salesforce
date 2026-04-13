# Payment methods

In Stripe payment methods are how customers pay for goods or services with Stripe. Stripe supports a range of different payment methods. In the Stripe App for Salesforce, Payment Methods are mostly read-only data related to Accounts.&#x20;

When a customer enters their payment information i.e., card number, expiry date and billing information, this is stored in Stripe. The payment method is a record synced from Stripe and held against the account record, alongside other transactional data.&#x20;

## Payment Method record

In Stripe for Salesforce, we create a record of the customer payment method and any changes to the information that the customer has entered during the payment process, for example, if a customer has changed their card when next paying an invoice or adds a new billing address to their next payment and this is overwritten in the record and captured.&#x20;

You can find your customer's payment method records by navigating to the **Payment Method** object.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FGUYGqLtLlueANIgXsuF5%2FScreenshot%202023-11-03%20at%2012.52.03%20copy.png?alt=media&#x26;token=ccbf3379-f857-4f74-a816-6b70eb7cc9cf" alt=""><figcaption></figcaption></figure></div>

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FhC48nqQ1FHvyAG36V8mW%2FScreenshot%202023-11-06%20at%2014.45.18.png?alt=media&#x26;token=571ae8e0-c0c2-4a53-9a1a-15ec4ba621af" alt=""><figcaption></figcaption></figure></div>

As you can see from the example provided the Payment Method record provides an oversight to  transactional data such as payment method type, card brand, the last 4 digits of the payment card.&#x20;

Other related information such as PaymentIntents and Charges made with this payment method can be viewed from the Payment method record.  These records are intrinsically linked to the Customer Accounts, PaymentIntents and charges to capture accurate transactional data.
