# BentoBoxWorld
BentoBox World plugin and addons management repository.

This repository contains ant build script that allows to checkout BentoBox plugin and all official addons.

This build script creates 2 folders: addons and plugin.

Usage:
 - ant bentobox-plugin - checkouts only bentobox plugin. It will be placed in plugin directory.
 - ant bentobox-addons - checkouts all official addons for BentoBox plugin. 
 - ant bentobox-complete - checkouts plugin and all addons.
	
Configuration also contains separate checkout scripts for each addon.

