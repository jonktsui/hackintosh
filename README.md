# EFI folder for current Hackintosh

Please check out: [My Blog Post][blogposthack] for more details.

Note my Serial # has been removed

## Hardware
```
          [CPU] [Intel Core i9-9900K 3.6 GHz 8-Core Processor]
   [CPU Cooler] [Corsair H60 (2018) 57.2 CFM Liquid CPU Cooler]
  [Motherboard] [Asus ROG STRIX Z390-I GAMING Mini ITX LGA1151 Motherboard]
       [Memory] [G.Skill Ripjaws V 64 GB (2 x 32 GB) DDR4-3600 CL18 Memory]
      [Storage] [Samsung 970 Evo 1 TB M.2-2280 NVME Solid State Drive]
   [Video Card] [Sapphire Radeon RX 580 8 GB NITRO+ Video Card]
 [Power Supply] [Corsair SF 600 W 80+ Platinum Certified Fully Modular SFX Power Supply]
```

## EFI Folder structure

```
/EFI/
├── APPLE
│   └── EXTENSIONS
│       └── Firmware.scap
├── BOOT
│   └── BOOTx64.efi
└── OC
    ├── ACPI
    │   ├── SSDT-AWAC.aml
    │   ├── SSDT-EC.aml
    │   ├── SSDT-PLUG.aml
    │   ├── SSDT-PMC.aml
    │   └── SSDT-USBX.aml
    ├── Bootstrap
    │   └── Bootstrap.efi
    ├── Drivers
    │   ├── AudioDxe.efi
    │   ├── CrScreenshotDxe.efi
    │   ├── HfsPlus.efi
    │   └── OpenRuntime.efi
    ├── Kexts
    │   ├── AppleALC.kext
    │   │   └── Contents
    │   │       ├── Info.plist
    │   │       └── MacOS
    │   │           └── AppleALC
    │   ├── IntelBluetoothFirmware.kext
    │   │   └── Contents
    │   │       ├── Info.plist
    │   │       └── MacOS
    │   │           └── IntelBluetoothFirmware
    │   ├── IntelMausiEthernet.kext
    │   │   └── Contents
    │   │       ├── Info.plist
    │   │       └── MacOS
    │   │           └── IntelMausiEthernet
    │   ├── Lilu.kext
    │   │   └── Contents
    │   │       ├── Info.plist
    │   │       └── MacOS
    │   │           └── Lilu
    │   ├── NVMeFix.kext
    │   │   └── Contents
    │   │       ├── Info.plist
    │   │       └── MacOS
    │   │           └── NVMeFix
    │   ├── SMCLightSensor.kext
    │   │   └── Contents
    │   │       ├── Info.plist
    │   │       └── MacOS
    │   │           └── SMCLightSensor
    │   ├── SMCProcessor.kext
    │   │   └── Contents
    │   │       ├── Info.plist
    │   │       └── MacOS
    │   │           └── SMCProcessor
    │   ├── SMCSuperIO.kext
    │   │   └── Contents
    │   │       ├── Info.plist
    │   │       └── MacOS
    │   │           └── SMCSuperIO
    │   ├── USBMap.kext
    │   │   └── Contents
    │   │       └── Info.plist
    │   ├── VirtualSMC.kext
    │   │   └── Contents
    │   │       ├── Info.plist
    │   │       └── MacOS
    │   │           └── VirtualSMC
    │   └── WhateverGreen.kext
    │       └── Contents
    │           ├── Info.plist
    │           └── MacOS
    │               └── WhateverGreen
    ├── OpenCore.efi
    ├── Resources
    │   ├── Audio
    │   ├── Font
    │   ├── Image
    │   └── Label
    ├── Tools
    │   └── OpenShell.efi
    └── config.plist
```

[blogposthack]: https://jonktsui.github.io/blog/tech/building-a-hackintosh-part2/
