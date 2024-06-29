# OpenCore Catalina config

- MOBO: [MSI MPG X570 Gaming Plus](https://it.msi.com/Motherboard/MPG-X570-GAMING-PLUS/Specification)
- GPU:  [AMD Radeon PRO WX 4100](https://www.techpowerup.com/gpu-specs/radeon-pro-wx-4100.c2874)
- CPU:  Ryzen 7 5800X
- RAM:  2x [Corsair Vengeance RGB Pro 8GB 4000CL18](https://www.corsair.com/it/en/p/memory/cmw16gx4m2z4000c18/vengeancea-rgb-pro-16gb-2-x-8gb-ddr4-dram-4000mhz-c18-amd-ryzen-memory-kit-a-black-cmw16gx4m2z4000c18)
- Network:  [Fenvi FV-HB1200](https://www.fenvi.com/product_detail_32.html)

My pc also has a 3070, which has been disabled from `Root > DeviceProperties`. The WX 4100 is in the second X16 slot.

I did [map the RAM](https://dortania.github.io/OpenCore-Post-Install/universal/memory.html#cleaning-up). USB Ports [should also be mapped](https://dortania.github.io/OpenCore-Post-Install/usb/).

My DDR4 is overclocked to 3733CL14

Wi-Fi chipset is BCM4360 

Audio is enabled and SPDIF works too.

Has issues with sleep that i can't be bothered to fix.

CHANGE THE SMBIOS STUFF

SecureBoot should work but you have to enroll the .EFIs into your UEFI settings
