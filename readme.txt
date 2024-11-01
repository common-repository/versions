=== Plugin Name ===
Contributors: iseqqavoq
Tags: versions, speed, cache, versionnumber
Requires at least: 4.4.2
Tested up to: 4.7.3
Stable tag: 1.0.3
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Plugin for generating version numbers on external resources automatically.

== Description ==

Versions takes care of your cache issues of stylesheets and javascripts.

A reoccuring issue when developing sites and making changes to css- and javascript-files is that they get cached and prevents visitors from experiencing what they're supposed to experience.

Versions takes care of this reoccurring headache.
This is done by adding version numbers to your resources based on the timestamp of when the resource was most recently modified.

Users with the ability to manage options are given the choices of switching between two different ways of filtering for resources. The two different functionalities are more closely explained in the FAQ.

Feel free to make pull requests for improvement on Github at https://github.com/iseqqavoq/versions

== Installation ==

1. Upload the `versions` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Check the Versions settings page in order to switch the plugin on.

== Frequently Asked Questions ==

== Screenshots ==

== Upgrade Notice ==

= 1.0.3 = 
* Tested from 4.4.8 -> 4.7.3

= 1.0.2 =
* Tested from WP 4.0 -> 4.4.2

= 1.0.1 =
*Fixed a bug that caused the version numbers not be to be added to scripts loaded with wp_footer()
*Added plugin description
*Translation fixes

= 1.0 =
