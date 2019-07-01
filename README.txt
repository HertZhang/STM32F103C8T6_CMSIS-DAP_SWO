V1.0 match to nanoDAP V1.0

V1.1 match to nanoDAP V2.0 
actually just GPIO re-config between V1.0 and V1.1

V1.2 match to nanoDAP V2.1
just modify usb enum gpio to PA15

V1.3 match to nanoDAP V2.1 with DAPLink
just V1.2 source code, but link the system image to 0x0800C000,
so you can drag and drop, use DAPLink bootloader to upgrade to cmsis-dap system. :)


ps:
current pcb support both cmsis-dap & DAPLink
(cmsis-dap use the stm32f103c8t6, and DAPLink use the stm32f103cbt6)

