Maintenance Mode
================

* Contributors: Lukas Juhas
* Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2XPA4CKT836FJ


## Description

Very simple maintenance plugin for your website using Wordpress's wp_die() function, there is settings page under "Settings" where you can enable maintenance mode or set your custom message. There is also a default message. When activated and logged as admin, you can see website as usual, just rest of the users / visitors can see maintenance mode. You can see the maintenance mode as admin using preview button or simply opening your website in private mode. There is also indicator in admin bar that changes colour to red when maintenance mode is enabled.

Bugs and pull requests are welcomed.

## Wordpress Info

* Requires at least: 3.8.0
* Tested up to: 4.3

## Installation

1. Upload `lj-maintenance-mode` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Navigate to Settings -> Maintenance Mode  or simply click on Admin Bar indicator for settings to enable maintenance mode.

## FAQ
1. Is this plugin really ad free ?<br>
Yes.

2. Can I change colours?<br>
Not by default. Unless you are developer and you "inject" your own styles in to the wp_die() page.

3. Plugin doesn't seem to work. What should I do ?<br>
First, if you are using Cache plugin such as WP Super Cache or W3 Total Cache, flush all your cache. Secondly, disable all other plugins and try enabling just Maintenance Mode and see if problem persist. This should solve most common problems. If not, don't hesitate to contact me via Support button from Settings page


## Changelog

### 1.2.1
* Bug fixes
* Deprecated clear cache functionality as it caused errors to some users. From now on, plugin shows simple reminder to flush cache after enabling or disabling Maintenance Mode.


### 1.2
* Improvement: Improved Multisite Support
* Improvement: Show default maintenance message in the settings
* Improvement: Uninstalling will now clean up database
* Improvement: Added support link to the settings page
* Improvement: Translatable strings
* Improvement: Changed default site title while MM is active
* Improvement: Added preview button
* Improvement: Added support button
* Improvement: Added support for WP Super Cache
* Improvement: Added support for W3 Total Cache
* Bug Fixes

### 1.1.1
* Bug Fixes

### 1.1
* Added Indicator to Admin menu bar
* Added Settings button on plugins page
* Added Default maintenance mode message.
* Bug Fixes

### 1.0
* First release
