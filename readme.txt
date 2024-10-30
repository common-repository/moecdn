=== Plugin Name ===
Contributors: a913844287
Donate link: https://qaq.cat
Tags: cdn, gravatar, googleapis, gfw
Requires at least: 3.0
Tested up to: 4.5
Stable tag: 1.5
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This is a CDN of static resources which is blocked by GFW in China Mainland.

== Description ==

As we know, Gravatar, GoogleAPIs and WordPress.com are blocked by GFW in China. It makes accessing WordPress sites slow, even causing Javascript errors, or breaking page styles. In order to solve this issue, some people and companies deployed Reverse Proxy CDN Servers to accelerate these resources, and we're one of them. With this plugin, you can easily replace the blocked resources into accessible ones.

= Here's our replacement rules: =

http://*.gravatar.com -> http://gravatar.moefont.com (excluding secure.gravatar.com)

//secure.gravatar.com -> //gravatar-ssl.moefont.com

//fonts.googleapis.com -> //cdn.moefont.com/fonts

//ajax.googleapis.com -> //cdn.moefont.com/ajax

//s.w.org -> cdn.moefont.com/worg

//s*.wp.com -> cdn.moefont.com/wpcom

//pixel.wp.com -> cdn.moefont.com/pixel.wpcom

The server is provided by [MoeNet Inc.](http://www.moenetwork.com) and this plugin is maintained by [Balthild Ires](https://qaq.cat/).

GitHub repo: [MoeNetwork/MoeCDN-WordPress](https://github.com/MoeNetwork/MoeCDN-WordPress)

= About informations collecting =

Your blog name, url and WP version. Just these, no more!

= Why collect you information? =

In order to provide better service.

= If you don't want us to collect my informations... =

When you first activate the plugin, we'll take tou to the settings page. Please unchecked the last checkbox and save the options. Note that before you first save the plugin options, we WILL NOT and HAVE NOT collect any informations.

== Installation ==

Just upload the plugin, activate it, and choose something you want to accelerate, then save the options. The plugin will complete replacement automatically.

== Frequently Asked Questions ==

= Why my blog becomes very slow after activeted the plugin? =

Because this plugin is only should be used when you or your readers is in China. Our servers is located in China.

== Screenshots ==

1. The setting page.

== Changelog ==

= 1.5 =
* Avoid flushing wrong output buffer.

= 1.4 =
* Support pixel.wp.com.

= 1.3 =
* Combine ssl and non-ssl domains of Gravatar.

= 1.2 =
* Fix a silly coding accident that causes the plugin can't take any effect.

= 1.1 =
* Fix a bug that can't enable the WordPress.org option

= 1.0 =
* The first version.

== Upgrade Notice ==

= 1.5 =
* Avoid flushing wrong output buffer.

= 1.4 =
* Support pixel.wp.com.

= 1.3 =
* Combine ssl and non-ssl domains of Gravatar.

= 1.2 =
* Fix a silly coding accident that causes the plugin can't take any effect.

= 1.1 =
* Fix a bug that can't enable the WordPress.org option.

= 1.0 =
The first version.
