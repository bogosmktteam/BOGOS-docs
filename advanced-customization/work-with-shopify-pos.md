# Work with Shopify POS

BOGOS allows you to **run gift with purchase offers directly on Shopify Point of Sales (POS)**, making it easy to reward customers in your physical stores just like you do online.

{% hint style="info" %}
**Before diving in, please read these notes first:**

1. **All products involved** in the offers must be published to the POS channel.
2. Both **Gift Clone and Gift Function** mechanisms support Shopify POS.
3. **For offers applying to collections** (only selected collections, all except selected collections), you must publish both these collections and all their products to your Online Store.
4. POS currently **DOESN'T support** gift offers with:

* Sub-conditions (except for Sales Channels).
* Gift products as gift cards (due to Shopify rules).
{% endhint %}

{% embed url="https://youtu.be/P4uPN8PXNCA" %}

## Set up BOGOS on Shopify POS

Please have **BOGOS installed** in your Admin and **Shopify POS installed** on your device (iOS or Android).&#x20;

**Once it's done:**

1. On your device, open the Shopify POS app.
2. From the POS Home screen, tap Add tile
3. Tap the App option
4. Select BOGOS.io: Free gift on the screen
5. Add the BOGOS POS UI extension
6. Click Save.

<figure><img src="../.gitbook/assets/unknown (166).png" alt=""><figcaption></figcaption></figure>

## Add gift(s) to an order on POS

**To do this:**

1. Publish a gift offer(s) in BOGOS app.
2. Publish all products involved in the offer to the POS channel.
3. Open Shopify POS. You can then add gifts to the cart based on your offer setup:

* [Automatically add gift(s) to cart](work-with-shopify-pos.md#automatically-add-gift-s-to-cart-on-pos)
* [Choose gift(s) from a list](work-with-shopify-pos.md#choose-a-gift-s-from-a-list-on-pos)

{% hint style="warning" %}
For the Gift Clone mechanism, gift clone products are usually created after you create an offer. Therefore, please double-check if the **gift clone products are published** on the POS channel.
{% endhint %}

### Automatically add gift(s) to cart on POS

When the POS cart meets your offer conditions, a gift(s) will be automatically added to the order.

**To use this option:**

1. Double-check if you enable 'Automatically add gift to cart' setting under Settings → Gift Condition.

<figure><img src="../.gitbook/assets/unknown (167).png" alt=""><figcaption></figcaption></figure>

2. When creating the offer, choose 'Automatically add all gifts'.

<figure><img src="../.gitbook/assets/unknown (168).png" alt="" width="495"><figcaption></figcaption></figure>

_For details, please visit_ [_Create Gift Offer_](../detailed-guide/gift-offer/create-gift-offer.md#id-4.-select-gifts) _guide._

### Choose a gift(s) from a list on POS

When the POS cart meets your offer conditions, customers will receive a real-time notification and can pick the one(s) they like from a gift list.&#x20;

**To add gifts to their order:**

1. Add products to your cart. Make sure the cart reaches the condition of your offer
2. Navigate to the POS Home screen > Tap Bogos Pos
3. From the list of available gift products, click Claim gift
4. The gift is now added. Complete the order and checkout

<figure><img src="../.gitbook/assets/unknown (169).png" alt=""><figcaption></figcaption></figure>

**To use this option, when creating the offer:**

1. Select “Number of gifts customer will receive”.
2. Enter the number of gifts you want customers to be eligible to claim.

<figure><img src="../.gitbook/assets/unknown (170).png" alt="" width="496"><figcaption></figcaption></figure>

_For details, please visit_ [_Create Gift Offer_](../detailed-guide/gift-offer/create-gift-offer.md#id-4.-select-gifts) _guide._

### Run gift offer only on POS channel/ specific POS locations

This feature creates gift offers that are exclusively available on POS or specific locations, meaning they can only be available when buying via your specific physical stores.

To set it up:

1. Open BOGOS app > Create a new or select an existing gift offer.
2. Add Offer sub-condition > Add Sales channel condition
3. Enable Point of sale channel
4. Select your desired POS location (optional)
5. Click Publish your offer.

<figure><img src="../.gitbook/assets/unknown (68).png" alt=""><figcaption></figcaption></figure>

### Manage Gift Inventory on POS

**For Gift Function mechanisms**, gift quantities are auto-synchronized with your inventory setup in Shopify. If inventory reaches 0, the offer won't run on POS.

**For the Gift Clone mechanism**, gift quantity follows your setup in Settings:

* _Sync clone products’ quantity with originals automatically_: Gift quantity in POS stays in sync with the original product inventory.
* _Input gift product’s inventory manually:_ You manually control the gift quantity independently from the original product.

<figure><img src="../.gitbook/assets/unknown (171).png" alt=""><figcaption></figcaption></figure>

_For details on Gift inventory management, please visit_ [_Settings_](../detailed-guide/settings.md#id-5.-gift-inventory-management) _guide._
