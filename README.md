AMD BIOS Settings

Note: Most of these options may not be present in your firmware, 
we recommend matching up as closely as possible but don't be too concerned if many of these options are not available in your BIOS.

Disable: 

Fast Boot
Secure Boot
Serial/COM Port
Parallel Port
Compatibility Support Module (CSM)(Must be off, GPU errors like gIO are common when this option in enabled)


Enable:

Above 4G decoding(This must be on, if you can't find the option then add npci=0x2000 to boot-args. Do not have both this option and npci enabled at the same time.)
If you are on a Gigabyte/Aorus or an AsRock motherboard, enabling this option may break certain drivers(ie. Ethernet) and/or boot failures on other OSes, if it does happen then disable this option and opt for npci instead
EHCI/XHCI Hand-off
OS type: Windows 8.1/10 UEFI Mode
SATA Mode: AHCI
