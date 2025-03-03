# TurboPack VirtualTree

Please refer to [https://github.com/JAM-Software/Virtual-TreeView](https://github.com/JAM-Software/Virtual-TreeView) for the most up to date version.

This repository is currently set to archive state.
---------


Updated for **10.3 Rio** / VER330 / PKG 260

You can still access [10.2 Tokyo](https://github.com/TurboPack/VirtualTreeView/releases/tag/102Tokyo) and [10.1 Berlin](https://github.com/TurboPack/VirtualTreeView/releases/tag/101Berlin) versions too.

## Table of contents

1.  Introduction
2.  Package names
3.  Installation

---------

## 1. Introduction


Virtual Treeview is a Delphi treeview control built from ground up. Many years of 
development made it one of the most flexible and advanced tree controls available today. 
Virtual Treeview starts off with the claim to improve many aspects of existing solutions 
and introduces some new technologies and principles which were not available before.

This is a source-only release of TurboPack VirtualTree. It includes
designtime and runtime packages for Delphi and CBuilder and supports Win32 and Win64.

---------

## 2. Package names


TurboPack VirtualTree package names have the following form:

### Delphi
* VirtualTreeDR.bpl   (Delphi Runtime)
* VirtualTreeDD.bpl   (Delphi Designtime)
* VirtualTreeDBDR.bpl (Delphi data aware Runtime)
* VirtualTreeDBDD.bpl (Delphi data aware Designtime)

### C++Builder
* VirtualTreeCR.bpl   (C++Builder Runtime)
* VirtualTreeCD.bpl   (C++Builder Designtime)
* VirtualTreeDBCR.bpl (C++Builder data aware Runtime)
* VirtualTreeDBCD.bpl (C++Builder data aware Designtime)


---------

## 3. Installation


VirtualTreeView is available via the [GetIt Package Manager](http://docwiki.embarcadero.com/RADStudio/en/Installing_a_Package_Using_GetIt_Package_Manager) where you can quickly and easily install and uninstall it.

To manually install TurboPack VirtualTree into your IDE, take the following
steps:

1. Unzip the release files into a directory (e.g., d:\VirtualTree).

2. Start RAD Studio.

3. Add the source subdirectory (e.g., d:\VirtualTree\source) to the
     IDE's library path. For CBuilder, add the hpp subdirectory
     (e.g., d:\VirtualTree\source\hpp\win32\Release) to the IDE's system include path.

4. Open & install the designtime package specific to the IDE being
     used. The IDE should notify you the components have been
     installed.
