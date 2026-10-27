# Embedded Linux Training Progress Tracker

**Current Status: 🟨 In Progress**

Current Focus: Environment Setup

## Stage 0 - Environment Setup

Development Environment:
- Install WSL2
- Install Ubuntu
- Update system packages
- Install VS Code
- Connect VS Code to WSL
- Configure Git
- Configure GitHub SSH authentication
- Clone repository in WSL

## Stage 1 - Linux Fundamentals
Goal: Become comfortable working in a Linux environment.

Topics:
- Filesystem navigation
- Linux permissions
- Processes
- Package management
- Networking basics
- Shell usage
- SSH

## Stage 2 - Cross Compilation Toolchain
Based on: Bootlin - Building a Cross-Compiling Toolchain

Tasks:
- Download Crosstool-NG
- Configure ct-ng
- Build ARM toolchain
- Analyze generated toolchain
- Compile hello.c
- Execute ARM binary through QEMU
- Understand sysroot
- Understand target tuple

## Stage 3 - Bootloader (U-Boot)
Based on: Bootlin - Bootloader Lab

Tasks:
- Download U-Boot
- Configure target board
- Build U-Boot
- Launch U-Boot in QEMU
- Explore available commands
- Create SD card image
- Configure networking
- Configure TFTP
- Store environment variables
- Automate boot sequence

## Stage 4 - Linux Kernel Sources
Based on: Bootlin - Fetching Linux Kernel Sources

Tasks:
- Clone Linux repository
- Add stable remote
- Understand repository structure
- Check out Linux 6.1 branch
- Identify important source directories

## Stage 5 - Linux Kernel Build
Based on: Bootlin - Kernel Cross-Compiling

Tasks:
- Configure build environment
- Apply vexpress_defconfig
- Explore menuconfig
- Build kernel
- Analyze generated outputs
- Understand zImage
- Understand DTB files
- Boot kernel using U-Boot
- Automate kernel booting

## Stage 6 - Root Filesystem and BusyBox
Based on: Bootlin - Tiny Embedded System

Tasks:
- Configure NFS
- Create root filesystem
- Build BusyBox
- Install BusyBox
- Configure init system
- Create inittab
- Create rcS startup script
- Mount proc
- Mount sysfs
- Configure shared libraries
- Deploy simple web interface

## Stage 7 - Hardware Access
Based on: Bootlin - Accessing Hardware Devices

Tasks:
- Explore /dev
- Explore /sys
- Explore network devices
- Explore storage devices
- Explore buses
- Understand sysfs layout

## Stage 8 - Filesystems
Based on: Bootlin - Block Filesystems

Tasks:
- Configure ext4
- Configure SquashFS
- Configure tmpfs
- Partition SD image
- Deploy root filesystem
- Boot from SD image

## Stage 9 - Third-Party Libraries and Applications
Based on: Bootlin - Third Party Libraries and Applications

Tasks:
- Build alsa-lib
- Build alsa-utils
- Understand staging directory
- Understand target directory
- Use pkg-config
- Use autotools
- Use Meson
- Build ipcalc
- Strip binaries

## Stage 10 - Buildroot
Based on: Bootlin - Buildroot

Tasks:
- Download Buildroot
- Configure Buildroot
- Integrate external toolchain
- Build Linux kernel
- Build BusyBox
- Build ALSA packages
- Build MPD
- Generate root filesystem
- Analyze dependency graph

## Stage 11 - Application Development
Based on: Bootlin - Application Development

Tasks:
- Build ncurses application
- Use pkg-config
- Deploy application
- Execute application on target

## Stage 12 - Debugging
Based on: Bootlin - Remote Application Debugging

Tasks:
- Use strace
- Use ltrace
- Use gdbserver
- Connect remote GDB
- Analyze crashes
- Generate backtraces
- Analyze core dumps
