# Extensions / Integrations: Settings Overview
Overview of the various settings available in the extensions and integrations offered by Clerk.io.
## Extensions
Extensions are the solutions we offer which must be installed on an individually hosted server in order to be used.
### Magento 1

Magento 1.9^ Clerk.io Extension

##### General

`Enabled` : Whether the extension is enabled in the currently selected scope.

`Public API key`: Public API key from my.clerk.io Store.

`Private API key`: Private API key from my.clerk.io Store.

`Use Real-time Updates`: Push individual product changes to my.clerk.io between full syncs.

`Additional Fields`: Additional fields you wish to import in the product data.

`Sync Subscribers`: Synchronize the commercial email subscription status of clients.

`Include Pages`: Include CMS page content in daily sync.

`Only Synchronize Product with Visibility`: You can choose to import products as filtered by their visibility. The options are Catalog, Search, Catalog & Search, or All of the Above.

`Additional Fields For Pages`: Additional fields to sync for pages during daily sync.

`Collect Emails`: Whether to include emails in sales / syncs / tracking.

`Collect Baskets`: Whether to log the basket add and remove behavior to visitor data.

`Disable Order Synchronization`: Disable orders from being sent in the daily sync. They will still be logged in real-time from visitors, so this can speed up the daily sync by being set.

`Enable Return Tracking`: Amend the state of orders in Clerk, in case their status changes in future.

`Include Out of Stock Products`: Include Sold Out items in the daily sync.

`Custom Image Width`: The width in pixels of the synced product image URL's, defaults to 210.

`Custom Image Height`: The height in pixels of the synced product image URL's, defaults to 210.

`Language`: Language set in Clerk.js frontend. Should match the language of the store in my.clerk.io, for search to function.

`Import Url`: This is meant to be copy-pasted into the settings in my.clerk.io.

##### Search  

`Enable`: If the Search Page is enabled.

`Show Categories`: Whether to include categories in the results on the Search Page.

`Number of Categories`: Limit to category page results on Search Page.

`Number of Pages`: Limit to CMS page results on Search Page.

`Pages Type`: Type of CMS Pages to filter in results. Only option is "CMS Page".

`Content`: The name of the content from my.clerk.io you wish to use on your Search Page.

`Load more text`: Load more placeholder text for button at the bottom of the page. Most current designs include this element from my.clerk.io, thus this feature has little effect.

`No results text`: Placeholder text to display when no results are returned from the Clerk.io API.

##### Faceted Search  

`Enable`: If Facets are enabled on the Search Page.

`Attributes`: Select the attributes you wish to used for the Facets on the Search Page. The available attributes are checked against the synced data in my.clerk.io, thus 1 data sync must be completed before this can be configured.

`Multiselect Attributes`: Select the attributes you wish to allow multiple selections of within a respective group. Eg. within the "Color" facet you was select both "Green" and "Blue" in order to see products which match at least one value.

`Labels`: Enter the title you would like a Facet group to have. If an attribute has the slug "product_type" you may want that to appear as "Product Type". You also have the option to affect the order of the facets with a numbered order.

`Design`: The numeric ID for the Design from my.clerk.io you may wish to use for your Facets.

##### Live Search  

`Enable`: Whether the Live Search is enabled in the current scope.

`Show Categories`: Whether to show Category Pages in the results of the Live Search.

`Number of Suggestions`: Limit to the number of suggestions returned in the Live Search results.

`Number of Categories`: Limit to the number of categories returned in the Live Search results.

`Number of Pages`: Limit to the number of pages returned in the Live Search results.

`Pages Type`: Type of CMS Pages to filter in results. Only option is "CMS Page".

`Dropdown Positioning`: Where to place the Live Search in relation to the input field it reads from. Options are left, right, below, center and off.

`Content`: The name of the content from my.clerk.io you wish to use for your Live Search.

`Live Search Input Selector`: The CSS selector used for finding the input field used to search on the site.

##### Powerstep  

`Enabled`: Whether the Powerstep is enabled in the current scope.

`Type`: Whether you wish to show the Powerstep as a Page or as a Popup.

