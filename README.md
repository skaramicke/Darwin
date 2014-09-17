Darwin
======

Scripts I use on my OS X machines

# open_xcworkspace
I use this script with Sourcetree as a custom action.

1. Create a custom action and bind a keystroke to it.
2. Provide the path to the script (i.e. /usr/local/bin/open_xcworkspace)
4. Type $REPO in the Paramters box.

When you use your keystroke, the script will look for an .xcworkspace file and open it. If it can't find one, it instead looks for a .xcodeproj file. This is to support Cocoapod and normal Xcode projects nicely and automagically.