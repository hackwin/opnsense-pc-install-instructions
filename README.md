# About

This is a quick-start tutorial for installing and configuring OPNSense Linux on a x64-based computer

# Why choose OPNSense?
Free, open-source.  Alternative to Netgate pfSense.

# Recommended Hardware
Fanless mini-PC: https://www.aliexpress.com/item/4000930882001.html

# Instructions
1. Download OPNSense
	1. Choose whether to download installer for USB flash drive or DVD
	2. Verify downloaded install image checksum
		* Nirsoft HashMyFiles (for Windows)
		* `sha256sum <filename>` (Linux/Mac)
2. Write Installer
	1. Write to USB or DVD
		* DVD: ImgBurn (Windows)
		* USB: balenaEtcher (Windows, Mac, Linux)
3. Connect keyboard, monitor, power, and ethernet cable from your network
4. Boot from installation media
5. Install OS
6. Choose WAN ethernet port
7. Choose LAN ethernet port
8. Configure your PC to turn itself back on after power loss
	1. Setting may be in BIOS or a jumper on the motherboard
	
# Where to find free support?
* chat.freenode.net IRC room #OPNSense
	* HexChat (Windows, Mac, Linux)

# Alternatives:
* Netgate pfSense
* m0n0wall
* ddwrt
