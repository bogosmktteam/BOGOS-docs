# Create Discount on Cheapest/Most Expensive Item

{% embed url="https://youtu.be/Due8rU6VqB8?si=yA54zHhoV3q_QIkS" %}

This feature allows you to apply a discount on either the cheapest or the most expensive item in the customer’s cart.

To get started, follow these steps:

* Find **Create offer** in **All offers** section or **BOGOS dashboard.**
* Choose the **Discount offer.**
* Click **Discount on Cheapest/Most expensive Item**, then select **Create discount.**

Then fill in the details to complete your offer setup.

### 1. Offer information&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeqNcvmaFprT1PZerj919znbObL8pojws70jG3ScU1PZgh2AUamCq_GblwqzDxAHf723J6mjWGCEY1urVoqLPm5wxN9I28gKVp5jMT3PUY4jc96aAZ3QJIvi3mFuFECruVHAoXXcw?key=APwpMqxaYlxpG4ng8MqyiA" alt=""><figcaption></figcaption></figure>

#### **1.1. Offer name**

The internal name of the offer. It won’t be shown to customers, only stored in the All Offers section for management.

#### **1.2. Display on widget**&#x20;

* **Widget title:** The public title displayed on the store that customers will see.
* **Block description:** Details about the offer to help customers better understand it.

#### **1.3. Start time and End time**

* **Start time:** The exact time the offer begins.
* **End time:** The exact time the offer ends.

#### 1.4. Show countdown timer (optional)

Enable a countdown timer on the widget to motivate customers to buy before the offer ends.

* This option is disabled by default. It becomes available once you set an End time or enable Recurring time.
* Without Recurring time, the countdown runs based on the End time.
* When Recurring time is set, the countdown runs based on each recurring session's End time (in days).

#### 1.5. Recurring time (optional)

Enable the offer on a repeating schedule within its active period, ideal for daily flash sales, weekend promotions, or monthly campaigns. When enabled, the active period's End time is automatically synced with the recurrence end date.

To set it up, configure the following:

**1.5.1. Frequency**

Select how often the offer repeats: Daily, Weekly, or Monthly.

* **Daily:** The offer runs every day within the chosen time window.

<figure><img src="../../.gitbook/assets/image (442).png" alt=""><figcaption></figcaption></figure>

* **Weekly:** The offer runs on selected days of the week.&#x20;

<figure><img src="../../.gitbook/assets/image (444).png" alt=""><figcaption></figcaption></figure>

* **Monthly:** The offer runs on a specific day each month. If you select day 29, 30, or 31, the offer will repeat on the month's last day if that date doesn't exist.

<figure><img src="../../.gitbook/assets/image (445).png" alt=""><figcaption></figcaption></figure>

**1.5.2. Start time (in day) / End time (in day)**

The daily time window when the offer is active during each recurring session (e.g., 09:00 to 11:00). Times are set to your store's current timezone.

**1.5.3. End recurring when**

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

### 2. Offers&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdKhIcXfKM6FgLqG_FM5eDjVV4ExOxJ8pfJpuaUiIkC-8woNlvt8ogZYZ7-4s9_IeDXvWw_O7RmInYGXs5ISBQJKy0plTUaDO14mGHoJ5a2yQdFbrQwu8tV0MkZS9A6y6QVhE85eA?key=APwpMqxaYlxpG4ng8MqyiA" alt=""><figcaption></figcaption></figure>

This section lets you choose which products the offer applies to:

* **Any products:** Applies to all products in your store.
* **All except selected products:** Applies to all products except the specific products you select.
* **All except selected types/vendors/collections:** Applies to everything except the types, vendors, or collections you select.
* **Selected products:** Applies only to the chosen products.
* **Products in selected types/vendors/collections:** Applies only to products within the chosen types, vendors, or collections.

Enabling the **Count unique products only** option changes how item quantities are counted for the offer:

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXcMpeHm8wBHTQwjsyIWsuJGGYCH1q1KAxFshgLddGblFFk80TVU6qABQEbk9JX8Urv332fpihkF5r0SXG8LbkW--tDn78YATJlU5W-qNui9I8lx2SbS0GTJSuEUF8CCML62PWUzxw?key=APwpMqxaYlxpG4ng8MqyiA" alt=""><figcaption></figcaption></figure>

* **Unique by product:** Each product is counted once, even if it has multiple variants or quantities.

_Example: 2×T-shirt (Red), 2×T-shirt (Blue), 2×Shoes (Size 42), 1×Hat (Black) = 3 products counted (T-shirt, Shoes, Hat)._

