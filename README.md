YAMJ Plugin for unRAID v5
=========================

Hello,

I am proud to present the YAMJ plugin for unRAID v5.

This plugin will help you view existing YAMJ online and local versions, add scheduled YAMJ scan to the server and allow for manual YAMJ scan.
In addition you can download latest version of YAMJ (stable or snapshot).

This plugin will not install and configure YAMJ's settings themselves - it is not a GUI for YAMJ.

To install:
-----------
1. Initial Download of plugin at https://raw.github.com/theone11/yamj_plugin/master/yamj.plg (future updates can be done via the WEBUI)
2. Copy plugin to /boot/config/plugins on your flash drive.
3. Reboot unRAID server or Install from command line:
   - installplg /boot/config/plugins/yamj.plg
   - /etc/rc.d/rc.yamj boot
4. Go to plugin WEGUI and change initial settings

The WEBUI is divided into 3 parts:
----------------------------------
1. Status Summary - Shows status of local and online YAMJ versions and plugin version.
2. Actions - Shows all possible actions available to the user depending on the status of the user's server.
   - Start YAMJ.
   - Download latest YAMJ versions.
   - Update plugin.
3. Configuration - Change settings of the plugin and YAMJ.

Configuration Notes:
--------------------
1. Mount and Startup options - Change what happens during array mount.
2. YAMJ settings - Change location of existing YAMJ installation and download folder.
3. Scheduled YAMJ Scan settings - Change script and scan schedule times.

Please comment on any problems encountered and any enhancements or missing features, that you would like added.
(Here if possible: https://github.com/theone11/yamj_plugin/issues)

Enjoy the plugin  :)

