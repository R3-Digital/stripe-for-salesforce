# Products

A product object in Stripe represents a physical or digital good or service that you sell. It can be used to create invoices, charge subscriptions, and track inventory.&#x20;

## **Create new product in Stripe app**

Here we will look at how to create a new product in the Stripe app.

Firstly, we need to go to the Products tab and click on the new action button on the page layout.

![Products1](assets\Products1.png)
*Product tab > New action button*

Then fill in the product information form fields and click save (or save and new). Locate the new product record, and you are able see all the information about the product you just added.

![Products2](assets\Products2.png)
*New product form fields*

![Products3](assets\Products3.png)
*New Product*

![Products4](assets\Products4.png)
*New product details*

## **Edit products in stripe app for salesforce**

Now let’s take a look at how to edit a product in the Stripe app for Salesforce. Here we will be able to edit a number of fields on the Product record and sync with Stripe.

Go to the product tab and locate the product record that is being edited.

![Products5](assets\Products5.png)
*Product tab > Product record to edit*

Next we navigate to and click the ![Products6](assets\Products6.png) (downward arrow) action button on the page layout and select edit.

![Products7](assets\Products7.png)
*Product tab > Edit*

![Products8](assets\Products8.png)
*Product record > Edit*

Now we can edit the fields that we need to and click save. Locate the product record, and you are able see all the information about the product you just edited.

![Products9](assets\Products9.png)
*Product tab > Edit the product fields*

![Products10](assets\Products10.png)
*Product record > Edit the product fields*

## **Manual Syncing Products From Stripe**

Here we will discuss how to sync a product record from Salesforce to Stripe. This is normally done through the integrated webhooks, but if you need to do this manually please follow these instructions.

To send this product information to Stripe, click on the **Send Product** action button in the Product record. Or to Sync products from Stripe to Salesforce click **Sync Product.** Once the request has been sent to Stripe or from Stripe, you will then be shown a completion message once the flow is complete.

![Products11](assets\Products11.png)

![Products12](assets\Products12.png)

![Products13](assets\Products12.png)
*Sync flow completion message*

To verify whether the product is synced with Stripe, you can go to your Stripe account and look at the product catalogue and view the synced products.

![Products14](assets\Products14.png)
