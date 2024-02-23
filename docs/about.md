# About this site

Archmoured arises from the idea of documenting the installation of my current Arch install 
with the purpose of deeply understanding everything I did (plagiarized) in order to obtain such 
a solid system. As there are almost no up-to-date instructions for this specific setup, I decided 
to share it on the internet in extreme detail so that anyone can replicate it and understand it as well.

By using btrfs in order to make use of snapshots, luks for encryption and systemd-boot as bootloader, 
this installation is truly unbreakable and easily recoverable. User-made mistakes are still a thing, 
but any miscalculation is just a ```timeshift --restore``` away from going back to a functional, comfy setup.

Archmoured does _not_ intend to market itself as some kind of product/distro of its own. This is merely 
a guide that intends to take you through a descriptive process that shows what to do, how 
to do it and why is it important for the installation.

This site wouldn't be possible without the help of these guides:

- [Arch Linux Installation guide](https://wiki.archlinux.org/title/Installation_guide)

- [Setting up Arch + LUKS + BTRFS + systemd-boot + apparmor + Secure Boot + TPM 2.0 - A long, nightmarish journey, now simplified](https://lemmy.eus/post/2898)

- [Installing Arch Linux with Btrfs, systemd-boot and LUKS](https://nerdstuff.org/posts/2020/2020-004_arch_linux_luks_btrfs_systemd-boot/)