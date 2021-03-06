[Plugin on
WordPress.org](http://wordpress.org/plugins/gravity-forms-first-data-global-gateway-addon)

_________________________

**This plugin no longer works with the latest WordPress or Gravity Forms, and has been dis-continued.** ~~It is currently being updated (see develop branch).~~

_________________________________

# Gravity Forms + First Data Global Gateway e4

**Gravity Forms + First Data Global Gateway e4** is a plugin and addon for
Gravity Forms that will allow you to process products using the
[First Data Global Gateway e4](https://www.firstdata.com/en_us/products/merchants/ecommerce/online-payment-processing.html) service.

You can install this plugin and get more information from [WordPress.org](http://wordpress.org/plugins/gravity-forms-first-data-global-gateway-addon).

## How to Debug on Form Submit

To get debug information when a form is submitted, just use
(in `wp-config.php`):

	define('GFFD_DEBUG_FORM_SUBMIT', true);

This will stop Gravity Forms from submitting the entry and show information about the request.

# Changelog

# 1.1

- Fixed issues where various PHP Warning notices were being thrown
- Various bug fixes
- Reference and Customer Reference Numbers are now recorded for cross-referencing

# 1.0.2

- First release to WordPress.org
