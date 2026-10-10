Intel Rapid Storage Technology (IRST) Driver Files — Version 18.7.6.1010.3

Here are the Intel Rapid Storage Technology (IRST) driver files for version 18.7.6.1010.3, ready to download without needing to extract them from an executable installer.

I know not everyone has access to a second computer, and finding the correct driver files can be frustrating when you're trying to install Windows. I struggled with this myself, so I'm sharing these files to help others who might be running into the same problem.

I hope these files save someone else the time and frustration I experienced!

Using the EXE File to Extract the Drivers

If you download the original SetupRST.exe file, you can extract the driver files using the command below.

Download SetupRST.exe from Intel's official website.

Open Command Prompt in the folder where you downloaded the file.

Enter the following command:

SetupRST.exe -extractdrivers SetupRST_extracted

Press Enter. The extracted driver files should be saved in the SetupRST_extracted folder.

You can then copy the extracted files to a USB drive and load the appropriate storage driver during Windows Setup.

Official Intel Website

You can find Intel Rapid Storage Technology drivers on Intel's official website:

https://www.intel.com/content/www/us/en/download/19512/intel-rapid-storage-technology-driver-installation-software-with-intel-optane-memory-10th-and-11th-gen-platforms.html

Important Notes

These files are for Intel Rapid Storage Technology version 18.7.6.1010.3.

Make sure you select the correct driver for your system.

These drivers may be needed when Windows Setup cannot detect a drive configured to use Intel Rapid Storage Technology (RST) or Intel Volume Management Device (VMD).

Having the extracted driver files available on a USB drive can help when you cannot access another computer to extract them.

I hope this repository helps someone else get Windows installed without the extra hassle!

# Redistribution Notice

The Intel Rapid Storage Technology (IRST) driver files in this repository are
**redistributed for convenience only**. No ownership is claimed.

## Ownership

All driver files remain the property of Intel Corporation. "Intel" and
"Intel Rapid Storage Technology" are trademarks of Intel Corporation and are
used here for identification purposes only.

This repository is **not affiliated with, endorsed by, or sponsored by Intel**.

## Redistribution basis

These files are redistributed in **unmodified form** exactly as produced by
Intel's official `SetupRST.exe` extraction process. No driver files (`.inf`,
`.sys`, `.cat`, etc.) have been edited.

Intel's driver installers permit redistribution in unmodified form for the
purpose of installation and deployment. If Intel's terms change or a removal
request is made, this repository will be updated accordingly.

## Source

- **Product:** Intel Rapid Storage Technology (IRST) Driver
- **Version:** 18.7.6.1010.3
- **Obtained via:** `SetupRST.exe -extractdrivers SetupRST_extracted`
- **Original installer source:** https://www.intel.com/content/www/us/en/download/19512/
- **Date retrieved:** [YYYY-MM-DD]

## Verification

SHA-256 checksums for every bundled file are listed in `SOURCES.md`. Always
verify against Intel's official release when possible.

## Contact

If you are Intel and want a change or removal, open an issue.

Always verify the correct storage configuration and driver for your specific
computer before making changes. Use at your own risk.
