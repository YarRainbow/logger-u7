=== WP Logger ===
Contributors: hokku,casepress
Tags: logger,wp logger,log,debug,data logging,data logger,wp data logger,develop
Donate link: https://www.paypal.me/hokku
Requires at least: 3.5
Tested up to: 5.5
Requires PHP: 5.6
Stable tag: 2.0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Logging vars and event for debug site and apps.

== Description ==
Logger vars and event for debug site and apps.

0. Insert the hook do_action( 'logger', $data ); in your code
1. Go to Tools > Logger 

= Available additional hooks: =
* wp_logger_button_panel
* wp_logger_inline_css
* wp_logger_inline_js
* wp_data_logger_print_data

= Available constants: =
* WPDL_DISPLAY_LIMIT

[GitHub](https://github.com/hokoo/logger-u7)

== Installation ==
0. Upload plugin to the `/wp-content/plugins/` directory
1. Activate the plugin through the \'Plugins\' menu in WordPress
2. Insert the hook do_action( \'logger\', $data ); in your code
3. Go to Tools > Logger 

== Screenshots ==
1. Logger page

== Changelog ==
= 2.0.2 =
* Suppress DB errors while the data insert

= 2.0.1 =
* bug fixed

= 2.0 =
* Logged data was moved to custom table in DB
* WPDL_DISPLAY_LIMIT
* Hidding/showing rows

= 1.4 =
* Added types of data

= 1.2 =
* Init commit

== Upgrade Notice ==
= 2.0 =
During update will be lost all logged data. Please, make sure this won\'t hurt you