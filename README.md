# PC/QWERTZ Bindings for Karabiner-Elements

## General

These are my personally preferred keybindings on Mac OS, for use with Karabiner-Elements.  
  
I am used to a regular (if German) keyboard layout, with Control, Alt and Alt Graph keys.  
Since this is the layout that every non-Apple OS uses, I like my muscle memory just the way it is.

I'm sure there's a lot still missing, things that I haven't noticed in my usual workflow.  
Please feel very free to [open an Issue](https://github.com/leohoe/karabiner-pc-qwertz/issues/new) or a Pull Request if you come across any inconsistencies.

## How To Use

Karabiner's configuration files are located in `~/.config/karabiner`  
These keybindings rely on the following Mac-side settings:

1) Go to System Preferences -> Keyboard -> Keyboard -> Modifier Keys...
2) Switch the Control (^) and Command (⌘) keys

3) Go to System Preferences -> Keyboard -> Shortcuts -> App Shortcuts
4) Add entry: [All Applications] / "Redo" / Command-Y

## If you run into trouble with the ^ and < keys:

There are long-known and long-ignored bugs with Mac and Karabiner relating to these keys.
Specifically, external non-apple keyboards may end up swapping the key below Esc with the key to the right of Left Shift.

I have included the following Karabiner rules to help with this issue:

- "Change Caret to Less Than" (keep at the TOP of Rule list)
- "Change Less Than to Caret" (keep at the TOP of Rule list)
- "PC-Style German Alt Gr (pipe - compatible with switched < and ^ keys)" (keep BELOW the above two rules)
