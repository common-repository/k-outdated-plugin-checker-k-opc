=== k-OutDated Checker (k-OC) ===
Contributors: kanenas
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MBEQXMDLHQJPC
Tags: plugin updates, security
Requires at least: 2.8
Tested up to: 6.4.3
Requires PHP: 5.2
Stable tag: 1.3
License: GPLv2

Scans automatically, twice a day, all your installed plugins against the WordPress Plugin Directory for outdated plugins and email alert for update.

== Description ==
Scans automatically, twice a day, all of your installed plugins against the WordPress Plugin Directory for outdated plugins and email an alert for update.

= What k-OutDated Checker (k-OC) Does =

k-OC stands for k-OutDated Checker. k-OC scans automatically, twice a day, all your installed plugins against the WordPress Plugin Directory for outdated plugins and email an alert for immediate update.

= History =

k-OC got its start when I had to maintain a lot of WordPress installations which their owners didn't care much about maintenance and security.

= Included Languages =
* English (default)
* Greek (el)

If you want to help out, I have included the .pot file in /language folder. You can send them to nbran@kanenas.net

== Installation ==

After downloading and extracting the latest version of k-OC:

1. Upload the folder `k-outdated-plugin-checker-k-opc` to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. That's all!

== Changelog ==

= 1.3 25/08/2020 =

* ENHANCEMENT: Use of CURL instead of file_get_contents().
* FIX: PHP Notice:  Undefined variable: found_outdated.

= 1.2.3 08/02/2018 =

* ENHANCEMENT: Changed how the version of the plugins is checked against the WordPress Plugin Directory.
* NEW: Show next to current the new version of the plugin that needs update.
* Update the "Tested up to" in readme.txt.

= 1.2.1.1 10/10/2017 =

* NEW: Added "Minimum PHP Version Requirement" in readme.txt.
* Update the "Tested up to" in readme.txt.

= 1.2.1 17/09/2015 =

* NEW: Added the k-outdated-plugin-checker-k-opc.pot file in languages folder.
* NEW: Added translation for Greek.

= 1.2 17/09/2015 =

* ENHANCEMENT: Internationalizing the plugin (accepting translations).
* ENHANCEMENT: Implementation of WordPress "PHP Coding Standards" (https://make.wordpress.org/core/handbook/best-practices/coding-standards/php/).

= 1.1 05/05/2015 =

* FIX: Check only for plugins that exist in WordPress Plugin Directory.
* FIX: Send email alert only when at least one plugin is outdated.

= 1.0 (First Release) 04/05/2015 =

* This is the initial release of k-OC.

== Upgrade Notice ==
= 1.3 25/08/2020 =
* ENHANCEMENT: Use of CURL instead of file_get_contents().
* FIX: PHP Notice:  Undefined variable: found_outdated.

== Frequently Asked Questions ==

= I have activated the plugin. Now what? =

* You don't have to do anything else! k-OutDated Checker will scan all your plugins against the WordPress Plugin Directory (twice a day) and alert the administrator of your website (by email) if at least one plugin is outdated.

== Screenshots ==

1. This is how the email alert will look like if plugins are not up-to-date.
