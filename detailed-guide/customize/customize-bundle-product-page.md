# Customize Bundle Product Page

This guide explains how to customize the appearance and content of your Bundle Product Page in the BOGOS app.

**To customize, there are 4 steps:**

1. Set up the [preview and layout options](customize-bundle-product-page.md#preview-and-layout-options).
2. Choose what you want to customize: [By Offer Customize](customize-bundle-product-page.md#by-offer-customize), [Global Customize](customize-bundle-product-page.md#global-customize), or [Widget on Child Product Page](customize-bundle-product-page.md#widget-on-child-product-page).
3. Adjust all available settings for the selected area.
4. Preview your changes, then click Save.

## Preview & Layout Options

Before customizing anything, please choose the preview settings that best match your store setup. This helps you adjust the display more accurately.

![](<../../.gitbook/assets/unknown (307).png>)

* **Preview option**: Switch between Desktop and Mobile to check how the page looks on each device.
* **Layout**: Choose which layout you are customizing.

1. The product image appears next to the bundle content (default layout).
2. The bundle product page is added as a standalone section in your theme (for more details, visit \[[Adjust BOGOS Blocks](../../quick-start-guide/adjust-bogos-blocks.md)]).

* **Column ratio**: Choose the width ratio between the product image and the bundle content area to better fit your store layout.

## By Offer Customize

By Offer Customize lets you adjust the design for one specific bundle product page only. Any changes made here **WILL NOT affect any other bundle product pages**.

![](<../../.gitbook/assets/unknown (308).png>)

**To access this setting:**

1. Open BOGOS app > All offers > Open the setup of the bundle product page you want.
2. Click any **Customize** button > Make sure **By offer customize** is selected.

### a) Customize the Pack (Pack Select Field)

Fill in or adjust the following:

![](<../../.gitbook/assets/unknown (309).png>)

* **Pack select label**: The text shown above the pack size section to tell customers more details.
* **Label style**: Choose which part of the pack label is highlighted:
* **Highlight quantity**: Bold the number of items required for the pack.
* **Highlight discount**: Bold the discount value.
* **Text alignment**: Align the pack text to the Left, Center, or Right.
* **Image orientation**: Choose whether the pack image is Vertical or Horizontal to the text.
* **Number of packs per row**: Set how many packs appear in each row:
* **Full-width**: Applies when the bundle product page is added as a standalone block/section in your theme (for more details, visit \[Adjust BOGOS Blocks]).
* **Compact**: Applies when the bundle content is displayed beside the product image (default layout).
* **Mobile**: Applies to the mobile display.

Click **Save** when done.

### b)  Customize the Section

The Section has two customization areas, and each controls different settings: 1. Product select field or 2. By step.

#### _**b.1. Product Select Field**_

Here, customers can customize the overall product selection area.

Select **Product select fields**, then fill in or adjust the following:

![](<../../.gitbook/assets/unknown (310).png>)

* **Layout**: Choose how steps are displayed between:
* **Accordion**: Shows steps vertically as expandable sections. Customers can open multiple steps at a time to view and select products.
* **Tabs**: Shows steps horizontally as tabs. Customers switch between tabs to view and select products.
* **Step quantity indicator**: Choose how the number of selected items appears on each step header.&#x20;

{% hint style="info" %}
Add items in the preview to check how it looks.&#x20;
{% endhint %}

![](<../../.gitbook/assets/unknown (311).png>)

* **Add item button**: Customize the button customers use to add products to the bundle.&#x20;
* **Button style**: Choose among Icon & text, Text only, or Icon only.
* **Button label**: Enter the text shown on the add item button.
* **Select icon**: Choose an icon to display on the button.

#### _**b.2. By Step**_

Here, customers can customize the display of each step separately.&#x20;

Click **a step name** (for example, Choose Your Shoe), then fill in or adjust the following:

<img src="../../.gitbook/assets/unknown (312).png" alt="" height="311" width="624">

* **Product card layout**: Choose how each product card is displayed among:
* **Horizontal**: Best for when customers need to scan options quickly.
* **Vertical**: Best for visual products where images help customers choose.
* **Name only**: Best when product images are not important, or when you want a simple, text-focused selection list.
* **Product card style**:
  * Minimal card: Shows products with no background.
  * Card with background: Shows products inside a card with a background for stronger visual separation.&#x20;
* **Number of products per row**: Set how many products appear per row for:
* **Full-width**: Applies when the bundle product page is added as a standalone block/section in your theme (for more details, visit \[Adjust BOGOS Blocks]).
* **Compact**: Applies when the bundle content is displayed beside the product image (default layout).
* **Mobile**: Applies to the mobile display.

Click **Save** when done.

## Global Customize

Global Customize lets you adjust the overall display for ALL bundle product pages on your store.

![](<../../.gitbook/assets/unknown (317).png>)

### Access this setting

You can use either way:&#x20;

* Navigate to **All Offers** > Open the setup of any Bundle Product Page > Go to the Display the bundle panel on the right > Open Customize the page dropdown > click Global customize.
* Navigate to **Customize** > Bundles > Bundle product page > select the Global customize tab.

### Content

**Total price text**: Enter the label shown on the total price line of the bundle page.

**Add bundle button**:

* Button label: Enter the text shown on the add-to-cart button.
* Show countdown on button: Enable to display a live countdown message on the button as customers add items (e.g: Added 2 items, 1 to go)

{% hint style="info" %}
Use \{{amount\_added\}} to show the number of items customers have added.

Use \{{amount\_left\}} to show the number of items still needed to unlock the matching pack discount.
{% endhint %}

**Product quick view modal**: When customers click a product title, a quick view popup opens with product details.

* Go to product text: Enter the label for the link that directs customers to the full product page.

<img src="../../.gitbook/assets/unknown (314).png" alt="" height="340" width="624">

### Color

BOGOS allows you to customize the colors of all elements with any of the 4 methods below:

* Choose a **ready-made color set** from the dropdown.
* **Manually adjust** each color field for all the available colors.
* Use [AI Theme Detector](customize-bundle-product-page.md#ai-theme-detector) to auto-generate a full widget color palette based on your store's branding.
* **Contact the BOGOS support team** to get help with color customization.

Click **Save** when done.

#### AI Theme Detector

BOGOS AI scans your online store and detects your brand's primary, secondary, and text colors, then generates a full widget color palette automatically.

{% hint style="warning" %}
Your store must NOT be password-protected for AI to access and detect your brand colors.
{% endhint %}

To edit the colors with BOGOS AI:

1. Click the **pen icon**.

![](<../../.gitbook/assets/unknown (318).png>)

2. Click **Scan again** to let BOGOS AI re-detect, or **manually adjust** the Primary color, Secondary color, or Text fields.

![](<../../.gitbook/assets/unknown (319).png>)

3. Click **Apply** for preview to apply the colors to the widget preview.

## Widget on Child Product Page

The widget appears on the product pages of items included in a bundle. It lets customers know the item is part of a bundle deal and quickly redirects customers to the bundle product page.

<img src="../../.gitbook/assets/unknown (315).png" alt="" height="288" width="624">

### Access this setting

You can use either way:

* Navigate to **All Offers** > Open the setup of any Bundle Product Page > Go to the Display the bundle panel on the right > Open Widget on child product page dropdown > Enable Add widget on child product’s page > Click Widget customize.
* Navigate to **Customize** > Bundles > Bundle product page > Select the Widget on child product page tab.

### General

* **Widget style**: Select from 3 available layout options.
* **Products per row**: Set how many products appear per row on Desktop and Mobile.

### Content

![](<../../.gitbook/assets/unknown (316).png>)

* **Show discount label**: Showcase all the pack sizes alongside the discounts within the widget.
* **Show product & variant name**: Show the product names and selected variant names included in the bundle.
* **Label**: Set the heading shown above the widget. Use \{{number\}} to show how many bundle product pages include this product.
* **Redirect button label**: Set the text for the link that takes customers to the bundle product page.

### Color

BOGOS allows you to customize the colors of all elements with any of the 4 methods below:

* Choose a **ready-made color set** from the dropdown.
* **Manually adjust** each color field for all the available colors.
* Use [AI Theme Detector](customize-bundle-product-page.md#ai-theme-detector-1) to auto-generate a full widget color palette based on your store's branding.
* **Contact the BOGOS support team** to get help with color customization.

Click **Save** when done.

#### AI Theme Detector

BOGOS AI scans your online store and detects your brand's primary, secondary, and text colors, then generates a full widget color palette automatically.

{% hint style="warning" %}
Your store must NOT be password-protected for AI to access and detect your brand colors.
{% endhint %}

To edit the colors with BOGOS AI:

1. Click the **pen icon**.

![](<../../.gitbook/assets/unknown (318).png>)

2. Click **Scan again** to let BOGOS AI re-detect, or **manually adjust** the Primary color, Secondary color, or Text fields.

![](<../../.gitbook/assets/unknown (319).png>)

3. Click **Apply** for preview to apply the colors to the widget preview.

## Need Help?

If you need any assistance, feel free to reach out to our customer support team via live chat within the BOGOS app.<br>
