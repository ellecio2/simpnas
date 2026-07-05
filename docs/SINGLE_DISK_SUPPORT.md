# Single Disk Support

## Problem

The original simpNAS installer assumes that the operating system and data
must reside on different physical disks.

This prevents installations on:

- Mini PCs
- Laptops
- NUCs
- Repurposed desktops
- Systems with only one SSD/HDD

## Solution

Allow the installer to use an existing partition on the operating system disk
without repartitioning or formatting the entire disk.

## Benefits

- Existing partition support
- Non-destructive installation
- Home server friendly
- Better hardware compatibility