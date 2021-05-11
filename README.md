# lenovo_m710q_hackintosh

| Product | Lenovo m710q |
| - | - |
| CPU | Intel QNCT (i7 8850h) |
| MEM | Micron DDR4-2400 8GB * 1 |
| SSD | UMIS m.2 NVME 120GB |
| ETHERNET | Intel i219 |
| WIFI & BLE | Intel 7260AC |


[Taobao](https://item.taobao.com/item.htm?spm=a1z10.3-c-s.w4002-15933205976.15.507e5c73rBskTa&id=629359505141)

# UEFI setting
| Item | Value |
| - | - |
| CSM | Disabled |
| Boot Type | UEFI only |
| Secure Boot | Disabled |
| Intel Virtualization Technology | Enabled |
| VT-d | Disabled |
| Video Output | IGD |
| Video Pre-allocated Memory | 64MB |
| Wake on LAN | Disabled |


# OSX version tested
10.14.6 Mojave (current EFI)

11.3.1 Big sur (need to replace AirportItlwm.kext and USBMapLegacy.kext)

# Not Working
* WIFI and BLE not stable on Big sur
* Airdrop

# Thanks
[Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
