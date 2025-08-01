# Tanmay's Minimal Linux OS

A lightweight, educational Linux-based OS built from scratch using a custom Linux kernel and BusyBox.

## 🔧 Features

- Custom compiled Linux kernel
- BusyBox for userland tools
- Simple init script and RAM-based filesystem
- Boots fully in QEMU
- Educational breakdown of the Linux boot process

## 📁 Project Structure

minimal-linux-os/
├── linux/ # Custom Linux kernel source
├── busybox/ # BusyBox source and build
├── rootfs/ # Root filesystem with init script and symlinks
├── initramfs.cpio.gz # Compressed rootfs used during boot
├── run.sh # Script to boot the OS using QEMU


## 🚀 Booting in QEMU

```bash
./run.sh
