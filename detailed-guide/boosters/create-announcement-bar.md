# Create Announcement Bar

The Announcement Bar is a new booster developed by BOGOS: Free Gift Bundle Upsell app that displays promotional messages across your store or specific pages you choose to grab attention and drive more clicks.&#x20;

<figure><img src="../../.gitbook/assets/announcement bar - example.png" alt=""><figcaption></figcaption></figure>

→ [View demo](https://demo-store-by-bogos.myshopify.com/?utm_source=HelpDoc\&utm_medium=Booster\&utm_campaign=AnnouncementBar).

{% embed url="https://youtu.be/VYGWig6VdB4?si=CskwHogoOZZF6kJm" %}

Setting up and styling the Announcement Bar with BOGOS includes 5 steps:

1. Open Boosters > Announcement Bar.
2. Set up the bar content ([Content](create-announcement-bar.md#content)).
3. Style the bar's look ([Style](create-announcement-bar.md#style)).
4. Choose where the bar appears ([Placement](create-announcement-bar.md#placement)).
5. Click Save draft or Publish.

{% hint style="info" %}
The preview on the right shows the mobile view by default.&#x20;

Click **Show fullwidth** to get the preview on desktop.
{% endhint %}

## Content

This tab controls the content of your Announcement Bar. The available options change with the display mode you choose.

### General

![](<../../.gitbook/assets/unknown (343).png>)

To set it up:

1. Enter a **Booster name**. For easily managing within BOGOS app only.
2. **Choose a bar display mode** among:

* Static: Shows a single message.
* Marquee: Shows multiple messages scrolling together.
* Slider: Shows multiple messages one at a time, rotating through them.

### Content

This section is to customize the content of your announcement bar.

![](<../../.gitbook/assets/unknown (344).png>)

To set it up:

1. Choose the **content source** between:

* **Manual**: You write the message text yourself
* **Offers**: BOGOS pulls content from your available offers automatically. Click Select offers to choose which offers to display.

{% hint style="info" %}
If choosing Offers, please notice that:

* For the "**Static"** display mode, you can only choose one offer.
* **Inactive offers** can be selected, but won't show on the bar until activated.
* If you **update your offer title** after saving your announcement bar, please back to the that announcement bar setup, re-select the offer, and save again to let BOGOS sync with your newest updates.
{% endhint %}

2. Customize the **message list** (what your messages show). The message list differs depending on the bar display mode you selected.

* **Static**: Shows only one message with one redirect link.
* **Marquee**: Add multiple messages that share one redirect link. Click + Add message to add more, and drag the handle to reorder them.
* **Slider**: Add multiple messages, each with its own message and redirect link per message. Click + Add message to add more, and drag the handle to reorder them.

If available, you can fill in:

* **Message text**: The text shown on the bar.
  * For the “Manual” content source, fill in the text you want by yourself.
  * For the “Offers” content source, this is filled in automatically from your offer title.
* **Emoji**: Click the emoji icon to pick from the available emojis, or paste your own into the field.
* **Open link**: Insert a link that the bar will redirect to when customers click. Select one of the following:
  * None: No redirect.
  * When click on redirect button: Adds a redirect button to the bar. Fill in the Button text.
  * When click on the entire bar: Makes the whole bar clickable, with no separate button.
* **Open in new tab**: Enable to open the link in a new browser tab.

### Marquee Setting

This section is available only when you select the Marquee display mode.

![](<../../.gitbook/assets/unknown (345).png>)

To set it up, adjust these fields:

* **Running direction**: Choose which direction the messages scroll - Right to left or Left to right.
* **Running speed (1 - 100)**: Drag the slider to set how fast the messages scroll.
* **Stop scrolling when hover on bar**: Tick to pause scrolling when a customer hovers over the bar.

### Slider Setting

This section is available only when you select the Slider display mode.

![](<../../.gitbook/assets/unknown (346).png>)

To set it up, adjust these fields:

* **Choose slider icon style**: Select the navigation arrow style - Chevron, Filled, Arrow, or None.
* **Auto sliding**: Enable to rotate messages automatically. When it’s on:
* **Slide to next message after (seconds)**: Set the delay before the next message appears.
* **Auto sliding direction**: Choose which direction the messages slide - Right to left or Left to right.
* **Stop sliding when hover on bar**: Tick to pause rotation when a customer hovers over the bar.

## Style

This tab controls how your Announcement Bar looks.

![](<../../.gitbook/assets/unknown (347).png>)

### Position

Choose where the bar appears on the page:

* Top: Sits above the header.
* Top, fixed: Always sticks to the top as customers scroll.
* Top, shows on scroll up: Appears at the top when customers scroll up.
* Bottom, fixed: Always sticks to the bottom as customers scroll.
* Bottom, shows on scroll down: Appears at the bottom when customers scroll down.

### Typography

Control the font and text size of your bar.&#x20;

To set it up:

1. **Choose a font** from 2 options:

* Inherit from Store theme: BOGOS automatically detects and uses your store's existing font.
* Choose custom font: You pick from available Google Fonts.

2. Adjust the **message** and **button font size:** Set each for Desktop and Mobile.

{% hint style="info" %}
Click “Full width” on the Preview panel to check your changes on desktop.
{% endhint %}

### Theme

![](<../../.gitbook/assets/unknown (348).png>)

To customize the appearance of your announcement bar:

1. Pick a **ready-made theme** from the dropdown (optional).
2. Under the **Bar background style**, the fields change with your choice:

* Solid color: Set the Bar color.
* Gradient: Set two bar colors and the Gradient direction.
* Image: Upload an image as the bar background and enable these to highlight the texts better:
* Blur image to soften the background
* Add overlay color to layer a color on top of the image

3. Adjust the colors of other elements, including text and button color.&#x20;
4. Set **Padding top** and **Padding bottom** for Desktop and Mobile.

{% hint style="info" %}
Click “Full width” on the Preview panel to check your changes on desktop.
{% endhint %}

When you're done, click Save draft to keep your changes, or Publish to make the bar live.

## Placement

This tab controls where your Announcement Bar appears.

![](<../../.gitbook/assets/unknown (349).png>)

### Page display

Control which pages your bar appears on between 2 options:

**Show on all pages**: Display bar across your whole store.

**Show on specific pages**: Show the bar only on selected pages. Tick the pages to display it on:

* **Home page**
* **Cart page**
* **Product page** (all product pages).
* **Collection page** (all collection pages).
* **Custom page**: Show or hide the bar on specific pages. There are 4 options to choose from:
  * Equal to: Enter the exact URL where you want the widget to show (a link to a specific collection, a specific product page,...).
  * Not equal to: Enter the URL where you do NOT want the widget to show.
  * Contains: Enter a term. The widget will show only on pages with that term in the URL. Example: "summer-sale".
  * Not contains: Enter a term to hide the widget on pages with that term in the URL. Example: "summer-sale".

### Filter by location

Control which countries your bar is shown in or hidden from. BOGOS detects each customer's country based on their IP address.

To set it up:

* Click **Select location** to choose the target countries.
* Enable **Exclude selected locations** to hide the bar from the countries you just selected above.

### Block placement

![](<../../.gitbook/assets/unknown (426).png>)

By default, the Announcement Bar appears on the pages you selected above, in the position set under Style → Position.

If you want to place the bar in a custom position (e.g., a specific spot within your homepage or product page), follow these steps:

1. **Copy booster ID:** The theme block needs an ID to display the correct booster.

* Click Save draft or Publish first to generate the booster ID.
* Then copy the ID shown in this section.

2. **Open theme and paste:** Add the BOGOS: Announcement bar block to your theme and paste the ID.

* Click **Go to theme editor** to open your Shopify theme editor.
* Navigate to the page where you want the bar to appear.
* Add the BOGOS: Announcement bar block to your desired position.
* Paste the copied booster ID into the block.

For more details, visit our \[[Adjust BOGOS Blocks](https://docs.bogos.io/quick-start-guide/adjust-bogos-blocks)] guide.

## Need Help?

If you need any assistance, feel free to reach out to our customer support team via live chat within our BOGOS app.
