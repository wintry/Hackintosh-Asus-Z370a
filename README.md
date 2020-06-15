# Opencore(0.5.8) configuration on Asus Z370a

![About My Mac](about.png)

It's recommend to clear NVRAM after updating to [8b63c35(May 23, 2020)](https://github.com/KTGWKenta/Hackintosh-Asus-Z370a/commit/8b63c35cfe7c951f3177e01ff09ee50cefea86bf), as the boot-args are no longer used.

### Hardware

- Asus Z370a
- Intel Core 8700K
- 4 * Kingston Predator 3600MHz 8G
- 1 * Samsung 970 EVO NVMe M.2 250GB
- 1 * Broadcom BCM943602CDP

#### Working

- CPU Turbo Boost
- Memory XMP
- Ethernet
- Onboard Audio Output
- Sleep/Wake
- All USB ports Patched
- iMessage
- App Store
- Facetime
- Bluetooth
- Wi-Fi
- Airdrop

### Settings

```bash
pmset -b hibernatemode 0
```


#### ⚠️Attention

- Please generate your own PlatformInfo(Generic + platformNVRAM)
- If you are using discrete graphics card, please remove 'disable-external-gpu'
- If you changed the SystemProductName(`Macmini8,1`), please also change it in USBPorts-AsusZ370Axxxxxx.kext