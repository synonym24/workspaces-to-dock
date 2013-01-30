workspaces-to-dock Releases:
========================
In this branch you will find current and past non-debug releases of workspaces-to-dock extension.


Installation:
------------
The easiest way to install Workspaces-to-Dock is from https://extensions.gnome.org/extension/427/workspaces-to-dock/ using your browser.

If you would rather install it manually, please download the appropriate zip file from this branch. That zip file contains the same non-debug version of the extension as https://extensions.gnome.org and can be installed using Gnome Tweak tool.

	Gnome Tweak tool --> Shell Extensions --> Install from zip file --> choose the zip file.

If you're checking out code from the master branch (downloaded as zip or tar.gz), you will need to rename the extracted folder to workspaces-to-dock@passingthru67.gmail.com and manually copy it into your ~/.local/share/gnome-shell/extensions/ folder. I have included the gschemas.compiled file (compiled xml schema for gsettings) in the master branch so you won't have to compile it manually. 

	$ cp workspaces-to-dock@passingthru67@gmail.com ~/.local/share/gnome-shell/extensions/

Configure using `gnome-shell-extension-prefs`. No shell restarts required.


**Please see the readme file in the master branch (https://github.com/passingthru67/workspaces-to-dock) for release features and settings.**



