# LPIC

## Linux

1. Debian  
   ubuntu - GNU workstarion

2. RPM

- fedora - KDE workstation
- red hat - GNU workstation!

x86_64 | amd64: for intel and amd

- 64 refers to 64bit

M1 => ARM => before used for cellphones => aarch64 | arm64

## Hardware

**Firmware** is a software on a hardware or a divice
_BIOS_ Basic input/output System - works with MBR(Master Boot Record - First partition of the harddisk)to boot the computer
_UEFI_ unified extensible firmware interfae

**sysfs** => pseudo file system => on the kernel memory
/sys => to check what devices and hardwares are connectd

**udev** => userspace dev, it's a pseudo file system
/dev => device manager for the linux kernel

**dbus** => is a message bus system.

**/proc** => to check cpuinfo => cat cpuinfo

_lsusb - lspci - lsblc - lshw_

**.ko** => kernel loadable modules => like a hardware's driver => _lsmod_

## Boot the system

1. Motherboard(MB) firmware(BIOS | UEFI) does a PowerOnSelfTest(_POST_) it checks all the hardwars like RAM... (if there is a problem, it beeps!)
2. MB loads the _bootloader_(BL)
3. bootloader loads the kernel based on its config/commands
4. kernel loads and prepares the system(root filesystem) and runs the initialization program
5. init program start the service, other programs(_other services_), ..(webserver,graphical interface, networking,...)

**sudu dmesg | less => to see boot logs**

## Shared Libraries

**Linking** => when we write a program, we use libraries.
linking has two forms:
*static
*dynamic => linux dynamic libraries have names like: _libLIBNAME.so.VERSION_

1. /usr/lib\*/ => for installed progtam's libs
2. /lib\*/
3. /lib64/

## Package management

_Repository pkmng:_

- Brew
