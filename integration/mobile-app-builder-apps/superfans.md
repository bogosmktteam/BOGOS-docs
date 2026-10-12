# Superfans

{% embed url="https://youtu.be/0KbAk1bzALk?si=Zyvot70_HsUNLS0a" %}

[**Superfans**](https://apps.shopify.com/vajro?utm_source=partner\&utm_medium=BOGOS\&utm_campaign=integration_helpdoc) is a no-code mobile app builder for Shopify and Shopify Plus brands, designed to convert mobile shoppers into loyal customers through native iOS and Android apps. With its intuitive builder and powerful engagement tools, Superfans enables merchants to deliver fast, engaging, and high-converting mobile shopping experiences.

With the integration between [BOGOS](https://apps.shopify.com/freegifts?utm_source=gitbook\&utm_medium=integration\&utm_campaign=Superfans) and [Superfans](https://apps.shopify.com/vajro?utm_source=partner\&utm_medium=BOGOS\&utm_campaign=integration_helpdoc), you can easily create, manage, and display gift promotions on your mobile app directly from a single dashboard.&#x20;

**Superfans key features:**

* No-code mobile app builder – Create native iOS and Android apps with an easy drag-and-drop interface
* Unlimited push notifications – Send targeted mobile notifications to specific customer segments.
* One-click integrations – Connect your existing Shopify apps and tech stack seamlessly.
* Live selling capabilities – Host live sessions on your mobile app and Facebook to engage shoppers and drive more sales.

_**Note:**_ Gift offers only work on the mobile app when the Gift mechanism is set to Gift Clone.

To configure this:

* Go to BOGOS → Settings.
* Find Gift logic mechanism, then select Clone product.

<figure><img src="../../.gitbook/assets/unknown (177).png" alt=""><figcaption></figcaption></figure>

## How to integrate BOGOS with Superfans

**Step 1:** Install [BOGOS](https://apps.shopify.com/freegifts?utm_source=gitbook\&utm_medium=integration\&utm_campaign=Superfans) and [Superfans](https://apps.shopify.com/vajro?utm_source=partner\&utm_medium=BOGOS\&utm_campaign=integration_helpdoc) from Shopify app store&#x20;

**Step 2:** Set up gift offers on BOGOS App

To set up auto add gift(s) to cart, double-check if you enable 'Automatically add gift to cart' setting under Settings → Gift Condition.

<figure><img src="../../.gitbook/assets/unknown (178).png" alt=""><figcaption></figcaption></figure>

When creating the offer, choose 'Automatically add all gifts'.

<figure><img src="../../.gitbook/assets/unknown (179).png" alt=""><figcaption></figcaption></figure>

For details, please visit[ Create Gift Offer](https://bogos-guideline.gitbook.io/user-guide/detailed-guide/gift-offer/create-gift-offer#id-4.-select-gifts) guide.          &#x20;

**Step 3:** Activate the BOGOS integration in Superfans

* In Superfans, navigate to Plugins.&#x20;
* Find BOGOS and click View details or enable the toggle.

<figure><img src="../../.gitbook/assets/unknown (180).png" alt=""><figcaption></figcaption></figure>

* Enter your BOGOS API Key (Contact the BOGOS support team to obtain this key).
* Then, click Save and enable plugin.

<figure><img src="../../.gitbook/assets/unknown (181).png" alt=""><figcaption></figcaption></figure>

**Step 4:** Add BOGOS Gift Slider and BOGOS core in Superfans

* In Superfans, go to the Themes section and open your store theme.
* Open the Cart page.
* Click Add block → Plugin.

<figure><img src="../../.gitbook/assets/unknown (182).png" alt=""><figcaption></figcaption></figure>

* Add the following blocks: **BOGOS Gift Slider** & **BOGOS Core**

<figure><img src="../../.gitbook/assets/unknown (183).png" alt=""><figcaption></figcaption></figure>

**Step 5:** Add BOGOS gift products to Superfans

* In Shopify, go to Products.
* Select all gift products from BOGOS offers.
* Click the “…” icon and choose Include in sales channels.
* Select Superfans and Click Include products.

<figure><img src="../../.gitbook/assets/unknown (184).png" alt=""><figcaption></figcaption></figure>

**Step 6:** Test your offers on Superfans to ensure everything works smoothly

#### Run gift offer only on Mobile App Channel

This feature creates gift offers that are exclusively available on Mobile App, meaning they can only be available when buying via their Mobile App store version.

**To set it up:**

* Open BOGOS app > Create a new or select an existing gift offer.
* Add Offer sub-condition > Add Mobile app channel
* Click Publish your offer

<figure><img src="../../.gitbook/assets/unknown (188).png" alt=""><figcaption></figcaption></figure>

_Note: Other sub-conditions will **not work** on the mobile app._

#### Manage Gift Inventory on Mobile App

For the Gift Clone mechanism, the gift quantity follows the configuration in your Settings:

* Sync clone products’ quantity with originals automatically – The gift quantity in the mobile app stays synchronized with the original product’s inventory.
* Input gift product inventory manually – You can manually control the gift quantity independently from the original product.

<figure><img src="../../.gitbook/assets/unknown (187).png" alt=""><figcaption></figcaption></figure>
