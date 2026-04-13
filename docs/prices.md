# Prices

The Stripe price object is like a product's price tag. It includes info like the price's amount, currency, recurring billing info, and usage type. There are two types of prices in Stripe: one-time prices and recurring prices. Price data in Stripe is mapped to a custom object in Salesforce.

!!! info 
    **Note**: The Stripe for Salesforce app only lets you add one-time prices from Salesforce. If you want to add recurring prices, you'll need to do it in Stripe and then sync it back to Salesforce. Tier-based pricing isn't supported in the current Stripe for Salesforce app.

## Create a price from Salesforce:

To create a price for a Product in the Stripe app for Salesforce, firstly go to the Product object and select a Product record.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2F7ddWGv7JFD5tx7aLXL8r%2Fimage.png?alt=media&#x26;token=28304acd-e7ef-4dcd-a20d-f366c7ddad3e" alt=""><figcaption><p>Product object > Product record</p></figcaption></figure></div>

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FdnsmdNsIrJ2GE60X7xzp%2FScreenshot%202023-10-06%20at%2010.18.28.png?alt=media&#x26;token=3c80f515-0000-420a-bb3f-bcdf8a6ba29e" alt=""><figcaption><p>Product record > Create price action button</p></figcaption></figure></div>

Next we go to the create price action button on the record layout. Next fill in the form fields with the information required and click save. This sends and syncs the information to Stripe.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FuN6lapEjnsIAgQ4vhvQn%2FScreenshot%202023-11-10%20at%2016.23.37.png?alt=media&#x26;token=2dc8b508-d700-4f7c-b106-ab7c76c75362" alt=""><figcaption></figcaption></figure></div>

We can then view the related tab on the product record to see the prices attributed to this product record.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FzUh191h2AJSRd1c4p6Wz%2FScreenshot%202023-10-06%20at%2010.20.46.png?alt=media&#x26;token=1215e994-3cfa-45d1-8c2a-8b43b01b8b76" alt=""><figcaption><p>Product record > related > Stripe prices for the product record</p></figcaption></figure></div>

## **Manual Syncing Products From Stripe**

Here we will discuss how to sync a product's price record from Salesforce to Stripe. This is normally done through the integrated webhooks, but if you need to do this manually please follow these instructions.

To send this product information to Stripe, click on the **Sync Pice** action button in the Product record page layou&#x74;**.** If you go to the product catalogue of the Stripe dashboard, you'll be able to see that your product has an associated price. Entering the product catalogue record in Stripe will give you further information about when the price was added to the product.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2F9289MLPvmwP3N8MrcgD2%2FScreenshot%202023-11-10%20at%2016.26.43.png?alt=media&#x26;token=49da1c42-3b64-412c-ba7d-45d7826ae1de" alt=""><figcaption></figcaption></figure></div>

<figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FiolJFgsNG99GuOuTYIpp%2FScreenshot%202023-11-10%20at%2016.26.50.png?alt=media&#x26;token=0c9b402f-4756-4632-af36-903d18063dca" alt=""><figcaption></figcaption></figure>
