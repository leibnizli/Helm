# Helm

Helm is a `hosts` file manager that runs on macOS. Helm enables you to edit `hosts` files and switch between them. Helm merges the original file and the active file into one file each time you switch. Write to the `hosts` file of the mac system.

Helm develops in swift.

![helm](https://github.com/user-attachments/assets/c4a79e5d-e094-422b-8624-f4588eb4c75d)

## Install

* <a href="https://apps.apple.com/cn/app/id1099472017">App Store</a>

## Help

### Chrome does not take effect after modifying hosts

Perform the save operation in Helm, and Helm will automatically clear the dns cache. If the hosts do not take effect at this time, there are several ways to solve it:

* `command+shift+N`: Start incognito session in a new window in Chrome.
* Open `chrome://net-internals/#sockets` in chrome and click `Flush socket pools`.

### Skill

You can also quickly preview the modified hosts effect. Just press the shortcut key on the editing window: `Command + Shift + O`, and you can see the modified hosts file.

* `Command + shift + O`: Open System Host File
* `Command + D`: Duplicate
* `Command + /`: Toggle Comment
* `Command + +` : Make Text Bigger
* `Command + 0` : Make Text Normal Size
* `Command + -` : Make Text Smaller

## Similar product

[Gas Mask](https://github.com/2ndalpha/gasmask)
