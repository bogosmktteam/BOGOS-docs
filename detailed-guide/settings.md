---
description: >-
  The Settings page is where you manage app-level configurations and store-level
  settings for your Gift offers.
---

# Settings

Settings has 2 tabs:

* **General:** App-level settings for BOGOS.
* **Gift settings:** Store-level settings that apply to all Gift offers.

![](<../.gitbook/assets/unknown (399).png>)

### 1. General

This tab contains app-level settings for BOGOS on your store.

#### 1.1. App status, Time zone & Language

![](<../.gitbook/assets/unknown (400).png>)

* **BOGOS status:** Enable BOGOS status for the app to work on your online store.
* **Time zone:** Time is displayed based on your device's time zone.
* **Language:** Change app language to match your native language.

#### 1.2. Support

![](<../.gitbook/assets/unknown (401).png>)

Quick access to BOGOS support resources:

* **Chat with our team:** Open live chat with BOGOS support inside the app.
* **Help center:** Open BOGOS help documentation.
* **Terms and conditions:** Open BOGOS terms and conditions.

#### 1.3. Reset app data

Use this to fully remove all BOGOS app codes and cloned gift products from your store before uninstalling or disabling BOGOS in your theme.

![](<../.gitbook/assets/unknown (402).png>)

To reset:

1. Click **Reset app**.
2. Then remove or disable the app from your Shopify admin.

{% hint style="warning" %}
This action can't be reversed. Resetting the app will stop all offers from working and delete all cloned gift products. If you're unsure, contact BOGOS support before resetting.
{% endhint %}

### 2. Gift setting

This tab contains store-level settings that apply to all Gift offers. It has 5 sections:

* Gift logic mechanism
* Draft-Order & Inventory
* Gift behavior and prices
* Gift product creation
* Fraud protection

#### 2.1. Gift logic mechanism

{% embed url="https://youtu.be/gXwkfsbsWgI?si=1BbGRUUuEAqNRGNJ" %}

This setting controls how BOGOS technically adds gifts to the cart. Changing the logic will affect all offers and remove any existing cloned products from your store. You may need to re-enable offers once the app completes the logic switch.

BOGOS recommends contacting support before changing the logic to ensure a smooth transition.

![](<../.gitbook/assets/unknown (403).png>)

BOGOS offers two gift logic mechanisms:

**2.1.1. Clone product (default)**

{% embed url="https://youtu.be/2-Bg_Ep7W5s?si=DxOv2QdGlOSPYwS5" %}

Compatible with POS, Mobile app, Headless, Third-party checkout, and Fulfillment apps.

When a gift offer is created, BOGOS automatically creates a duplicate (a "clone") of the original gift product in your Shopify product catalog. These cloned products:

* Are hidden from the storefront/store search.
* Are tagged "bogos-gift".
* Are added to the cart instead of the original product.

Because the clone is a separate product entry, it gives BOGOS much more flexibility: hide gifts from search (to make a mystery gift), use a unique image/title for cloned gifts, no limit on the number of gift offers created, and more.

**2.1.2. Gift function**

Not compatible with Mobile app, Headless, or Third-party checkout.

Gifts are added to the cart as your original Shopify products, discounted via Shopify's native discount function. For example: it can't exceed Shopify's 100 discount limit across the store.

To change the logic, click **Change logic** on the option you want to switch to. The option currently in use will be marked with a **Currently enabled** badge.

#### 2.2. Draft-Order & Inventory

{% embed url="https://youtu.be/82iWUvMSP0E?si=96igeGKlsGFvvTP7" %}

This section controls how gift inventory is tracked and what happens to an offer when its gift runs out.

![](<../.gitbook/assets/unknown (404).png>)

**2.2.1. Draft-Order API**

This feature redirects orders that have gifts to the Draft-Order page instead of the normal checkout page. It's used so customers checkout at original price with a discount, rather than as gift products. Read more about Draft-Order API \[[here](https://help.shopify.com/en/manual/fulfillment/managing-orders/create-orders)].

This feature must be enabled if a gift card is selected as a gift.

When Draft-Order API is enabled, you can control how discounts combine with the draft order:

* **Automatic discount with Draft-Order:** Choose Allow to let automatic discounts combine with the Draft-Order created by BOGOS, or Do not allow to block them.
* **Discount code with Draft-Order:** Choose Allow to let discount codes combine with the Draft-Order created by BOGOS, or Do not allow to block them.

**2.2.2. Clone product logic**&#x20;

BOGOS creates a cloned gift product as a separate Shopify product. By default, its inventory is not tracked, so the clone itself does not stop the gift from being added to the cart.

To track the cloned product's inventory:

1. Go to Shopify admin > Products.
2. Open the cloned gift's page.
3. Enable Inventory tracked.
4. Input the inventory quantity.

{% hint style="success" %}
To quickly find all cloned gift products created by BOGOS, filter your product list by the tag bogos-gift.
{% endhint %}

**2.2.3. Deduct inventory from original product**

This setting controls whether BOGOS also deducts inventory from the original product when a cloned gift is purchased.

* **If disabled:** BOGOS only deducts inventory from the cloned product.
* **If enabled:** BOGOS deducts inventory from both the cloned product and the original product, so the original product's inventory stays in sync with gift usage. The offer will then stop or continue based on the original product's inventory settings in the Shopify admin.

**2.2.4. Display out-of-stock gift items**

