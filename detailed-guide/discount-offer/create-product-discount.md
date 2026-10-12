# Create Product Discount

A product discount **applies a discount per product** in your store, and the discounted price applies automatically in the cart, with no manual coupon entry needed.&#x20;

You can also run store-wide sales, flash sales, or private sales that rewards a specific group of customers.

![](<../../.gitbook/assets/unknown (320).png>)

Setting up a Product Discount offer with BOGOS app includes the 9 steps:

1. On the Menu, open All Offers > Create Offers > Discount > Product Discount.
2. [Set up offer information](create-product-discount.md#set-up-offer-information).
3. [Define which products the offer applies to](create-product-discount.md#define-offers-apply-to-which-products).
4. [Add sub-condition](create-product-discount.md#add-sub-condition) (optional).
5. [Set up maximum discount uses](create-product-discount.md#set-up-maximum-discount-uses) (optional).
6. [Set up a discount](create-product-discount.md#set-up-discount).
7. [Custom discount code & combination](create-product-discount.md#custom-discount-code-name-1) (optional).
8. Click Publish.
9. [Customize the display of discounted price & countdown widget](../customize/customize-product-discount.md).

{% embed url="https://youtu.be/wcDYt8VEct0?si=GRiLmJzTg2WKlN4G" %}

## 1. Set up Offer Information

This section sets the basic information for your Product Discount offer.

<figure><img src="../../.gitbook/assets/image (428).png" alt=""><figcaption></figcaption></figure>

To set it up, fill in these fields:

#### **1.1. Offer name**

For management in BOGOS only.

#### **1.2. Offer title, block description**

Text shown on the countdown timer.

#### **1.3. Start time / End time** (optional)

Schedule when the offer goes live and when it ends.

{% hint style="info" %}
Setting the offer End time will trigger a countdown timer on the product page. [Customize the countdown timer](../customize/customize-product-discount.md).
{% endhint %}

#### 1.4. Recurring time (optional)

Enable the offer on a repeating schedule within its active period, ideal for daily flash sales, weekend promotions, or monthly campaigns. When enabled, the active period's End time is automatically synced with the recurrence end date.

To set it up, configure the following:

**1.4.1. Frequency**

Select how often the offer repeats: Daily, or Weekly.

* **Daily:** The offer runs every day within the chosen time window.

<figure><img src="../../.gitbook/assets/image (452).png" alt=""><figcaption></figcaption></figure>

* **Weekly:** The offer runs on selected days of the week.&#x20;

<figure><img src="../../.gitbook/assets/image (454).png" alt=""><figcaption></figcaption></figure>

**1.4.2. Start time (in day) / End time (in day)**

The daily time window when the offer is active during each recurring session (e.g., 09:00 to 11:00). Times are set to your store's current timezone.

{% hint style="warning" %}
When created with Recurring time enabled, the offer appears with Scheduled status so you can track upcoming runs.&#x20;
{% endhint %}

{% hint style="warning" %}
If an offer expires while a customer is still in the checkout process, the discount is automatically removed, and products are charged at their original price.&#x20;
{% endhint %}

## 2. Define Offers Apply to Which Products

This setting controls which products the discount applies to.

![](<../../.gitbook/assets/unknown (323).png>)

To set it up, select one of the following from Apply discount to:

* any products
* all except selected products
* all except selected types/vendors/collections
* selected products
* products in selected types/vendors/collections

{% hint style="warning" %}
When a product has multiple discounts active at the same time, only the largest discount is applied.&#x20;
{% endhint %}

## 3. Add Sub-condition

Sub-conditions add extra rules that decide who can see and receive the discount. Only customers who meet the conditions will see and get the offer; others won't see it at all.

![](<../../.gitbook/assets/unknown (326).png>)

Click Add sub-condition, then choose one or more:

* Specific link address
* Customers' order history
* Customer tags
* Customer location
* Markets
* Subscription products

{% hint style="info" %}
You can combine multiple sub-conditions. Customers must meet ALL selected criteria to qualify.
{% endhint %}

_For more details, visit our \[_[_Sub-Condition on Bundle, Upsell, Discount_](../detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md)_] guide._

{% hint style="warning" %}
When Subscription products is set, the discount badge only shows on the matching purchase option. The product price does not update automatically on the product page; instead, a note appears (e.g., "+10% OFF discount will auto apply in cart"). You can customize this note in [Customize Product Discount](../customize/customize-product-discount.md).
{% endhint %}

## 4. Set up Maximum Discount Uses

This section lets you limit how many times the discount can be claimed in total or per customer, useful for running time-limited or exclusive discounts.

![](<../../.gitbook/assets/unknown (341).png>)

To set it up, enable one or both of the following:

* **Limit number of times this discount can be used in total**: Set a maximum number of times the discount can be redeemed across all customers.

{% hint style="info" %}
The “X/Y used” counter shows current usage.
{% endhint %}

* **Limit to one use per customer**: Ensure each customer can only redeem the discount once.
  * **For logged-in customers**, BOGOS checks their account usage. If they’ve reached the limit, the discount will be hidden and unavailable.
  * **For guest customers**, the discount stays visible and can be applied in cart. However, at checkout, BOGOS will check their email’s past orders. If the email has reached the limit, the discount is removed automatically.

## 5. Set up Discount

This section sets how much customers save.

![](<../../.gitbook/assets/unknown (329).png>)

To set it up, fill in these fields:

* **Discount type**: Choose how the discount is calculated:
  * Percentage (e.g., 10% off)
  * Fixed amount (e.g., $10 off)
  * Fixed price (e.g., buy this product at $9.99) (tip: a flat-price sale across your whole store).
* **Set maximum discount value** (for Percentage only): Cap the maximum amount a customer can save
  * Example: 10% off, up to $10.
* **Override cents**: Replace the cents portion of the final price with a value you set, for cleaner price endings.
  * Example: Override cents = 0.99 means if the discounted price is $12.34, the final price shown to customers is $12.99.
* **Add currency** (for Fixed amount, Fixed price, Maximum discount value only): If you use Shopify Markets, you can add currency to set a custom discount value for each market's currency.

<img src="../../.gitbook/assets/unknown (331).png" alt="" height="150" width="447">

<br>

## 6. Custom Discount Code Name

![](<../../.gitbook/assets/unknown (333).png>)

### 6.1. Add a custom discount code name

By default, BOGOS auto-generates and auto-applies a discount code for the offer (e.g; BOGOS-PpOp12).

To customize that code, tick **Add a custom discount code** and enter a name that fits your strategy (e.g., SUMMER20).&#x20;

![](<../../.gitbook/assets/unknown (335).png>)

{% hint style="info" %}
The code must be under 256 characters and unique across all discounts created with Shopify Discounts.
{% endhint %}

### 6.2. Combine with other discounts

By default, the product discount can combine with Order and Shipping discounts. Combination follows Shopify's discount rules. Make sure the other discounts are also set to allow combination on their end.

To stop it from combining, **untick the option** you don't want.

### Need Help?

If you need any assistance, feel free to reach out to our customer support team via live chat within our BOGOS app.
