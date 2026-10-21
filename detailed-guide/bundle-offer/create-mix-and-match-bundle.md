---
description: Overview of creating a Mix and Match bundle with BOGOS
---

# Create Mix and Match Bundle

<figure><img src="../../.gitbook/assets/image (485).png" alt=""><figcaption></figcaption></figure>

{% embed url="https://youtu.be/0y2P2tdWoIM" %}

## 1. Bundle information

<figure><img src="../../.gitbook/assets/image (481).png" alt=""><figcaption></figcaption></figure>

### 1.1 **Bundle Title**

Enter a title for your bundle. This title is for internal purposes only and will not be visible to customers.

### 1.2 **Block Header**

Provide a brief header that will display prominently on the bundle interface, introducing the bundle to customers.

### 1.3 **Bundle Description** (Optional)

Add an optional description that further explains the bundle's purpose or value to the customer.

### 1.4 **Start Time and End Time**

Set the start and end dates for the bundle's availability. Leave "End Time" empty if you want the offer to be ongoing.

## 2. Add sub-conditions

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

## 3. Choose Mix items

<figure><img src="../../.gitbook/assets/image (487).png" alt=""><figcaption></figcaption></figure>

### 3.1 **Choose mix item type**

* **Mix items from a list of products:** Select this if you want customers to choose from a predefined list of individual products. Each product in the list is a separate item that customers can mix and match within the bundle.
* **Each Mix item contains a different list of products:** Choose this if you want each "mix item" to represent a category or group with its own list of products. For example, "Mix item 1" could be accessories, and "Mix item 2" could be main products.

### 3.2 **Select products/collections**

* **Selected Products**: Allows you to add specific products to the mix item list.
* **Selected Collections**: Lets you add entire product collections, so customers can select from any item within a specified collection.

\
Click on **Select Products** to add the products available for selection in the bundle. You can add multiple products for flexibility.

### 3.3 **Set Default product**

This setting controls which product is shown first in each mix item when a customer opens the widget, helping you guide customers' first impression of the bundle.

![](<../../.gitbook/assets/unknown (446).png>)

To set it up, select one of the following options:

* **Auto - Show first product (default):** The system automatically shows the first product from the list or collection. When multiple mix items share the same collection, each Mix item automatically shows a different product.
* **Select a default product:** Pick a specific product from the list or collection to show as the default.
* **Leave empty - buyer chooses:** Leave the slot empty with a "Choose a product" placeholder, so the customer picks from scratch.

{% hint style="warning" %}
- If the default product you selected goes out of stock:
  * For Selected Products source: The product still appears in the picker with an "Out of stock!" label, and the Add bundle to cart button is disabled.
  * For Selected Collections source: The product is automatically removed from the list, and the next available in-stock product is shown instead.
- If you change the collection after selecting a default product, the default product will be reset to Auto.
- If the collection is empty or all products are out of stock, the slot shows "No products available".
{% endhint %}

### 3.4 **Add Mix items and Set min/max quantity (Optional)**

Click Add Mix item for an extra mix item to appear on the bundle widget.

![](<../../.gitbook/assets/unknown (447).png>)

For each mix item, you can set:

* **Set min quantity:** Specify the minimum number of items a customer must choose for this mix item.
* **Set max quantity:** Specify the maximum number of items a customer can choose for this mix item. Leave it off for no limit.

{% hint style="warning" %}
Max quantity must be greater than or equal to min quantity
{% endhint %}

## 4. Discount tiers

<figure><img src="../../.gitbook/assets/image (489).png" alt=""><figcaption></figcaption></figure>

### 4.1 **Define a discount tier**

To encourage larger purchases, **set up discount tiers:**

**Quantity**: The minimum number of items for the discount to apply.

**Product discount type:** Choose between options below

* Percentage: percentage of the discount will be deducted from the total price of all products in bundle.
* Amount: an amount of money will be deducted from the total price of all products in bundle.
* Fixed price: A specific price is set for all products in the bundle.
* Free gift: a free item that's automatically added to customer carts that meet the conditions.

If you choose **"amount"** or **"fixed price",** and also **sell in different currencies** (set up in Shopify Markets), you can **“add currency”** and custom how much discount amount to offer in each currency, instead of using Shopify’s exchange rates (e.g., SGD 10, CN¥8, A$12).

