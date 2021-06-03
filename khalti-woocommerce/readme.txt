=== Payment Gateway Module for Khalti ===
Contributors: Sanjog Humagain
Tags: khalti, woocommerce, khalti payment gateway, khalti woocommerce, Payment Gateway Module for Khalti
Requires at least: 4.0
Tested up to: 5.7.2
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Payment Gateway Module for Khalti. Start accepting payments from Khalti. Check all transactions and refund payments right from the dashboard
== Description ==

= Payment Gateway Module for Khalti. Start accepting payments from Khalti. Check all transactions and refund payments right from the dashboard =

Payment Gateway Module for Khalti. Start accepting payments from Khalti. Check all transactions and refund payments right from the dashboard

Please notice that [WooCommerce](https://wordpress.org/plugins/woocommerce/) must be installed and active.

= Introduction =

Payment Gateway Module for Khalti. Start accepting payments from Khalti. Check all transactions and refund payments right from the dashboard

= Requirements =

* WordPress 4.0 or later.
* WooCommerce 2.3 or later.


= Contribute =

You can contribute to the source code in our [GitHub](https://github.com/phyverse/khalti) page.

== Installation ==

1. Go to the plugin section in your WordPress dashboard
2. Click on Add New and upload the zip file of Khalti WooCommerce plugin and upload it. You can also search khalti and install from wrodpress.
3. After installation is complete, go to the WooCommerce section and to Settings
4. Go to Checkout option where you can find Khalti among other payment gateways
5. Click on Khalti option and enter your test secret key and test public key which you can get at Keys section in your merchant account
6. Click on save changes and complete a Khalti wallet transaction to pass the test
7. If you pass the test, Go to keys section in your merchant account, you can get your Live keys their
8. Enter your live key and click save changes

== Frequently Asked Questions ==

= What is the plugin license? =

* This plugin is released under a GPL license.

= What is needed to use this plugin? =

* WordPress 4.0 or later.
* WooCommerce 2.3 or later.
* Merchant/Service Code from Khalti.

= Khalti receives payments from which countries? =

At the moment the Khalti receives payments only from Nepal.

Configure the plugin to receive payments only users who select Nepal in payment information during checkout.

= Where is the khalti payment option during checkout? =

You forgot to select the Nepal during registration at checkout. The Khalti payment option works only with Nepal.

= The request was paid and got the status of "processing" and not as "complete", that is right? =

Yes, this is absolutely right and means that the plugin is working as it should.

All payment gateway in WooCommerce must change the order status to "processing" when the payment is confirmed and should never be changed alone to "complete" because the request should go only to the status "finished" after it has been delivered.

For downloadable products to WooCommerce default setting is to allow access only when the request has the status "completed", however in WooCommerce settings tab Products you can enable the option "Grant access to download the product after payment" and thus release download when the order status is as "processing."

== Screenshots ==



