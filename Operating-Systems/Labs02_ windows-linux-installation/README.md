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


<h3>Windows Partition Layout</h3>
<img src="Images/windows11-partition-graph.png" alt="Windows Partition" width="600"/>

<h3>Ubuntu Partition Layout via GParted</h3>
<img src="Images/ubuntu-partition-graph.png" alt="Ubuntu Partition" width="600"/>

<h3>fdisk Output</h3>
<img src="Images/Kdisk-output.png" alt="fdisk Output" width="600"/>


### Notes
- Partition strategy ensures OS separation and data integrity.
- Swap partition added for memory management on low-RAM systems.


## References
- Cisco IT Essentials v8 – OS & Bootloader modules
- IBM SkillsBuild – OS Fundamentals
- TESDA NC II – Hardware Servicing & Safety

## Outcome
Successfully installed both OSes, simulated GRUB failure, and restored boot functionality. Documented all steps with screenshots and terminal logs.

