# Customize using events

{% hint style="info" %}
Note:&#x20;

* In case you use those events below for customization, please make sure to use CSS to hide BOGOS' default component.&#x20;
* All customizations should be implemented inside the file snippet/freegifts-snippet.liquid
{% endhint %}

```typescript
type GiftVariant {
  id: number,
  title: string,
  price: number,
  original_price: number,
  thumbnail: string,
  discount_type: "percentage" | "fixed_amount",
  discount_value: number
}

type GiftProduct {
  id: number,
  title: string,
  handle: string,
  thumbnail: string,
  belongs_to_offer?: string | string[],
  variants: GiftVariant[]
}

type TodayOffer {
  id: string,
  title: string,
  gifts: GiftProduct[]
}

type CartMessage {
  value: string,
  offer_root: string, // offer id
}
```



### 1. Event for customizing the Gift slider

```javascript
document.addEventListener("fg-gifts:show-slider", (e) => {
  /* Event for customizing the gift slider */
  // Hidden default 
  // #freegifts-main-popup-container.sca-modal-fg {
  //   display: none !important;
  // }
  console.log("fg-gifts:show-slider", e.detail)
  // Data type of e.detail: {
  // addGiftToCartFunc: async (variantID, quantity, offerId) => void, // function handle add gift to cart by BOGOS
  // gifts: GiftProduct[] // array of gift products to show
  // }
})
```

{% hint style="info" %}
Note: Make sure to use the CSS below to hide BOGOS's default component of the Gift slider
{% endhint %}

```css
#freegifts-main-popup-container.sca-modal-fg {
  display: none !important;
}
```

### 2. Event for customizing the Gift icon, and Gift thumbnail on product page

```javascript
document.addEventListener("fg-gifts:gift-icon", (e) => {
  /* Event for customizing the Gift icon, and Gift thumbnail on product page */
  // Hidden default 
  // #sca-gift-icon, #sca-gift-thumbnail {
  //   display: none !important;
  // }
  console.log("fg-gifts:gift-icon", e.detail)
  // Data type of e.detail: {
  // icon: string, // url gift icon if products has gift
  // gifts: GiftProduct[] // gift can be added when buy that product
  // product: {
  //    handle: string,
  //    variant: number, // variant id selected
  // }
  // }
})
```

{% hint style="info" %}
Note: Make sure to use the CSS below to hide BOGOS's default component of the Gift icon, and Gift thumbnail
{% endhint %}

```css
#sca-gift-icon, #sca-gift-thumbnail {
  display: none !important;
}
```

### 3. Event for customizing the Today offer&#x20;

```javascript
document.addEventListener("fg-today-offer:render", (e) => {
  /* Event for customizing the rendering of Today offer */
  // Hidden default 
  // #sca-fg-today-offer-widget, #sca-fg-today-offer-iframe {
  //   display: none !important;
  // }
  console.log("fg-today-offer:render", e.detail)
  // Data type of e.detail: {
  // todayOffers: TodayOffer[] 
  // }
})
```

{% hint style="info" %}
Note: Make sure to use the CSS below to hide BOGOS's default component of the Today offer
{% endhint %}

```css
#sca-fg-today-offer-widget, #sca-fg-today-offer-iframe {
   display: none !important;
}
```

***

```javascript
document.addEventListener("fg-today-offer:success", (e) => {
  /* Event for customizing the Today offer when the state of the offer is changed. E.g. success, not reach,.. */
  console.log("fg-today-offer:success", e.detail)
  // Data type of e.detail: {
  //   idOffersSuccess: number[], // offers id success
  // } 
})
```

### 4. Event for customizing the Cart message

```javascript
document.addEventListener("fg-messages:render", (e) => {
  /* Event for customizing the Cart message */
  // Hidden default 
  // #sca-promotion-message-layout {
  //   display: none !important;
  // }
  console.log("fg-messages:render", e.detail)
  // Data type of e.detail: {
  // data: CartMessage[] 
  // }
})
```

{% hint style="info" %}
Note: Make sure to use the CSS below to hide BOGOS's default component of the Cart message
{% endhint %}

```css
#sca-promotion-message-layout {
  display: none !important;
}
```
