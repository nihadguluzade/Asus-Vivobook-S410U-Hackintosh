# Asus VivoBook S410U Hackintosh

[![contributions](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/nihadguluzade/Asus-Vivobook-S410U-Hackintosh/issues)

## Overview

This repo includes an EFI folder with all the OpenCore configurations, patches, and necessary drivers required to run macOS Big Sur on ASUS Vivobook 14 S410U laptop model. Last tested with macOS version 11.2.1 and OpenCore 0.6.6.

Clover version: [Asus Vivobook S510UA Hackintosh](https://github.com/nihadguluzade/Asus-Vivobook-S510UA-Hackintosh)

## System specifications

    1.Model:    Asus VivoBook S14 S410U
    2.CPU:      Intel Core i7-8550U @ 1.80 GHz
    3.Graphics: Intel UHD 620
    4.RAM:    	DDR4 8GB
    5.Audio:    Conexant Unknown (layout_id = 3)

## Known Issues

1. **Touchpad** and **keyboard backlight** are not working. Could not get it fixed with VoodooPS2 kext.
2. Laptop does not respond after **sleep**.
3. Although I DSDT patched the **battery**, it drains after approximately 2 hours with heavy usage.
4. **Wifi** card can be replaced with DW1560 or be used with TP-Link TL-WN725N wifi adapter. No issues with ethernet though.
5. Cannot sign in to the **iCloud** from system preferences. Getting *Could not communicate with the server* error.

## Useful resources
* [OpenCore Install Guide - Dortania](https://dortania.github.io/OpenCore-Install-Guide/)
* [MountEFI](https://github.com/corpnewt/MountEFI)
* [ProperTree](https://github.com/corpnewt/ProperTree)
* [Wireless-USB-OC-Big-Sur-Adapter](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter)
