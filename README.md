## Requirements
[PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/), [KiTTY](http://kitty.9bis.com/) or [Windows Terminal](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701)

## Usage
1. Launch putty-quake-console.ahk
2. Use configured keybinding to show/hide whatever you've set in the ini file. Windows Terminal in my case.

## Configuration
+ **putty_path** : Absolute path to putty.exe (or kitty.exe)
+ **putty_args** : Putty arguments. Depreciated for Windows Terminal
+ **putty_type** : specify either "PuTTY" or "KiTTY", depending on which you're using
+ **hotkey** = key combination to show/hide putty
+ **session_mode** : unused at this time
+ **session_path** : unused at this time
+ **start_hidden** : show mintty.exe when script is started (0) or wait for hotkey (1)
+ **top_pad** : Offset from top of screen, for people with taskbars/etc up there.
+ **initial_width** : width of the console as percent of screen
+ **initial_width** : width of the console as percent of screen
+ **initial_height** : height of the console as percent of screen
+ **pinned_by_default** : set to 0 to automatically hide mintty when it loses focus
+ **animation_step** : number of pixels to shift each step of the slide animation
+ **animation_timeout** : how long (in ms) to wait between each animation_step
