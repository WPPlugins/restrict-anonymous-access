=== Restrict Anonymous Access ===
Contributors: cleuenberg
Donate link: 
Tags: user access, restrict content, capabilities, access-control
Requires at least: 
Tested up to: 4.8
Stable tag: 1.1
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

Adds a shortcode to restrict content from anonymous users.

== Description ==

If you simply want to have parts of your content only visible to logged-in users or to a certain user role and hidden from anonymous than just use this plugin's shortcode.

Decide if you want to show the anonymous user an informational text instead of the restriced content or simply just hide the content parts without any information.

Features:

*   text within shortcode `[member][/member]` is not visible to anonymous users
*   hide content based on user roles (subscriber, contributor, author, editor, admin)
*   restriced text can be replaced with info text box
*   info text can be customized
*	comes with a handy TinyMCE button for quick access

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/restrict-anonymous-access` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Use the shortcode `[member][/member]` in any post, page or custom post type in order to hide content from anonymous users.
4. Optional parameters are `showinfo="0"` to hide the info message, `infotext="Your custom info for anons."` and `class="my-custom-css-class"` for adding CSS class to the info box.
5. Use parameter `role="[subscriber|contributor|author|editor|admin]"`, e.g. `role="editor"` to hide content from users below editor capabilities. 

== Screenshots ==

1. Inserted the shortcode in WordPress content editor.
2. Front-end view with anonymous user, content is hidden and info message shown instead.
3. Front-end view with logged-in user, content is shown.

== Changelog ==

= 1.1 =
* Added optional user role based content restriction.

= 1.0.3 =
* Tested with WordPress 4.8.
* Fixed: Text output with paragraph tag (wpautop).

= 1.0.2 =
* Initial release for WordPress plugin directory.