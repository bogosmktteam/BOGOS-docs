# Create Cart Discount

A cart discount rewards customers with **a discount off their total cart** when they **reach a certain spending value or product quantity threshold**, motivating customers to spend more and more.

<figure><img src="../../.gitbook/assets/image (410).png" alt=""><figcaption></figcaption></figure>

**Setting up a Cart Discount offer with** [**BOGOS app**](https://apps.shopify.com/freegifts?utm_source=HelpDoc\&utm_medium=CartDiscount\&utm_campaign=Create) **includes the 9 steps:**

{% stepper %}
{% step %}
On the Menu, open All Offers > Create Offers > Discount Offer > Cart Discount.
{% endstep %}

{% step %}
[Set up offer information.](create-cart-discount.md#set-up-offer-information)
{% endstep %}

{% step %}
[Define which products the offer applies to.](create-cart-discount.md#define-offers-apply-to-which-products)
{% endstep %}

{% step %}
[Set up maximum discount uses ](create-cart-discount.md#set-up-maximum-discount-uses)(optional).
{% endstep %}

{% step %}
[Add sub-conditions](create-cart-discount.md#add-sub-conditions) (optional).
{% endstep %}

{% step %}
[Set up discounts & tiers.](create-cart-discount.md#set-up-discounts-and-tiers)
{% endstep %}

{% step %}
[Custom discount code](create-cart-discount.md#custom-discount-code) & [discount combination](create-cart-discount.md#combine-with-other-discounts) (optional).
{% endstep %}

{% step %}
Click Publish.
{% endstep %}

{% step %}
Customize the [widget display](../customize/customize-cart-discount.md#id-1.-customize-product-page-widget) & [congratulation message](../customize/customize-cart-discount.md#id-2.-customize-congrats-message).
{% endstep %}
{% endstepper %}

{% embed url="https://www.youtube.com/watch?v=n33xNlhbvDg" %}

### 1. Set up Offer Information

This section sets the basic information for your Cart Discount offer.

<figure><img src="../../.gitbook/assets/unknown (57).png" alt=""><figcaption></figcaption></figure>

To set it up, fill in these fields:

#### **1.1. Offer name**

For internal use only, helping you identify and manage multiple offers within the BOGOS app.

#### **1.2. Offer title**

The display title that introduces this discount to your customers.

#### **1.3. Block description** (optional)

Add extra details to clarify or highlight the offer.

#### **1.4. Start** and **End time** (optional)

Schedule when the offer goes live and when it ends. If left unchanged, the offer will be automatically active after publishing.

#### **1.5. Show countdown timer (optional)**

Enable a countdown timer on the widget to motivate customers to buy before the offer ends.

* This option is disabled by default. It becomes available once you set an End time or enable Recurring time.
* Without Recurring time, the countdown runs based on the End time.
* When Recurring time is set, the countdown runs based on each recurring session's End time (in days).

#### 1.6. Recurring time (optional)

Enable the offer on a repeating schedule within its active period, ideal for daily flash sales, weekend promotions, or monthly campaigns. When enabled, the active period's End time is automatically synced with the recurrence end date.

To set it up, configure the following:

**1.6.1. Frequency**

Select how often the offer repeats: Daily, Weekly, or Monthly.

* **Daily:** The offer runs every day within the chosen time window.

<figure><img src="../../.gitbook/assets/image (446).png" alt=""><figcaption></figcaption></figure>

* **Weekly:** The offer runs on selected days of the week.&#x20;

<figure><img src="../../.gitbook/assets/image (449).png" alt=""><figcaption></figcaption></figure>

* **Monthly:** The offer runs on a specific day each month. If you select day 29, 30, or 31, the offer will repeat on the month's last day if that date doesn't exist.

<figure><img src="../../.gitbook/assets/image (450).png" alt=""><figcaption></figcaption></figure>

**1.6.2. Start time (in day) / End time (in day)**

The daily time window when the offer is active during each recurring session (e.g., 09:00 to 11:00). Times are set to your store's current timezone.

**1.6.3. End recurring when**

Choose when the recurrence stops.

* **No end date:** The offer keeps recurring until you manually deactivate it.
* **On date:** The offer stops on a specific date. If you already set an End time, this field defaults to that date, but you can still change it.
* **After N times:** The offer stops after it has run a set number of times.

{% hint style="warning" %}
When created with Recurring time enabled, the offer appears with Scheduled status so you can track upcoming runs.&#x20;
{% endhint %}

{% hint style="warning" %}
If an offer expires while a customer is still in the checkout process, the discount is automatically removed, and products are charged at their original price.&#x20;
{% endhint %}

### 2. Define Offers Apply to Which Products

This setting controls which products in the cart count toward the discount condition and are eligible for the discount.&#x20;

<figure><img src="../../.gitbook/assets/image (455).png" alt="" width="563"><figcaption></figcaption></figure>

To set it up, select one of the following options:

* **Any products**: apply discount to all products in the cart.
* **All except selected products**: apply discount to all products except specific ones you choose.
* **All except selected type/vendor/collection**: apply discount to all products except those in a specific type, vendor, or collection.
* **Selected products**: apply discount only to specific products you choose.
* **Selected type/vendor/collection**: apply discount only to products in a specific type, vendor, or collection.

### 3. Set up Maximum Discount Uses

This section lets you limit how many times the discount can be claimed in total or per customer, useful for running time-limited or exclusive discounts.

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

To set it up, enable **one or both** of the following:

1. **Limit number of times this discount can be used in total:** Set a maximum number of times the discount can be redeemed across all customers (e.g., first 100 uses).&#x20;

{% hint style="info" %}
The “X/Y used” counter shows current usage (e.g., "89/100 used" means this discount has been claimed for 89 out of 100 times).
{% endhint %}

2. **Limit to one use per customer:** Ensure each customer can only redeem the discount once.

* **For logged-in customers**, BOGOS checks their account usage. If they’ve reached the limit, the Cart Discount widget will be hidden, and the discount won’t be available.
* **For guest customers**, the widget stays visible, and the discount can be applied in cart. However, at checkout, Shopify will check their email’s past orders. If the email has reached the limit, the discount is removed automatically.

### 4. Add Sub-conditions

Sub-conditions are optional to set up, but they can add extra rules to decide who can see and get your offers. Therefore, only targeted customers can see and apply the offer, while others won't see it at all.

<figure><img src="../../.gitbook/assets/unknown (60).png" alt="" width="503"><figcaption></figcaption></figure>

* **Specific link address** – Apply offers to customers accessing your store from a specific link. Perfect for email campaigns, social posts, or affiliates.
* **Order history** – Target customers based on purchase behavior. Best for rewarding first-time buyers, high spenders, and more.
* **Customer tags** – Show or hide offers based on customer tags.
* **Customer location** – Run country-specific promotions based on the customer’s IP address.
* **Markets** – Run region-specific offers based on your Shopify Markets.
* **Subscription products** – Apply the discount only when the cart contains subscription products, or only when the cart contains one-time purchase products.

{% hint style="info" %}
You can combine multiple sub-conditions. Customers must meet all selected criteria to qualify.
{% endhint %}

_For more details, visit our \[_[_Sub-Condition on Bundle, Upsell, Discount_](https://bogos-guideline.gitbook.io/user-guide/detailed-guide/detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount)_] guide._

### 5. Set up Discounts & Tiers

This section allows you to create discounts that encourage customers to buy more. You can set a single discount or use tiered discounts (spend more, save more) to reward higher spending.

![](<../../.gitbook/assets/unknown (358).png>)

{% hint style="warning" %}
If you have added the Subscription products sub-condition, choose how the discount is applied:

* **Apply discount to entire order:** The discount applies to the full cart as long as the cart contains at least one subscription (or one-time) product matching your sub-condition. In this case, the subscription product acts as the trigger, the discount is not limited to subscription items.
* **Apply discount only to eligible products:** The discount applies only to the subscription (or one-time) products matching the sub-condition. Other items in the cart are charged at full price.
{% endhint %}

If in the Offers section, you have selected **All except selected products**, **All except selected type/vendor/collection**, **Selected products**, or **Selected type/vendor/collection**, choose how the discount is applied:

* **Apply discount to entire order:** Deduct the discount from the total cart value, including non-eligible products.
* **Apply discount only to eligible products:** Deduct the discount only from the eligible products in the cart.



To set it up, fill in these fields:

1. Select the **Discount by** to choose how the discount is triggered:

* **Cart value**: Based on the total cart value (e.g., spend £100).
* **Cart quantity**: Based on the number of items in the cart (e.g., buy 5 items).



2. Select the **Discount type**:

* **Percentage**: Deduct a percentage of the total cart value (e.g., 10% off).
* **Amount**: Deduct a fixed amount from the total cart value (e.g., £10 off).



3. **Add tiers** to create a tiered discount for “spend more, save more” offer (optional).



4. Configure each tier by filling in the following fields:

* **Cart value required / Cart quantity required**: The minimum cart value or quantity a customer must reach to unlock this tier's discount.
* **Discount value**: The % or fixed amount to deduct when this tier is reached.
* **Max discount amount** (if choosing percentage discount): Set the maximum savings a customer can get (e.g., 10% off, max $10).
* **Label text**: A label displayed on the widget to help customers better understand this discount tier (e.g., "Buy $100 get 5% OFF").

{% hint style="info" %}
If you choose Cart value or Fixed amount discount or Max discount value, and also use Shopify Markets, you can “**add currency**” and **customize the money amount to each market**, instead of using Shopify’s exchange rates (e.g., SGD 10, CN¥8, A$12).

<p align="center"><img src="../../.gitbook/assets/unknown (65).png" alt="" data-size="original"></p>
{% endhint %}

### 6. Custom Discount Code

By default, BOGOS **auto-generates a random discount code** (e.g., BOGOS-XSJSC) for the discount. This code is auto-applied in the customer's cart.

However, you can replace that auto-generated code with a custom name that fits your strategy (e.g., SUMMER20). To do this, fill in the **Custom discount code** field.

<figure><img src="../../.gitbook/assets/unknown (63).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The discount code name must be under 256 characters and unique across all discounts created with Shopify Discounts.
{% endhint %}

### 7. Combine with other discounts

By default, BOGOS Cart Discount will work with any other discounts. To prevent combining, you can **untick the option** you want:

<figure><img src="../../.gitbook/assets/unknown (64).png" alt=""><figcaption></figcaption></figure>

* **Product discount**: Combine with product-level discounts
* **Order discount**: Combine with order-level discounts
* **Shipping discount**: Combine with shipping discounts

{% hint style="info" %}
Combination settings follow Shopify's discount rules. Make sure the discounts you want to combine are also configured to allow combination on their end.
{% endhint %}

### Need Help?

If you need any assistance, feel free to reach out to our customer support team via **live chat** within our BOGOS app.