`Contents`: A comma separated list of contents from my.clerk.io, which you wish to display in your Powerstep.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the included sliders.

##### Exit Intent  

`Enabled`: Whether the Exit Intent popup is enabled in the current scope.

`Content`: The name of the content from my.clerk.io you wish to use for your Exit Intent.

##### Category Page

`Enabled`: Whether the Category Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Category Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the included sliders.

##### Product Page

`Enabled`: Whether the Product Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Product Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the included sliders.

##### Cart Page

`Enabled`: Whether the Cart Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Cart Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the included sliders.

##### Logging Settings

`Enable`: Whether to enable logging by the Clerk.io module specifically.

`Logging Level`: Set logging level to Err, Warn or Both.

`Logging To`: Set whether log is saved to server filesystem, or sent to the store log in my.clerk.io.

### Magento 2

Magento 2.2^ Clerk.io Extension

##### General

`Public API key`: Public API key from my.clerk.io Store.

`Private API key`: Private API key from my.clerk.io Store.

`Include Pages`: Include CMS page content in daily sync.

`Additional Fields For Pages`: Additional fields to sync for pages during daily sync.

`Language`: Language set in Clerk.js frontend. Should match the language of the store in my.clerk.io, for search to function.

`Store ID`: Should not need to be set, but if you set it, select the same value as you select for language if you wish for the imported data to match the scope it is shown in.

##### Synchronization

`Use Real-time Updates`: Push individual product changes to my.clerk.io between full syncs.

`Collect Emails`: Whether to include emails in sales / syncs / tracking.

`Collect Baskets`: Whether to log the basket add and remove behavior to visitor data.

`Additional Fields`: Additional fields you wish to import in the product data.

`Sync Subscribers`: Synchronize the commercial email subscription status of clients.

`Only Synchronize Saleable Products`: Only synchronize products with which are saleable. It is 
very similar to  publish status and stock status, but is instead an abstraction for both. Saleable items are items which can be bought.

`Only Synchronize Product with Visibility`: You can choose to import products as filtered by their visibility. The options are Catalog, Search, Catalog & Search.

`Track Returned Orders`: Amend the state of orders in Clerk, in case their status changes in future.

`Disable Order Synchronization`: Disable orders from being sent in the daily sync. They will still be logged in real-time from visitors, so this can speed up the daily sync by being set.

`Image Type`: The size of the imported images. Must be selected from one of the created types on the store from the dropdown. Please note, that just because an image type exists for a product, does not mean an image has been uploaded for that product. It is advised to check which on the client actually uses frontend and to pick that one.

##### Customer Synchronization

`Enable`: Whether to synchronize customer data during the daily sync.

`Extra Customer Attributes`: A comma separated list of the additional fields to include in the customer data during sync.

##### Search  

`Enable`: If the Search Page is enabled.

`Include Categories`: Whether to include categories in the results on the Search Page.

`Number of Categories`: Limit to category page results on Search Page.

`Number of Pages`: Limit to CMS page results on Search Page.

`Pages Type`: Type of CMS Pages to filter in results. Only option is "CMS Page".

`Content`: The name of the content from my.clerk.io you wish to use on your Search Page.

`Load more text`: Load more placeholder text for button at the bottom of the page. Most current 
designs include this element from my.clerk.io, thus this feature has little effect.

`No results text`: Placeholder text to display when no results are returned from the Clerk.io API.

##### Faceted Search  

`Enable`: If Facets are enabled on the Search Page.

`Attributes`: Select the attributes you wish to used for the Facets on the Search Page. The available attributes are checked against the synced data in my.clerk.io, thus 1 data sync must be completed before this can be configured.

`Multiselect Attributes`: Select the attributes you wish to allow multiple selections of within a respective group. Eg. within the "Color" facet you was select both "Green" and "Blue" in order to see products which match at least one value.

`Titles`: Enter the title you would like a Facet group to have. If an attribute has the slug "product_type" you may want that to appear as "Product Type". You also have the option to affect the order of the facets with a numbered order.

