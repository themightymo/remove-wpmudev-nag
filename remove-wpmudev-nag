<?php
/**
* Plugin Name: Remove WPMUDEV Nag
* Plugin URI: http://mypluginuri.com/
* Description: A brief description about your plugin.
* Version: 1.0 or whatever version of the plugin (pretty self explanatory)
* Author: Plugin Author's Name
* Author URI: Author's website
* License: A "Slug" license name e.g. GPL12
*/

// Remove WPMUDEV's annoying dashboard nag
add_action('admin_head', 'remove_wpmudev_shit');
function remove_wpmudev_shit() {
  echo '<style>
	div.wpmudev-new, div.wpmudev-message, div.wpdv-msg, #wpmu-install-dashboard {
		display: none !important;
	}
	</style>';
}
