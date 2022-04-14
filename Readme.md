# NUC11BTM-tosh (WIP)

Repo housing work for launching nuc11btm-tosh Monteray. This is very much a WIP.

This requires the use of a AMD supported GPU, currently the boot-args contains the patch for 6800 series of cards.

## Not Working
 - iGPU (UHD 750) - not supported under macOS
 - Intel AX210 Bluetooth (5.2) - not supported by the current intel bluetooth kext
 - LAN (i225-LM (3)) - Potentially can support, it should be native and it detects fine but won't connect

## Working
 - Card Reader
 - TB4 (No Hot plug)
 - USB