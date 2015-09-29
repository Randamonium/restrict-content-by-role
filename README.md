# Restrict Content by Role

Restrict users with certain User Roles from accessing certain pieces of content and sub-content within the WordPress Dashboard (WP Admin).

## About

If you have a WordPress website with multiple users and several User Roles defined, and you wish to prevent certain User Roles from accessing certain pieces of content (and sub-content) within `wp-admin`, then this plugin is for you.

The plugin provides the following functionality:

- A meta box to allow you to set user role permissions for content and its sub-content
- An option to allow content, content and sub-content or just sub content to be restricted
- An option to allow a custom redirect URL (overriding default redirect URL settings)
- The ability to override parent content restrictions on sub-content (including the ability to make it public)
- An options page, with the following options:
 - Choose post types that the meta box should appear on
 - Define a login screen error message (if no custom redirect URL is set)
 - Set a custom redirect URL

## Installation

1. Download this repository and unzip it into the folder `restrict-content-by-role`
2. Upload the `restrict-content-by-role` folder to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress
4. Configure the plugin var the 'Restrict Pages by Role' options page under the WordPress 'Settings' Menu

## Changelog

**1.0.0** - *29.09.2015* - First stable release.  
