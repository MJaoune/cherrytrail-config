# Linux kernel config for Intel Cherry Trail-based devices

This configuration was mainly created for iLife ZedBook II device, however, the SoC configuration should work on all similar devices. I try to make this config as minimal as possible as such devices are usually low on resources.

## Installation
1. Rename "ct-config" file to ".config".
2. Move file to kernel source tree directory.
3. (Optional) Use "make menuconfig" to edit the configuration if needed.
4. Execute "make && make modules\_install && make install".
