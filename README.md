RosBE-Manager
=============

Purpose
-------
Easily build the ReactOS operating system on Linux and helps translating.

Downloads and installs the ReactOS Build Environment (RosBE), the ReactOS source files with git and creates and runs a Docker image providing RosBE.
Then follow the instructions [here](https://www.reactos.org/wiki/Building_ReactOS#Linux.2FUnix).

Features
--------
* Pulls from git repository
* Downloads, configures and runs the ReactOS Build Environment in an Ubuntu based Docker container
* Adds and removes optional modules to integrate into built reactos images, e.g.:
  * Wine Gecko
  * Microsoft (c) Foundation Classes
  * VirtIO network drivers
  * AC97 sound driver
* Searches for untranslated resources and opens them for translation

Usage
-----
Run `./RosBE-Manager`
Then select functions with cursor up and down followed by the Enter key.
Select Back and hit the Enter key to return to the main menu from a submenu.
Select Exit and hit the Enter key to exit RosBE-Manager.

Target systems
--------------
Tested on:
* Debian
* Ubuntu
* Arch Linux
