GIGABYTE Z490 VISION D Hackintosh
[Screenshot](https://github.com/Hckntsh/GigabyteZ490VisionDHack/blob/main/Screenshot.png)
(-*-)

Here are the main specs:

• System-board: Gigabyte Z490 Vision D

• CPU: Intel® Core™ i9-10900F

• GPU: Sapphire AMD RX 5500XT 8GB (with NZXT KRAKEN G12 GPU Cooling bracket and NZXT Kraken x73)

• Memory: Corsair Vengeance LPX 64 GB (2x32 GB) DDR4 3200 (CMK64GX4M2E3200C16)

• Storage: Samsung 980 Pro 1TB MZ-V8P1T0BW, Sabrent Rocket 2TB Nvme, WD Black WDS250G2X0C 250GB (Windows 10 installed)

• PSU: PSU: Super Flower Leadex Platinum 2000w

• Case: Loop StormForce Tabular E-ATX/ATX Aluminium Case

(-*-)

+Peripherals:

• Keyboards: Logitech Craft 

• Mouses/Trackpad: Corsair M65 RGB Elite

• Xbox Elite Wireless Controller Series 2

• External SoundCard: Creative Sound BlasterX G5

• CFExpress type-B Card reader

• Monitor: Samsung U32R592 32" Curved UHD 4K

(-*-)

What's Not working (or in working progress):

Thunderbolt 3 not showing up in SystemReport (Thunderbolt: No drivers are loaded), Thunderbolt 3 maybe working if the external usb-C device is connected from the boot.
Apart from that, everything else works including Sidecar. Haven't tested Handoff, iMessage and Airdrop yet.

(-*-)

Tools used to build EFI folder:

In the begining used @SchmockLord EFI, later used these tools to build/update EFI folder:

@Pavo-IM Opencore builder
@corpnewt MountEFI Commmand-line file and also his OCConfigCompare Command-line file, links below:

https://github.com/SchmockLord/Hackintosh-Intel-i9-10900k-Gigabyte-Z490-Vision-D

https://github.com/Pavo-IM/ocbuilder

https://github.com/corpnewt/OCConfigCompare

https://github.com/corpnewt/MountEFI

Important NOTE: Please change MLB, SystemSerialNumber, SystemUUID into your Config.plist file, PlatformInfo section.
