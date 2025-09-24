# Lab 02: Windows + Linux Installation & GRUB Recovery

## Objective
Set up a dual-boot system with Windows 11 and Ubuntu 22.04, simulate GRUB bootloader failure, and perform recovery.

## Key Skills
- Disk partitioning and OS installation
- GRUB bootloader troubleshooting
- User account configuration with least privilege
- Cross-platform recovery documentation

## Tools Used
- Windows Disk Management
- Ubuntu fdisk, grub-install
- Terminal (CMD, Bash)
- Screenshot tools

## Step 1: Disk Partitioning

### Windows Installer
- Created a **Primary Partition** (NTFS) for Windows 11.
- Left **Unallocated Space** for Ubuntu installation.

### Ubuntu Installer
- Used **GParted** to create:
  - `/` root partition (ext4)
  - `swap` partition (optional)
  - `/home` partition (ext4)

### Tools Used
- Windows Disk Management
- Ubuntu GParted and `fdisk`

### Screenshots
- <img src="images/windows11-partition.png" alt="Windows 11 Partition Layout" width="600"/>
- [Ubuntu Partition Layout via GParted](Images/ubuntu-partition-gparted.png)
- [fdisk Output](Images/fdisk-output.png)

### Notes
- Partition strategy ensures OS separation and data integrity.
- Swap partition added for memory management on low-RAM systems.



## References
- Cisco IT Essentials v8 – OS & Bootloader modules
- IBM SkillsBuild – OS Fundamentals
- TESDA NC II – Hardware Servicing & Safety

## Outcome
Successfully installed both OSes, simulated GRUB failure, and restored boot functionality. Documented all steps with screenshots and terminal logs.

