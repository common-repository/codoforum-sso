=== codoforum-sso ===
Contributors: evnix 
Tags: SSO, forum,codoforum
Requires at least: 3.1
Tested up to: 5.5.1
Stable tag: 1.1.0
License: MIT License
License URI: https://github.com/evnix/wordpress-codoforum-sso/blob/master/License.txt

Integrates Codoforum forum software with WordPress using SSO(Single Sign On)

== Description ==

<a href="https://codoforum.com">Codoforum</a> is a modern forum software built for better user engagement.
wordpress-codoforum-sso plugin allows you to integrate this forum with your wordpress website.
It uses SSO, this means, users once logged into your website will be automatically logged into codoforum.

== Installation ==

Extract the zip file and just drop the contents in the wp-content/plugins/ directory of your WordPress installation and then activate the Plugin from Plugins page.

Go to Settings and Enter the Client Id and Secret. (This must be same as what you have entered in codofrum)

Note: Make Sure you have enabled the SSO plugin in Codoforum Software. 


Enter the following details: 
Assuming your wordpress website is installed at:
https://myamazingsite.com

Your settings will be like this:

SSO Get User Path:
https://myamazingsite.com/?codoforum=sso

SSO Login User Path:
https://myamazingsite.com/wp-login.php

SSO Logout User Path:
https://myamazingsite.com/wp-login.php?action=logout

SSO Register User Path:
https://myamazingsite.com/wp-login.php?action=register


For any further detailed documentation or help, refer: https://codoforum.com
