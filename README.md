# INFORMATION #

Activate Users from Mod CP (1.2) for MyBB 1.8
Created by: Starpaul20
Copyright: ©2010
License: GPL

Allows Moderators and Administrators to activate or delete user accounts that are Awaiting Activation from the Moderator CP.

This plugin offers full language support.

The 'oldrelease' branch contains the 1.6 version of the plugin.


# INSTALLATION #

1. Upload all files above, keeping the file structure intact.
2. Go to Configuration > Plugins
3. Click "Activate"
4. Enjoy!


# UPDATING #

If you're updating from any previous version, you must first deactivate the plugin, upload all new files and reactivate.

# Changelogs

1.2 (July 27th, 2017)
- Optimized PNG image
- Show N/A for IP address if no regip exists
- Sanitized username
- Removed PHP closing tags
- Use THIS_SCRIPT for template caching
- Updated the activation code
- Send activation email after activating user
- Added confirmation notice when clicking the activate/delete users
- Indented templates

1.1 (April 14th, 2015)
- Added PostgreSQL and SQLite support
- Changed $mybb->input to $mybb->get_input
- Update awaitingactivation cache when activating/deleting users
- Updated query
- General cleanup of stuff

1.0 (September 13th, 2014)
- Updated plugin to work with MyBB 1.8

## Version number reset for MyBB 1.8 ##

2.1 (September 14th, 2011)
- Dropped MyBB 1.4 support
- Fixed minor template design issue
- Optimization and general plugin updating

2.0.1 (September 25th, 2010)
- Bug: Fixed permission issue causing activation section to not display to Super Moderators

2.0 (August 5th, 2010)
- Updated plugin to work with MyBB 1.6

1.0.1 (July 5th, 2010)
- Bug: Fixed bug with Multi-page

1.0 (July 2nd, 2010)
- Initial release
