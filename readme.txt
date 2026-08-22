=== Double Opt-In Helper ===
Contributors: rocklobsterinc, takayukister
Tags: privacy, consent, opt-in
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html
Donate link: https://contactform7.com/donate/
Stable tag: trunk
Requires at least: 7.1
Requires PHP: 8.3
Tested up to: 6.5

Double Opt-In Helper is a WordPress plugin that helps developers implement the double opt-in process in their plugins.

== Description ==

Double Opt-In Helper is a WordPress plugin that helps developers implement the double opt-in process in their plugins.

= What is double opt-in? =

Double opt-in is a procedure used to confirm users' consent. Today, service providers are often required to obtain clear consent from users before collecting or using their personal data, and in some situations, asking the user to tick an "I agree" checkbox is not sufficient. Double opt-in serves a useful role in such situations.

A typical double opt-in process starts by the service provider sending an email message to the user. The message includes a URL link to the provider's website and asks the user to click the link if they agree on conditions. Usually, the URL includes some sort of unique random code that works as a token to confirm the user's consent.

By doing this, the service provider can confirm that the real user (not a bot or someone else) has consented, because only the user should be able to access messages to their email address.

For details on how to use it, see [Double Opt-In Helper](https://contactform7.com/doi-helper/) on contactform7.com.

== Installation ==

1. Upload the entire `doi-helper` folder to the `/wp-content/plugins/` directory.
1. Activate the plugin through the **Plugins** screen (**Plugins > Installed Plugins**).

== Frequently Asked Questions ==

== Screenshots ==

== Changelog ==

= 1.1 =

* Bumps up the minimum required WordPress version to 7.1.
* Bumps up the minimum required PHP version to 8.3.
* Changes the author name to Rock Lobster Inc. (a Japan-based company that the original author, Takayuki Miyoshi, owns)
* Improves the post type capabilities definition.

= 1.0 =

* Bumps up the minimum required WordPress version to 6.1.
* Bumps up the minimum required PHP version to 7.4.

== Upgrade Notice ==
