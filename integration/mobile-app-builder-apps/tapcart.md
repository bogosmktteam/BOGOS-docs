---
hidden: true
noIndex: true
layout:
  width: default
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# Tapcart

[**Tapcart**](https://apps.shopify.com/freegifts?app_code=bogos\&referral_code=tapcart\&utm_term=tapcart\&utm_campaign=integration_helpdoc\&utm_medium=Tapcart\&utm_source=Partner\&sca_ref_code=tapcart\&sca_ref_offer=all) is a mobile app builder for Shopify merchants who want a fully branded iOS and Android app without any developer work. With App Studio, your marketing team can independently control design and content, while built-in AI helps personalize campaigns, product recommendations, and customer journeys based on shopper behavior.

With the integration between [BOGOS](https://apps.shopify.com/freegifts?utm_source=gitbook\&utm_medium=integration\&utm_campaign=Tapcart) and [Tapcart](https://apps.shopify.com/freegifts?app_code=bogos\&referral_code=tapcart\&utm_term=tapcart\&utm_campaign=integration_helpdoc\&utm_medium=Tapcart\&utm_source=Partner\&sca_ref_code=tapcart\&sca_ref_offer=all), you can easily create, manage, and display gift promotions on your mobile app from a single dashboard.

**Tapcart’s key features:**

* No-code app builder – Launch a fully branded mobile app quickly with full creative control
* Personalized engagement – Use AI to deliver tailored campaigns, recommendations, and user journeys
* Push notifications – Reach customers directly on their home screen with targeted messages
* Retention-focused tools – Improve loyalty with customized onboarding and order experiences
* Real-time insights – Optimize performance with analytics and automatic updates

_**Note:**_

Gift offers only work on the mobile app when the Gift mechanism is set to Gift Clone.

To configure this:

* Go to BOGOS → Settings.
* Find Gift logic mechanism, then select Clone product.

<figure><img src="../../.gitbook/assets/unknown (224).png" alt=""><figcaption></figcaption></figure>

## How to integrate BOGOS with Tapcart

**Step 1:** Install [BOGOS](https://apps.shopify.com/freegifts?utm_source=gitbook\&utm_medium=integration\&utm_campaign=Tapcart) and [Tapcart](https://apps.shopify.com/freegifts?app_code=bogos\&referral_code=tapcart\&utm_term=tapcart\&utm_campaign=integration_helpdoc\&utm_medium=Tapcart\&utm_source=Partner\&sca_ref_code=tapcart\&sca_ref_offer=all) from Shopify App Store&#x20;

Currently, we haven’t deployed the Tapcart integration to production yet. For testing purposes, please send a collaborator request to **bogos-tapcart-integration.myshopify.com** (code: 2315).&#x20;

For any setup requests, please contact the Tapcart team for assistance.&#x20;

**Step 2:** Set up gift offers on **BOGOS App**

To set up gift offers, you should follow the guidelines here:[ Create Gift Offer](https://bogos-guideline.gitbook.io/user-guide/detailed-guide/gift-offer/create-gift-offer#id-4.-select-gifts).          &#x20;

To set up auto add gift(s) to cart, choose **"Automatically add all gifts"** when setting up gift offer.

<figure><img src="../../.gitbook/assets/unknown (225).png" alt=""><figcaption></figcaption></figure>

_**Note**_:&#x20;

* Please make sure the **“Automatically add gift to cart”** option is turned on. To check this, go to Settings → Gift Condition.&#x20;

<figure><img src="../../.gitbook/assets/unknown (226).png" alt=""><figcaption></figcaption></figure>

* Uncheck the box **"Automatically add gift to cart",** if you want to always display gift(s) on a gift slider.

If you want customers to select a gift from a gift slider, tick “**Number of gifts customer will receive**”, then fill a number that is less than the number of gifts selected.&#x20;

**Step 3:** Activate gift offer on **Tapcart**&#x20;

* In **BOGOS**, go to **Settings**.
* Scroll down to **Clone gift product**, Click to **Edit Sale channels**.
* Tick **Tapcart - Mobile App,** then **Done**.

<figure><img src="../../.gitbook/assets/unknown (227).png" alt=""><figcaption></figcaption></figure>

**Step 4:** Add BOGOS Gift Slider and BOGOS core in **Tapcart**

* In Tapcart, go to the **App Studio** section and choose **My Blocks**.
* Open the **Legacy Custom Blocks**
* Drag and drop the **BOGOS Blocks**.

**BOGOS CORE**: Drag it to the **Home page** or **Cart page** for better performance.   &#x20;

**BOGOS - Gift slider:** Drag it into the **Cart page** or any other location where you want customers to see the gift slider.

<figure><img src="../../.gitbook/assets/unknown (228).png" alt=""><figcaption></figcaption></figure>

**Step 5:** Add BOGOS gift products to **Tapcart**

* In **Shopify**, go to **Products**.
* Select all gift products from BOGOS offers.&#x20;

_**Note:**_ To find gift products, go to the **Search & Filter tab**, choose **Tag**, and select “**bogos-gift**.”&#x20;

* Click the “…” icon and choose Include in sales channels.
* Select **Tapcart** and Click **Include products**.

<figure><img src="../../.gitbook/assets/unknown (229).png" alt=""><figcaption></figcaption></figure>

**Step 6:** Test your offers on **Tapcart** to ensure everything works smoothly

#### Run gift offer only on Mobile App Channel

This feature creates gift offers that are exclusively available on Mobile App, meaning they can only be available when buying via their Mobile App store version.

To set it up:

* Open BOGOS app > Create a new or select an existing gift offer.
* Add **Offer sub-condition** > Add **Mobile app channel**
* Click **Publish your offer**

<figure><img src="../../.gitbook/assets/unknown (230).png" alt=""><figcaption></figcaption></figure>

_**Note:**_ Other sub-conditions will not work on the mobile app.

Manage Gift Inventory on Mobile App

For the Gift Clone mechanism, the gift quantity follows the configuration in your Settings:

* Sync clone products’ quantity with originals automatically – The gift quantity in the mobile app stays synchronized with the original product’s inventory.
* Input gift product inventory manually – You can manually control the gift quantity independently from the original product.

<figure><img src="../../.gitbook/assets/unknown (231).png" alt=""><figcaption></figcaption></figure>

<br>
