# Refunds

In the Stripe for Salesforce app, refunds can be sent to customers directly from a Salesforce org. Users are able to generate and send refunds to customers, alongside update the payment intents and charge records. The updates to this workflow will then also be synced with Stripe.

## Refund generation

To generate a refund to a customer, the user must first navigate to the Payment intent tab. From here the user will need to select a payment intent record from which the refund will be sent.&#x20;

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FzZBuX4KSpzp9bOT1PaKY%2FScreenshot%202023-11-09%20at%2009.56.23.png?alt=media&#x26;token=81c057e6-f9f4-498e-8e15-4efe11b63b2e" alt=""><figcaption></figcaption></figure></div>

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FISkRBeAEk4alclCyyDny%2FScreenshot%202023-11-09%20at%2009.56.38.png?alt=media&#x26;token=4c4e27b0-3c56-4816-a2f9-d48349ebf013" alt=""><figcaption></figcaption></figure></div>

Next locate and click the **Refund** action button on the page layout.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FziYSFmzJUv7c2tdxpWfs%2FScreenshot%202023-11-09%20at%2009.56.38%20copy.png?alt=media&#x26;token=9aeba7dd-f640-41dd-9b66-248bba4d7065" alt=""><figcaption></figcaption></figure></div>

Clicking the refund action button opens a modal window in Salesforce. The amount is populated from the succeeded payment from the customer - this is editable by clicking into the form field and changing the numerical amount.&#x20;

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2F92IlRokpwtgeF5PwmCbA%2FScreenshot%202023-11-09%20at%2009.56.45.png?alt=media&#x26;token=d5cdeff5-17a6-4d9f-b79c-b36af52aeb85" alt=""><figcaption></figcaption></figure></div>

Next we need to select a reason for the refund, this is done by clicking into the reason form field. One the reason has been confirmed, click next and the refund will be processed.&#x20;

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FU9T08twhdIh7dn9pi8pO%2FScreenshot%202023-11-09%20at%2009.56.51.png?alt=media&#x26;token=04790ab9-1680-45ee-b3f9-a9de82ff1d8f" alt=""><figcaption></figcaption></figure></div>

Coming back to the payment intent record, we can see the refund is succeeded.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FE99uZgdLVYl0RG1QCc3q%2FScreenshot%202023-11-09%20at%2009.57.05.png?alt=media&#x26;token=ac23f053-0e29-4c53-b795-1a3b12070914" alt=""><figcaption></figcaption></figure></div>

## Verifying Refunds in the Stripe Dashboard

To verify the status of the refund in the Stripe for Salesforce application you can go to your Stripe Dashboard > payments.&#x20;

As you can see here the status of the refund is recorded on both the list view in the Stripe dashboard and in the individual timeline of each Stripe payment record (*below)*.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2F6cDrCPGzDT3vEIeLZ9KC%2FScreenshot%202023-11-09%20at%2009.57.22.png?alt=media&#x26;token=5779a094-0675-411c-8d28-14cfaf506936" alt=""><figcaption></figcaption></figure></div>

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FfEnFJKdmiMgnOrIBH1M3%2FScreenshot%202023-11-09%20at%2010.56.58.png?alt=media&#x26;token=058fa6da-868a-4725-b5f5-1217a1b0e8c0" alt=""><figcaption></figcaption></figure></div>
