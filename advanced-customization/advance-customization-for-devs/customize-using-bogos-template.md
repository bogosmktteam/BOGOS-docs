# Customize using BOGOS template

### Step 1

Create file _freegifts-snippet.liquid_ and include it in the _theme.liquid_

### Step 2

Add the content below into the file _freegifts-snippet_

```liquid
{% comment %}
BOGOS: Free gift & Buy X Get Y
https://bogos.io
-----------------------------
The snippets below make up for the BOGOS Gift slider's default template.
All non-defined variables are open for editing. Defined variables must be kept the same for the app to work properly.

If you require any assistance, reach out to the BOGOS team via Live chat or Email at support@secomapp.com
{% endcomment %}

<script id="sca_fg_cart_section_gifts_slider" type="text/template">
    {% raw %}
        <div class="slide-container">
            <div class="fg-section-title">
                {{ fg_slider_title }}
            </div>
            <div class="glider-contain">
                <div class="glider" id="fg-gift-items"></div>
                <div>
                    <button aria-label="Previous" class="glider-prev nav left-nav btn-nav-slide">❮</button>
                </div>
                <div>
                    <button aria-label="Next" class="glider-next nav right-nav btn-nav-slide">❯</button>
                </div>
            </div>
            <div role="tablist" class="dots"></div>

            {{ sca_fg_disable_slider_section }}
        </div>
    {% endraw %}
</script>

<script id="sca_fg_section_gifts_popup" type="text/template">
    {% raw %}
        <div class="slide-container sca-modal-dialog-fg">
            <button class="sca-close-modal-fg btn" aria-label="close modal" data-close>✕</button>
            <div class="fg-section-title">
                {{ fg_slider_title }}
            </div>
            <div class="glider-contain">
                <div class="glider" id="fg-gift-items"></div>
                <div>
                    <button aria-label="Previous" class="glider-prev nav left-nav btn-nav-slide">❮</button>
                </div>
                <div>
                    <button aria-label="Next" class="glider-next nav right-nav btn-nav-slide">❯</button>
                </div>
            </div>
            <div role="tablist" class="dots"></div>

            {{ sca_fg_disable_slider_section }}
        </div>
    {% endraw %}
</script>

<script id="sca_fg_section_gift_item" type="text/template">
    {% raw %}
        <div class="d-flex product-item">
            <div class="product-content">
                <div class="top-content">
                    <a class="gift-original-url" href="/products/{{ fg_product_handle }}" target="_blank">
                        <img class="product-item-thumbnail" src="{{ fg_product_img }}" alt="{{ fg_product_img_alt }}">
                        <p class="product-title">{{ fg_product_title }}</p>
                        <p class="product-title variant-title {{ fg_gifts_check_show_by_variants }}">
                        <span class="selected-variant {{ fg_check_selected_variant }}">
                            {{ fg_variant_title }}
                        </span>
                        </p>
                    </a>
                </div>
                <div class="d-flex bottom-content">
                    <div class="d-flex price-section">
                    <span class="original-price transcy-money">
                        <del>{{ fg_original_price }}</del>
                    </span>
                        <span class="gift-price transcy-money">{{ fg_gift_price }}</span>
                    </div>

                    <div class="dropdown {{ fg_gifts_check_show_by_products }}">
                        <div class="select">
                        <span class="selected-variant {{ fg_check_selected_variant }}">
                            {{ fg_variant_title }}
                        </span>
                            <i class="fa fa-chevron-left"></i>
                        </div>
                        <ul class="dropdown-menu">
                            {{ sca_fg_variant_select_section }}
                        </ul>
                    </div>

                    <button href="javascript:void(0)" class="btn-add-to-cart"
                            data-offer="{{ fg_product_belongs_to_offer }}"
                            data-variant="{{ fg_variant_id }}">
                        {{ fg_add_to_cart }}
                    </button>
                </div>
            </div>
        </div>
    {% endraw %}
</script>

<script id="sca_fg_variant_select_section" type="text/template">
    {% raw %}
        <li class="variant-item" data-img="{{ fg_variant_img }}" id="{{ fg_variant_id }}"
            data-original-id="{{ fg_original_variant_id }}"
            data-price="{{ fg_variant_price }}" data-original-price="{{ fg_original_variant_price }}">
            {{ fg_variant_title }}
        </li>
    {% endraw %}
</script>

<script id="sca_fg_disable_slider_section" type="text/template">
    {% raw %}
        <div id="sca-hidden-gift-popup">
            <input type="checkbox" id="sca-disable-checkbox" class="sca-disable-checkbox" name="sca-disable-checkbox"/>
            <label class="sca-disable-text" for="sca-disable-checkbox">{{ fg_text_disable_slider }}</label>
        </div>
    {% endraw %}
</script>

<script id="sca_fg_cart_message_section" type="text/template">
    {% raw %}
        <div id="sca-promotion-glider" class="glider sca-promotion-glider">
            {{ sca_fg_cart_message_items_section }}
        </div>
    {% endraw %}
</script>

<script id="sca_fg_cart_message_items_section" type="text/template">
    {% raw %}
        <p class="content-promotion-message">
            {{ fg_cart_message }}
        </p>
    {% endraw %}
</script>

<script id="sca_fg_gift_thumbnail_section" type="text/template">
    {% raw %}
        <div class="sca-gift-thumbnail-title">{{ fg_gift_thumbnail_title }}</div>

        <div class="slide-container" id="fg-gift-thumbnail-title">
            <div class="glider-contain">
                <div class="glider sca-list-gift-thumbnail">
                    {{ sca_fg_gift_thumbnail_items_section }}
                </div>

                <div class="{{ fg_check_show_narrow }}">
                    <a href="javascript:void(0)" aria-label="Previous"
                       class="glider-prev nav left-nav btn-nav-slide">«</a>
                    <a href="javascript:void(0)" aria-label="Next" class="glider-next nav right-nav btn-nav-slide">»</a>
                </div>
                <div role="tablist" class="dots-thumbnail"></div>
            </div>
        </div>
    {% endraw %}
</script>

<script id="sca_fg_gift_thumbnail_items_section" type="text/template">
    {% raw %}
        <div class="d-flex product-item">
            <a class="gift-original-url" href="/products/{{ fg_product_handle }}" target="_blank">
                <img class="product-item-thumbnail sca-gift-image" src="{{ fg_product_img }}"
                     alt="{{ fg_product_img_alt }}">
            </a>
        </div>
    {% endraw %}
</script>

<script id="sca_fg_gift_icon_section" type="text/template">
    {% raw %}
        <img src="{{ fg_gift_icon }}" alt="{{ fg_gift_icon_alt }}" class="{{ fg_class_product_or_collection_page }}"/>
    {% endraw %}
</script>

<script id="sca_fg_today_offer_section" type="text/template">
    {% raw %}
        <div id="sca-today-offer-wrap">
            <div class="sca-fg-header">
                <div class="sca-fg-header-title">
                    <span class="sca-fg-today-offer-title">{{ sca_fg_today_offer_title }}</span>
                    <span class="sca-fg-close-today-offer" aria-label="close" data-close>
                      <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="#5e5873" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                        <line x1="18" y1="6" x2="6" y2="18"></line>
                        <line x1="6" y1="6" x2="18" y2="18"></line>
                      </svg>
                    </span>
                </div>
                <span class="sca-fg-today-offer-subtitle">{{ sca_fg_today_offer_subtitle }}</span>
            </div>

            <div class="sca-fg-body">
                <div class="sca-fg-offers">
                </div>
            </div>
            <div class="sca-fg-footer">
                  <span class="sca-fg-footer-content">
                    Created by
                    <a target="_blank" style="color: #5E5873;" href="https://apps.shopify.com/freegifts?utm_source=todayoffer&utm_medium=todayoffer_brandmark">
                      BOGOS
                    </a>
                  </span>
            </div>
        </div>
    {% endraw %}
</script>

<script id="sca_fg_today_offer_item_section" type="text/template">
    {% raw %}
        <div class="sca-fg-offer" data-fg-offer-id="{{ sca_fg_offer_id }}">
            <div class="sca-offer-info">
                <img
                        class="sca-img-offer"
                        width="50"
                        height="50"
                        loading="eager"
                        src="{{ sca_fg_offer_img }}"
                >
                <b class="sca-offer-title" sca-fg-today-offer-title-tooltip="{{ sca_fg_offer_title_tooltip }}" style="cursor: default">{{ sca_fg_offer_title }}</b>
            </div>
            <span class="sca-fg-icon-success">
                <svg
                    width="28"
                    height="28"
                    viewBox="0 0 28 28"
                    fill="none"
                    xmlns="http://www.w3.org/2000/svg"
                >
                <rect x="1" y="1" width="27" height="27" rx="13.5" fill="#28C76F"></rect><path d="M8.5 15.4L13.645 19L20.5 10" stroke="white" stroke-width="2.25" stroke-linecap="round" stroke-linejoin="round"></path>
                </svg>
            </span>
        </div>
    {% endraw %}
</script>

<script id="sca_fg_today_offer_widget" type="text/template">
    {% raw %}
        <img id="sca-fg-today-offer-widget-img" src="{{ sca_fg_today_offer_widget }}" width="50" height="50" alt="fg-widget-today-offer"/>
        <span class="sca-fg-count-offers"></span>
    {% endraw %}
</script>
```