<figure><img src="../../.gitbook/assets/unknown (76).png" alt="" width="506"><figcaption></figcaption></figure>

**Add shipping discount**

<figure><img src="../../.gitbook/assets/unknown (112).png" alt=""><figcaption></figcaption></figure>

There are two types of shipping discount:

* Percentage: A percentage of the shipping cost will be deducted.
* Amount: A fixed amount will be deducted from the total shipping cost. If you sell in different currencies (set up in Shopify Markets), you can “add currency” and **custom how much shipping discount amount to offer in each currency**, instead of using Shopify’s exchange rates (e.g., SGD 10, €8, A$12).

**Label on widget**: This text informs customers whether the bundle includes a shipping discount.

**Discount Value**: Specify the discount percentage or amount.

### 4.2 **Add multiple tiers (Optional)**

Add additional tiers to provide increasing discounts as customers add more items.

## 5. **Layout**

This setting controls how customers choose products in each mix item on the storefront.

To set it up, select one of the following options:

* **Open a modal (default):** When a customer clicks on a mix item, a popup opens to pick the product.

![](<../../.gitbook/assets/unknown (448).png>)

* **Expand on widget (New):** When a customer clicks on a mix item, the product list expands inline within the widget as an accordion. Only one panel can be open at a time; opening another mix item collapses the current one.

![](<../../.gitbook/assets/unknown (449).png>)

## 6. **Display on**

This setting controls which product pages will show the bundle widget.

![](<../../.gitbook/assets/unknown (450).png>)

To set it up, select one of the following options:

* **All products in this bundle (default):** The widget appears on the product page of every product in the bundle.
* **Selected products only:** The widget appears only on the product pages you choose.

Under the card, a counter line always shows: This bundle widget shows on {n} of {total} product pages, helping you track how many pages this bundle is live on.

{% hint style="warning" %}
* If you untick all products, the bundle is saved, but the widget won't appear on any page.
* If you remove a product from the bundle after ticking it, it is automatically removed from the display list and the counter updates.
{% endhint %}

## 7. **Combination**

By default, BOGOS bundles work with any other discounts, such as order discounts and shipping discounts. Untick each checkbox to disable the combination with other discounts.&#x20;

* Order discounts&#x20;
* Shipping discount

## 8. **Discount code**

#### Add a custom discount code

This section allows you to customize the discount code name to match your brand.<br>

<figure><img src="../../.gitbook/assets/image (46).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The discount code name must be under 256 characters and unique across all Shopify discounts
{% endhint %}

## FAQs

<details>

<summary><strong>Can I customize the discount code name for Mix and match bundle?</strong></summary>

Yes, you can customize the **discount code name** (up to **256 characters**) to better match your brand.\
\
Please follow the steps here:

1. Go to the offer
2. Scroll down to Discount code

![](<../../.gitbook/assets/unknown (189).png>)

3. Tick the box Add a custom discount code

![](<../../.gitbook/assets/unknown (191).png>)

4. Put your own discount name
5. Save.<br>

</details>

<details>

<summary><strong>Can customers choose a gift variant in Mix and match offer?</strong></summary>

No. In a Mix and Match offer, products selected as Discount type “Free Product” are automatically added to the cart after clicking Add bundle to cart. With that, the customer is not prompted to choose a variant (like size or color).

If you need your customers to be able to select a specific variant for their free gift, you should create a **Gift Offer** instead.

</details>

<details>

<summary><strong>How does BOGOS handle out-of-stock items in Mix and Match?</strong></summary>

BOGOS automatically syncs with your Shopify inventory.

**If you select a list of products by Products in Mix item:**\
The out-of-stock item will still be visible in the list so customers know it exists, but they will not be able to select it. To make this clear, BOGOS automatically hides the quantity box for that specific item.

![](<../../.gitbook/assets/unknown (194).png>)

**If you select a list of products by Collection in Mix item:**\
BOGOS will automatically hide any out-of-stock products from the list. Your customers will only see the items that are currently available to buy and add to their bundle

![](<../../.gitbook/assets/unknown (195).png>)

</details>
