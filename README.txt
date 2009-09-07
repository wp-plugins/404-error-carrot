=== Plugin Name ===
Contributors: 2046
Donate link: http://404-carrot.org
Tags: 404, error, vegetables,
Requires at least: 2.0.2
Tested up to: 2.8
Stable tag: 4.3

Here is a short description of the plugin.  This should be no more than 150 chars.  No markup here.

== Description ==

Custom 404 error carrot page is an Internet art project.
It puts an image of bunch carrots on your 404 error page which is only seen when someone reaches nonexistent page anyway. 
The goal of this project is light weight advertisement for vegetables ;), 
more about this project on http://404-carrot.org.
Even though the plug-in is easily installable you have to touch your template folder as well.

== Installation ==

This section describes how to install the plugin and get it working.

* Download  it from http://404-carrot.org.
* Once you activate the plug-in go to your current template folder (wp-content/themes/your-template/) and put the following piece of code into the 404.php file.
<?php if (function_exists(’funct_404_error_carrot’)) { funct_404_error_carrot() ; } ?>
If it doesn’t exists then create it your self. The best put in to the 404.php file also the header, sidebar, and footer as well. Then the page will looks the same as your regular page but the information of nonexistent content with a carrot on the top :)

== Frequently Asked Questions ==

If you have any questions go to http://404-carrot.org/wordpress-plugin

== Screenshots ==

http://404-carrot.org/screenshot-gallery

== Changelog ==

= 0.9 =
* inicialization.

