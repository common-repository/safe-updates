=== Safe Updates ===
Contributors: nfmohit
Donate link: https://www.patreon.com/nfmohit
Tags: updates, plugins, themes, safe, secure, test, compatibility, wordpress
Requires at least: 4.0
Tested up to: 5.5
Stable tag: 1.0.2
Requires PHP: 5.6
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Make sure your theme and plugins are tested before updating WordPress.

== Backstory ==

Recently, WordPress 5.3 came out which included quite a good number of outstanding improvements. I was excited and updated few of my installations only to find out that some of them ran into fatal errors.  Upon investigation, I discovered some plugins which were conflicting simply because they were not tested and incompatible with the update. I wondered, only if there was a plugin which could warn me about plugins or themes that might have not been tested, just before I tried to run updates.

Thus, I decided to build ***Safe Updates***, a small nifty WordPress plugin which lets you know if there are any plugin or theme on your installation that might have not been tested with the target WordPress version before you try to update.

### Use Cases
The use case of this plugin is very straight-forward. It just gives you an idea about untested plugins or themes that may be untested with the updated WordPress versions and helps you be cautious for conflicts and errors.

### Core Features
The core features of this plugin include:

1. Display active plugin(s) that might have not been tested with the target WordPress version.
2. Show if the current theme has not been tested with the target WordPress version.

### Notes
Some notes to consider while using this plugin:

1. The interface only shows up when a core update is available.
2. A plugin/theme author might choose **not to** disclose the WordPress version up to which it might have been tested up to. In such a case, a plugin/theme might still be incompatible with the targetted update, but ***Safe Updates*** might not show it if its author didn't disclose its tested up to version.

### Installation
Installation of the **Safe Updates** plugin is very simple. Follow along with the installation procedure in the dedicated [**Installation** tab](#installation).

### Usage
1. [Install](#installation) and activate the plugin
2. Go to *WP Admin → Dashboard → Updates*.
3. If a WordPress update is available, this plugin will add an interface above the **"Update"** button which shows if any of your theme or plugins have not been tested with the target WordPress version.

### Support
If the above usage steps don't answer your question(s), if you want to report an issue or if something is not working as expected, please create a topic in the [Support Forum](https://wordpress.org/support/plugin/safe-updates/) or [create an issue on GitHub](https://github.com/nfmohit/safe-updates/issues/new/choose).

### Contribute
If you want to contribute to the plugin by reporting issues, implementing new features and so on, [here's its development repository on Github](https://github.com/nfmohit/safe-updates).

### Credits
The interface design of this plugin is heavily inspired by the [Shared UI](https://github.com/wpmudev/shared-ui) from [WPMU DEV](https://premium.wpmudev.org/) (Yes, you got that right! I currently work there, we're a wonderful company and [we're hiring](https://incsub.com/careers/)!)

### Sponsor
You can sponsor this project and support my open-source development by [becoming a Patron](https://www.patreon.com/nfmohit)!

== Installation ==

### Install
#### Automatic Installation
1. Go to your *WordPress Dashboard→Plugins→Add New*.
2. Search for **"Safe Updates"**.
3. Click on **"Install"**.
4. Once installed, click on **"Activate"**.

#### Manual Installation
1. Download the plugin *.zip* folder using the download button on this page.
2. Go to your *WordPress Dashboard→Plugins→Add New*.
3. Click on the **"Upload Plugin"** button.
4. Upload the downloaded *.zip* file.
5. Activate it.

### Usage
1. Install and activate the plugin
2. Go to *WP Admin → Dashboard → Updates*.
3. If a WordPress update is available, this plugin will add an interface above the **"Update"** button which shows if any of your theme or plugins have not been tested with the target WordPress version.

== Frequently Asked Questions ==

= Is this plugin free? =

Definitely! Safe Updates is free and always will be.

== Screenshots ==

1. The Safe Updates interface.

== Changelog ==

= 1.0.2 =
* Fixed issue where notices were showing up if the component was tested further than the target version

= 1.0.1 =
* Tested up-to WordPress 5.4
* Fixed issue which was causing the interface to show up even when an update was not available
* Updated developer tools

= 1.0 =
* Initial Release

== Upgrade Notice ==

= 1.0.2 =
* Fixed issue where notices were showing up if the component was tested further than the target version

= 1.0.1 =
* Tested up-to WordPress 5.4
* Fixed issue which was causing the interface to show up even when an update was not available

= 1.0 =
* Initial Release