* **Unique by variant:** Each variant is counted once, even if it appears multiple times.

_Example: 2×T-shirt (Red), 2×T-shirt (Blue), 2×Shoes (Size 42), 1×Hat (Black) = 4 variants counted  (T-shirt Red, T-shirt Blue, Shoes Size 42, Hat Black)._

### 3. Add sub-conditions

Sub-conditions add extra rules to decide who can see and get your offers. Therefore, only targeted customers can see and apply the offer, while others won't see it at all.

{% hint style="info" %}
* These sub-conditions are optional. If you don't add any, the offer will be available to all customers.
* You can combine multiple sub-conditions. Customers must meet all selected criteria to qualify.
{% endhint %}

![](<../../.gitbook/assets/unknown (463).png>)

1. _Specific link address_ – Apply offers to customers accessing your store from a specific link. Perfect for email campaigns, social posts, or affiliates.
2. _Order history_ – Target customers based on purchase behavior. Best for rewarding first-time buyers, high spenders, and more.
3. _Customer tags_ – Show or hide offers based on customer tags.
4. _Customer location_ – Run country-specific promotions based on the customer’s IP address.
5. _Markets_ – Run region-specific offers based on your Shopify Markets.
6. _Subscription products_ – Apply the offer only to subscription products or only to one-time purchase products

♦️ For more details, visit our \[[Sub-Condition](../detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md)] guide.

When Subscription products is set, only matching products appear in the widget's product list; the others are hidden. For subscription products, customers can choose a subscription plan directly from the widget through a purchase option modal. You can customize this modal in [Customize Discount on Cheapest/Most Expensive Item](../customize/customize-discount-on-cheapest-most-expensive-item.md).

### 4. Tiers

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXeJuXCBuSq1hInWb63o-YQ9WX1nVnhM49_ryLojenY6sU6rLBgIverKQtaZ6GKo7Q8JwY4PhVFD_3csBQZSStpNZK5yp6XTTjsEHc4JWSl5g18wNxL9y7P5SdGqEXI-1m2WVwRrAw?key=APwpMqxaYlxpG4ng8MqyiA" alt=""><figcaption></figcaption></figure>

This section controls how the discount is applied based on the number of items a customer buys.

**Discount on:** Choose whether the discount applies to the cheapest item or the most expensive item in the cart.

**Tier setup:** Complete the essential fields for each tier

* **Number of items required:** The number of items a customer must buy to qualify for the offer.
* **Number of discounted items:** The number of items that will receive the discount.
* **Type:** Select the discount type. There are 3 options:
  * **Percentage:** Deduct a percentage from the price of each discounted item. Enter the percentage in the **Value** field.
  * **Amount:** Deduct a fixed amount from the price of each discounted item. Enter the amount in the **Value** field.
  * **Fixed price per item:** Set a fixed final price for each discounted item, regardless of its original price (e.g., set the 2nd item to just $1). Enter the price in the **Price per item** field. Items priced at or below the fixed price still count toward the required quantity but won't receive the discount.
* **Add currency** (for Amount and Fixed price per item): If you also sell in different currencies (set up in Shopify Markets), you can Add currency and customize the amount or fixed price for each currency, instead of using Shopify's exchange rates (e.g., SGD 10, CN¥8, A$12).

<figure><img src="../../.gitbook/assets/unknown (118).png" alt="" width="563"><figcaption></figcaption></figure>

* **Label text:** The message shown to customers in the tier widget, explaining the offer.
* **Add tier:** Add more discount tiers to encourage larger purchases with bigger rewards.
* **Multiply last tier:** When enabled, the multiply logic applies only to the last tier. Within an offer, only the tier with the highest quantity can be applied with the multiply function. Our system will automatically detect and apply this tier, even if it is not the last one.

{% hint style="warning" %}
Within an offer, only the tier with the highest quantity can be applied with **multiply** function. Our system will automatically detect and apply this tier, even if it is not the last one.&#x20;
{% endhint %}

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdOJshF0z0Q2dHzsAsMVrSNkBs6xKn4kkRHdKAl0ZL0tUA930ugDW7WZaXpVbeYAVLZsG2nAR6ptDEF4zwjw-MjtufpAU97JDv-VqtRerxaP-oWtp7eBVrlxM_yXg6R8yRsROn7GA?key=APwpMqxaYlxpG4ng8MqyiA" alt=""><figcaption></figcaption></figure>

### 5. Discount code&#x20;

