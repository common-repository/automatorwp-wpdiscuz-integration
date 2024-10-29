=== AutomatorWP - wpDiscuz integration ===
Contributors: automatorwp, rubengc, eneribs
Tags: wpdiscuz, automatorwp, automator, automation, comment, vote, live
Requires at least: 4.4
Tested up to: 5.9
Stable tag: 1.0.5
License: GNU AGPLv3
License URI: http://www.gnu.org/licenses/agpl-3.0.html

Connect AutomatorWP with wpDiscuz

== Description ==

> **Important:** Now all free integrations are included in [AutomatorWP](https://wordpress.org/plugins/automatorwp/ "AutomatorWP") so you no longer need to install them one by one!
>
> We will continue working to improve AutomatorWP and make it easier, faster and more accessible to everyone.

[wpDiscuz](https://wordpress.org/plugins/wpdiscuz/ "wpDiscuz") is an ajax realtime comment system with custom comment form and fields designed to supercharge WordPress native comments.

This plugin automatically connects [AutomatorWP](https://wordpress.org/plugins/automatorwp/ "AutomatorWP") with wpDiscuz adding new triggers that you can use to connect with other plugins and automate workflows letting you save time and get focused on your most important work.

= Triggers =

* User votes up/down a comment.
* User gets a vote up/down on a comment.

**Important:** For triggers related to commenting, wpDiscuz uses the WordPress comments which means that AutomatorWP built-in events for comments will work for wpDiscuz comments too.

= What is AutomatorWP? =

AutomatorWP is an automator plugin that lets you connect your WordPress plugins together and add automation to unlimited workflows.

You can automate anything including sales, marketing, administrative tasks, learning and any other kind of processes you want letting you save time and get focused on your most important work.

= More integrations =

WordPress.org is home to some amazing integrations for AutomatorWP, including:

* [wpForo](https://wordpress.org/plugins/automatorwp-wpforo-integration/)
* [Tutor LMS](https://wordpress.org/plugins/automatorwp-tutor-integration/)
* [H5P](https://wordpress.org/plugins/automatorwp-h5p-integration/)
* [WP Fusion](https://wordpress.org/plugins/automatorwp-wp-fusion-integration/)
* [MemberPress](https://wordpress.org/plugins/automatorwp-memberpress-integration/)

== Installation ==

= From WordPress backend =

1. Navigate to Plugins -> Add new.
2. Click the button "Upload Plugin" next to "Add plugins" title.
3. Upload the downloaded zip file and activate it.

= Direct upload =

1. Upload the downloaded zip file into your `wp-content/plugins/` folder.
2. Unzip the uploaded zip file.
3. Navigate to Plugins menu on your WordPress admin area.
4. Activate this plugin.

== Frequently Asked Questions ==

= The triggers are not getting triggered =

wpDiscuz includes an option to enable/disable the use of WordPress ajax.

Be sure you have checked the option wpDiscuz > Settings > General Settings > "Use WordPress native AJAX functions" to get triggers working correctly.

== Screenshots ==

== Changelog ==

= 1.0.5 =

* **Improvements**
* Prevent use of undefined constant

= 1.0.4 =

* **New Features**
* Added new tags to the wpDiscuz triggers.

= 1.0.3 =

* **Bug Fixes**
* Fixed undefined variable.

= 1.0.2 =

* **Improvements**
* Improved the vote listener.

= 1.0.1 =

* **Bug Fixes**
* Fixed undefined function call.

= 1.0.0 =

* Initial release.
