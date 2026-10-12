---
description: An overview of creating Classic bundle
---

# Create Classic Bundle

<figure><img src="../../.gitbook/assets/unknown (6).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://youtu.be/xormwYiFkRM?si=n72-y7a_tjnkEIxt" %}

### 1. Bundle information

<figure><img src="../../.gitbook/assets/image (368).png" alt=""><figcaption></figcaption></figure>

#### 1.1 Bundle name

This name is for internal management only and won’t be visible to customers.

#### 1.2 Bundle title

The bundle title is the name of the bundle, it will be displayed on the top of the bundle as the block header

#### 1.3 Bundle description&#x20;

The bundle description provides customers with more information about the deal being offered. This field is optional.&#x20;

#### 1.4 Start time and End time&#x20;

* **Start time:** The time that bundle becomes active and visible to customers on Online store and product page&#x20;
* **End time:** The time that the bundle becomes deactivated on the Online store and product page. Leave this field blank to let the bundle work continuously.&#x20;

#### 1.5. Show countdown timer (optional)

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

<figure><img src="../../.gitbook/assets/image (435).png" alt=""><figcaption></figcaption></figure>

* **Weekly:** The offer runs on selected days of the week.&#x20;

<figure><img src="../../.gitbook/assets/image (437).png" alt=""><figcaption></figcaption></figure>

* **Monthly:** The offer runs on a specific day each month. If you select day 29, 30, or 31, the offer will repeat on the month's last day if that date doesn't exist.

<figure><img src="../../.gitbook/assets/image (441).png" alt=""><figcaption></figcaption></figure>

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

### 2. Add sub-conditions

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

### 3. Select bundle

#### 3.1 Bundle item level:

Select how each item in the bundle is counted.

* **Product level:** Each product counts as one bundle item. The widget displays each product as a single line item, with an option to select the preferred variant.

<figure><img src="../../.gitbook/assets/unknown (7).png" alt=""><figcaption></figcaption></figure>

* **Variant level:** Each variant counts as one bundle item and is displayed as a separate line item on the widget.

<figure><img src="../../.gitbook/assets/unknown (8).png" alt=""><figcaption></figcaption></figure>

#### 3.2 Bundle discount type

There are two separate options for you to set up your promotion campaigns.

<figure><img src="../../.gitbook/assets/image (291).png" alt=""><figcaption></figcaption></figure>

**4 discount types**

* Percentage: percentage of the discount will be deducted from the total price of all products in bundle.
* Amount: an amount of money will be deducted from the total price of all products in bundle.&#x20;
* Fixed price: A specific price is set for all products in the bundle.
* Free gift: a free item that's automatically added to customer carts that meet the condition

**Shipping discount**

<figure><img src="../../.gitbook/assets/unknown (111).png" alt=""><figcaption></figcaption></figure>

There are 2 types of shipping discount:

* Percentage: A percentage of the shipping cost will be deducted.
* Amount: A fixed amount will be deducted from the total shipping cost.

**Label on widget:** This text informs customers whether the bundle includes a shipping discount.&#x20;

**Add currency:** If you have Shopify Markets set up, you can customize how much discount amount to offer in each currency, instead of using Shopify’s exchange rates (e.g., SGD 10, CN¥8, A$12).

<figure><img src="../../.gitbook/assets/image (377).png" alt="" width="506"><figcaption></figcaption></figure>

### 4. Display on

This setting controls which product pages will show the bundle widget.

![](<../../.gitbook/assets/unknown (445).png>)

To set it up, select one of the following options:

* **All products in this bundle (default):** The widget appears on the product page of every product in the bundle.
* **Selected products only:** The widget appears only on the product pages you choose.

Under the card, a counter line always shows: This bundle widget shows on {n} of {total} product pages, helping you track how many pages this bundle is live on.

{% hint style="warning" %}
* If you remove a product from the bundle after ticking it, it is automatically removed from the display list and the counter updates.
* If you untick all products, the bundle is saved, but the widget won't appear on any page.
{% endhint %}

