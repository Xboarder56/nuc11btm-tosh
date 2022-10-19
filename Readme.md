# NUC11BTM-tosh (WIP)

Repo housing work for launching nuc11btm-tosh Monteray. This is very much a WIP.

This requires the use of a AMD supported GPU, currently the boot-args contains the patch for 6800 series of cards. Additionally, I have swapped the WiFi (AX210) with a Broadcom M.2 supported card so the intel kexts are not provided.

## Hardware
 - NUC11BTMi9
 - RX 6800 Reference
 - BCM94360NG M.2 (replaces Intel AX210)

## Post Install
1. Fix iServices with the following steps: https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#using-gensmbios

## Not Working
 - iGPU (UHD 750) - not supported under macOS
 - Sleep (Kernel Panics)
 - LAN (i225-LM (3)) - Potentially can support, it should be native and it detects fine but won't connect

## Working
 - HW Sensors
 - Card Reader
 - TB4 (No Hot plug)
 - USB
 - Intel AX210 (Wifi + Bluetooth)