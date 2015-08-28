=== Clear Cache for Me ===
Contributors: webheadllc
Donate link: http://webheadcoder.com/donate-clear-cache-for-me
Tags: wpengine, widget, menu, cache, clear, purge, w3t, W3 Total Cache, WP Super Cache, WP Fastest Cache, refresh, update, empty, performance, optimization, contact form 7
Requires at least: 3.8
Tested up to: 4.3
Stable tag: 0.7
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Purges all cache on WPEngine, W3 Total Cache, WP Super Cache, WP Fastest Cache when updating widgets, menus, settings.

== Description ==

**NOTE:  If you do not use the W3 Total Cache or WP Super Cache plugins, WP Fastest Cache, or do not host your website on WPEngine, this plugin will do nothing for you.**

W3 Total Cache and WP Super Cache are great caching plugins, but they do not know when a widget is updated.  WPEngine is the best place to host your WordPress installation, but their caching system is no smarter when it comes to updating widgets and menus.  I created this plugin because my website did not see any changes when saving widgets or menus using these caching systems.  Clear Cache For Me will purge ALL your cache each time you do a save without having to press an additional button.  It may be overkill, which may be why it's not built in, but some people need simplicity.

Works with the following caching systems:

* W3 Total Cache
* WP Super Cache
* WP Fastest Cache
* WPEngine hosting

Clears all cache for following actions:

* When Widgets are saved
* When Customizer is saved
* When Menus are saved
* When Settings from a settings page is saved.
* When a Contact Form 7 form is saved.

There is a convenient clear cache button on the dashboard for users with the right capability.  Admins (users with the 'manage_options' capability) can set which capability a user needs to view the button.  If you are using this button often, please consider submitting a request to have this plugin do your button-pushing for you.  This plugin is meant to work behind the scenes to make your life easier and less frustrating.


== Changelog ==

= 0.7 =
Added clear cache for settings pages.
Added clear cache for Contact Form 7 form saving.
Updated description and added donation link on plugin page only.

= 0.6.2 =
minor updates to css class names

= 0.6.1 =
Updated German translation (thanks to Ov3rfly!).
Updated admin HTML and styles (thanks to Ov3rfly!).

= 0.6 =
Fixed cache not clearing when widgets are re-ordered or deleted (thanks to Ov3rfly!).  
Added optional instructions to be shown above the button (thanks to Ov3rfly!).  
Added to and updated German translations (thanks to Ov3rfly!).  
Added more security checks. (thanks to Ov3rfly!).  
Added customize theme detection.  Clears cache when customizing theme.  
Reorganized code a bit.

= 0.5 =
Added German language translation (thanks to Ov3rfly)
Added hooks for 3rd party code.

= 0.4 =
Bug fixed: Fixed cache not clearing when updating nav menu. (thanks to Ov3rfly for catching this and supplying the fix)

= 0.3 =
Added clear caching for menus
Added clear cache button to dashboard
Added option to set what capability is needed to view the clear cache button for admins.

= 0.2 =
Removed garbage at the end of the plugin url.

= 0.1 =
Initial release.
