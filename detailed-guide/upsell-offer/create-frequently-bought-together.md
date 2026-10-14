---
description: >-
  Frequently bought together upsell allows you to offer additional products to
  customers at product page, helping to increase your average order value (AOV)
  and scale your sales.
---

# Create Frequently Bought Together

There are 3 upsell widget types:

1. **Frequently Bought Together**

![](<../../.gitbook/assets/unknown (276).png>)

{% embed url="https://youtu.be/KL0GlTxJFoY?si=Ppx8wzoMH6AASzVl" %}

2. **Product Add-on**

![](<../../.gitbook/assets/unknown (277).png>)

{% embed url="https://youtu.be/JVkftQsJ45o?si=_wiWOBkffz_X3StK" %}

3. **Product Recommendation in Cart Drawer & Cart Page**

<figure><img src="../../.gitbook/assets/image (478).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://youtu.be/y8yLwfSEQTo?si=MxrQIhIczwL3NVJ6" %}

Creating Frequently Bought Together upsell with BOGOS includes the **9 steps**:

1. Open All Offers> Create Offer > Upsell > Frequently Bought Together.
2. Set up [upsell information](create-frequently-bought-together.md#id-1.-upsell-information).
3. Define [Upsell trigger](create-frequently-bought-together.md#id-2.-upsell-trigger), when the widget will appear to your customers.
4. Add [Sub-conditions](create-frequently-bought-together.md#id-3.-add-sub-conditions) to decide who can get your offers (optional).
5. Define [Upsell method](create-frequently-bought-together.md#id-4.-upsell-method) to choose the upsell products.
6. Set [Display placement](create-frequently-bought-together.md#id-5.-display-placement) to choose where the widget appears.
7. Set up a [discount](create-frequently-bought-together.md#id-6.-discount) (optional).
8. [Custom discount code](create-frequently-bought-together.md#id-7.1-custom-discount-code) & [discount combination](create-frequently-bought-together.md#id-7.2-combine-with-other-discounts) (optional).
9. Click Publish.
10. [Customize the widget display](../customize/customize-frequently-bought-together.md).

## 1. Upsell information

* **Upsell name** is the name of the upsell, which isn’t visible to customers and is displayed in the “All offers” section of the BOGOS app for easy management alongside other offers.
* **Widget title** introduces the upsell offer to customers and encourages them to explore additional products. It will be displayed prominently on the product page.
* **Widget sub-title** appears below the widget title and complements the title by explaining the value of the upsell.&#x20;
* **Start and end time** for the upsell offer. If you want the offer to be available indefinitely, leave the "End time" field empty.

## 2. Upsell trigger

Define how the Frequently Bought Together upsell will appear to your customers. Choose from the options below to control which products or collections will display the upsell.

### 2.1 Always display upsell

The upsell will be shown on all product pages with no triggers.

### 2.2 Selected products

The upsell will only be displayed on the specific products you choose. This is useful when you want to target specific items that are frequently purchased together.

### 2.3 All except selected products

The upsell will be shown on all product pages except for the specific products you exclude. This option prevents the upsell from appearing on products that do not need additional recommendations.

### 2.4 Selected collections/types/vendors

The upsell will appear only on products that match the selected collection(s), product type(s), and vendor(s).

{% hint style="info" %}
* The conditions between collections, types, and vendors work on an **AND** basis. This means the product must match all selected criteria to trigger the upsell.
* The conditions within each selected collection, type, or vendor work on an **OR** basis. This means the upsell will trigger if a product belongs to any of the selected collections, types, or vendors.
{% endhint %}

**Example:**

* If you select Collection A, Product Type B, and Vendor C, the upsell will only appear on products that belong to Collection A AND Product Type B AND are from Vendor C.&#x20;
* However, if you select multiple collections (e.g., Collection A and Collection D), the upsell will appear on products from either Collection A OR Collection D, as long as they also match the selected product type and vendor.

### 2.5 All except selected collections/types/vendor

The upsell will be displayed on all product pages except those in the selected collections, product types, or vendors.

## 3. Add sub-conditions

Sub-conditions add extra rules to decide who can see and get your offers. Therefore, only targeted customers can see and apply the offer, while others won't see it at all.

{% hint style="info" %}
* These sub-conditions are optional. If you don't add any, the offer will be available to all customers.
* You can combine multiple sub-conditions. Customers must meet all selected criteria to qualify.
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (154).png" alt="" width="503"><figcaption></figcaption></figure>

1. _Specific link address_ – Apply offers to customers accessing your store from a specific link. Perfect for email campaigns, social posts, or affiliates.
2. _Order history_ – Target customers based on purchase behavior. Best for rewarding first-time buyers, high spenders, and more.
3. _Customer tags_ – Show or hide offers based on customer tags.
4. _Customer location_ – Run country-specific promotions based on the customer’s IP address.
5. _Markets_ – Run region-specific offers based on your Shopify Markets.

♦️ For more details, visit our \[[Sub-Condition](../detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md)] guide.

## 4. Upsell method

### 4.1 Upsell widget type

Choose the widget type that best fits how you want to display upsell products on the product page:

<table data-header-hidden><thead><tr><th width="128"></th><th width="293.6667175292969"></th><th></th></tr></thead><tbody><tr><td><strong>Upsell Widget Type</strong></td><td><strong>Frequently Bought Together</strong></td><td><strong>Product Add-on</strong></td></tr><tr><td></td><td>Encouraging customers to buy a group of products, including the trigger product.</td><td>Encouraging customers to buy more add-ons alongside the main item</td></tr><tr><td>Widget display</td><td><p>- Stack</p><p>- Amazon:</p><p><img src="../../.gitbook/assets/unknown (265).png" alt="" data-size="original"></p></td><td><p>- Horizontal</p><p>- Vertical:</p><p><img src="../../.gitbook/assets/unknown (266).png" alt="" data-size="original"></p></td></tr><tr><td>Checkbox</td><td>Enabled by default</td><td>Unenabled by default</td></tr><tr><td>Add to Cart Button</td><td>Uses the widget's own button to get discount</td><td>Uses your store's default Add to cart button</td></tr><tr><td>The trigger product can be discounted</td><td>Yes, it’s optional</td><td>No, only upsell products will be discounted</td></tr></tbody></table>

### 4.2 Select Method

Select how you want to choose the upsell products. There are three methods: **Manual, Auto, and Random.**

#### 4.2.1 Manual

Manually select the products you want to upsell. You can specify which products will be displayed as upsell recommendations.&#x20;

#### 4.2.2 Auto

To use this option, you must install the [Shopify Search & Discovery app](https://apps.shopify.com/search-and-discovery) (free) in your store. BOGOS will automatically select upsell products based on the data synchronized with this app.

In BOGOS settings, there are two recommendation types synced from the Shopify Search & Discovery app:

* **Complementary Products:** You manually select recommended products within the Shopify Search & Discovery app.
* **Related Products**: Shopify’s AI auto-generates product recommendations based on store data.

{% hint style="info" %}
For “Complementary products” you must manually select products within the Shopify Search & Discovery app.&#x20;

For “Related Products,” Shopify uses AI to auto-generate product recommendations.

[Click here to view its help docs.](https://help.shopify.com/en/manual/online-store/search-and-discovery/product-recommendations)
{% endhint %}

#### 4.2.3 Random

With this option, BOGOS will randomly display upsell products based on your preferences.

* **Number of upsell products:** Set the number of products that will be recommended.
* **Selection criteria**: Choose where the random products should be selected from:
  * In selected types only
  * In selected vendors only
  * In selected collections only

### 4.3. Set quantity for current item

<img src="../../.gitbook/assets/unknown (267).png" alt="" height="313.84615384615387" width="610.307210031348">

By default, the widget **shows 1 of the main item on the page** (also called the current or trigger product).

To change this, enable “Set quantity for current item” and enter a new number.

{% hint style="info" %}
Only available for the Frequently Bought Together widget type.&#x20;

For Product Add-ons, the quantity automatically matches your store's main quantity selector.
{% endhint %}

### 4.4 Upsell product quantity

This setting controls **how the quantity of upsell products** is handled. Please choose between:

* **Allow customers to change quantity**: Let customers adjust the quantity of each product.
* **Fixed quantity**: Sets a fixed quantity for upsell products. Customers can’t change the quantity on the widget, but they can still adjust it in the cart later.
  * If the “**Manual**” method is used, enter the quantity directly in the product selection fields to set a custom fixed quantity.
  * If the "**Auto**" or "**Random**" select method is used, the widget auto-shows 1 product.

{% hint style="info" %}
Fixed quantity option goes with Multiply discount logic (explained in [6. Discount](create-frequently-bought-together.md#id-6.-discount) section).
{% endhint %}

## 5. Display placement

This setting controls where the upsell widget appears on your store. You can display the offer on one or multiple surfaces to reach customers at different steps of their shopping journey.

![](<../../.gitbook/assets/unknown (374).png>)

To set it up, select at least one of the following to show the upsell widget on:

* Product page
* Cart page
* Cart drawer

{% hint style="warning" %}
On the cart page & cart drawer, the offer shows when the cart contains the trigger product (not while viewing it). One upsell offer is shown at a time; the first offer that meets its trigger conditions is displayed.
{% endhint %}

## 6. Discount

### 6.1 Enable discount

**If unchecked**, customers will add the upsell products at their regular price.

**If checked**, a discount is applied to your upsell products. **Multiply logic** will also apply by default, meaning the discount scales up with the number of products in the cart.

For example, if a customer adds 1x Trigger Product A + 2x Upsell Product B (at 10% off):

* Increasing to 2x A + 4x B → all 4x B are discounted.
* Increasing to 2x A + 3x B → 2x B are discounted, 1x B is added at full price.

{% hint style="info" %}
Multiply logic scales by the number of unique products for Frequently Bought Together, but it depends on your "[When trigger product is removed](create-frequently-bought-together.md#id-6.3-discount-product-add-on-widget)" setting for Product Add-ons.
{% endhint %}

### 6.2 Discount/ Frequently Bought Together widget

To set a discount using Frequently Bought Together widget, please follow these steps:

<img src="../../.gitbook/assets/unknown (271).png" alt="" height="269" width="624">

1. Enter **Number of unique products required for discount**. Multiple quantities of the same item only count as 1 unique product.

{% hint style="info" %}
Multiply logic is based on this number.
{% endhint %}

2. **Apply discount to:**

* **Any item:** The discount applies to both the trigger and upsell products.
* **Any item, except the current one:** The discount applies to the upsell products only. The trigger product is added at full price.

3. Select **Type**

{% hint style="info" %}
Discount is applied to the **total price** of all selected products.
{% endhint %}

* **Percentage** (e.g., 10% off).
* **Amount** (e.g., $10 off). If you have set up Shopify Markets, click **Add currency** to set a custom discount amount for each currency (e.g., Singapore customers get $10 off, while European get €12 off).

<figure><img src="../../.gitbook/assets/unknown (72).png" alt="" width="563"><figcaption></figcaption></figure>

* **Cheapest item free:** Automatically makes the cheapest item in the widget free.\\

4. **Add shipping discount**

<figure><img src="../../.gitbook/assets/image (27).png" alt="" width="461"><figcaption></figcaption></figure>

There are two types of shipping discount:

* **Percentage**: A percentage of the shipping cost will be deducted.
* **Amount:** A fixed amount will be deducted from the total shipping cost. If you sell in different currencies (set up in Shopify Markets), you can **Add currency** and custom how much shipping discount amount to offer in each currency.

**Label on widget**: This text informs customers whether the offer includes a shipping discount.

### 6.3 Discount/ Product Add-on Widget

To set a discount using the Product Add-on widget, please follow these steps:

<img src="../../.gitbook/assets/unknown (272).png" alt="" height="344" width="624">

1. Select **When trigger product is removed** (what happens to upsell products if the trigger product is removed from the cart):

* **Remove discount:** The discount is removed from all upsell products. Under _**Multiply logic**_, customers must multiply the quantity of both trigger and upsell items.
* **Keep discount:** The discount remains on all upsell products. Under _**Multiply logic**_, customers just have to multiply the quantity of upsell items.

2. Set **Limit number of discounted items** (optional): If you enter 1 in this field while offering 3 upsell products, the discount will apply to just 1 item. Others will be added at full price.
3. Select **Type**

{% hint style="info" %}
Discount is applied to the price of each upsell product.<br>
{% endhint %}

* **Percentage** (e.g., 10% off).
* **Amount** (e.g., $10 off). If you have set up Shopify Markets, click **Add currency** to set a custom discount amount for each currency (e.g., US customers get $10 off, while Canadian customers get CA$20 off).

## 7. Discount code

### 7.1 Custom discount code

By default, BOGOS **auto-generates a random discount code** (e.g., BOGOS-XSJSC) for the discount. This code is auto-applied in the customer's cart.

However, you can replace that auto-generated code with a custom name that fits your strategy (e.g., SUMMER20). To do this, fill in the **Custom discount code** field.

<figure><img src="../../.gitbook/assets/unknown (63).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The discount code name must be under 256 characters and unique across all discounts created with Shopify Discounts.
{% endhint %}

### 7.2 Combine with other discounts

By default, BOGOS Frequently Bought Together will work with any other discounts. To prevent combining, you can **untick the option** you want:

<figure><img src="../../.gitbook/assets/image (325).png" alt=""><figcaption></figcaption></figure>

* **Order discount**: Indicates if the upsell discount can be combined with order-level discounts, such as promotional codes or automatic discounts.
* **Shipping discount**: Indicates if the upsell discount can be combined with shipping discounts, such as free or reduced shipping promotions.

{% hint style="info" %}
Combination settings follow Shopify's discount rules. Make sure the discounts you want to combine are also configured to allow combination on their end.
{% endhint %}

## Need Help?

If you need any assistance, feel free to reach out to our customer support team via **live chat** within our BOGOS app.

## FAQs

<details>

<summary><strong>Is it possible to set up “Get Free shipping when buying upsell products”</strong></summary>

Yes, you can certainly set that up. As illustrated in the screenshot, you'll need to set the **Product Discount to 0%** and the **Shipping Discount to 100%**. This effectively offers free shipping when buying the upsell items without discounting the items themselves.

![](<../../.gitbook/assets/unknown (214).png>)

</details>

<details>

<summary><strong>Is it possible to apply a discount for only upsell products</strong></summary>

Yes. In the discount settings, you can choose to apply the discount to **"Any item, except for the current one"** (the main product).

![](<../../.gitbook/assets/unknown (215).png>)

</details>

<details>

<summary><strong>How can I change the position of Frequently bought together widget?</strong></summary>

In order to change the position of Frequently bought together widget, please follow these steps:&#x20;

* Step 1: Go to Shopify admin > Online Store > Themes > Edit Theme > Product page

![](<../../.gitbook/assets/unknown (216).png>)

* Step 2: In product information, click Add “Frequently bought together” block in the position you want

![](<../../.gitbook/assets/unknown (217).png>)

</details>
