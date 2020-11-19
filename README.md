# Hackintosh Opencore Asrock B365-M PRO4 / ASUS ROG STRIX GAMING RX VEGA 64 O8G

## Hardware
| Hardware    | Model                                 |
| ----------- | --------------------------------------|
| Motherboard | Asrock B365-M PRO4                    |
| CPU         | Intel i5-9600K                        |
| DGPU        | ASUS ROG STRIX GAMING RX VEGA 64 O8G  |

## Software
| Software    | Version                      |
| ----------- | ---------------------------- |
| Opencore    | 0.5.9                        |
| OSX         | Catalina / 10.15.7           |
| Bios        | 0803                         |

## Working Fine
- Onboard Audio
- Onboard Ethernet
- Hardware Acceleration (H264 & HVEC)
- Shut Down, Restart, Sleep
- iServices

## How to build

1. Format flash drive in Disk Utility (as Untitled)
2. Download Catalina 
3. Create Mac OS install 
```sudo /Applications/Install\ macOS\ Catalina.app/Contents/Resources/createinstallmedia --volume /Volumes/Untitled```
4. MountEFI of the flash drive
5. Copy `EFI` folder to the flash `EFI` partition


## Important tools
| Tool (repo link)                     | Note                                |
| ------------------------------------ | ----------------------------------- |
| https://github.com/corpnewt/gibMacOS | Download MacOS X releases           |
| https://github.com/corpnewt/MountEFI | Mount the EFI partition             |

