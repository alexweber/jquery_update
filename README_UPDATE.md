This module is forked from jquery_update module http://drupal.org/project/jquery_update and implements the 1.5.2 port (http://drupal.org/node/1067290)

This module allows for jQuery 1.5.2 to be used with Drupal 6.

- Requires a core hack to includes/common.inc to fix JSON formatting.
- Allows jQuery UI 1.8.11 to be used, with https://github.com/alexweber/jquery_ui
- Updates jQuery Form Plugin to 2.69
- Has been thoroughly tested with a lot of javascript-heavy websites and works flawlessly so far with everything I've thrown at it!

See:
http://drupal.org/node/1067290
http://echodittolabs.org/blog/2010/08/drupal-6x-jquery-142-new-possibilities
http://blog.harrspy.com/using-jquery142-in-druapl-6x
http://blog.harrspy.com/fix-tabledrag-for-drupal6-with-jquery142

HOW TO APPLY THE PATCH

Copy the file jQuery-1.4_plus_JSON_Validation_Fix.patch to /includes and run it:
patch -p1 < jQuery-1.4_plus_JSON_Validation_Fix.patch

It should work with no errors
