# Subscriptions

Stripe subscriptions are a way to bill your customers on a regular basis. This is a great way to charge for products or services that are delivered over time.&#x20;

The Stripe for Salesforce app can be used to add subscriptions for a customer directly from within Salesforce, so you don't have to switch to Stripe. It can also sync changes from Stripe.

## **Create and set up subscriptions from the Stripe app for Salesforce.**

To create a subscription in Salesforce, go to the Customer Account tab and click on the **Create Subscription** button in the page layout.&#x20;

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FP3u4IEyCC1fXKHs2bNen%2FScreenshot%202023-11-10%20at%2015.50.55.png?alt=media&#x26;token=cd6705d0-6af6-43f3-8861-867d132f4304" alt=""><figcaption></figcaption></figure></div>

From here the user will need to fill out the modal window fields. Selecting the product(s), the cost(s) and quantities to add to the subscription.&#x20;

<figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2Fk5j93jR4Yqila6LBP1Ga%2FScreenshot%202023-11-10%20at%2015.51.03.png?alt=media&#x26;token=3aeb4b80-fcf2-47f1-abb3-925ed14f2a22" alt=""><figcaption></figcaption></figure>

<figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FNyeMY263cAWWIElUWi20%2FScreenshot%202023-11-10%20at%2015.51.21.png?alt=media&#x26;token=11964d9d-a1e8-4767-8d22-ea9ab1a574b4" alt=""><figcaption></figcaption></figure>

<figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2Fj02vXO5Sm0Qg0CWlFJUT%2FScreenshot%202023-11-10%20at%2015.51.30.png?alt=media&#x26;token=de9279f9-ac4a-42e5-a073-91bfd8a010fe" alt=""><figcaption></figcaption></figure>

If you don't see the product or price you may need to create or sync a new product and/or price record.&#x20;

Once completed, the subscription record will be updated with the related subscription items, i.e. products and prices.

Navigating to and clicking on the Subscription item record, will display the relevant subscription item information.

## Manual sync subscription to stripe&#x20;

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FlYovuptFviNLTwwFNwKy%2FScreenshot%202023-11-03%20at%2011.04.18.png?alt=media&#x26;token=3ef9888d-a514-4ec6-88ad-da5e000504a8" alt=""><figcaption></figcaption></figure></div>

Entering the subscription record, the user is able to manually sync the subscription record to Stripe by clicking on the **Send customer** action button. Completing this step will produce a completion message and you will see a status change to active on the Subscription record.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FKHsYos5KppqT36vGV1vb%2FScreenshot%202023-11-03%20at%2011.04.27.png?alt=media&#x26;token=519bfc76-65a0-4396-9ad5-ebaf66941e26" alt=""><figcaption><p>Send customer action button completion message</p></figcaption></figure></div>

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FHJHuXPbcFyaJX3cMHhOF%2FScreenshot%202023-11-03%20at%2011.04.53.png?alt=media&#x26;token=0e2de446-f522-4464-a68f-c4eb6ae92bd0" alt=""><figcaption><p>Subscription status update in Salesforce</p></figcaption></figure></div>

## Verifying the subscription in Stripe

B.y logging into the Stripe dashboard and navigating to the developer area and clicking on **Subscriptions** on the left hand column. The user can the review the synced subscriptions statuses from this area in the Stripe dashboard.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FE0nOXpHm9ppCrCAvOx8y%2FScreenshot%202023-11-03%20at%2011.42.38.png?alt=media&#x26;token=e95e54e7-78e2-4308-a011-79efa20f09e6" alt=""><figcaption></figcaption></figure></div>