`Design`: The numeric ID for the Design from my.clerk.io you may wish to use for your Facets.

##### Live Search  

`Enable`: Whether the Live Search is enabled in the current scope.

`Show Categories`: Whether to show Category Pages in the results of the Live Search.

`Number of Suggestions`: Limit to the number of suggestions returned in the Live Search results.

`Number of Categories`: Limit to the number of categories returned in the Live Search results.

`Number of Pages`: Limit to the number of pages returned in the Live Search results.

`Pages Type`: Type of CMS Pages to filter in results. Only option is "CMS Page".

`Dropdown Positioning`: Where to place the Live Search in relation to the input field it reads 
from. Options are left, right, below, center and off.

`Content`: The name of the content from my.clerk.io you wish to use for your Live Search.

`Live Search Input Selector`: The CSS selector used for finding the input field used to search on 
the site.

`Live Search Form Selector`: The CSS selector used for finding the form containing the input used to search on the site.

##### Powerstep  

`Enabled`: Whether the Powerstep is enabled in the current scope.

`Type`: Whether you wish to show the Powerstep as a Page or as a Popup.

`Contents`: A comma separated list of contents from my.clerk.io, which you wish to display in 
your Powerstep.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the 
included sliders.

##### Exit Intent  

`Enabled`: Whether the Exit Intent popup is enabled in the current scope.

`Content`: The name of the content from my.clerk.io you wish to use for your Exit Intent.

##### Category Page

`Enabled`: Whether the Category Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Category Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the 
included sliders.

##### Product Page

`Enabled`: Whether the Product Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Product Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the 
included sliders.

##### Cart Page

`Enabled`: Whether the Cart Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Cart Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the 
included sliders.

##### Logging Settings

`Enable`: Whether to enable logging by the Clerk.io module specifically.

`Logging Level`: Set logging level to Err, Warn or Both.

`Logging To`: Set whether log is saved to server filesystem, or sent to the store log in 
my.clerk.io.

### WooCommerce

WooCommerce 3.0^ Clerk.io Extension

##### General

`Public API key`: Public API key from my.clerk.io Store.

`Private API key`: Private API key from my.clerk.io Store.

`Language`: Language set in Clerk.js frontend. Should match the language of the store in 
my.clerk.io, for search to function.

##### Customer Synchronization

`Enable`: Whether to synchronize customer data during the daily sync.

`Extra Customer Attributes`: A comma separated list of the additional fields to include in the 
customer data during sync.

##### Data Synchronization

`Use Real-time Updates`: Push individual product changes to my.clerk.io between full syncs.

`Include Pages`: Include CMS page content in daily sync.

`Additional Fields For Pages`: Additional fields to sync for pages during daily sync.

`Additional Types For Pages`: Additional Types of pages to sync. Useful for getting custom page types. You can provide a comma separated list to get more than 1 of these.

`Include Out of Stock Products`: Include Sold Out items in the daily sync.

`Collect Emails`: Whether to include emails in sales / syncs / tracking.

`Collect Emails Signup Message`: If you want to have a checkbox at checkout where we subscribe 
the email within my.clerk.io, you can provide a message here while Collect Emails is also active. The signup checkbox will not be present if left blank.

`Collect Baskets`: Whether to log the basket add and remove behavior to visitor data.

`Additional Fields`: Additional fields you wish to import in the product data.

`Strip/Trim Split Attributes`: When unchecked (Strip), it removes all spaces within strings during import e.g. turning' Option 1' into 'Option1'. When checked (Trim), it only removes leading and trailing spaces, preserving spaces within the string e.g. resulting in 'Option 1'.

`Additional Fields Raw`: Input the attribute slug from Additional Fields if you want the attribute to be imported without any sanitation. For example, if the attribute value contains a comma, using the raw value will not split the value into a list with the comma.

`Disable Order Synchronization`: Disable orders from being sent in the daily sync. They will still be logged in real-time from visitors, so this can speed up the daily sync by being set.

`Image Size`: The size of the imported images. Must be selected from one of the created types on the store from the dropdown. Please note, that just because an image type exists for a product, does not mean an image has been uploaded for that product. It is advised to check which on the client actually uses frontend and to pick that one.

