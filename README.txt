Exchange Security Bypass Xposed Mode for Nexus 4 (Android 4.3)

This mod should be used along with Xposed ( http://forum.xda-developers.com/showthread.php?t=1574401 ).

This mod will bypass the Email app from becoming device admin for your phone and prevent it from setting up any security restrictions on your device including pin/password/remote wipe, etc.

Instructions for users
- Remove your existing email account from phone and reboot
- Install Xposed installer (from link above)
- Install this mod (Download apk from here: https://github.com/shantanugoel/ExchangeBypassXposed/blob/master/ExchangeBypassForXposed/ExchangeBypassForXposed.apk )
- Enable the mod in xposed (Preferences for other devices/versions coming Soon)
- Reboot
- Add your email account again. This time, it will ask you that the email
  might require security restrictions, say yes to it but it will never actually set the restrictions.
- Done. :)

Instructions for developers
- Read the xda link at the top of this readme and go through basics of xposed development
- Install xposed as an android sdk addon on your system
- Clone this git repo
- Import in Android Studio
- Make changes
- Build :)

Credits:
- rovo89 from xda (for creating xposed)
- mpcjanssen from xda (for original mod)

Please visit http://tech.shantanugoel.com/ for any queries and feedback

Changelog:
1.0 14-Oct-13
Initial version. Working for Nexus 4 Android 4.3
