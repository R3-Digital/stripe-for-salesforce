# How it works

The Stripe for Salesforce app will automatically synchronise the information between Salesforce and Stripe.

## Data Model

The Stripe for Salesforce app contains a data model that mirrors the data store inside Stripe.

This information that is synchronised:

* Products
* Pricing
* Customers
* Invoices
* Charges
* Payment Methods
* Subscriptions

## Data Synchronisation

### Automatically Updating Stripe

When a record is created or updated in Salesforce, the Stripe for Salesforce app will automatically create or update Stripe, using existing prebuilt Salesforce Flow automations that are included in the Stripe for Salesforce app.

### Automatically Updating Salesforce

When a record is created or updated in Stripe, the Stripe for Salesforce app will automatically create or update Salesforce, because it will receive a webhook message from Stripe which it will process.
