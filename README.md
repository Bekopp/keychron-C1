# Keychron-C1
## Kubuntu 20.04 - Windows mode setup

1. Create a file: /etc/modprobe.d/hid_apple.conf
2. Write "options hid_apple fnmode=2" (without quotes) and save
3. Run terminal command: sudo update-initramfs -u
4. Reboot