##### Live Search  

`Enable`: Whether the Live Search is enabled in the current scope.

`Include Categories`: Whether to show Category Pages in the results of the Live Search.

`Number of Categories`: Limit to the number of categories returned in the Live Search results.

`Include Suggestions`: Whether to show search suggestions in the results of the Live Search.

`Number of Suggestions`: Limit to the number of suggestions returned in the Live Search results.

`Include Pages`: Whether to show search pages in the results of the Live Search.

`Number of Pages`: Limit to the number of pages returned in the Live Search results.

`Pages Type`: Type of CMS Pages to filter in results. Only option is "CMS Page".

`Dropdown Positioning`: Where to place the Live Search in relation to the input field it reads 
from. Options are left, right, below, center and off.

`Live Search Input Selector`: The CSS selector used for finding the input field used to search on the site.

`Live Search Form Selector`: The CSS selector used for finding the form containing the input used to search on the site.

`Content`: The name of the content from my.clerk.io you wish to use for your Live Search.

##### Search  

`Enable`: If the Search Page is enabled.

`Search Page`: CMS page to use as a target for rendering the Clerk.io Search.

`Include Categories`: Whether to include categories in the results on the Search Page.

`Number of Categories`: Limit to category page results on Search Page.

`Include Pages`: Whether to include pages in the results on the Search Page.

`Number of Pages`: Limit to CMS page results on Search Page.

`Pages Type`: Type of CMS Pages to filter in results. Only option is "CMS Page".

`Content`: The name of the content from my.clerk.io you wish to use on your Search Page.

`Load more text`: Load more placeholder text for button at the bottom of the page. Most current 
designs include this element from my.clerk.io, thus this feature has little effect.

##### Faceted Search  

`Enable`: If Facets are enabled on the Search Page.

`Add Custom Attribute`: Input field for adding and attribute you wish to use in facets.

`Facet Attributes`: Select the attributes you wish to used for the Facets on the Search Page. You 
can rename their titles and change the order in which they are listed, and whether they are shown.

`Design`: The numeric ID for the Design from my.clerk.io you may wish to use for your Facets.

##### Powerstep  

`Enabled`: Whether the Powerstep is enabled in the current scope.

`Powerstep Type`: Whether you wish to show the Powerstep as a Page or as a Popup.

`Powerstep Page`: The CMS page you wish to use as a target for rendering the PowerStep.

`Contents`: A comma separated list of contents from my.clerk.io, which you wish to display in 
your Powerstep.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the included sliders.

`Enable Custom Texts`: Toggle whether to overwrite the localized powerstep text, with personally defined values.

`Back Button`: Text message on the Powerstep Back Button.

`Cart Button`: Text message on the Powerstep Cart Button.

`Product Title`: Text message on the Powerstep Title.

##### Exit Intent  

`Enabled`: Whether the Exit Intent popup is enabled in the current scope.

`Content`: The name of the content from my.clerk.io you wish to use for your Exit Intent.

##### Category Page

`Enabled`: Whether the Category Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Category Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the included sliders.

`Category ID Shortcode`: Shortcode for rendering the category ID when on a category page.

##### Product Page

`Enabled`: Whether the Product Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Product Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the included sliders.

`Product ID Shortcode`: Shortcode for rendering the product ID when on a product page.

##### Cart Page

`Enabled`: Whether the Cart Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Cart Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the 
included sliders.

`Cart IDs Shortcode`: Shortcode for rendering the product ids in cart for the current session.

##### Additional Scripts

`Enabled`: Whether to enable the injection of additional header scripts.

`JS Code`: Code field where you can define the script you would like to load.

##### Logging Settings

`Enable`: Whether to enable logging by the Clerk.io module specifically.

`Logging Level`: Set logging level to Err, Warn or Both.

`Logging To`: Set whether log is saved to server filesystem, or sent to the store log in my.clerk.io.

### PrestaShop

Prestashop 1.6.X & 1.7.X

##### General

