=== WPSSO Strip Schema Microdata ===
Plugin Name: WPSSO Strip Schema Microdata
Plugin Slug: wpsso-strip-schema-microdata
Text Domain: wpsso-strip-schema-microdata
Domain Path: /languages
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl.txt
Assets URI: https://surniaulula.github.io/wpsso-strip-schema-microdata/assets/
Tags: structured data, rich snippets, schema, microdata, duplicate, remove, strip, fix, json-ld, ld+json, json, markup, meta tags, schema.org
Contributors: jsmoriss
Requires PHP: 7.0
Requires At Least: 5.0
Tested Up To: 5.8
Stable Tag: 2.11.2

Remove Schema Microdata and RDFa from the webpage for better Google Rich Results using Schema JSON-LD markup.

== Description ==

<p><img class="readme-icon" src="https://surniaulula.github.io/wpsso-strip-schema-microdata/assets/icon-256x256.png"><strong>Is Google Search picking up incorrect or invalid Schema from your theme templates?</strong></p>

<p><strong>Do you need to remove old <em>Microdata</em> and <em>RDFa</em> markup from your theme templates?</strong></p>

<p><strong>Do you need to remove duplicate social or SEO meta tags from your webpage?</strong></p>

The WPSSO Strip Schema Microdata (WPSSO SSM) add-on removes old Schema Microdata and RDFa markup from the webpage. The settings page also provides for the removal of duplicate / conflicting social and SEO meta tags. WPSSO SSM filters the webpage dynamically, allowing you to activate / deactivate the add-on to easily enable / disable the removal of old Schema Midata, RDFa, and duplicate meta tags. WPSSO SSM filters are *very* fast - generally running in under 0.003 seconds!

<h3>Users Love the WPSSO SSM Add-on</h3>

&#x2605;&#x2605;&#x2605;&#x2605;&#x2605; - "This worked great to automatically remove almost 100 invalid microdata markup hentry entries from a divi/woocommerce project, bringing the error count to 0 in Google webmaster tools. The WPSSO plugin suite is the best out of many SSO solutions I've tried. Thank you!" - [marvtech](https://wordpress.org/support/topic/works-great-where-other-solutions-fail/)

&#x2605;&#x2605;&#x2605;&#x2605;&#x2605; - "Fantastic tool and necessary if you want proper schema markup on your website. Many themes come with markup that is unnecessary and conflicts. This handles that perfectly." - [krisfannin](https://wordpress.org/support/topic/necessary-plugin-for-proper-schema-markup/)

<h3>WPSSO Core Required</h3>

WPSSO Strip Schema Microdata (WPSSO SSM) is an add-on for the [WPSSO Core plugin](https://wordpress.org/plugins/wpsso/).

== Installation ==

<h3 class="top">Install and Uninstall</h3>

* [Install the WPSSO Strip Schema Microdata add-on](https://wpsso.com/docs/plugins/wpsso-strip-schema-microdata/installation/install-the-plugin/).
* [Uninstall the WPSSO Strip Schema Microdata add-on](https://wpsso.com/docs/plugins/wpsso-strip-schema-microdata/installation/uninstall-the-plugin/).

== Frequently Asked Questions ==

== Screenshots ==

01. WPSSO SSM settings page with options to remove of duplicate / conflicting meta tags, application/ld+json scripts, and/or Schema HTML attributes.

== Changelog ==

<h3 class="top">Version Numbering</h3>

Version components: `{major}.{minor}.{bugfix}[-{stage}.{level}]`

* {major} = Major structural code changes / re-writes or incompatible API changes.
* {minor} = New functionality was added or improved in a backwards-compatible manner.
* {bugfix} = Backwards-compatible bug fixes or small improvements.
* {stage}.{level} = Pre-production release: dev < a (alpha) < b (beta) < rc (release candidate).

<h3>Standard Version Repositories</h3>

* [GitHub](https://surniaulula.github.io/wpsso-strip-schema-microdata/)
* [WordPress.org](https://plugins.trac.wordpress.org/browser/wpsso-strip-schema-microdata/)

<h3>Changelog / Release Notes</h3>

**Version 2.11.2 (2021/07/10)**

* **New Features**
	* None.
* **Improvements**
	* None.
* **Bugfixes**
	* None.
* **Developer Notes**
	* Renamed the `WpssoHead->get_mt_mark()` method call to `get_mt_data()` for WPSSO Core v8.35.0.
* **Requires At Least**
	* PHP v7.0.
	* WordPress v5.0.
	* WPSSO Core v8.35.0.

**Version 2.11.1 (2021/02/25)**

* **New Features**
	* None.
* **Improvements**
	* Updated the banners and icons of WPSSO Core and its add-ons.
* **Bugfixes**
	* None.
* **Developer Notes**
	* None.
* **Requires At Least**
	* PHP v7.0.
	* WordPress v5.0.
	* WPSSO Core v8.34.0.

**Version 2.11.0 (2020/12/10)**

* **New Features**
	* None.
* **Improvements**
	* Updated the SSO &gt; Strip Microdata settings page tooltip messages.
* **Bugfixes**
	* Fixed an incorrectly named option key for the removal of Schema microdata attributes.
* **Developer Notes**
	* Fixed a missing 'add_meta_name_wpsso:mark' filter hook when stripping application/ld+json scripts is enabled.
* **Requires At Least**
	* PHP v7.0.
	* WordPress v4.5.
	* WPSSO Core v8.16.0.

**Version 2.9.0 (2020/12/04)**

* **New Features**
	* None.
* **Improvements**
	* None.
* **Bugfixes**
	* None.
* **Developer Notes**
	* Included the `$addon` argument for library class constructors.
* **Requires At Least**
	* PHP v5.6.
	* WordPress v4.5.
	* WPSSO Core v8.16.0.

**Version 2.8.1 (2020/10/17)**

* **New Features**
	* None.
* **Improvements**
	* Refactored the add-on class to extend a new WpssoAddOn abstract class.
* **Bugfixes**
	* Fixed a syntax error when appending a warning message for an invalid body tag (props @swissspidy).
	* Fixed backwards compatibility with older 'init_objects' and 'init_plugin' action arguments.
* **Developer Notes**
	* Added a new WpssoAddOn class in lib/abstracts/add-on.php.
	* Added a new SucomAddOn class in lib/abstracts/com/add-on.php.
* **Requires At Least**
	* PHP v5.6.
	* WordPress v4.4.
	* WPSSO Core v8.13.0.

== Upgrade Notice ==

= 2.11.2 =

(2021/07/10) Renamed the `WpssoHead->get_mt_mark()` method call to `get_mt_data()` for WPSSO Core v8.35.0.

= 2.11.1 =

(2021/02/25) Updated the banners and icons of WPSSO Core and its add-ons.

= 2.11.0 =

(2020/12/10) Fixed an incorrectly named option key for the removal of Schema microdata attributes.

= 2.9.0 =

(2020/12/04) Included the `$addon` argument for library class constructors.

= 2.8.1 =

(2020/10/17) Refactored the add-on class to extend a new WpssoAddOn abstract class. Fixed a syntax error when appending a warning message for an invalid body tag.

