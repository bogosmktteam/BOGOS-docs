---
description: Overview of creating a Bundle builder with BOGOS
---

# Create Bundle Builder

{% embed url="https://youtu.be/N6XmiirL3wY" %}

This feature allows store owners to create a "Build your own bundle" page for customers to create a bundle customized to their needs. This feature is designed to enhance customer engagement and increase average order value by offering tailored bundling options.

## 1. Bundle information

The **Bundle Information** section allows you to configure the foundational details of your Bundle builder. Each input field is explained below to help you set up your bundle effectively.

<figure><img src="../../../.gitbook/assets/image (138).png" alt=""><figcaption></figcaption></figure>

### **1.1. Bundle name**

A unique identifier for your bundle. This name will not be visible to customers but is used internally for easy management.

### **1.2. Page heading**

<figure><img src="../../../.gitbook/assets/image (134).png" alt=""><figcaption></figcaption></figure>

The title displayed at the top of your Bundle builder, visible to customers.

### **1.3. Page sub-heading**

<figure><img src="../../../.gitbook/assets/image (135).png" alt=""><figcaption></figcaption></figure>

A subtitle displayed beneath the heading, providing additional information about the bundle.

### **1.4. Start & End time**

The date and time when the bundle offer will become active.

The date and time when the bundle offer will expire.

### **1.6. Steps**

* **One step per page:** Displays one product selection step at a time, creating a step-by-step flow for customers.
* **Multiple steps in one page:** Displays all steps on a single page, allowing customers to complete their selections in one view.

### **1.7. Banner Image**

An image displayed at the top of the Bundle builder to visually enhance its appeal.

**Image Specifications:**

* Dimensions: 1200 x 800 pixels
* File size: Under 1 MB
* Formats supported: GIF, JPG, PNG

## 2. Add sub-conditions

Sub-conditions add extra rules to decide who can see and get your offers. Therefore, only targeted customers can see and apply the offer, while others won't see it at all.

{% hint style="info" %}
* These sub-conditions are optional. If you don't add any, the offer will be available to all customers.
* You can combine multiple sub-conditions. Customers must meet all selected criteria to qualify.
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (154).png" alt="" width="503"><figcaption></figcaption></figure>

1. _Specific link address_ – Apply offers to customers accessing your store from a specific link. Perfect for email campaigns, social posts, or affiliates.
2. _Order history_ – Target customers based on purchase behavior. Best for rewarding first-time buyers, high spenders, and more.
3. _Customer tags_ – Show or hide offers based on customer tags.
4. _Customer location_ – Run country-specific promotions based on the customer’s IP address.
5. _Markets_ – Run region-specific offers based on your Shopify Markets.

♦️ For more details, visit our \[[Sub-Condition](../../detailed-doc/how-to-add-bogos-sub-conditions-to-bundle-upsell-discount.md)] guide.

## 3. Bundle structure

<figure><img src="../../../.gitbook/assets/Max quantity.jpg" alt=""><figcaption></figcaption></figure>

### **3.1. Step title**

<figure><img src="../../../.gitbook/assets/image (269).png" alt="" width="563"><figcaption></figcaption></figure>

This is the title for the current step in the bundle creation process, visible to customers; use it to clearly indicate the purpose of the step (e.g., "Step 1: Choose Your Main Items").

