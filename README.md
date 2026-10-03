ZOS
---
<img width="1536" height="1024" alt="163225" src="https://github.com/user-attachments/assets/a7b81f8e-f22a-412c-919c-d8ec1d84e5f0" />

> Zos command pkg and apt install 😭
> 
Custom Termux Package Manager Interface

ZOS is a colorful custom command interface for Android Termux.

It provides simple commands for common package-management operations such as installing, removing, updating, upgrading and searching packages.

Repository

GitHub:

https://github.com/krishn-145/Zos

Features

- 📦 Install packages
- 🗑️ Remove packages
- 🔄 Update repositories
- ⬆️ Upgrade packages
- 🔎 Search packages
- 📋 List installed packages
- ℹ️ Package information
- 👤 Owner information
- 🎨 Colorful terminal interface
- 📱 Android / Termux support

Commands

Install
```
zos install python
```
Multiple packages:
```
zos install python git wget curl
```
Remove
```
zos remove python
```
Update
```
zos update
```
Upgrade
```
zos upgrade
```
Search
```
zos search python
```
List
```
zos list
```
Package Information
```
zos info python
```
Owner
```
zos owner
```
About
```
zos about
```
Version
```
zos version
```
Help
```
zos help
```
Installation

Clone the repository:
```
git clone https://github.com/krishn-145/Zos.git
cd Zos
chmod +x install
./install
```
After installation:
```
zos
```
Command Examples

Traditional Termux command:
```
pkg install python 
```
ZOS:
```
zos install python
```
Traditional update:
```
pkg update
```
ZOS:
```
zos update
```
Traditional upgrade:
```
pkg upgrade
```
ZOS:
```
zos upgrade
```
Traditional search:
```
pkg search python
```
ZOS:
```
zos search python
```
Important

ZOS is a custom interface around the existing Termux package-management backend.

It does not delete or damage the underlying "apt" or "pkg" system.

The original Termux package commands can still be used when required.

Owner

Owner: Krishn

Telegram: @krishn18

Instagram: ur_.krishn._02

GitHub: krishn-145

Repository: https://github.com/krishn-145/Zos

Platform

- Android
- Termux
- Bash

ZOS

Simple commands. Colorful terminal. Android + Termux.