This setting controls how out-of-stock gifts appear in the BOGOS gift slider.

Select one of the 2 options:

* **Hide out-of-stock items:** Out-of-stock gifts are hidden from the gift slider.
* **Show out-of-stock items with an Out-of-stock status:** Out-of-stock gifts remain visible in the gift slider, marked with an Out-of-stock status.

To edit the Out-of-stock label shown to shoppers, go to **Customize - Gift slider**.

**2.2.5. Out-of-stock behavior**

When this setting is enabled, BOGOS checks whether the original product is available for sale on Shopify:

* Original product available → The gift can be added to cart.
* Original product not available → The gift cannot be added to cart. You can choose whether to hide it or show it with an Out-of-stock status.

{% hint style="warning" %}
Shopify decides product availability based on inventory, market, location, shipping, and other Shopify settings.
{% endhint %}

#### 2.3. Gift behavior and prices

![](<../.gitbook/assets/unknown (406).png>)

This section controls how gifts are added to the cart and how their discount is calculated.

* **Automatically add gift to cart:** When there is only one gift selected in the offer, this gift is automatically added to the customer's cart. If disabled, gift products always appear in a gift slider.
* **Gift price must be less than/equal to products:** Restricts customers to only getting gifts at a price lower than or equal to the items in their cart. When enabled, choose whether the gift item's price is calculated by Current price or Compare-at price.
* **Limit one selection per gift:** Restricts customers from picking a gift item a second time from the gift slider. They can no longer select this gift item even if they meet the conditions of other offers with the same gift.
* **Exclude added product:** Restricts customers from getting a gift if they already have the same item in their cart.

#### 2.4. Gift product creation

![](<../.gitbook/assets/unknown (407).png>)

This section controls how BOGOS creates the gift version of your products. Most stores set this once.

**Calculate gift discount by:** Choose how the gift discount percentage is calculated

* Current price (default)
* Compare-at price

**Gift product SKU format:** By default, cloned gift products have the same SKU as the original.&#x20;

* Same as original product (default)
* Same as original product suffix (e.g., SKU (100%OFF))
* Blank

**Gift product Barcode format:** By default, cloned gift products have a blank barcode.&#x20;

* Blank (default)
* Same as original product
* Same as original product suffix

This helps if you use an inventory management system or third-party fulfillment for your store.

**Gift product title format:** Choose how cloned gift titles are displayed

* Product Name (100% off)
* 🎁 Product Name (100% off)
* » Product Name (100% off)

{% hint style="success" %}
Please reactivate the offers once you've changed this setting.
{% endhint %}

**Sale channels:** By default, gift products are published only on Online Store. If you have other sales channels such as POS or Mobile app, click Edit to automatically publish them on those channels.

{% hint style="warning" %}
Please carefully review your campaign and contact our support team if you plan to run offers on many different channels.
{% endhint %}

**Include original product details:** By default, BOGOS does not duplicate this information from the original product. Enable each option to include:

* Product type
* Tags
* Compare-at price: Set a compare-at price on the original product to show on the clone; otherwise, the clone uses the current price.
* Product metafields: Changes to product metafields apply when the offer is reactivated.

**Delete gift products after turning off offers:** Enabled by default. When enabled, cloned products are deleted after deactivating the offers. If disabled, cloned products are only deleted after deleting the offers.

#### 2.5. Fraud protection

{% embed url="https://youtu.be/82iWUvMSP0E?si=96igeGKlsGFvvTP7" %}

This section helps stop shoppers from claiming gifts without meeting your offer conditions.

![](<../.gitbook/assets/unknown (408).png>)

**Notify via email**

Receive email notifications about fraud orders. The email contains a summary of the order considered fraudulent. When enabled, enter the email address to receive notifications.

**Cart and Checkout protection rule (Recommended)**

BOGOS integrates the Shopify Checkout Validation right into app settings. When activated, BOGOS adds a custom validation rule to **Settings > Checkout > Checkout rules**. This rule prevents customers from checking out with only gifts.

* Additional condition: Choose whether customers must meet all conditions (default) or any conditions below to check out successfully:
  * Minimum cart value: Customers can't check out with gifts if their cart value is below this minimum.
  * Minimum cart quantity: Customers can't check out with gifts if their cart quantity is below this minimum.
  * Maximum number of gifts per order: Customers can't check out with gifts if their total gift number exceeds this maximum.

**Add Cart and Checkout protection rule to each offer**

Once activated, a separate rule is added for each active offer in Checkout > Checkout rules, and Product attributes are added to cloned gift products in Checkout and Orders. Those additional details are used to validate customer checkout.

{% hint style="warning" %}
This feature is built only for Online store sale channels. If your store has other sale channels such as Headless, Mobile apps, POS, etc., please contact support before enabling.
{% endhint %}

**Orders protection**

When enabled, choose a protection level:

* **Basic protection:** Automatically cancels gift-only orders after being created.
* **Advanced protection:** Rechecks all orders after they are created. If a new order does not meet the offer condition, BOGOS performs one of the following actions:
  * Hold fulfillment, then choose Hold gift items only or Hold entire order.
  * Cancel order

Since this setting is more advanced, we recommend chatting directly with the Support team. Our agents will consult you on suitable rules to better protect your store.

## Need Help?

If you need any assistance, feel free to reach out to our customer support team via live chat within our BOGOS app.
