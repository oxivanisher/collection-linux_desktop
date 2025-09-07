## 2025-09-07
* Bump for Kodi role bugfix

## 2025-08-29
* Bump for Kodi role for background images

## 2025-05-29
* Bump for obsidian bugfix
* Bump for prusaslicer bugfix

## 2025-05-24
* Add flatpak_update role to collection

## 2025-05-08
* Bump for desktop app roles to fix check mode
* Bump for obsidian to ensure snapd is installed
* Add prusaslicer role
* Only run gnome_disable_initial_setup role when ansible_distribution == Ubuntu
* Only run gnome_longinscreen_configure when the gdm3 package is installed
* Bump for vscode role to use a deb822 source file again
* Bump for vivaldi role to ensure a deb822 source file
* Handling sources for Linux Mint
* Bump for nextcloud role to install correct filemanager extensions

## 2025-05-02
* Bump for change nas_mount role (might have security implications!)

## 2025-02-22
* Bump for bugfix in gnome_disable_inital_setup role

## 2025-02-08
* Bump for all roles to remove unused tests directory to make linter happy
* Bump for nas_mounts now adding _netdev option
* Everything is now correctly linted

## 2024-12-29
* Bump for nextcloud client role
* Bump for howdy role

## 2024-10-01
* Bump for gnome_loginscreen_configure role

## 2024-09-28
* Bump for fonts role. Attention: Fonts files location changed

## 2024-09-27
* Bump for gnome_loginscreen_configure role. Attention: Variable names changed

## 2024-09-18
* Bump for howdy role

## 2024-09-03
* Add role ubuntu_update_manager

## 2024-08-12
* Bump wold role (only setup WOL for ethernet interfaces)

## 2024-07-18
* Add obsidian role
* Bump spotify role (just adding a readme)

## 2024-06-28
* Adding pipeline badge
* Adding supported minimal version for linter
* Improve readme

## 2024-04-28
* Update kodi role to use flatpak instead of no longer maintained PPA repo on Ubuntu
* Fix variable names for kodi role
