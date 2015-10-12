# Bootcamp Setup Instructions

### Start

1. Make sure you have a current backup of *all* your important files
2. Make sure you have at least 70 Gb free hard drive space (50GB for Windows + 20GB left for OS X's uses)
2. Make sure you have a 4+ GB USB Drive, plugged in
2. Close all programs
3. If you have a CD drive, insert the Windows Installation disk
3. Open "Boot Camp Assistant.app"

### Screen 1 (Boot Camp Assistant)

1. Check "Download the latest Windows support software from Apple"
2. Check "Install Windows 7 or later"
3. If you don't have an internal CD drive, check "Create a Windows 7 or later version install disk"
4. Click 'Continue'

If you don't see "or later" in those checkboxes, that means that your computer doesn't support Windows 8 installation directly.  See me for next steps.

### Screen 2

1. Select the USB drive (from above) as your "Destination disk"
2. Click 'Continue'

### Screen 3

The Windows support software for your machine will download automatically, and slowly. So. Slowly.  Do not give up.

At this point, you'll be brought to the Create a Partition for Windows screen.  If you aren't, it's because you don't have an install disk inserted/plugged in.  If you don't have the install disk available, Boot Camp Assistant will prompt you to insert the disk and then press "Ok".  Do so.  It will return you to the initial Boot Camp Assistant screen, but with "Install Windows [...]" as the only checked option.  Click "Continue".

### Screen 4 (Create a Partition for Windows)

1. Adjust the partitions so that Windows is allocated _at minimum_ 50 GB, but I would recommend more if you have the disk space available.  Leave at least 20GB free disk space on your OS X partition.
2. Click "Install"

Boot Camp Assistant will partition your hard drive, and then restart your computer to install Windows.

*From here, follow windows-install-steps.md instructions to choose installation options.*

If you have a retina display, you may need a magnifying glass.

After the Windows installation process completes, the Boot Camp program will turn on once Windows is installed.

### Installing drivers using Boot Camp

1. Click 'Next'
2. Click 'I accept'
3. Click 'Install'
4. Wait a while

Once it's done, it'll prompt you to restart.  Click 'Yes'