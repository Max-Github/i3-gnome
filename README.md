# i3-gnome

[![License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](http://choosealicense.com/licenses/mit/)

--------------------------------------------------------------------------------

Allows you to use i3-wm with GNOME 3 Session infrastructure on Ubuntu GNOME 15.10. 

Based on https://aur.archlinux.org/packages/i3-gnome/

## Build & Install

1. Clone Repo, and CD to it.

2. Install missing dependancies and build tools.

3. Use the following command to build: 
    ```bash
    debuild -i -us -uc -b
    ```

4. Use the following command to install: 
    ```bash
    sudo dpkg -i ./../i3-gnome_1.1.0-1_all.deb
    ```
    
    This assumes that you are still in the repo folder.



## Usage

At this point you have to log-out from your current session. You should see a new session type
called "GNOME + i3" in your display manager. Choose it and log back in.