`Public Key`: Public API key from my.clerk.io Store.

`Private Key`: Private API key from my.clerk.io Store.

`Language`: Language set in Clerk.js frontend. Should match the language of the store in 
my.clerk.io, for search to function.

`Tracking Script Hook Position`: The position where the Clerk.io tracking script is injected in the theme.


##### Data Synchronization

`Use Real-time Updates`: Push individual product changes to my.clerk.io between full syncs.

`Include Pages`: Include CMS page content in daily sync.

`Additional Fields For Pages`: Additional fields to sync for pages during daily sync.

`Collect Emails`: Whether to include emails in sales / syncs / tracking.

`Disable Customer Sync`: If you wish to disable output from the customer endpoint during sync.

`Sync Subscribers`: If you wish to sync the commercial subscription status of a known email to Clerk. Only works if collect emails is turned on and disable customer sync is not turned on.

`Collect Baskets`: Whether to log the basket add and remove behavior to visitor data.

`Additional Fields Products`: Additional fields you wish to import in the product data.

`Disable Order Synchronization`: Disable orders from being sent in the daily sync. They will still be logged in real-time from visitors, so this can speed up the daily sync by being set.

`Include Variant References`: Include variant data as lists.

`Include Product Features`: Include product features in product data. These function very similar to tags on other platforms.

`Include Out of Stock Products`: Include Sold Out items in the daily sync.

`Only Check Local Stock`: Toggle whether the stock is retrieved for the shop context, or the country context dictated by the request IP.

`Get Product Vat by Country`: Explicitly calculate product vat as defined for the default country associated with the language for the scope.

`Order Products Query by Stock`: Order product collection used for sync by aggregate stock count. Default is order by ID, but using stock is more performant for very large catalogs.

`Image Size`: The size of the imported images. Must be selected from one of the created types on the store from the dropdown. Please note, that just because an image type exists for a product, does not mean an image has been uploaded for that product. It is advised to check which on the client actually uses frontend and to pick that one.

##### Search  

`Enable`: If the Search Page is enabled.

`Include Categories`: Whether to include categories in the results on the Search Page.

`Number of Categories`: Limit to category page results on Search Page.

`Number of Pages`: Limit to CMS page results on Search Page.

`Pages Type`: Type of CMS Pages to filter in results. Only option is "CMS Page".

`Content`: The name of the content from my.clerk.io you wish to use on your Search Page.

`Load more text`: Load more placeholder text for button at the bottom of the page. Most current designs include this element from my.clerk.io, thus this feature has little effect.

`No results text`: Placeholder text to display when no results are returned from the Clerk.io API.

##### Faceted Search  

`Enable`: If Facets are enabled on the Search Page.

`Attributes`: Select the attributes you wish to used for the Facets on the Search Page. The available attributes are checked against the synced data in my.clerk.io, thus 1 data sync must be completed before this can be configured.

`Multiselect Attributes`: Select the attributes you wish to allow multiple selections of within a respective group. Eg. within the "Color" facet you was select both "Green" and "Blue" in order to see products which match at least one value.

`Titles`: Enter the title you would like a Facet group to have. If an attribute has the slug "product_type" you may want that to appear as "Product Type". You also have the option to affect the order of the facets with a numbered order.

`Design`: The numeric ID for the Design from my.clerk.io you may wish to use for your Facets.

##### Live Search  

`Enable`: Whether the Live Search is enabled in the current scope.

`Show Categories`: Whether to show Category Pages in the results of the Live Search.

`Number of Suggestions`: Limit to the number of suggestions returned in the Live Search results.

`Number of Categories`: Limit to the number of categories returned in the Live Search results.

`Number of Pages`: Limit to the number of pages returned in the Live Search results.

`Pages Type`: Type of CMS Pages to filter in results. Only option is "CMS Page".

`Dropdown Positioning`: Where to place the Live Search in relation to the input field it reads from. Options are left, right, below, center and off.

`Content`: The name of the content from my.clerk.io you wish to use for your Live Search.

`Live Search Input Selector`: The CSS selector used for finding the input field used to search on the site.

