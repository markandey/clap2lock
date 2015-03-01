# clap2lock
Turn your Linux desktop into a clapper switch.

A fun little project that locks your desktop if it hears a clap.

## Dependencies
* SoX
* XScreensaver or gnome-screensaver (change the line `xscreensaver -lock` to `gnome-screensaver-command -l` if you use gnome-screensaver, or to execute any other code when you clap)

## Usage
Run the script in a terminal to test it out. You may/will need to adjust the variables at the top of the script so that it works with your hardware and ambient noise levels.

If you run it in the background on login, you can clap and walk away from your screen while it locks behind you, like the cool kids. Bonus points if you set your screensaver to be an explosion animation.
