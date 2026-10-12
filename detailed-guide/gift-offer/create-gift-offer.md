# Create gift offer

**Before you begin:**&#x20;

Check [this guide](https://youtu.be/R-DeHLuCFOw) to see how you can create a free gift with purchase on Shopfy with BOGOS.

{% embed url="https://youtu.be/R-DeHLuCFOw" %}

Creating a gift offer consists of **5 fundamental parts**:

* Offer information
* Offer main condition
* Offer sub-condition&#x20;
* Select gift
* Advanced configuration (optional)

### 1. Offer information

<div data-full-width="false"><figure><img src="../../.gitbook/assets/image (367).png" alt=""><figcaption></figcaption></figure></div>

#### 1.1. Offer name

This name is for internal management only and won’t be visible to customers.

#### 1.2. Offer title

The offer title is the name of the offer. It appears in the All Offers management page and shows to customers in the Today Offer widget, Gift thumbnail, and Gift slider.

#### 1.3. Start time and End time

* Start time: The time that the offer starts working.
* End time (optional): The time that the offer stops working.&#x20;

### 2. Offer main conditions

Main condition is the condition that customers need to reach to get the gift of the offer.

<figure><img src="../../.gitbook/assets/image (95).png" alt="" width="496"><figcaption><p>Main condition selection modal</p></figcaption></figure>

#### **2.1. Cart value condition**

<figure><img src="../../.gitbook/assets/unknown (99).png" alt="" width="563"><figcaption></figcaption></figure>

* This condition lets you set the **minimum and/or maximum cart value** customers must reach to qualify for your gift offer.
* The cart value you enter is based on your store’s main currency (e.g., SGD as shown in the image).
* **For stores that have Shopify Markets set up:**

<figure><img src="../../.gitbook/assets/unknown (100).png" alt="" width="563"><figcaption></figcaption></figure>

Normally, BOGOS will auto-convert your main currency to the customers’ currency using Shopify’s exchange rate (e.g., 1 SGD = €0.666).

However, if you want to **set custom cart values for each currency** instead, after setting the value for your main market (min is 0), click “Add currency” and enter the value&#x20;

_Example: Customers from Europe must spend €300 to get the gift, while Australian customers just need to spend A$100._

* **The condition will apply to:**

▶ Any products: all products in cart will be counted toward the cart value condition.

▶ All except selected products: All except selected products' value will be counted toward cart value condition.

▶ All except selected types/vendors/collections: All except products selected by the condition of types/vendors/collections will be counted toward cart value condition.

▶ Selected products: Only products chosen below will be counted toward the cart value condition.

▶ Products in selected types/vendors/collections: Only products chosen by the condition of types/vendors/collections will be counted toward the cart value condition.

#### **2.2. Cart quantity condition**

<figure><img src="../../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

* Min: Minimum cart quantity customers need to reach to get the gift of the offer.
* Max: Maximum cart quantity customers need to stay below to get the gift of the offer.

**The condition will apply to:**

▶ Any products: all products in cart will be counted toward the cart quantity condition.

▶ All except selected products: All except selected products' value will be counted toward cart quantity condition.

▶ All except selected types/vendors/collections: All except products selected by the condition of types/vendors/collections will be counted toward cart quantity condition.

▶ Selected products: Only products chosen below will be counted toward cart quantity condition.

▶ Products in selected types/vendors/collections: Only products chosen by the condition of types/vendors/collections will be counted toward cart quantity condition.

#### **2.3. Specific product condition**

![](<../../.gitbook/assets/unknown (393).png>)

* **Number of products required:** Number of products that customers need to buy to get gifts.
* **Multiply gifts with number of products:** If customers purchase more than the required products, they will get more gifts.&#x20;

_Example: Buy 2 get 1, Buy 4 get 2, Buy 6 get 3, and more._

* **Match gift with selected products:** Tick this checkbox to decide how the gift customers receive relates to the products they buy. Then choose:
  * **Gifts will be the same:** Customers receive the same product they bought as their gift. Then select Same by product or Same by variant.
  * **Gift will match variant:** Customers receive a different product as their gift, but the variant automatically matches an option (e.g., Size/Color) of the product they bought.

{% hint style="warning" %}
Only available when the condition will apply to is set to selected products.
{% endhint %}

![](<../../.gitbook/assets/unknown (394).png>)

When **Gift will match variant** is selected, two more fields appear:

* **Choose an option to match:** Pick the option (e.g., Size, Color) that BOGOS uses to match the gift variant to the purchased product.
* **When the matched option of the gift is unavailable:** Choose what happens if no matching gift variant exists (e.g., the customer buys size S but the gift product has no size S, or size S is out of stock):
  * **Let customer choose the remaining options:** Show the available variants of the gift in the Gift slider for the customer to pick.
  * **Hide that gift:** Remove that gift from the offer for this customer.

{% hint style="warning" %}
Available for Buy X Get Y offers only.
{% endhint %}

#### **2.4. Cart value multiplier condition**

<figure><img src="../../.gitbook/assets/unknown (103).png" alt="" width="563"><figcaption></figcaption></figure>

* This condition allows you to set a cart value threshold that multiplies the number of gifts customers can receive.
* The cart value you enter is based on your store’s main currency (e.g., SGD as shown in the image).

_Example: Customers receive 1 gift when spending $200, 2 gifts when spending $400, and so on_

* **For stores that have Shopify Markets set up:**

<figure><img src="../../.gitbook/assets/unknown (102).png" alt="" width="563"><figcaption></figcaption></figure>

Normally, BOGOS will auto-convert your main currency to the customers’ currency using Shopify’s exchange rate (e.g., 1 SGD = €0.666).

However, if you want to **set custom cart values for each currency** instead, after setting the cart value for your main market, click “Add currency” and enter the value.

_Example: Customers from Europe must spend €300 to get the gift, while Australian customers just need to spend A$100._

#### **2.5. Pack of products condition**

<figure><img src="../../.gitbook/assets/image (102).png" alt=""><figcaption></figcaption></figure>

* Pack of products conditions: Only when customers purchase all the selected products will get the gifts
* Verify pack of products condition:

▶ By products: Customers need to purchase at least a variant from each selected product to get gifts.

▶ By variants: Customers need to purchase all variants from all products selected to get gifts.

* Multiply gifts with a number of packs: The more packs purchased, the more gifts customers will get.

### 3. Offer sub-conditions&#x20;

These sub-conditions are optional to set up. They will provide more conditions that customers need to meet to get the gifts. Check here for all Sub-conditions.

<figure><img src="../../.gitbook/assets/unknown (66).png" alt=""><figcaption></figcaption></figure>

You can combine any conditions together to make offers specifically to your customers.

#### **3.1. Specific link address**

<figure><img src="../../.gitbook/assets/Specific link URL.jpg" alt=""><figcaption></figcaption></figure>

This condition only allows customers who access to your store through specific link to get gifts. Enter a word to customize the URL for each campaign. This feature is most suitable for any social and email campaign.

**Customize the offer link:**

Alternatively, if you want to add the parameter to an existing link on your store, use the Copy parameter option to copy just the parameter (e.g., ?freegifts\_code=summersale2024).

{% hint style="warning" %}
If the URL you’re adding the parameter to already includes a ? symbol (e.g., https://yourstore.com/product?variant=12345), **change the ? in the parameter to &**:

**Original Parameter:** ?freegifts\_code=summersale2024

**Modified Parameter for existing query:** \&freegifts\_code=summersale2024
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=1huoyancpmg&list=PLfZvxg1NZTJgkPK3iPXFBivJcXPpIHY33&index=4" %}

#### **3.2. Customers' order history**

<figure><img src="../../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

This sub-condition will narrow down only customers with specific order history will be eligible to the offer.

* Total spent in order history: Total order value in customers' order history.
* Total spent on last order: Latest order value.
* Total number of order placed: Total number of orders in order history.
* Limit to one use per customers: Customer is only able to get gift from this offer for one time only. Once an order is placed with gift from this offer, customers are not eligible to this offer any more.

You can input 0 to max in Total number of order placed to create an offer for new customer only\
This sub-condition requires customers to log in to your store.

{% embed url="https://youtu.be/Fngi7aS1AYU" %}

#### **3.3. Customer tags**

<figure><img src="../../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

This feature allows you to target the offer to customers who have or don’t have specific tags.\
This sub-condition requires customers to log in to your store.

{% embed url="https://www.youtube.com/watch?v=ZFce5y1g7Ws" %}

#### **3.4. Customer location**

<figure><img src="../../.gitbook/assets/image (107).png" alt=""><figcaption></figcaption></figure>

Use this if you want your gift offers to be available **only to customers from a specific country**.

In contrast, to exclude customers from a specific country from your offers, select that country and tick the “exclude customers from selected locations” box.

{% embed url="https://www.youtube.com/watch?v=aD5Kh6BJm1o&list=PLfZvxg1NZTJgkPK3iPXFBivJcXPpIHY33&index=3" %}

#### 3.5.  Markets

<figure><img src="../../.gitbook/assets/unknown (105).png" alt=""><figcaption></figcaption></figure>

Use this if you want to display your offer **only to customers from markets that include a group of countries or regions**, which should be already set up in Shopify Markets.

* To set it up, simply select Shopify markets where you want your gift offers to apply.
* In contrast, to exclude customers from specific markets, select those markets and tick the “Exclude customers from selected markets” box.

{% hint style="warning" %}
If you see this yellow notification, it means BOGOS can’t read your Shopify Markets data. Click “Update Permissions” to enable syncing first.
{% endhint %}

<figure><img src="../../.gitbook/assets/unknown (106).png" alt="" width="456"><figcaption></figcaption></figure>

#### 3.6.  Subscription products

<figure><img src="../../.gitbook/assets/image (108).png" alt=""><figcaption></figcaption></figure>

By default, BOGOS offers work with both One-time purchase and Subscription products.&#x20;

This feature allow you to narrow the offer to only one type of product.

#### 3.7. Sales channels

<figure><img src="../../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>

This feature allows you to create offers for customers from multiple sales channels: online store, mobile app channel, and point of sale channel.

#### **3.8. Product quantity limits**

<figure><img src="../../.gitbook/assets/unknown (67).png" alt=""><figcaption></figcaption></figure>

Use this to add **extra quantity rules** for your Main Condition. The items in the cart must satisfy these limits to qualify for the gift.

**Popular use cases:**

* Buy at least 2 items from Collection A and 1 item from Collection B to get a gift.
* Spend $250+ and include at least 1 Product A to get a gift.
* Buy from a collection (excluding Product A) to get a gift.
* Buy from collection A (excluding products that also appear in collection B) to get a gift.
* No gift if certain items are in the cart, even if the main conditions are met.

**To set it up:**

{% embed url="https://youtu.be/fQQSJ1LOJIg?si=Lys2gnF2Plyx25Oz" %}

1. Choose **Customers must reach** (if you want to set many rules):

* **All rules** (AND): the customer must satisfy all rules you set up below to get the gift.
* **Any rule** (OR): meeting just one of your rules is enough to qualify.

2. Select the **Buy** rule, and **enter how many items** are needed to meet the requirement.

* **At least**: The cart must have equal to or greater than (≥) this number of items from your selected products.
* **At most:** The cart must have equal to or fewer than (≤) this number of items from your selected products.

3. Select the **From** rule, so the quantity set above will apply to selected products/ types/vendors/collections.
4. Select your desired products/ types/vendors/collections.
5. To stack multiple rules, click **Add rule** and repeat the process - they follow your All rules/Any rule choice.

{% hint style="success" %}
* To **exclude** specific products, set Buy “At most 0” from “selected products: Product A”.
* To **require an exact quantity** of items, set All rules with both At least X and At most X (using the same number X).
{% endhint %}

{% hint style="warning" %}
**Free gifts from other offers don’t count toward this rule**.&#x20;

E.g: If your rule requires buying Product A, any free Product A added by a different offer will not count. The customer must buy another Product A to qualify.
{% endhint %}

### 4. Select gifts

<figure><img src="../../.gitbook/assets/unknown (107).png" alt="" width="563"><figcaption></figcaption></figure>

This is where you choose the gifts you want to offer and apply discounts to them.

1. **Choose Gift discount type:**

▶ If you choose **a normal product as a gift,** there are 3 discount types:

* **Percentage:** The gift price will be discounted from the original price by a percentage of its original price. 100% means free gift.
* **Amount:** The gift price will be discounted from the original price by an amount of money.
* **Fixed price:** Set a fixed price for your gifts, which can be lower or higher than the original price.

{% hint style="info" %}
**For Gift Function,** the fixed price cannot be higher than the original product’s price (due to Shopify rules).&#x20;

To set a higher fixed price, please switch the Gift logic mechanism to Clone product.
{% endhint %}

▶ If you choose **a shipping discount as a gift**, there are 2 discount types:

<figure><img src="../../.gitbook/assets/unknown (108).png" alt="" width="563"><figcaption></figcaption></figure>

* **Percentage:** The original shipping cost will be discounted by a percentage. 100% means free shipping.
* **Amount:** The original shipping cost will be discounted by a fixed amount. If you sell in different currencies (set up in Shopify Markets), you can **"add currency"** and decide how much shipping discount amount to offer in each currency, instead of using Shopify’s exchange rates (e.g., SGD 100, €8, A$12).



2. **Choose how Customer will receive** (choose how customers will receive their gifts):

* _Automatically all gifts:_ Once the condition is met, gifts are automatically added to the customer's cart.

{% hint style="warning" %}
When **Gift will match variant** is enabled in the main condition, **Automatically all gifts** is disabled, and **Number of gifts customer will receive** is the only option (shopper chooses gift on Gift slider).&#x20;
{% endhint %}

* _Number of gifts customer will receive_: Once the condition is met, gifts are displayed in a Gift slider for customers to choose from.

{% hint style="info" %}
Note: If you want to customize the appearance of Gift slider, go to [Customize Gift slider](../customize/customize-gift-slider.md)
{% endhint %}

3. **Select gifts:**&#x20;

* Select a product(s) or variant(s) that will be offered as gifts.
* Set the quantity for each gift (if choosing Automatically all gifts). When customers qualify, gifts are auto-added to cart in the quantities you set.

<figure><img src="../../.gitbook/assets/unknown (165).png" alt="" width="507"><figcaption></figcaption></figure>

{% hint style="warning" %}
The following product types CAN NOT be selected as gifts and will be auto-removed if accidentally picked:

* Cloned gifts (created by the gift clone mechanism).
* Bundle as a separate product (created by Classic Bundle).
{% endhint %}

### 5. Advanced configuration (optional)

#### 5.1. Works with other offers

<figure><img src="../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>

* _**Priority:**_ Set a numerical priority level for this offer. Offers with a lower number (e.g., 1) have a higher priority than those with higher numbers (e.g., 2, 3). This affects how multiple offers are applied when customers qualify for more than one.



* _**Stop lower priority:**_ Enable this setting to automatically stop offers with a lower priority if customers meet the conditions for this higher-priority offer. For example, if this offer is set to priority 1, then offers with priority 2, 3, etc., will not apply if the conditions for priority 1 are met.



* _**Gift will be applied toward other offers:**_ If selected, the value of the gift in this offer will count towards the minimum purchase requirements of other offers (only when the gift has a price above $0). This can help customers qualify for multiple promotions more easily.

#### **5.2. Cart message**

<figure><img src="../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>

_**Add a Cart Message:**_ This option lets you add a custom message that will appear on the Cart page when this offer is active.

For more details, please read [Customize Cart Message](../customize/customize-cart-message.md).

#### **5.3. Today offer**

<figure><img src="../../.gitbook/assets/image (115).png" alt=""><figcaption></figcaption></figure>

* **Offer title:** Enter a title that will be displayed on the Today Offer widget on your store’s Online Store. Changing this will not change the original title of the offer.
* **Add a redirect button:** You can add a clickable button to the Today Offer widget that links to where you want customers to clain the offer.

For more details, please read [Customize Today offer](../boosters/create-today-offer-widget.md).

#### **5.4. Add a custom discount code**

This section allows you to customize the discount code name to match your brand.

<figure><img src="../../.gitbook/assets/image (320).png" alt=""><figcaption></figcaption></figure>

\
**Take notice:**&#x20;

* This option option is appear automatically when your Gift logic is set to Gift Function.
* If your store uses Gift clone logic, this option is only available when you select Shipping discount as gift.
* The discount code name must be under 256 characters and unique across all Shopify discounts.

Then choose to **combine the offer** with Order discounts or Shipping discounts

### FAQs

<details>

<summary><strong>How to allow customers to choose their gift?</strong></summary>

You can let customers pick their own gift instead of having it automatically added to their cart. There are two ways to set this up in BOGOS:

**Option 1: Set it in the gift offer**

When creating or editing a gift offer, Under Select gifts > Choose how customer will receive, select Number of gifts customer will receive and enter how many gifts the customer can pick.

**Option 2: Disable auto-add in Settings**

Go to Settings → Gift Condition and turn off Automatically add gift to cart. This forces the gift slider to always appear — even if you choose Automatically all gifts in your Gift Offer

When they qualify for the offer, a gift slider will appear showing all available options for them to choose from. You can adjust the slider's text, colors, layout, and product display in Customize → Gift slider.

</details>

<details>

<summary><strong>Can I limit my gift offers to customers in specific countries?</strong></summary>

Yes. Under **Sub-conditions**, you can use the **Customer Location** or **Markets** feature to ensure gifts are only available to shoppers in your selected regions, synced directly with Shopify Markets.

{% hint style="info" %}
Location setting is based on the customer's current connection (their IP address or VPN), while the Market setting follows the specific data and regions you have already set up in your Shopify Markets settings.
{% endhint %}

**Please follow the steps here:**\
1\. Go to the offer\
2\. Add the sub-condition.

![](<../../.gitbook/assets/unknown (196).png>)\
\
3\. Select Customer Location or Customer Markets<br>

![](<../../.gitbook/assets/unknown (197).png>)

4\. Add the country or market(s) you want\
5\. Save

</details>

<details>

<summary><strong>I want to reward my VIP customers only. Is this possible?</strong></summary>

Yes! You can set a **Customer Tag** sub-condition. The gift will only be offered to logged-in customers who have the specific tag (e.g., "VIP" or "Member") in their Shopify profile.\
\
**Please follow the steps here:**\
1\. Go to the offer\
2\. Add Sub-condition<br>

![](<../../.gitbook/assets/unknown (198).png>)

3\. Select Customer tags<br>

![](<../../.gitbook/assets/unknown (199).png>)

4\. Add the tag that you want to apply<br>

![](<../../.gitbook/assets/unknown (200).png>)

5\. Save.

</details>

<details>

<summary><strong>Is there a way to offer gifts exclusively through a marketing email or influencer link?</strong></summary>

Yes. You can use the **Specific Link Address** sub-condition. This ensures that only customers who enter your store through that unique URL will see and receive the gift offer.\
\
**Please follow the steps here:**\
1\. Go to the offer\
2\. Add Sub-condition<br>

![](<../../.gitbook/assets/unknown (201).png>)

3\. Click Specific Link Address<br>

![](<../../.gitbook/assets/unknown (202).png>)

4\. Add a simple text for the app to generate the link

![](<../../.gitbook/assets/unknown (37).png>)

5\. Copy the link and Save. Then you can send the link via email campaign to whom you want to reward

</details>

<details>

<summary><strong>What’s the difference between Gift App mechanisms?</strong></summary>

**1. Clone Products:** Gift products are indirectly added to the cart by creating duplicate versions of the original product with a discounted price using the BOGOS function. It allows customers to use a discount code at checkout. You can manage gift inventory in the Settings.

[Watch guide.](https://youtu.be/gXwkfsbsWgI?si=M0TTUqjOFRReHsmb\&t=90)

**2. Gift Function:** This option doesn’t create cloned products. Gift products are directly added to the cart as the original products, discounted using Shopify’s built-in discount function.

[Watch tutorial.](https://youtu.be/gXwkfsbsWgI?si=XynDYGtVgg_Gdq6-\&t=147)

</details>

<details>

<summary><strong>How to offer free gift with a discount code?</strong></summary>

The only way to offer a free gift after a customer enters a discount code on Shopify is to set up a **Checkout Upsell** — but this **is only available** for Shopify Plus stores.

**Here's how to set it up:**

1. First, set up a discount code in Shopify's built-in Discounts. Choose Amount off products > Enter your preferred code > Enter 0 in Discount value > Under Combinations, enable Product discounts > Save
2. Go to All offers > Create an Upsell offer > Select Checkout Upsell
3. Choose an Upsell trigger
4. Select an Upsell method
5. Set the discount type to Percentage and enter 100 to make it free
6. Under Advanced Configuration > enable Discount Code > enter exactly the discount code from Step 1
7. Choose either Show products on Checkout page or Auto add products to cart
8. Click Publish

[Watch tutorial.](https://youtu.be/kWeZvSDxRkg?si=m4YcbI_3FLev32b3)

</details>

<details>

<summary><strong>How to set up a gift card as a gift properly?</strong></summary>

You can easily reward your customers with a digital gift card when they purchase specific items. Here’s how to set it up:

**1. Create Your Offer**

* Go to All offers > Create a gift offer.
* Under the Main Condition, select the specific products that customers need to buy to qualify.
* Scroll down to the Gift selection section and choose your Gift card product.

**2. Adjust Settings for "Clone Product" Users**&#x20;

If your store uses the Clone product mechanism, you’ll need to make one quick adjustment to ensure the gift cards are delivered:

* Navigate to BOGOS Settings > Draft order API.
* Turn on the Draft Order API.
* Ensure you select "Do not allow discount" for both options.

**How it works:** Once the order is completed, your customers will automatically receive their gift card code via email.

{% hint style="success" %}
Pro-Tip: If you prefer a simpler setup, you can switch your app mechanism to **Gift Function** in the Settings. This allows you to select and manage gift cards just like any other standard gift in your offer setup.
{% endhint %}

</details>
