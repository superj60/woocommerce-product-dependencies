=== WooCommerce Product Dependencies ===

Contributors: franticpsyx, SomewhereWarm
Tags: woocommerce, products, dependencies, prerequisite, access, restrict, ownership, purchase, together
Requires at least: 3.8
Tested up to: 4.8
Stable tag: 1.1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Restrict access to any WooCommerce product, depending on the ownership and/or purchase of other, prerequisite items.

== Description ==

Restrict access to any WooCommerce product, depending on the ownership and/or purchase of other, prerequisite items.

Features:

* **Conditional product access** based on the ownership and/or purchase of prerequisite items.
* Streamlined admin interface – prerequisite products are entered in a dedicated Dependencies tab.
* Support for multiple product dependencies.
* Support for "ownership", "purchase" and "ownership/purchase" dependency types.

Developers can checkout and contribute to the source code on the plugin's [GitHub Repository](https://github.com/franticpsyx/woocommerce-product-dependencies/).

**Important**: Requires WooCommerce 2.2+. WooCommerce 2.4+ or higher recommended.


== Installation ==

1. Download the plugin.
2. Go to your WordPress Dashboard and then click **Plugins > Add New**.
3. Click **Upload Plugin** at the top.
4. Click **Choose File** and select the .zip file you downloaded in **Step 1**.
5. Click **Install Now** and **Activate** the plugin.


== Documentation ==

The integration of Product Dependencies with WooCommerce is as straightforward and simple as possible. When a product is added to the cart, it is checked for existing dependencies. If the ownership and/or purchase criteria are not met, the product will not be added to the cart and a notification will be displayed.

= Creating Dependencies =

Product dependencies can be created by simply clicking on the new **Dependencies** tab, found under **Product Data**, and adding products to the **Product Dependencies** field.

After saving, access to your product will be enabled conditionally, based on the ownership and/or purchase of ANY item that has been added to the Product Dependencies field.

= Ownership vs Purchase =

The plugin allows you to select between 3 different dependency types:

* **Ownership**: Access is granted only to customers that already own any of the items added to the Product Dependencies field.
* **Purchase**: The product can be purchased only in combination with any of the items added to the Product Dependencies field. Ownership is not taken into account.
* **Either**: Access is granted with ownership or purchase of any item added to the Product Dependencies field.


== Screenshots ==

1. Product dependencies can be created by simply clicking on the new **Dependencies** tab, found under **Product Data**, and adding products to the **Product Dependencies** field.
2. If the ownership and/or purchase criteria are not met, products with dependencies cannot be added to the cart and a notification will be displayed, such as this one.

== Changelog ==

= 1.1.2 =
* Fix - Variable product dependencies not validated correctly in the cart.

= 1.1.1 =
* Fix - Dependencies not working under WC < 3.0 after last update. Fixed!

= 1.1.0 =
* Refactored and cleaned up plugin.
* Fix - Added support for WooCommerce 3.0.
* Tweak - Add links to dependent products in notices.

= 1.0.7 =
* Fix - Stray "or" in dependent products list when only one dependency is present.
* Localization - Added Brazilian Portuguese translation.

= 1.0.6 =
* Fix - PHP array_values warning.

= 1.0.5 =
* Fix - WC 2.3 support.

= 1.0.4 =
* Localization - Added Brazilian translation (robertopc)

= 1.0.3 =
* Fix - Saving bug

= 1.0.2 =
* Fix - WC detection fix

= 1.0.1 =
* Tweak - Styling support for WooCommerce v2 write-panels

= 1.0 =
* Initial release

== Upgrade Notice ==

= 1.1.2 =
Variable product dependencies are now validated correctly in the cart.