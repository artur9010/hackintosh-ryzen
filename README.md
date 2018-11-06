# AMD Ryzen Hackintosh build
**OS version**: 10.13.6 (*17G65*)

## Specs
| **Component** | **Model** |
| ------------- | --------- |
| CPU | AMD Ryzen 2600 |
| GPU | ASUS RX580 4GB |
| Motherboard | Gigabyte B450M DS3H |
| RAM | One 8GB 3000MHz DDR4 |

## /kexts/Other
- **Lilu.kext**
- realtekALC.kext

## /kexts/10.13
- AHCIPortInjector.kext
- **FakeSMC.kext**
- AHCI_3rdParty_SATA.kext
- JMicron36xATA.kext
- AirportBrcmFixup.kext
- **NullCPUPowerManagement.kext**
- AppleACPIPS2Nub.kext
- RealtekRTL8111.kext
- AppleALC.kext
- SuperVIAATA.kext
- AppleATIATA.kext
- WhateverGreen.kext
- AppleNForceATA.kext

## Not working
- Power management (huh, AMD)
- iMessage/FaceTime