`Live Search Form Selector`: The CSS selector used for finding the form containing the input used to search on the site.

##### Powerstep  

`Enabled`: Whether the Powerstep is enabled in the current scope.

`Type`: Whether you wish to show the Powerstep as a Page or as a Popup.

`Contents`: A comma separated list of contents from my.clerk.io, which you wish to display in 
your Powerstep.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the included sliders.

##### Exit Intent  

`Enabled`: Whether the Exit Intent popup is enabled in the current scope.

`Content`: The name of the content from my.clerk.io you wish to use for your Exit Intent.

##### Category Page

`Enabled`: Whether the Category Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Category Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the included sliders.

##### Product Page

`Enabled`: Whether the Product Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Product Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the 
included sliders.

##### Cart Page

`Enabled`: Whether the Cart Page Recommendations is enabled in the current scope.

`Content`: The name of the contents from my.clerk.io you wish to use for your Cart Page.

`Filter Duplicates`: Filter the results, so that a product never appears in more than 1 of the included sliders.

##### Logging Settings

`Enable`: Whether to enable logging by the Clerk.io module specifically.

`Logging Level`: Set logging level to Err, Warn or Both.

`Logging To`: Set whether log is saved to server filesystem, or sent to the store log in my.clerk.io.


### Shopware 6

Shopware 6.4^ Extension

#### General

`Enabled`: Whether the plugin is enabled for the currently selected sales channel.

`Public Key`: Public API Key found in my.clerk.io.

`Private Key`: Private API Key found in my.clerk.io.

#### Add to Cart URL's

`Enabled`: Whether to allow adding product to cart via the submission of url params.

`domain.com/addtocart?ids=SW10001&qtys=5`

`domain.com/addtocart?ids=SW10001,SW10002&qtys=5,2`

#### Live Search

`Status`: If the live search is enabled.

`Number of Suggestions`: Limit of suggestions to include in live search results.

`Number of Categories`: Limit of categories to include in live search results.

`Number of Pages`: Limit of pages to include in live search results.

`Page Type`: The type of pages to be allowed in result. All means no filter.

`Dropdown Positioning`: Where the live search will appear in relation to the attached input field.

`Content`: The content ID from my.clerk.io you wish to use to render the live search.

`Input Selector`: The CSS selector for the input field you wish to use for submitting / typing queries.

`Form Selector`: The CSS selector of the form element which wraps your Search Input.

#### Search Page

`Status`: If the search page is enabled.

`Include Categories`: If category page results should be included in the search page.

`Number of Categories`: Limit to the number of category page results returned on the search page. 

`Number of Pages`: Limit to the number of CMS page results returned on the search page.

`Page Types`: The type of pages to be allowed in result. All means no filter.

`Content`: The content ID from my.clerk.io you wish to use to render the search page.

#### Faceted Search

`Status`: If the facets are enabled for the search page.

`Attributes`: A comma separated list of the attributes you wish to use in facets. Only valid for attributes which have been synced to my.clerk.io.

`Facet Titles`: The name you wish to display as the title on each facet group. If not provided the attribute slug will be displayed. Eg. `price:Price,categories:Categories,brand:Brand`

`Multi Selected Attributes`: A comma separated list of the attributes you wish to allow multiple concurrent selections of within a given facet group. 

`Design`: The design ID for the design you wish to use when rendering the facets on the search page. ID must be numeric if used, is optional to use.


#### Product Page

`Status`: If the product page recommendations are enabled for the current sales channel.

`Hook Location`: Choose which block to inject the product page recommendations within the theme. Options are description and cross selling block.

`Content`: A comma separated list of the contents from my.clerk.io you wish to use to on the product page.

#### Category Page

`Status`: If the category page recommendations are enabled for the current sales channel.

`Content`: The content from my.clerk.io you wish to display at the top of the category page.

#### Cart Page

`Status`: If the cart page recommendations are enabled for the current sales channel.

`Content`: The content from my.clerk.io you wish to display at the top of the category page.

#### Exit Inten

`Status`: If the exit intent is enabled for the current sales channel.