### 5. Create a product for this bundle (optional)

When enabled, the bundle will have **its own product page** (bundle as a product), in addition to showing a Classic Bundle widget on product pages.

{% hint style="info" %}
Due to Shopify rules, a bundle product can’t exceed 30 bundled products, 3 options, and 100 variants.
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (9).png" alt=""><figcaption></figcaption></figure>

**To set it up:**

1. Enable “**Create a product for this bundle**”

<figure><img src="../../.gitbook/assets/unknown (10).png" alt=""><figcaption></figcaption></figure>

2. Edit the bundle **title** & **description.**
3. Select the bundle product’s **status** (active, draft, unlisted)
4. **Sync images from bundle items** (optional): Automatically show the main image of each bundled product on the storefront.
5. **Delete bundle product when deactivate this bundle** (optional): Automatically delete this bundle product from your Shopify store when this Classic Bundle offer is deactivated in BOGOS app.

**After publishing the offer**, you can return to the setup screen to quickly manage the bundle product:

* **Edit details:** Quickly edit product details such as category, inventory, and publishing channels.

<figure><img src="../../.gitbook/assets/unknown (11).png" alt=""><figcaption></figcaption></figure>

* **Sync information:** If you have edited the bundle product directly in Shopify admin, click this to sync the latest Shopify data back to BOGOS app.
* **Delete product:** Quickly delete the bundle product from Shopify. This doesn’t delete the Classic bundle offer itself.

### 6. Discount code

#### Add a custom discount code

This section allows you to customize the discount code name to match your brand.

<figure><img src="../../.gitbook/assets/image (321).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" icon="triangle-exclamation" %}
The discount code name must be under 256 characters and unique across all Shopify discounts.
{% endhint %}

### 7. Combination

By default, BOGOS bundles work with any other discounts. Untick each checkbox to disable the combination with other discounts.&#x20;

* Order discounts: discount on order level
* Shipping discount

### FAQs

<details>

<summary><strong>How does the bundle as a product (created using “Create a product for this bundle” in Classic Bundle) track the inventory?</strong></summary>

When a bundle is purchased, the inventory is deducted from each bundled item (e.g. each t-shirt), ensuring accurate stock levels and smooth fulfillment.

![](<../../.gitbook/assets/unknown (12).png>)

</details>

<details>

<summary><strong>Can the bundle as a product (created using “Create a product for this bundle” in Classic Bundle) be tracked in Shopify and BOGOS analytics?</strong></summary>

Due to Shopify’s limitations, orders with this bundle product won’t be recorded in Shopify analytics.

However, you can still track its performance in BOGOS Analytics with a clear funnel view of how it converts.

![](<../../.gitbook/assets/unknown (13).png>)

</details>

<details>

<summary><strong>Can I combine a Classic Bundle discount with other Shopify discount codes?</strong></summary>

By default, BOGOS allows you to combine bundle discounts with order discounts and shipping discounts. However, you can choose to disable this feature in the "**Combination**" section of the settings.

If both Classic bundle discount and Shopify discount apply for the same products, Shopify will only apply the highest discount code.

</details>

<details>

<summary><strong>Can I customize the discount code of my bundle to match my own campaign?</strong></summary>

Yes, you can customize the **discount code name** (up to **256 characters**) to better match your brand by going to the Discount code in the offer > tick Add a custom discount code.

![](<../../.gitbook/assets/unknown (1).png>)

</details>

<details>

<summary><strong>I have activated the classic bundle but I don’t see it. Where is it shown?</strong></summary>

By default, the bundle widget will appear on the product pages of each individual item included in the bundle.

**In order to make it shown, please follow these steps:**&#x20;

Step 1: Go to Shopify admin > Online Store > Themes > Edit Theme > Product page

![](<../../.gitbook/assets/unknown (2).png>)

Step 2: In product information, add Classic bundle block from BOGOS

![](<../../.gitbook/assets/unknown (3).png>)

Step 3: Click the Save button

</details>
