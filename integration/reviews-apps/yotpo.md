# Yotpo

With BOGOS and Yotpo integration, you can collect authentic reviews from gift products and showcase star ratings directly on the BOGOS gift slider and bundle widget.

[Yotpo](https://apps.shopify.com/yotpo-social-reviews?utm_source=Partner\&utm_medium=BOGOS\&utm_campaign=Helpdoc) is a user-friendly review app that empowers merchants to collect and display authentic customer feedback. With strong social proof, it builds trust and motivates shoppers to convert.

**Yotpo key features:**

* Automated Review Collection – Collect product and site reviews, photos, and videos automatically with customizable email templates and AI-powered prompts.
* Reviews & Ratings Display – Showcase eye-catching reviews and star ratings with Smart Filters to build trust and drive conversions.
* Customizable Review Widgets – Add beautiful review widgets, including carousels and AI-powered review summaries, to your storefront.
* Google & Social Integration – Display reviews across Google and social channels to reach more shoppers and build credibility.
* Review Sync & Analytics – Easily sync reviews across platforms like TikTok and Walmart, while using detailed analytics to optimize conversions.

## How to integrate BOGOS with Yotpo

**Step 1: Install BOGOS** from [Shopify App Store](https://apps.shopify.com/freegifts?utm_source=gitbook\&utm_medium=integration\&utm_campaign=Yotpo) and set up your gift offers

**Step 2: Install Yotpo** from the [Shopify App Store](https://apps.shopify.com/yotpo-social-reviews?utm_source=Partner\&utm_medium=BOGOS\&utm_campaign=Helpdoc)

**Step 3: Enable the Integration**

In the BOGOS app, go to Integration.

Find Yotpo and click Connect.

Select I have already installed.

<img src="../../.gitbook/assets/unknown (454).png" alt="" height="349" width="624">

Turn on the Yotpo integration toggle.

<img src="../../.gitbook/assets/unknown (455).png" alt="" height="351" width="624">

You will be redirected to the connect page. Select the Shopify store where you want to enable the BOGOS–Yotpo integration.

<img src="../../.gitbook/assets/unknown (456).png" alt="" height="351" width="624">

Click Connect to authorize the integration.

<img src="../../.gitbook/assets/unknown (457).png" alt="" height="351" width="624">

You will be redirected back to the BOGOS homepage. Go to Integration > Connect Yotpo > I have already installed again.

Under Integration options, turn on the toggle to activate the Yotpo integration one more time

<img src="../../.gitbook/assets/unknown (458).png" alt="" height="349" width="624">

**Step 4: Select the options you want:**

* Collect reviews through gift products: Reviews collected from cloned gift products will sync with the original.
* Display star ratings: Show star ratings on the Gift Slider or Bundle Widget.

<img src="../../.gitbook/assets/unknown (459).png" alt="" height="349" width="624">

**Step 5: Configure Product Grouping**

Yotpo shares reviews between products that belong to the same product group tag. To ensure that reviews from gift clones are associated with the original product, add the required group tag to the original product. Gift clones created by BOGOS will inherit this tag.

**1. Enable product tags in BOGOS**

In BOGOS, go to Settings > Gift Settings and enable Tags under Include original product details.

<br>

<img src="../../.gitbook/assets/unknown (460).png" alt="" height="352" width="624">



**2. Add a Yotpo group tag to the original product**

In Shopify, add a tag to the original product using the following format:

`YGroup_[group name]`

For example:

`YGroup_summer-tee`

The YGroup\_ prefix is required. Without this prefix, Yotpo will not recognize the tag for product grouping.

<img src="../../.gitbook/assets/unknown (461).png" alt="" height="228" width="624">

Once the product group tag is added to the original product, the cloned gift product will automatically receive the same product group tag. As a result, reviews collected from the cloned gift product will be merged with those of the original product in Yotpo.

#### Important Notes

* Existing gift products will not automatically receive the new tag. Re-activate the relevant gift offer to recreate the gift products with the correct tag.
* Group names can contain letters, numbers, hyphens (-), and underscores (\_) only.
* Each product can belong to one group only.
* A group can contain up to 1,000 products.
* It may take up to 24 hours for reviews to appear after products are grouped.

For more information, see[ Yotpo's product grouping documentation](https://support.yotpo.com/docs/keeping-your-shopify-and-yotpo-product-catalogs-updated#grouping-products).

<br>
