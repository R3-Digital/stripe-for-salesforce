# Invoices

In the Stripe for Salesforce app, invoices can be sent to customers directly from a Salesforce org. Users are able to generate and send new invoices to customers, alongside update record the updates to the invoice status or stages within Salesforce. The updates to this workflow will then also be synced with Salesforce.

## Invoice generation

To generate a new invoice for a customer, the user must first navigate to the Customer Account. From here the user will need to locate and click the **Raise Invoice** action button on the page layout.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FNMFS7QtnOUyvjzActuPZ%2FScreenshot%202023-11-03%20at%2011.56.52.png?alt=media&#x26;token=6c30094f-cb6f-43d7-bf2e-99a997af307f" alt=""><figcaption></figcaption></figure></div>

Next fill in the form fields with the information required for this invoice. Start by adding a description and due date.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2F0y36jny4SdqI2aL3aC8V%2FScreenshot%202023-11-03%20at%2011.57.01.png?alt=media&#x26;token=1af64c25-38ea-4c8d-8ed3-0c5d79fa9ca8" alt=""><figcaption></figcaption></figure></div>

On the next window select the product.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2F4uhaOJEOxoaHzvGhmoqO%2FScreenshot%202023-11-03%20at%2011.57.15.png?alt=media&#x26;token=09ad194b-85c3-4a49-9dfd-247bd1a9a83d" alt=""><figcaption></figcaption></figure></div>

And, finally add the price and quantities for the invoice. Here the user also can choose to add more items to the invoice by click the box for **Create More Items**, this will then take the user back to the first model window to input their invoice line item information.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FtzI2UV9C2UU5pHna3G36%2FScreenshot%202023-11-03%20at%2011.57.31.png?alt=media&#x26;token=c5cb0c00-9f94-4a5c-a86a-d4fca1f81acc" alt=""><figcaption></figcaption></figure></div>

Once this is is completed, the user can navigate to the invoice record and see the invoice in its draft form. This can be edited and revised before being sent to the customer and Stripe.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FnLufJy2pxLpwdL1nYtfw%2FScreenshot%202023-11-03%20at%2011.58.06.png?alt=media&#x26;token=9588a159-bcb5-4540-9afe-842b8dc744ac" alt=""><figcaption></figcaption></figure></div>

## Send the invoice to your customer

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2Fibi8NtSZozkgCFUT1mJs%2FScreenshot%202023-11-03%20at%2011.58.34.png?alt=media&#x26;token=9314f7d1-bd59-4e70-8714-1ca7e920847d" alt=""><figcaption></figcaption></figure></div>

Once the user has generated an invoice and is ready to send it to the customer they will need to: navigate to the invoice record and select the **Send To Customer** action button on the page layout. Clicking the **Send To Customer** initiates the process in which Salesforce tells Stripe to send the invoice to the customer.

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FWsf8IFpqA7e5zay93OP1%2FScreenshot%202023-11-03%20at%2011.58.53.png?alt=media&#x26;token=c641d9dd-ffce-4395-8292-4b6a52aa23a1" alt=""><figcaption></figcaption></figure></div>

Upon completing this action the status of the *draft* invoice is then changed to **Open**. As you'll see here the invoice status is reflected within both Salesforce and the Stripe dashboard.&#x20;

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FsGmPmFFhF8oByjXJ1ks2%2FScreenshot%202023-11-03%20at%2011.59.26.png?alt=media&#x26;token=715e1623-046d-48fe-b785-978da22e6fc3" alt=""><figcaption></figcaption></figure></div>

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2F8fCzUy2NLzxCRM81uDTi%2FScreenshot%202023-11-03%20at%2012.26.16.png?alt=media&#x26;token=4dfeb2dc-63c9-41cc-b835-229c2659aa4d" alt=""><figcaption></figcaption></figure></div>

The customer will then receive an invoice with a payment link to a hosted payment page, where payment information can be entered. &#x20;

*Emailed invoice and payment link example:*

<div data-full-width="true"><figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2Fz1HVfdpuvq26mFjCe1TF%2FScreenshot%202023-11-03%20at%2012.01.57.png?alt=media&#x26;token=2f9bf05a-b56b-4b85-846c-a123c5c6127e" alt=""><figcaption></figcaption></figure></div>

<figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FzaX2hjkIWig9OusN6efY%2FScreenshot%202023-11-03%20at%2012.01.13.png?alt=media&#x26;token=17ef724b-e406-4468-b128-db288647a11d" alt=""><figcaption></figcaption></figure>

*Hosted payment page example:*

<figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FhRw6WuEVpb3R5iUkA83f%2FScreenshot%202023-11-03%20at%2012.00.54.png?alt=media&#x26;token=a903ff96-394b-4d2d-b6dd-3087904b453b" alt=""><figcaption></figcaption></figure>

##

## Manual syncing invoice data from Stripe

Here we will discuss how to sync an invoice record from Salesforce to Stripe. This is normally done through the integrated webhooks, but if you need to do this manually please follow these instructions.

To send this invoice to Stripe, click on the **sync invoice** action button in the Product record. You will then be shown a completion message.

<figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2FGshs57AGwJNqLeVhxC3z%2FScreenshot%202023-11-03%20at%2011.58.44.png?alt=media&#x26;token=29c4fc47-04d1-4b52-87c7-d2e943b36c63" alt=""><figcaption></figcaption></figure>

<figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2F25dndqpyCcG0ViKyIW6Z%2FScreenshot%202023-11-03%20at%2011.59.12.png?alt=media&#x26;token=4a53669e-2600-43b4-a225-ad7f3c3650a7" alt=""><figcaption></figcaption></figure>

Then if you check your Stripe dashboard in the Invoices section you will see and updated list of Invoices and invoice payment statuses.

<figure><img src="https://987883418-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F7t6q91Y6zv0SwcAX1Met%2Fuploads%2F6alUzZfqaQ14otoP67KR%2FScreenshot%202023-11-03%20at%2012.46.38.png?alt=media&#x26;token=62e57a50-ba0d-40a1-b3ce-15501aa0bfbe" alt=""><figcaption></figcaption></figure>
