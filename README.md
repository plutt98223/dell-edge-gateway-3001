# Dell Edge Gateway 3001 Info

## Hardware

CPU - dual core Intel Atom E3805 @ 1.33GHz

RAM - 2 GB

Storage - 28.5 GiB MMC card

Wireless - RS9113 Silicon Labs Wi-Fi/Bluetooth Chipset

Ethernet - Realtek RTL8169 gigabit ethernet Chipset

Cellular - Telit LN930 Data Card (appears to be for Verizon)

## Operating System

Ubuntu Core 16

## Installed Packages

```
Name              Version          Rev    Tracking       Publisher   Notes
alsa-utils        1.1.2-5          68     latest/stable  canonical✓  -
bluez             5.48-4           314    latest/stable  canonical✓  -
caracalla         16.04-1.39       53     latest/stable  canonical✓  gadget
caracalla-kernel  4.4.0-234.268    173    latest/stable  canonical✓  kernel
core              16-2.57.2        13886  latest/stable  canonical✓  core
locationd         4.2.1            163    latest/stable  canonical✓  -
modem-manager     1.8.0-12         426    latest/stable  canonical✓  -
nano-editor       2.6.3            1      latest/stable  rws         -
network-manager   1.2.2-29         693    latest/stable  canonical✓  -
tpm2              1.0-5            42     latest/stable  canonical✓  -
udisks2           2.6.4-2          100    latest/stable  canonical✓  -
uefi-fw-tools     1.5.4-0.7.2+git  50     latest/stable  canonical✓  -
wifi-ap           30               355    latest/stable  canonical✓  -
wpa-supplicant    2.4.4            53     latest/stable  canonical✓  -
```

## Ubuntu documentation

[Ubuntu Core](https://ubuntu.com/core/docs)

[Network Manager](https://ubuntu.com/core/docs/networkmanager) -
Covers Wi-Fi and Cellular

[Bluetooth Management](https://ubuntu.com/core/docs/bluez)

## Misc. Notes

### Booting

First DHCP request appears to start at the 3 minute mark

### Login

The default login for the Dell provided Core 16 image is:
- login: admin
- pw: admin

### Wi-Fi/Bluetooth Antenna

Wi-Fi and Bluetooth appear to share the same antenna

