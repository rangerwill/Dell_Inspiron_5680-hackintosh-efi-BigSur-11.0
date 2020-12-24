# Dell_Inspiron_5680-hackintosh-efi-BigSur-11.0
适用于戴尔灵越5680的黑苹果配置文件 (独显从Nvidia GTX1066替换为AMD RX564)





Not finished yet.

This EFI Uses OpenCore

Derived From 

https://www.tonymacx86.com/threads/guide-dell-xps-8930-catalina-10-15-7-rx580-uhd630-opencore.306636/

Huge Thanks To @dandelionclock from tonymacx86

Dell Inspiron 5680

CPU: i7-8700

Graphics Card: RX560 4G

Wireless Network Card and Bluetooth: DW1820a

Yep, as you have noticed, I had already swapped the Wireless Network Card to make sure bluetooth and WiFi can function well.

Integrated LAN: Realtek 8111



After My Tweaking, 

recovering from sleep seems not function well,

ALC sound card seems still not function,

Intel integrated graphics (output only) (QuickSync works): Dell BIOS seems to automatically turn off output of the IGPU when a discrete graphics card has been installed. 

I have not tried the -wegnoegpu flag for whatevergreen



Attention! 

Do make sure you have already booted into bios and made the suggested changes below:

    Intel SpeedStep, Virtualization, VT for Direct I/O = Enabled
    SATA Operation: ACHI
    Everything else = disabled
    Secure Boot = Disabled

Otherwise your hackintosh might be not bootable.