Note: To edit the "Step" label text on the Bundle builder progress bar, please visit [Customize](../../customize/customize-bundle-builder.md#id-2.1.1.-bundle-product).

<figure><img src="../../../.gitbook/assets/image (272).png" alt="" width="375"><figcaption></figcaption></figure>

### **3.2. Step sub-title (optional)**

<figure><img src="../../../.gitbook/assets/image (260).png" alt="" width="563"><figcaption></figcaption></figure>

A brief description or instruction for the step, displayed beneath the step title, guiding customers (e.g., "Choose two items from the products listed below").

### **3.3. Select a list of products**

Allows you to choose a predefined product list or collection for this step by selecting an existing list of products.

* Selected products: Enables you to select specific products for this step by clicking **Select Products** and choosing individual items to display to customers.
* Selected collections: Allow selecting collections as a list of products for this step.

### 3.4. Advanced settings

<figure><img src="../../../.gitbook/assets/unknown (39).png" alt=""><figcaption></figcaption></figure>

* **Search bar:** Enable this to display a search bar on the Bundle builder, allowing customers to quickly find products by name.
* **Sort by:** Choose the sorting options customers can use from Name, Date, Price, and Best Selling. The data is synced with your product information.

{% hint style="info" %}
If you wanna choose "Best Selling" as the sort option, it's best to select only one collection in “Select a list of products” to ensure everything works smoothly.
{% endhint %}

<figure><img src="../../../.gitbook/assets/unknown (38).png" alt=""><figcaption></figcaption></figure>

* **Filter by**: Add this option to let customers filter products more easily based on: Category, Collection, Product tag, Product type, or Price range.&#x20;

<figure><img src="../../../.gitbook/assets/image (353).png" alt="" width="476"><figcaption></figcaption></figure>

{% hint style="info" %}
**Filter label** is the title of the filter option that customers will see on your storefront. Use simple words to make it clear.&#x20;
{% endhint %}

**Some key notes to keep in mind:**

* All filter options are automatically detected from your store setup and can be combined.
* For each filter’s value, you can select only one option at a time.
* For the Price range filter, simply add a label, and customers can then set their own price range freely.

**Set minimum quantity (optional):** Defines the minimum number of products a customer must select in this step by enabling the option and specifying the required quantity (e.g., 2 items).

This minimum quantity sets the number of items customers must purchase to proceed to the next step. It differs from the [minimum quantity required to unlock a discount tier.](./#id-3.2.-quantity)

**Set maximum quantity (optional):** Defines the maximum number of products a customer can select in this step by enabling the option and specifying the required quantity.

This maximum quantity limits the number of items customers can purchase in the bundle. If customers try to exceed this limit on the Bundle builder, they won't be able to add more items.

However, if customers manually adjust the quantity in their cart to surpass this limitation, the system will create a separate product at the original price.

{% hint style="info" %}
In case your bundle offer has 2 or more products, and you don't know which specific product your customer has adjusted to surpass the maximum quantity, we will select the product with the highest price to revert to the original price.
{% endhint %}

### **3.5. Additional Features**

* **Add Step**: Lets you create additional steps for the bundle, each with unique titles, sub-titles, and product settings.
* **Remove Step**: The trash icon next to a step lets you delete it if it’s no longer needed.

## 4. Bundle discount

<figure><img src="../../../.gitbook/assets/image (142).png" alt=""><figcaption></figcaption></figure>

### **4.1. Label text**

Specifies the discount label that will be visible to customers (e.g., "10% OFF" or "Buy More, Save More").

### **4.2. Quantity**

Defines the minimum number of items the customer must select to qualify for this discount tier.

Note: the minimum quantity of a subsequent tier (e.g. tier 2) has to be equal to or larger than a previous one.

### **4.3. Discount type**

**>Product discount:** Allows you to choose the type of discount&#x20;

* Percentage: for a percentage-based discount
* Amount: for a fixed monetary discount
* Fixed price: offer products at a certain price point
* Free gift: automatically add a free gift to cart

If you choose **"amount"** or **"fixed price",** and also sell in different currencies (set up in Shopify Markets), you can “add currency” and **custom how much discount amount to offer in each currency**, instead of using Shopify’s exchange rates (e.g., SGD 10, CN¥8, A$12).

<figure><img src="../../../.gitbook/assets/unknown (74).png" alt="" width="506"><figcaption></figcaption></figure>

Note:

* **Flexible discount updates**: When the quantity of items in a bundle changes (excluding free gifts), the discount will automatically update to reflect the changes.
* **Line item updates for free gift discounts**: If a gift is added using a free gift discount, the product will appear with its original price (not zero) in the cart. For carts that don’t support line item updates, increasing the quantity of the gift will not create a separate line item but will update the existing one correctly at checkout.

**>Add shipping discount**

<figure><img src="../../../.gitbook/assets/unknown (113).png" alt="" width="461"><figcaption></figcaption></figure>

There are two types of shipping discount:

* Percentage: A percentage of the shipping cost will be deducted.
* Amount: A fixed amount will be deducted from the total shipping cost. If you sell in different currencies (set up in Shopify Markets), you can “add currency” and custom how much shipping discount amount to offer in each currency, instead of using Shopify’s exchange rates (e.g., SGD 10, €8, A$12).

**Label on widget**: This text informs customers whether the bundle includes a shipping discount.

### **4.4. Value**

Specifies the value of the discount; for a percentage, enter the percentage amount (e.g., 10), and for a fixed amount, enter the monetary value (e.g., $10).

### **4.5. Add tier**

Enables you to create additional discount tiers to offer varied discounts based on the number of items purchased.

### **4.6. Remove tier**

The trash icon allows you to delete an existing tier if it is no longer needed.

## 5. Advanced configuration (optional)

<figure><img src="../../../.gitbook/assets/Jump.JPG" alt=""><figcaption></figcaption></figure>

## 6. Discount code

#### Add a custom discount code

This section allows you to customize the discount code name to match your brand.

<figure><img src="../../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The discount code name must be under 256 characters and unique across all Shopify discounts.
{% endhint %}

#### Combinations

This option allows you to directly navigate customers to the next step if their carts meet the minimum number of products you established previously.&#x20;

<div align="left"><figure><img src="../../../.gitbook/assets/image (144).png" alt=""><figcaption></figcaption></figure></div>

If you skip the minimum quantity condition, customers will be guided to the second step as soon as they add any item to their cart. This will only happen once.&#x20;

{% hint style="info" %}
Note: This section only applies to the Minimum quantity option.
{% endhint %}

### **6.1. Order discounts**

Indicates if the bundle discount can be combined with order-level discounts, such as promotional codes or automatic discounts.

### **6.2. Shipping discounts**

Indicates if the bundle discount can be combined with shipping discounts, such as free or reduced shipping promotions.

## 7. Bundle builder summary

<div align="left"><figure><img src="../../../.gitbook/assets/image (145).png" alt=""><figcaption></figcaption></figure></div>

The Bundle builder **Summary** panel on the right updates dynamically as you configure your steps. It displays the number of steps, selected products, and added discounts for easy tracking.

## FAQs

<details>

<summary><strong>Can we not show the out-of-stock products in each step?</strong></summary>

That is **certainly possible**! As this involves a tailored customization, we’d like to involve our engineering team to ensure it's executed perfectly. Please contact us through Live Chat so we can begin to work on it.

</details>

<details>

<summary><strong>Is it possible to limit the number of products a customer can select in each step?</strong></summary>

**Yes**. In the Advanced settings of each step, you can set a **Minimum quantity** (the number of items required to proceed) and a **Maximum quantity** (the limit of items allowed in that step). And if customers buy more than the maximum quantity or fewer than the minimum quantity in each step, they won’t get the discount on the Bundle builder.&#x20;

![](<../../../.gitbook/assets/unknown (206).png>)<br>

</details>

<details>

<summary><strong>How can I show the</strong> Bundle builder <strong>on my online store?</strong></summary>

There are 2 ways to show the Bundle builders in your store:&#x20;

* **Add a button on related product pages:** In the Create/Edit Bundle builder, check on "Show a button on product page"

![](<../../../.gitbook/assets/unknown (207).png>)

* Add bundle to your store's navigation:&#x20;
  * Copy your bundle's link in Edit Bundle builder

![](<../../../.gitbook/assets/unknown (210).png>)

* Go to your store Content > Menus > Main menu > Add menu item > Insert Label and copy the bundle link and Save

![](<../../../.gitbook/assets/unknown (211).png>)

![](<../../../.gitbook/assets/unknown (212).png>)

![](<../../../.gitbook/assets/unknown (213).png>)<br>

</details>
