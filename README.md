# Snap Packaging for scrcpy

**This is a snap for scrcpy**, *"Display and control your Android device"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.


![Screenshot of the Snapped Application](https://github.com/Genymobile/scrcpy/blob/master/assets/screenshot-debian-600.jpg "Screenshot of the Snapped Application")


## Installation
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### The Graphical Way
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/scrcpy)
-->

### From the Terminal
  
##### The latest stable version (currently v1.12) is in the stable channel:
    sudo snap install scrcpy
    
##### The latest (non stable) version built from scrcpy's master branch is in the beta channel:
    sudo snap install --channel=beta scrcpy
    
##### The development version build from the dev branch is in the edge channel:
    sudo snap install --channel=edge scrcpy

##### On some systems the core snap is not installed by default but it's needed:
    sudo snap install core


##### Usage:
    scrcpy
##### You can also use the builtin adb tool:
    scrcpy.adb [options]
##### For example:
    scrcpy.adb devices
    scrcpy.adb kill-server
    
#### To uninstall the scrcpy snap:
    sudo snap remove scrcpy
