---
Title: Install Palera1n
date: 2023-12-8 2:45 -500
categories: [Tech, How-to]
tags: [iphone, jailbreak, linux]
---

# Installing palera1n

If you need help in English, join my [Codex](https://discord.gg/v6Z7xWpNrj) Discord Server. You can also check out the [Linux guide](https://ios.cfw.guide/installing-palera1n/).

palera1n is an unfinished jailbreak that works with A11 (iPhone X) and older devices on iOS 15.0 or higher, with some limitations for A11 devices.

On A11 devices, you have to turn off your passcode and you cannot use your passcode, or any SEP features, until you restart your device in a normal iOS state. SEP features include things like a passcode, Face ID/Touch ID, and Apple Pay.

Also, if your device is an A11 device on iOS 16 and you had a passcode before, you will have to wipe out all your data and settings to be able to jailbreak.

If you are using an outdated version of palera1n that was tethered, you have to uninstall palera1n before proceeding.

If you are using Windows, you should follow Using palen1x instead.

### Notice

Depending on the Linux version you are using, you may encounter problems with the latest version (2.0.0b8) of palera1n.

If you do encounter problems and you are trying to jailbreak a 15.0 to 16.7.2 device, you can manually install palera1n 2.0.0b7 instead.

If you are trying to use a Virtual Machine software of some kind from Windows (e.g. Virtualbox, VMWare, Windows Subsystem for Linux, etc) you will not succeed with following this guide.

If you are using a computer with an AMD Ryzen CPU, you will likely run into problems. If you do run into problems, you should use a Mac or a computer with an Intel CPU to follow this guide.

If you are using a USB-C to Lightning cable to do this process, you may encounter problems entering into DFU mode

If you do have problems, get a USB-A to Lightning cable and, if needed, also get a USB-C to USB-A adapter.

A9(X) and older devices have an issue where they will get stuck halfway through this process in pongoOS. To fix this issue, you'll need to do the following:

In the terminal window, press Control + C on your keyboard
Run the command that you just ran again
You'll need to do this every time you jailbreak your device again.

### Setting up palera1n

#### Steps:

* Open up a terminal window
* Run `sudo systemctl stop usbmuxd`
* Run `sudo usbmuxd -f -p`
* Open up another terminal window
* Run `sudo /bin/sh -c "$(curl -fsSL https://static.palera.in/scripts/install.sh)"`

### Installing palera1n

#### Steps:

* Connect device when entering this command
* Run sudo palera1n
* Press Enter and follow the instructions on the screen to enter DFU mode.
* Open the palera1n loader app and tap Sileo. After a while, you'll be asked to set a passcode for using command line stuff, and then afterwards, Sileo should be on your home screen.
* To jailbreak your device again, simply run the command you just ran again and then repeat any other relevant steps.

