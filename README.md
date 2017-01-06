# hammerspoon_ergodox
Use Hammerspoon to configure ErgoDox EZ without reloading firmware.

* "Quick and Dirty" way to get the keyboard up to speed
* Uses technology I'm used to
* Maybe not as efficient as having the keyboard doing it
* Needs to (mostly) avoid having the behavior change for the MacBook Pro keyboard
* Designed around a "42" key keyboard.
* Support simulation on the Razer Anansi keyboard

## Current layout illustration:
![Layout](/images/ergodoxez_layout.png?raw=true "ErgoDox layout illustration")


## Todo list:
* Prepare workspace area
* Add SpaceFn functions, or keep using Karabiner.
* Decide how to Cut, Copy, Paste, Undo (and Select All?) Currently SpaceFn, Numb & Func, Nav Punct all have ZXCV occupied.
* Move Karabiner SpaceFn keys from right to left hand.
	* HJKL gets moved to SDFG
	* 123 gets 0-=
	* etc.
* Configure for ErgoDox only. Turn off Hammerspoon (manually) whenever MacBook Pro keyboard is to be used
* Although MacBook Pro keyboard cannot simulate ErgoDox in any practical way, Razer could. Try that.
* Move any keys, as needed
	* Move/create modifier keys - 1-Shot (actually "sticky")
	* finish off thumb clusters (and T1-T7 on Razer)
	* add central Hyper & Backspace & Return
* Add press & hold support for Backspace --> Del, and Tab --> Esc.
* Decide: Functions on same layer as numerics? or, better yet punctuation+navigation?
* Use a separate .lua file for each layer definition
* Navigation / Punctuation functions as mode key
* Support additional keys as Navigation / Punctuation mode keys (D, J, T4)
* Numeric / Function as mode key
* Support additional keys as Numeric / Function mode keys (F, K, T2)
* Add "Edit" keys (select all, Copy, Cut, Paste, Undo) to periphery (and M2-M4 for Razer)

