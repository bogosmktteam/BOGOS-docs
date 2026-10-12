# Create Thank You Page Upsell

Thank You Page Upsell is a post-purchase offer shown on the order confirmation page to encourage customers to buy additional products, increasing average order value (AOV).

Here's a quick demo of Thank You Page upsell widget:

<figure><img src="../../.gitbook/assets/unknown (44).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
After publishing your upsell, you have to [enable the widget](create-thank-you-page-upsell.md#id-8.-enable-the-widget) to make it appear on your storefront.
{% endhint %}

{% embed url="https://youtu.be/h1sh0dM4oWI?si=tOGoazsqmIHTDY9o" %}

### 1. Upsell information

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeZwZzN7YDt_qMzwMgQjnH7JbDUmNcj_3YuGl3W6NkiWi4_oRfuCWh4-FPAUOgYG4Aae1vHM7ZEY_gF_D6TfIZthG8-8iv4kRsZKRHyvZMEp1vQz97stgkJCAlkGZauGaanuPPE?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

**Upsell Title:** The upsell's name, shown in the “All offers” section for easy management.

**Start Time:** When the upsell is visible at checkout.

**End Time:** When the upsell expires. Leave blank for it to run indefinitely.

### 2. Upsell Trigger

#### Always display upsell

The upsell will be shown to customers at checkout without any conditions.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXf2lzo_-7D2AkuWojXyW9shFuecsoEBL3aIkVyzbaSEmYd6QbJTlowkPGbtKkiQIXkZ9U1jLLKlb8CpJzWhkqOtFZuO13Xyyg7kQgqzRJq4jUbgIt4Csq119o5A3I2hKB-Z7J7ZAA?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

#### Cart trigger

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdlRKl9-kdgmoRCag1dYpo5EzPhCcJlMrObT7TioPi_YKd9I0yQm03uxxp_uKnYnnB1xg6pebP8xIyzm0vJuuG89ozEkeaWegiXfIG9Tdd1kpeHaWs34EZwGgqm_hGzsdXMqG2HCQ?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

**Quantity:** The cart must meet a minimum and/or maximum number of products.

**Value:** The cart must meet a minimum and/or maximum total value you set.

* Normally, BOGOS will auto-convert your main currency to the customers’ currency using Shopify’s exchange rate (e.g., 1 SGD = €0.666).
* However, if you want to set custom cart values for each currency instead, after setting the value for your main market (min is 0), click “Add currency” and enter the value

<figure><img src="../../.gitbook/assets/image (383).png" alt=""><figcaption></figcaption></figure>

#### Specific product trigger

**Product:** The checkout must include products from your selected list and meet the required quantity.

**Collection:** Any product from the specific collection(s) you choose.&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcJ7wuuWemvpDODB-jIl2LvIZ7-EfxIlKRHDOiNCWVyT0xdLW7_6h4NAMhXHpaZqYqHDJm6pSYhuRa3hKGg4bDSm7PLMzdHFH8s3edkaDDYYW3RNvUyWKygLfzI7TYYTN6q1D_D2A?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

#### Customer trigger

The upsell will activate based on specific customer conditions.

* **Customer Tags:** Show only to customers with selected tags.\
  _&#x45;xclude customers with these tags:_ Everyone except those with selected tags will see the upsell.\
  \- _No-login customers treated as tagless:_ Logged-out customers are included/excluded based on tag settings.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdwv-W45SzdeCtf_Uu3nlynPG16NJ8d-_SjbmowSOl5mSmVJiv1CHwIEW1yxkFS6T01b8pL-fc88LKTXvlhNkWt5BQyrJmqVqRtwtpYYvFh0AGoyy89gyVzBo6HFl6kdk1EoKn3Qg?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

* **Location:** Shown only to customers from selected locations.\
  _&#x45;xclude selected locations:_ Everyone except those in chosen locations will see the upsell.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXd5SUIfhnbt5Ad7ElcVCW4hut_Xr6UAQavPWrkP2DgdkiXubmvjpHkpFA7XEx7i5wAjKVTTcLXj3MDK2R5jvJ2knYwRIbyKIGyJKbkdyalo6rl6JdADVHedFxam-5Mjkjvt4GvtgQ?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

*   **Order History:** Shown only to customers who placed orders from a chosen start date, based on:

    _Total Spent in Order History:_ Orders since the start date must meet a spending range.

    _Total Spent on Last Order:_ The most recent order must meet a spending range.

    _Total Orders Placed:_ The number of orders since the start date must meet a set range.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdEbFdnLWYMIYEXa6740EjS6pS11-4BRJZldKeM1jSJQ-IhV1ZPIyjwaKb_fY05VVQSEPoXqaBQqUW4_mYbSKXPXOZf1W0_1-sk4TyEHbjiwAddaJrdJBQry4pJ-g_63IwZ89kf?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

### 3. Add sub-conditions

Sub-conditions add extra rules to decide who can see and get your offers. Therefore, only targeted customers can see and apply the offer, while others won't see it at all.

{% hint style="info" %}
* These sub-conditions are optional. If you don't add any, the offer will be available to all customers.
* You can combine multiple sub-conditions. Customers must meet all selected criteria to qualify.
{% endhint %}

<figure><img src="../../.gitbook/assets/image (388).png" alt="" width="563"><figcaption></figcaption></figure>

1. _Specific link address_ – Apply offers to customers accessing your store from a specific link. Perfect for email campaigns, social posts, or affiliates.
2. _Markets_ – Run region-specific offers based on your Shopify Markets.

♦️ For more details, visit our \[[Sub-Condition](../detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md)] guide.

### 4. Upsell method

Defines how upsell products are offered to customers at checkout.

**Manual:** Manually select upsell products and apply either a percentage or fixed discount.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfXuIdsIxFjIYclcgPqEI_FkICj1YrCnPJHo_Izy7FeeSjlrGDhXX9rebfgyHzMBgAsn-LNlpRE4NDxlkZq5-HAIc6tK-TECiPoTsr0OJOBht8CgYVQrM4yf1p8cJxv0JMyLxslJA?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

**Auto:** Automatically selects upsell products using data from the [Shopify Search & Discovery app](https://apps.shopify.com/search-and-discovery).&#x20;

* Recommendation Types:\
  _&#x43;omplementary Products:_ Products that pair well together.\
  _&#x52;elated Products:_ Similar or frequently bought items.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdBvIIMvxr_J9sJ6YYKxkXlRKLjPMWqSfPbq6IC57r45AUxPE542smMf4pW-UfIh6H4ozCShdPNv3is6KM3notLvl7TJENhu6oR1RlizmPgULdd9OLlsthqpPibYeN7Vr-bx65LfA?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

**Random:** Randomly selects upsell products from a predefined group based on collections, vendors, or product types.

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcNxFHwte9g8e0kPhGcu-6Yo101lUwxu1NiKx4wSRmyYWy_aujkMNpAl6YAXMgTTeFyD5uFm9e0eq_tyAJhf3ZSk7F4mnhmQTLkt51xYwhzyiVRiNWFI4jXQuPd8WSs-tBi3usXpA?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

### 5. Discount

#### 5.1 Discount type

<figure><img src="../../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

**Product discount:** Allows you to choose the type of discount

* Percentage: for a percentage-based discount
* Amount: for a fixed monetary discount. If you also sell in different currencies (set up in Shopify Markets), you can “add currency” and custom how much discount amount to offer in each currency, instead of using Shopify’s exchange rates (e.g., SGD 10, CN¥8, A$12).

<figure><img src="../../.gitbook/assets/unknown (115).png" alt="" width="563"><figcaption></figcaption></figure>

#### 5.2 Add shipping discount

<figure><img src="../../.gitbook/assets/unknown (114).png" alt=""><figcaption></figcaption></figure>

There are two types of shipping discount:

* Percentage: A percentage of the shipping cost will be deducted.
* Amount: A fixed amount will be deducted from the total shipping cost. If you sell in different currencies (set up in Shopify Markets), you can “add currency” and custom how much shipping discount amount to offer in each currency, instead of using Shopify’s exchange rates (e.g., SGD 10, €8, A$12).

**Label on widget**: This text informs customers whether the bundle includes a shipping discount.

### 6. Advanced configuration (optional)

**Exclude products in cart**

This feature lets you include or exclude upselling products already in customers’ carts.

<figure><img src="../../.gitbook/assets/image (281).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
This feature works at the product level. If your cart contains a product with variant A, other variants of the same product (e.g., variant B) will also be hidden.
{% endhint %}

**Upsell product variant matching**

This feature automatically matches the variant of the upsell product to the variant of the product in the customer's cart.

**Example:** If a customer buys a T-shirt (size M), the upsell widget will recommend another T-shirt (size M).

_Note: Only apply to the upsell method “Manual.”_

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcTv2iVmdHWOHmGdojWRbHUuoYIJ9_zEHKJIy9Y3dmLcMo8IYqSO9W5KxofbfYZWbh9zD1M0vFvgID5amZHNERP-g4xLKRmHiCaw3-010h-xoNQfdOmQxK97Th2-GvqKfMTl47l?key=AIxlYn9hwP4xvs3rgpboLynD" alt=""><figcaption></figcaption></figure>

### 7. Discount code

#### Add a custom code

This section allows you to customize the discount code name to match your brand.

<figure><img src="../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The discount code name must be under 256 characters and unique across all Shopify discounts.
{% endhint %}

#### Combination

<figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

**Order Discounts:** Determines if the upsell discount can be combined with order-level discounts like promo codes or automatic discounts.

**Shipping Discounts:** Determines if the upsell discount can be combined with shipping discounts like free or reduced shipping.

### 8. Enable the widget

After publishing your upsell, you have to add the "**BOGOS Checkout Upsell**" block in your **theme editor** so the upsell widget appears at thank you page.

**Here’s how:**

1. Go to your **Shopify Dashboard**
2. Navigate to **Online Store > Themes**
3. Click **Edit Themes**
4. Switch from **Home Page** > find and select **Checkout and customer accounts**

<figure><img src="../../.gitbook/assets/image (348).png" alt=""><figcaption></figcaption></figure>

5. Switch from **Checkout** to **Thank you**

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption></figcaption></figure>

6. In the Menu sidebar, click **Add section** > Select **BOGOS Thank You Page Upsell**

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

7. Drag & drop the block where you want.

♦️ For more details, visit our guide on \[[Adjust BOGOS blocks](../../quick-start-guide/adjust-bogos-blocks.md)].

### FAQs

<details>

<summary><strong>Is the Thank You page upsell available in Basic Plan?</strong></summary>

Yes, this feature is available on **all BOGOS plans**. As long as you have already set up and customized your "Thank You" (Order Confirmation) page within your Shopify Theme settings, BOGOS can display upsell offers there.

</details>

<details>

<summary><strong>Why don’t I see any upsell widget on Thank You page?</strong></summary>

After publishing your upsell, you have to add the "**BOGOS Thank You Page Upsell**" block in your theme editor so the upsell widget appears at thank you page.

<div align="left"><figure><img src="../../.gitbook/assets/image (9).png" alt="" width="375"><figcaption></figcaption></figure></div>

**Here’s how:**

1. Go to your Shopify Dashboard
2. Navigate to Online Store > Themes
3. Click Edit Themes
4. Switch from Home Page > find and select Checkout and customer accounts
5. Switch from Checkout to Thank you
6. In the Menu sidebar, click Add section > Select BOGOS Thank You Page Upsell
7. Drag & drop the block where you want.<br>

</details>

<details>

<summary><strong>Can products be shown randomly in the Thank You Page Upsell?</strong></summary>

Yes, they can! If you want to keep your offers fresh and show different products to different customers, you can use our **Random upsell method**.

**How to set it up:**

1. While creating your Thank You Page offer, look for the Upsell Method section.
2. Select the "Random" method.
3. You can then choose to pull these random products from specific Collections, Vendors, or Product Types.

![](<../../.gitbook/assets/unknown (4).png>)

</details>

<details>

<summary><strong>Can I match the size of the upsell item to what they already bought?</strong></summary>

Yes, you can.&#x20;

**Please follow the steps:**

1. Go to the Thankyou upsell offer
2. Go to Advanced configurations > Upsell product variant matching
3. Tick the box Match the upsell product variant with cart product

![](<../../.gitbook/assets/unknown (5).png>)

4. Save&#x20;

If they bought a Medium shirt, the upsell widget will automatically recommend the Medium size for the next item, making the choice easier for them!

</details>
