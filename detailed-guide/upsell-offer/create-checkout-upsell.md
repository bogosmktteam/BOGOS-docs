# Create Checkout Upsell

Checkout upsell allows you to offer additional products to customers at checkout, helping to increase your average order value (AOV) and scale your sales.

Here's a quick demo of how Checkout Upsell widget show on your store:

<figure><img src="../../.gitbook/assets/unknown (41).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
After publishing your upsell, you have to [enable the widget](create-checkout-upsell.md#id-8.-enable-the-checkout-upsell-widget) to make it appear on your storefront.
{% endhint %}

{% hint style="info" %}
Shopify only allows **Shopify Plus** to edit checkout pages, so this feature is currently available only for Shopify Plus.&#x20;
{% endhint %}

{% embed url="https://youtu.be/A0EKHj3ZtyQ?si=ds35FtxozKolQvg7" %}

## 1. Upsell information

### 1.1 Upsell title

The upsell title is the name of the upsell, which isn’t visible to customers and is displayed in the “All offers” section of the BOGOS app for easy management alongside other offers.

### 1.2 Start & End time

* **Start Time:** This is when the upsell becomes active and visible to customers at your store’s checkout.
* **End Time:** This is when the upsell expires and is no longer visible at your store’s checkout. Leave this field blank so the upsell can run continuously.

## 2. Upsell trigger

This is where you choose one from the 4 conditions below that customers must meet for the upsell to appear at checkout.

### 2.1 Always display upsell

The upsell will always be shown to customers at checkout without any specific conditions.

### 2.2 Cart trigger

The upsell will be shown if the customer’s cart meets one of these 2 conditions:

* **Quantity**: The customer’s cart must meet a minimum and/or maximum number of products.
* **Value**: The customer’s cart must meet a minimum and/or maximum total value you set.&#x20;

**For stores that have Shopify Markets set up and choose "cart value":**

Normally, BOGOS will auto-convert your main currency to the customers’ currency using Shopify’s exchange rate (e.g., 1 SGD = €0.666).

However, if you want to **set custom cart values for each currency** instead, after setting the value for your main market (min is 0), click “Add currency” and enter the value.

<figure><img src="../../.gitbook/assets/image (382).png" alt=""><figcaption></figcaption></figure>

### 2.3 Specific product trigger

The upsell will trigger when the customer's checkout includes:

* **Product**: The customer's checkout summary must include products from the list you select and meet the “number of products required” you specify.
* **Collection**: Any product from a specific collection(s) you select.
* **Subscription Product**: A product(s) you select with a subscription plan.

### 2.4 Customer trigger

The upsell will trigger based on specific customer conditions, including:

* **Customer tags:** The upsell will be shown only to customers with the specific tags you select. You also have 2 optional settings:
  * Exclude customers with these tags: All customers except those with the selected tags will see the upsell.
  * Consider no-login as a customer with no tags: Customers who are not logged in will be treated as if they have no tags, meaning they will be included or excluded based on your tag settings.
* **Location**: The upsell will be shown only to customers from the specific location(s) you select. You also have 1 optional setting:
  * Exclude customers from selected locations: Customers from any location except the selected location(s) will see the upsell.
* **Order history:** The upsell will be shown only to customers who have placed orders starting from the date you choose. You then need to select which condition(s) those orders must meet for the upsell to trigger:
* **Total Spent in Order History**: The total spending from orders, placed after the start date, must meet a minimum and/or maximum amount.
* **Total Spent on Last Order:** The customer’s most recent order, placed after the start date, must meet a minimum and/or maximum value.
* **Total Number of Orders Placed:** Starting from the selected date, the customer must place a minimum and/or maximum number of orders.

## 3. Add sub-conditions

Sub-conditions add extra rules to decide who can see and get your offers. Therefore, only targeted customers can see and apply the offer, while others won't see it at all.

{% hint style="info" %}
* These sub-conditions are optional. If you don't add any, the offer will be available to all customers.
* You can combine multiple sub-conditions. Customers must meet all selected criteria to qualify.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (388).png" alt="" width="563"><figcaption></figcaption></figure>

1. _Specific link address_ – Apply offers to customers accessing your store from a specific link. Perfect for email campaigns, social posts, or affiliates.
2. _Markets_ – Run region-specific offers based on your Shopify Markets.

♦️ For more details, visit our \[[Sub-Condition](../detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md)] guide.

## 4. Upsell method

This is where you define how you want to offer the upsell products to customers during checkout. There are 3 methods.

### 4.1 Manual

You manually select the products to upsell and choose the discount type (either percentage or fixed amount) to apply.

### 4.2 Auto

First, to use this option, you must have the **Shopify Search & Discovery** app installed in your store. BOGOS will auto-select upsell products based on the data synchronized with the Shopify Search & Discovery app. [Install this FREE app here.](https://apps.shopify.com/search-and-discovery)

On BOGOS’s settings screen, there are 2 recommendation types: **Complementary Products** and **Related Products**, both synced with data from the Shopify Search & Discovery app, as shown in the example below.

{% hint style="info" %}
For “Complementary products” in the Shopify Search & Discovery app, you must manually select products within the app. For “Related Products,” Shopify uses AI to auto-generate product recommendations. [Click here to view its help docs.](https://help.shopify.com/en/manual/online-store/search-and-discovery/product-recommendations)
{% endhint %}

### 4.3 Subscription product

This method only appears when you select Subscription Product in the **Upsell Trigger** above.&#x20;

Subscription products can only use this upsell method, which automatically upsells customers to the highest-valued plan with the biggest discount.

#### 4.4 Limit number of upsell products can be added

Enable this to control the maximum number of upsell products a customer can add to their cart from the upsell section.&#x20;

Once the limit is reached, the upsell section will automatically disappear.

<figure><img src="../../.gitbook/assets/unknown (40).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
This option isn’t available when using the "Auto add products to cart" method of the "Discount code required" setting in Advanced configuration.
{% endhint %}

### 4.5 Discount type

<figure><img src="../../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>

**Product discount:** Allows you to choose the type of discount

* Percentage: for a percentage-based discount
* Amount: for a fixed monetary discount. If you also sell in different currencies (set up in Shopify Markets), you can “add currency” and **custom how much discount amount** to offer in each currency, instead of using Shopify’s exchange rates (e.g., SGD 10, CN¥8, A$12).

<figure><img src="../../.gitbook/assets/image (379).png" alt="" width="563"><figcaption></figcaption></figure>

### 4.6 Add shipping discount

<figure><img src="../../.gitbook/assets/image (380).png" alt="" width="461"><figcaption></figcaption></figure>

There are two types of shipping discount:

* Percentage: A percentage of the shipping cost will be deducted.
* Amount: A fixed amount will be deducted from the total shipping cost. If you sell in different currencies (set up in Shopify Markets), you can “add currency” and **custom how much shipping discount amount to offer in each currency**, instead of using Shopify’s exchange rates (e.g., SGD 10, €8, A$12).

**Label on widget**: This text informs customers whether the bundle includes a shipping discount.

## 5. Advanced configuration (optional)

1. **Exclude products in cart**

<figure><img src="../../.gitbook/assets/image (280).png" alt=""><figcaption></figcaption></figure>

This feature lets you include or exclude upselling products already in customers’ carts.

{% hint style="info" %}
This feature works at the product level. If your cart contains a product with variant A, other variants of the same product (e.g., variant B) will also be hidden.
{% endhint %}

2. **Upsell product variant matching**

This feature automatically matches the variant of the upsell product to the variant of the product in the customer's cart.

**Example**: If a customer buys a T-shirt (size M), the upsell widget will recommend another T-shirt (size M).

{% hint style="info" %}
Only apply to the upsell method “Manual.”
{% endhint %}

3. **Discount Code**

You can generate a discount code that customers will need to manually enter on the Checkout page to trigger their purchase journeys efficiently.&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXesoGHQspnuAcp993O2524cYImpeQ3cfJOvz7APcHKaCOAWL7QA9iMoqi4slaWTFOEkgbbX7g-MGHX1KMRC1sr1n7ScNzmQdOxUUYAc6p4YJU-QwHzlS8X1tldr7CXTMlVi9zoXPQ?key=h6X-GCR3Ue_E-vh3IcgWlzIw" alt=""><figcaption></figcaption></figure>

## 6. Discount code

**Add a custom discount code**

This section allows you to customize the discount code name to match your brand.<br>

<figure><img src="../../.gitbook/assets/image (322).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The discount code name must be under 256 characters and unique across all Shopify discounts.
{% endhint %}

**Combinations**

<figure><img src="../../.gitbook/assets/image (323).png" alt=""><figcaption></figcaption></figure>

#### Order discounts

Indicates if the upsell discount can be combined with order-level discounts, such as promotional codes or automatic discounts.

#### Shipping discounts

Indicates if the upsell discount can be combined with shipping discounts, such as free or reduced shipping promotions.

## 7. Summary

The upsell summary widget pinned on the right will update everything you’ve set up for easy tracking.

## 8. Enable the widget

Make sure you’ve added the "**BOGOS Checkout Upsell**" block in your **theme editor** so the upsell widget appears at checkout.

**Here’s how:**

1. Go to your **Shopify Dashboard**
2. Navigate to **Online Store > Themes**
3. Click **Customize**
4. Switch from **Home Page** > find and select **Checkout and customer accounts**

<figure><img src="../../.gitbook/assets/image (348).png" alt=""><figcaption></figcaption></figure>

5. In the Menu sidebar, click **Add section** > Select **BOGOS Checkout Upsell** and place it where you want

<figure><img src="../../.gitbook/assets/image (349).png" alt=""><figcaption></figcaption></figure>

## FAQs

<details>

<summary><strong>Can I trigger a free gift by discount code at checkout?</strong></summary>

Here’s the full guideline to create a discount code for gift products:

**Step 1 – Create a $0 discount code in Shopify**

* Go to Shopify › Discounts › Create discount and choose Amount off order.
* Set Discount code, choose Fixed amount = 0, and keep All customers.
* In Combinations, select Product discounts only, then Save.

This discount code for the checkout upsell is actually a way for us to identify when to add the gift. Its purpose isn't to reduce the price. Our app already handles the price reduction, and it's set up within the checkout upsell.

**Step 2 – Add the code to your Checkout Upsell in BOGOS**

* In BOGOS, go to Offers › Create › Upsell Offer › Checkout upsell.
* In Advanced configuration, paste the exact discount code you created.

**Step 3 – Publish and test**

Save the offer and test at checkout. The code should show $0 off, and the upsell will trigger as expected.

</details>

<details>

<summary><strong>Can I hide upsell products if the customer already has them in their cart?</strong></summary>

**Yes, you can!** To ensure you aren't upselling a product that the customer is already purchasing, you can use the **Exclusion** feature.

**How to set it up:**

1. Go to the Checkout Upsell offer
2. Go to Advanced configurations
3. Tick the box Exclude products in cart
4. Save

![](<../../.gitbook/assets/unknown (203).png>)

</details>

<details>

<summary><strong>Can I just upsell the same size for products at checkout?</strong></summary>

Yes, that’s possible. Please follow the steps:

1. Go to the Checkout upsell offer
2. Go to Advanced configurations > Upsell product variant matching
3. Tick the box Match the upsell product variant with cart product
4. Save

![](<../../.gitbook/assets/unknown (204).png>)

</details>
