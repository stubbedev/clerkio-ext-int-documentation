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

### General

`Enabled`: Whether the plugin is enabled for the currently selected sales channel.

`Public Key`: Public API Key found in my.clerk.io.

`Private Key`: Private API Key found in my.clerk.io.

### Add to Cart URL's

`Enabled`: Whether to allow adding product to cart via the submission of url params.

`domain.com/addtocart?ids=SW10001&qtys=5`

`domain.com/addtocart?ids=SW10001,SW10002&qtys=5,2`

### Live Search

`Status`: If the live search is enabled.

`Number of Suggestions`: Limit of suggestions to include in live search results.

`Number of Categories`: Limit of categories to include in live search results.

`Number of Pages`: Limit of pages to include in live search results.

`Page Type`: The type of pages to be allowed in result. All means no filter.

`Dropdown Positioning`: Where the live search will appear in relation to the attached input field.

`Content`: The content ID from my.clerk.io you wish to use to render the live search.

`Input Selector`: The CSS selector for the input field you wish to use for submitting / typing queries.

`Form Selector`: The CSS selector of the form element which wraps your Search Input.

### Search Page

`Status`: If the search page is enabled.

`Include Categories`: If category page results should be included in the search page.

`Number of Categories`: Limit to the number of category page results returned on the search page. 

`Number of Pages`: Limit to the number of CMS page results returned on the search page.

`Page Types`: The type of pages to be allowed in result. All means no filter.

`Content`: The content ID from my.clerk.io you wish to use to render the search page.

### Faceted Search

`Status`: If the facets are enabled for the search page.

`Attributes`: A comma separated list of the attributes you wish to use in facets. Only valid for attributes which have been synced to my.clerk.io.

`Facet Titles`: The name you wish to display as the title on each facet group. If not provided the attribute slug will be displayed. Eg. `price:Price,categories:Categories,brand:Brand`

`Multi Selected Attributes`: A comma separated list of the attributes you wish to allow multiple concurrent selections of within a given facet group. 

`Design`: The design ID for the design you wish to use when rendering the facets on the search page. ID must be numeric if used, is optional to use.


### Product Page

`Status`: If the product page recommendations are enabled for the current sales channel.

`Hook Location`: Choose which block to inject the product page recommendations within the theme. Options are description and cross selling block.

`Content`: A comma separated list of the contents from my.clerk.io you wish to use to on the product page.

### Category Page

`Status`: If the category page recommendations are enabled for the current sales channel.

`Content`: The content from my.clerk.io you wish to display at the top of the category page.

### Cart Page

`Status`: If the cart page recommendations are enabled for the current sales channel.

`Content`: The content from my.clerk.io you wish to display at the top of the category page.

### Exit Intent

`Status`: If the exit intent is enabled for the current sales channel.

`Content`: The content from my.clerk.io you wish to use to display the exit intent.

### PowerStep

`Status`: If you wish to display the powerstep with recommendations after an item is added to the cart.

`Type`: The type of Powerstep you wish to display. The options are Popup and Page.

`Content`: A comma separated list contents from my.clerk.io which you wish to display within the powerstep.

## Integrations
