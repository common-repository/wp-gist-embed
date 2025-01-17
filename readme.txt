=== Plugin Name ===
Contributors: imaginarymedia
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=BNWNBPEK33UBA
Tags: gist, github, shortcode
Requires at least: 3.0.1
Tested up to: 4.8
Stable tag: 0.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin provides Gist embedding via shortcode as well as adding Gist embed buttons to the visual and text editors.

== Description ==

A simple plugin that enables a shortcode for embedding Gist code in WordPress.

The shortcode has two attributes, the Gist source URL and, optionally, the height of the embedded code window.

`[gist src="" height=""]`

The Gist `src` attribute must be the embed URL, for example: https://gist.github.com/imaginarymedia/316a29936e5e7d709665.js

The Gist `height` attribute is optional and can be any value with a valid CSS unit measure: em, %, px, vh, etc. It will apply a max-height to the gist.

The plugin also creates UI buttons for both the visual and text editors.

If you have suggestions for improvements, please contact us. via the [plugin support page](https://wordpress.org/support/plugin/wp-gist-embed) and if you find this useful, please [review the plugin](https://wordpress.org/support/view/plugin-reviews/wp-gist-embed).

Developed by [James Robinson](https://jmr.codes).

**TO DO**

* Validate the gist src URL

== Installation ==

1. Unzip the plugin and copy the `wp-gist-embed` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress


== Changelog ==

= 0.2 =
* Minor updates and compatability checks

= 0.1 =
* Initial launch