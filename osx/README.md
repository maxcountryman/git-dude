# Setup for launchd 

These scripts, com.sickill.git-dude.plist and git-dude-launcher.sh are intended 
to automatically load git-dude upon restart.

To install simply copy com.sickill.git-dude.plist to ~/Library/LaunchAgents,
e.g. `$cp com.sickill.git-dude.plist ~/Library/LaunchAgents`. Then copy the
shell script to your .git-dude folder, e.g. `$cp git-dude-launcher.sh
~/.git-dude`.

You must now load the launcher: `$launchctl load
~/Library/LaunchAgents/com.sickill.git-dude.plist` and that's it! From now on
git-dude should be launched when you reboot.
