=== Snooth Widget for Snooth.com ===
Contributors: bobby_baboon
Tags: wine, widget, snooth, snooth.com, sidebar
Requires at least: 2.8
Tested up to: 2.8.6
Stable tag: 0.1

This widget will retrieve recent reviews from Snooth.com and display them in a widgetized sidebar.

== Description ==

This plugin uses the same javascript that Snooth.com provides for their blog widgets (go to http://www.snooth.com/account/blog-widget/ when you're logged in.)

Note: there is a widget very similar to this one (http://wordpress.org/extend/plugins/snooth-widget/). I created this widget because I wanted to load the data in through javascript instead of php.

== Installation ==

1. Upload `snooth-widget.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to Appearance -> Widgets and add Snooth Widget to a sidebar. You'll need to get your User Id and hash from this page http://www.snooth.com/account/blog-widget in order to access your data on Snooth.com. You'll find it in the area where you can copy the code for their official Snooth Blog Widget. It should look like this:

	var snooth_userID = 292883;
	var snooth_hashPath = '1/4/0/';
	var snooth_syndicationContent = 'ratings';
	var snooth_wineCount = 3;

Input those variables into the widget settings are your golden!

== Frequently Asked Questions ==


== Screenshots ==


== Changelog ==

= 0.1 =
* first version