`Content`: The content from my.clerk.io you wish to use to display the exit intent.

#### PowerStep

`Status`: If you wish to display the powerstep with recommendations after an item is added to the cart.

`Type`: The type of Powerstep you wish to display. The options are Popup and Page.

`Content`: A comma separated list contents from my.clerk.io which you wish to display within the powerstep.

## Integrations

### Shopify

#### DataSync

`Shopify Domain`: domain-shop.myshopify.com

`Shopify API Key`: Private app API key.

`Shopify API Access Token`: Token from private shopify app.

`Shopify API Secret`: One time revealed secret when creating Shopify private app credentials.

`Default Image Size`: Custom measurements to importer image links. You want the size to be the biggest size the image will ever be displayed at for max efficiency. Normally this ranges between 160px - 400px in height, depending on the theme.

`Shop Market`: The name of the market you wish the product data to sync with. For multilanaguage and currency sites, you can think of Market as the localization which affects availability and pricing. Optional, for single market sites.

`Shop Locale`: The locale string used for the multilanguage sites. Eg. `da` or `da-dk`. This is only used for text translations which are localized. Meaning you can sync the translations independently from the pricing and availability models.

`Prefix Urls with Locale`: Due to backwards compatibility with older designs, the choice to concatenate the locale string to the urls during data import can be selected here.

`Custom Attributes`: Provide the custom attributes you wish to attempt to sync for the product. These attributes are either created using mutations in the admin api, or are contained in tags or metafield. This does not refer to variants or options.

`Inventory Locations`: The name of alternate stock locations you wish to sync. Inventory locations can hold exclusive stock for products, meaning a product can be active and return stock 0, you do not provide the alternate stock location name due to it having no recorded stock in the abstract inventory. Always ask client which ones they set up if in doubt.

`Include Pages`: Whether to sync CMS pages and blogs during daily sync.

`Include Out-of-stock Products`: Include products with stock <= 0.

`Include Continue Selling When OOS`: Force products with continue selling policy to always be in stock for sync.

`Shopify Published Status`: Include / exclude products based on publication status.

`Shopify Category Published Status`: Include / exclude categories based on publication status.

`Shopify Pages Published Status`: Include / exclude pages based on publication status.

`Enable Real Time Updates`: Enabled pushing product changes into Clerk using weebhook. Not that the data available in the webhook, depends on when it was created. Market info and publication contexts was added in 2022.

`Only Import in Stock Variant Data`: Remove all option and variant references for non purchasable variants.

`Separate Varaint Options`: Creates separate lists with the property variations for each variant. Usually the most common ones are Color and Size. 

`Order History`: The number of days of order history to include in the daily sync.

`Import Tags`: Choose whether to filter some tags out of the product data which is synced.

`Include Subscriber State`: Include the commercial correspondance subscriber state as a field in the customer sync.

### Shopware 6

#### DataSync

`Store URL`: The public URL of the webshop as seen when visiting it in the browser.

`Access Key ID`: The access key ID as created under integrations in the Shopware 6 Admin.

`Secret Access Key`: The one time access key created for the integration in the Shopware 6 Admin.

`Language Name`: The Language name of the scope you wish to sync. Must be name as written within the Shopware 6 admin. Field also accepts the corresponding hashed ID for the language, but this id is only revealed in the network calls within the admin.

`Page Size`: The size of the pages when syncing. Important due to Shopware 6 being self hosted, so some clients may run it on weaker hardware.

`Default Image Size`: The default dimensions for the images we sync for products. 

`Custom Attributes`: A comma separated list of attributes you wish to sync from the product. Unlike some of our other platforms, he it is possible to define a you want a nested field on the product with dot notation. Eg. `cheapestPrice.price.gross`

`Include Product Properties`: Product Properties are like options in shopify. They are things like size, coolor material.

`Include Product Tags`: Tags are simple string associated with a product. Including these will add a list of these string to the product data.

`Order History`: The Number of days you wish to include when syncing order data daily. 

### Shoporama

#### DataSync

`Store URL`: The domain of the shop as seen when visiting the site.

