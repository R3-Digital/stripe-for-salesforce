# Payment methods

In Stripe payment methods are how customers pay for goods or services with Stripe. Stripe supports a range of different payment methods. In the Stripe App for Salesforce, Payment Methods are mostly read-only data related to Accounts.&#x20;

When a customer enters their payment information i.e., card number, expiry date and billing information, this is stored in Stripe. The payment method is a record synced from Stripe and held against the account record, alongside other transactional data.&#x20;

## Payment Method record

In Stripe for Salesforce, we create a record of the customer payment method and any changes to the information that the customer has entered during the payment process, for example, if a customer has changed their card when next paying an invoice or adds a new billing address to their next payment and this is overwritten in the record and captured.&#x20;

You can find your customer's payment method records by navigating to the **Payment Method** object.

![PaymentMethods1](assets\Payment-Methods1.png)

![PaymentMethods2](assets\Payment-Methods2.png)

As you can see from the example provided the Payment Method record provides an oversight to  transactional data such as payment method type, card brand, the last 4 digits of the payment card.&#x20;

Other related information such as PaymentIntents and Charges made with this payment method can be viewed from the Payment method record.  These records are intrinsically linked to the Customer Accounts, PaymentIntents and charges to capture accurate transactional data.
