# Customize Product Discount

This doc explains how to customize the discount display of your product and the Countdown widget - helping you show the discounted price clearly and create urgency with a timer on your product pages.

Customizing these with BOGOS includes the 4 steps:

1. In BOGOS Admin, open Customize > Discount > Product Discount.
2. [Customize the Countdown widget](customize-product-discount.md#customize-countdown-widget).
3. [Customize the Discount price display](customize-product-discount.md#customize-discount-price-display).
4. Click Save.

## Customize Countdown Widget

The Countdown widget appears on your product pages to show customers how much time is left on the discount, creating urgency to buy before the offer ends.

![](<../../.gitbook/assets/unknown (338).png>)

### General

* **Enable countdown widget**: Show the countdown timer on your product pages. The countdown displays based on your offer's Start/End time and Repeat discount in a time range settings.
* **Widget style**: Choose between Bar (slim look) or Banner (more attention).
* **Wrap number background**: Add a background block behind each countdown digit.
* **Show labels** (for Banner widget style only): Enable to display text labels below each countdown unit. You can customize all the label text available.
* **Widget border radius**: Drag the slider (0–24px) to adjust the corner roundness of the widget. The background behind each digit rounds at half that value automatically.

### Color

BOGOS allows you to customize the colors of all elements with any of the 3 methods below:

* Choose a ready-made color set from the dropdown.
* Manually adjust each color field for all the available colors.
* Contact the BOGOS support team to get help with color customization.

Click Save when done.

## Customize Discount Price Display

The Discount price display shows customers the discounted price and how much they are saving. You can display it on the product page, on the product list (e.g., collection page, featured collection, recommended products), or both.

<div><img src="../../.gitbook/assets/unknown (427).png" alt=""> <figure><img src="../../.gitbook/assets/unknown (428).png" alt=""><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/unknown (429).png" alt=""><figcaption></figcaption></figure></div>

### General

<figure><img src="../../.gitbook/assets/image (475).png" alt=""><figcaption></figcaption></figure>

* **Custom discount price display:** Enable to show the discounted price in a compare-at price style. When enabled, choose where to display it:
  * **Show on Product page:** Show the discount price and label on the product page.
  * **Show on Product list:** Show the discount price and label on product cards across your store (e.g., collection page, featured collection, recommended products).

{% hint style="warning" %}
If turned off, your store only shows the theme's original price until the product is added to cart.
{% endhint %}

### Product page

![](<../../.gitbook/assets/unknown (431).png>)

To set it up, configure the following:

* **Show discount price:** Show the discounted price alongside the original price on the product page. When enabled, set:
  * **Discount price font:** Set the font size and weight (Regular or Bold) for the discounted price.
  * **Original price font:** Set the font size and weight (Regular or Bold) for the original price.
  * **Strikethrough:** Enable to display the original price with a strikethrough (e.g., ~~$165~~).
* **Show label:** Show a label next to the price to display the discount. When enabled, set:
  * **Discount label:** The text shown on the label. Use \{{discount\_amount\}} to dynamically display the discount value (e.g., "10% OFF").

### Product list

![](<../../.gitbook/assets/unknown (432).png>)

To set it up, configure the following:

* **Show discount price:** Show the discounted price alongside the original price on product cards. When enabled, set:
  * **Discount price font:** Set the font size and weight (Regular or Bold) for the discounted price.
  * **Original price font:** Set the font size and weight (Regular or Bold) for the original price.
  * **Strikethrough:** Enable to display the original price with a strikethrough (e.g., ~~$165~~).
* **Show label:** Show a label on the product card to display the discount. When enabled, set:
  * **Discount label:** The text shown on the label. Use \{{discount\_amount\}} to dynamically display the discount value (e.g., "10% OFF").
  * **Label position:** Choose where the label appears on the product image:&#x20;
    * On image - top left
    * On image - top right
    * On image - bottom left
    * On image - bottom right.

{% hint style="warning" %}
In some cases, only the discount label will show on the product card while the price stays as the theme's original, this protects your store from displaying wrong prices. This applies when:

* The product has mixed-variant discounts (only some variants are on sale).
* Your theme displays a price range (e.g., "From $20").
* Your store uses Shopify Markets with per-market pricing.
* Your theme has no available spot to display the discount price on the product card.
{% endhint %}

### Color

![](<../../.gitbook/assets/unknown (433).png>)

BOGOS allows you to customize the colors of all elements with any of the 4 methods below:

* Choose a ready-made color set from the dropdown.
* Manually adjust each color field for all the available colors.
* Use AI Theme Detector to auto-generate a full widget color palette based on your store's branding. For more details, visit our \[[AI Theme Detector](https://docs.bogos.io/detailed-guide/customize/ai-theme-detector)] guide.
* Contact the BOGOS support team to get help with color customization.

Click Save when done.

### Add on&#x20;

#### Discount note

![](<../../.gitbook/assets/unknown (443).png>)

The Discount note is a short message shown next to the discounted price, letting customers know the discount will apply later in the cart. This is useful for subscription products, where the price does not update directly on the product page.

{% hint style="warning" %}
These settings only apply to subscription products.
{% endhint %}

To set it up, configure the following:

* Choose note display: Select Show to display the note, or Hide to turn it off.
* Note text: The message shown to customers (e.g., "discount will auto apply at checkout").
* Text color

Click Save when done.

If you need any assistance, feel free to reach out to our customer support team via live chat within our BOGOS app.
