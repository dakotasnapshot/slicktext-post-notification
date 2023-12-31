# slicktext-post-notification
SlickText Post Notification is a WordPress plugin that sends a post link to the SlickText API every time a post is published on your WordPress site. It utilizes HTTP Basic Authorization with public and private keys for secure communication with the SlickText API. If you do not know your textword ID plase use plugin SlickText API Explorer to discover the ID for your textword.


=== SlickText Post Notification ===
Contributors: dakotasnapshot
Donate link: https://www.buymeacoffee.com/dakota
Tags: slicktext, post notification, sms, notification
Requires at least: 4.0
Tested up to: 6.4.2
Stable tag: 2.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

SlickText Post Notification is a WordPress plugin that sends a post link to the SlickText API every time a post is published on your WordPress site. It utilizes HTTP Basic Authorization with public and private keys for secure communication with the SlickText API.

= Features =

- Sends post links to SlickText API on post publish.
- Uses HTTP Basic Authorization for API authentication.
- Securely stores SlickText API settings.

== Installation ==

1. Upload the `slicktext-post-notification` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Navigate to 'SlickText Settings' in the admin menu to configure your SlickText API settings.

== Configuration ==

1. After activating the plugin, go to 'SlickText Settings' in the admin menu.
2. Enter your SlickText Textword, Public API Key, Private API Key, and the default message.
3. Save the settings.

== Usage ==

- The plugin will automatically send a post link to the SlickText API every time a post is published on your WordPress site.

== Frequently Asked Questions ==

= Does this plugin require a SlickText account? =

Yes, you need an active SlickText account with API access to use this plugin.

= Can I customize the message sent to SlickText? =

Yes, you can customize the default message in the plugin settings.

== Changelog ==

= 2.0 =
* Updated to use "SEND" action in the SlickText API request.
* Removed the "number" parameter as it is not required.

= 1.0 =
* Initial release.

== Upgrade Notice ==

= 2.0 =
* This version updates the plugin to use the "SEND" action in the SlickText API request. Remove the "number" parameter from your API request.

== Screenshots ==
- No screenshots available.

== Arbitrary section ==

* Tested up to: 6.4.2

== Support ==

For support or feature requests, please contact dakotacole@gmail.com.

== Donate ==

If you find this plugin helpful, consider supporting the developer by making a donation at https://www.buymeacoffee.com/dakota.
