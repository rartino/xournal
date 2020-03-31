=================================================================
This is forked version of Xournal adapted for doing presentations
=================================================================

Forked from Daniel German's repo to produe a version of Xournal better adapted for doing presentations showing pdf files where one dynamically draws on them. (Preferably with some hardware pen solution.)

The official repository of Xournal is hosted at: http://xournal.sourceforge.net

This fork contains the following changes:

- A presentation view mode has been added that combines:
  
  * Fullscreen mode
  * Single page view
  * Resizes canvas to max that fits both height and width
  * Upon activating presentation mode, all pages are pre-rendered. This makes drawing stutter for a while, but once done, all wait time when changing pages is eliminated.

- A number of keyboard shortcuts have been added for changing colors and other featurs useful for presentations running in fullscreen:

  * Change colors with alt+<number>
  * Change brush size with ctrl+<number>
  * Create a new empty page as the next page in the pdf with alt+n
  * Delete the curent page with alt+d
  * Clear all drawings with alt+c (delete layer)
  * Open the set zoom dialog with alt+z. With this shortcut one can use zoom-to-heigh and zoom-to-width while fullscreen mode is activated, so the correct zoom for fullscreen is used.
    
- Change of the dated-looking pen cursor into a normal pointer arrow.

Installation on Ubuntu
----------------------

* sudo apt build-dep xournal
* ./autogen.sh
* make

Resulting binary in: `src/xournal`