<figure><img src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXdFNBqJ54z9rZ1ZNeW1V9w6QGDsTqFffyYbv7RJxaLs8CTcc7mpYsdXe4jELh4It1X7w6H0uAAMpqbiQpcW42rdvN3dJ0CG0MjOryAhlFTFyUAxpkuI4Uh3PRW5De8i3BljDuCj?key=APwpMqxaYlxpG4ng8MqyiA" alt=""><figcaption></figcaption></figure>

* **Add a discount code:** Create a custom code name that matches your brand.

{% hint style="warning" %}
In case you left unchecked, BOGOS will automatically apply its default discount code.
{% endhint %}

* **Combination with other discounts:** By default, BOGOS discount offers work with other discounts,including Order discounts and Shipping discounts. Untick one of these checkbox to disable the combination with that type of discount.

## FAQs

<details>

<summary><strong>Can we apply the cheapest discount for customers without them purchasing from the Cheapest discount widget?</strong></summary>

Yes. The “Discount on Cheapest/Most Expensive Item” works on the cart, not only via its widget.

As long as:

* The Discount on Cheapest/Most Expensive Item offer is active, and
* The cart meets the tier conditions (products included in the offer + number of items required),

BOGOS will automatically apply the Cheapest discount‑item discount on cart even if the customer never adds products through the Cheapest Discount widget. The widget is only for promoting/visualizing the deal.

</details>

<details>

<summary><strong>Is it possible to ONLY apply the cheapest discount to different products?</strong></summary>

Yes. You can limit the Cheapest discount to only a specific group of different products.&#x20;

Step 1: In your Discount on Cheapest/Most Expensive Item offer

Step 2: Tick the box Count unique products only

* Unique by product
* Unique by variant

</details>

<details>

<summary><strong>Is there any way to run the Cheapest Discounts for customers from specific countries?</strong></summary>

Yes. You can target Cheapest/Most Expensive Item discounts by customer country.

Please follow the steps:&#x20;

Step 1: Go to BOGOS > Create offer > Discount offer > Discount on Cheapest/Most expensive Item.

Step 2: Set up your tiers as usual (Cheapest discount/most expensive, items required, discount type/value, etc.).

Step 3: Add the Customer Location sub-condition.

<div align="left"><img src="../../.gitbook/assets/unknown (253).png" alt="" height="179" width="316"></div>

<div align="left"><img src="../../.gitbook/assets/unknown (254).png" alt="" height="192" width="321"></div>

<div align="left"><img src="../../.gitbook/assets/unknown (255).png" alt="" height="153" width="328"></div>

* Choose the country/countries you want to include, or
* Choose them and tick “Exclude customers from selected locations” if you want to block them instead.

Step 4: Save and activate the offer

This way, the Cheapest Item discount only runs for customers from the selected countries.

</details>

<details>

<summary><strong>Can I exclude wholesale customers from my Cheapest Discount offers?</strong></summary>

Yes sure, please follow the steps below:

Step 1: Go to BOGOS > Create offer > Discount offer > Discount on Cheapest/Most expensive Items.

Step 2: Set up your tiers as usual (Cheapest discount/most expensive, items required, discount type/value, etc.)

Step 3: Add Sub-condition > Select Customers tag > Add the Wholesale tag

<div align="left"><img src="../../.gitbook/assets/unknown (256).png" alt="" height="161" width="261"></div>

<div align="left"><img src="../../.gitbook/assets/unknown (257).png" alt="" height="287" width="283"></div>

Step 4: Tick the checkbox Exclude customers with these tags

<div align="left"><img src="../../.gitbook/assets/unknown (258).png" alt="" height="249" width="369"></div>

{% hint style="warning" %}
Please note that customers have to log in their customer accounts to see the offer. In case you want to allow non-login customers to get discounts, please tick the box Consider no-login as a customer with no tags
{% endhint %}

<div align="left"><img src="../../.gitbook/assets/unknown (259).png" alt="" height="259" width="365"></div>

</details>

<details>

<summary><strong>How to achieve the offer: Buy 2 get 1 free, Buy 4 get 2, and so on?</strong></summary>

Please follow the steps here:

Step 1: Go to BOGOS > Create offer > Discount offer > Discount on Cheapest/Most expensive Items.

Step 2: Set up your tiers as usual (Cheapest discount/most expensive, items required, discount type/value, etc.)

Step 3: Under Tiers, please tick the box Multiply last tier

<div align="left"><img src="../../.gitbook/assets/unknown (260).png" alt="" height="299" width="292"></div>

</details>
