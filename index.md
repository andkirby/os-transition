---
layout: page
title: Adopt Windows behaviour on MacOS (tested on Monterey)
---

This guide can help to make MacOS behave like Windows (but not completely).



| Command | Windows | MacOS |
| --- | -------- | --- |
| Remap on Windows keyboard | <kbd>Ctrl</kbd> <kbd>Win</kbd> <kbd>Alt</kbd> | <kbd>⌃ Control</kbd> <kbd>⌥ Option</kbd>  <kbd>⌘ Command</kbd> |
| Cut/Copy/Paste | <kbd>Ctrl</kbd> + <kbd>x</kbd> / <kbd>c</kbd> / <kbd>v</kbd> | <kbd>⌘ Command</kbd> + <kbd>x</kbd> / <kbd>c</kbd> / <kbd>v</kbd> |
| Paste clipboard from history | <kbd>Win</kbd> + <kbd>v</kbd> | There is **no** the same ability on MacOS. <br> [CopyClip app](https://apps.apple.com/ua/app/copyclip-clipboard-history/id595191960) (or similar) may help to have access to the clipboard history. |
| Delete a file (move to bin) | <kbd>Delete</kbd> | <kbd>⌘ Command</kbd> + <kbd>Backspace</kbd><br>(because <kbd>Backspace</kbd> [is <kbd>Delete</kbd> on mac's keyboard](https://apple.stackexchange.com/a/91173/196397).) |
| Delete a file (permanently) | <kbd>Shift</kbd> + <kbd>Delete</kbd> | <kbd>⌥ Option</kbd><kbd>⌘ Command</kbd> + <kbd>Backspace</kbd><br>(because <kbd>Backspace</kbd> [is <kbd>Delete</kbd> on mac's keyboard](https://apple.stackexchange.com/a/91173/196397).) |
| Switch input language | <kbd>Win</kbd> + <kbd>Space</kbd> <br>  <kbd>Ctrl</kbd> + <kbd>Shift</kbd> - change keyboard layout | <kbd>⌃ Control</kbd> + <kbd>Space</kbd> (a bit slow to show window pop-up),<br> <kbd>Fn</kbd> <br> Single press will switch back to previously selected. |
| Switch window/s | <kbd>Alt</kbd> + <kbd>Tab</kbd>  | <kbd>⌘ Command</kbd> + <kbd>Tab</kbd><br> But it's better to use [AltTab app](https://alt-tab-macos.netlify.app/) or similar. |
| Undo/Redo | <kbd>Win</kbd> + <kbd>z</kbd> / <br> <kbd>Win</kbd> + <kbd>Shift</kbd> + <kbd>z</kbd> | <kbd>⌘ Command</kbd> + <kbd>z</kbd> / <br> <kbd>⌘ Command</kbd> + <kbd>Shift</kbd> + <kbd>z</kbd> |
| Call an app from taskbar/dock. | <kbd>Win</kbd> + <kbd>1</kbd> / <kbd>2</kbd> ... <kbd>0</kbd> | [Snap application](https://apps.apple.com/us/app/snap/id418073146) can add this feature. |
| Move a window, snap to edges | <kbd>Win</kbd> + <kbd>↑</kbd> / <kbd>↓</kbd> / <kbd>←</kbd> / <kbd>→</kbd> | [Rectangle application](https://rectangleapp.com/) can add this feature. <br /><kbd>⌥ Option</kbd> + <kbd>⌃ Control</kbd> + <kbd>↑</kbd> / <kbd>↓</kbd> / <kbd>←</kbd> / <kbd>→</kbd> and more. |
| Move coursor to the beginning/end of the line | <kbd>Home</kbd> / <kbd>End</kbd> | <kbd>⌘ Command</kbd> +  <kbd>←</kbd> / <kbd>→</kbd> <br> [Karabiner-Elements](https://karabiner-elements.pqrs.org/) may help to remap these keys. |
| Move cursor to the next/previous word | <kbd>Ctrl</kbd> + <kbd>←</kbd> / <kbd>→</kbd> | <kbd>⌥ Option</kbd> +  <kbd>←</kbd> / <kbd>→</kbd> |
| Minimize a window | <kbd>Win</kbd> + <kbd>↓</kbd> | <kbd>⌘ Command</kbd> + <kbd>H</kbd> to hide window <br> Hint: Do not use minimize from the keyboard, it would bring some pain in restore a window. It easier to use "Hide", window/s will be restored easily after <kbd>⌘ Command</kbd> + <kbd>Tab</kbd> <br> - [Disable minimize](https://apple.stackexchange.com/questions/79528/is-there-a-way-to-disable-minimising-windows-with-the-yellow-button-in-os-x)<br>- Watch [use Hide instead of Minimize]()|
| Restore after minimize | (Works in native way, e.g. after Alt+Tab the window will be restored automatically) | [Restore windows native MacOS approach](https://apple.stackexchange.com/questions/55432/keyboard-shortcut-for-restoring-applications-from-the-mac-os-x-dock) <br> In a nutshell, it can be **ONLY** restored by click on a dock app icon. Unfortunately. |
| Restore after hide (more like minimize in Windows) | No such thing like "hide" in Windows, but minimized windows works in quite similar way. | [Difference between Hide and Minimize](https://superuser.com/a/543072/405044) |

### Issues
**RU language has non-windows layout in MacOS (e.g. for comma (,) and dot (.)).**
Q: Just remove Russian, but install Russian-PC.