`Access Token`: The access tokem created for the REST api in the Shoporama admin.

`Custom Attributes`: A comma separated list of attributes you wish to read from the product data during daily sync.

`Include Out-Of-Stock Products`: Whether to include OOS products during the daily sync.

`Order History Days`: The number of days from current date you wish to look at when importing order data daily.

`Image Format`: The file type of the images synced for products daily.

### LightSpeed

#### DataSync

`Domain`: The public url of the webshop.

`Cluster ID`: The server which supports your webshop. [Info](https://ecom-support.lightspeedhq.com/hc/en-us/articles/115000272353-2-b-Cluster-information)

`API Key`: The API key created for the integration in the LightSpeed admin.

`API Secret`: The one time secret created for the integration in the LightSpeed admin.

`Language`: The language iso string you wish to get texts for. Eg. `en`

`Auto Detect Attributes for Filtering`: Automatically attempt to sync all attributes used in the native site filters.

`Custom Attributes`: A comma separated list of customn attributes, tags or metafields you wish to attempt to retrieve for products in the daily sync.

`Image Size`: The size of the synced images in the product feed. Format is WxHxZoom, Eg. `300x400x1`

`Include Orders`: Choose how much order data to include in the daily sync. If you receive rate limit warnings in sync, lowering this is advised as the limit is quite low from LightSpeed unless requested to be increased, and the order details cannot be queried in bulk for their containing line items.

`Accepted Order Statuses`: A comma separated list of the status an order can have for it to be considered valid.

`Include Out-Of-Stock Products`: Whether to include all products in sync regardless of stock count.

`Collect Emails`: Whether to include customer emails when syncing order data.

`Include Pages`: Whether to include CMS pages and Blogs when syncing daily.

`Include Customers`: Whether to include customers in general during sync. Disabling this, removes the ability to sync any customer details which are not the function of a completed order.

`Include Free Products`: Whether to include Free Products in the sync. This is done based on a free_product attribute, not the sale price value, and is meant to target promotional items not meant to be sold individually.

`Include Avg Review Score`: Include the native product review ratings in daily sync product data.

`Include Variant Data`: Include lists with the product variation data, such as size or color.

`Include Variant Stock`: Include a list with the stock count for each variant.

`Include Variant Stock Tracking`: Choose whether the the Stock on the parent product is read directly or constructed in aggregate of its variants.

`Include hidden Categories`: Whter to include categories in sync which are hidden in the menu frontend.

### BigCommerce

#### DataSync

`Store Hash`: The unique hash associated with the store.

`Client ID`: The client account ID.

`Client Secret`: The one time reveal secret created for the API credentials.

`Access Token`: The access token created for the API credentials.

`Custom Attributes`: A comma separated list of attributes you wish to sync with the product data.

`Get product review ratings`: Include the native product review ratings recorded in BigCommerce in the data sync.

`Get local prices`: Include the price of product as defined for each currency it can be sold in.

`Include Pages`: Include CMS pages and blogs in the daily sync.

`Include Out-of-stock Products`: Include products with stock <= 0.

`Only import visible categories`: Include only categories which are visible in menu.

`Enable Realtime Updates`: Push product changes to Clerk as they are realised in BigCommerce.


### TeamBlue (DanDomain / SmartWeb / ScanNet)

#### DataSync

`Shop ID`: The ID of the shop. Usually `shop` followed by a number.

`API Username`: The username of the user created for the SOAP API.

`API Password`: The password of the user created for the SOAP API.

`Shop Language`: The Shop language. Usually an ISO code, frequently followed by a number. Eg. `DK1`, `SE`, `NO4`

`Shop Currency`: The 3 letter currency code for which to get price data.

`Custom Attributes`: A comma separated list of attributes you wish to include in the product data. 

`Blog Page ID`: The ID of your Blog Overview page. This is needed if you wish to import your blogs in order to make them searchable for the /pages endpoint.

`Include Inactive Products`: Whether to include deactivated products in sync.

`Include Out-Of-Stock Products`: Include products with 0 or negative stock numbers.