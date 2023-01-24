# DEll OptiPlex 3050 OC EFI on Ventura (macOS 13.0.1)

## 🖥️ System configuration :
```
CPU：i7-7700(QS) QKHA
RAM：32G DDR4 2400
GPU：HD630
Storage：MX500 2.5 sata ssd + intel 670p SSD
Wi-Fi：Boardcam bcm943224pciebt2 with transfer card
```
## 💸 Total Cost :

|  Item   |                     Detail                     | Cost             |
| :-----: | :--------------------------------------------: | :--------------- |
|   CPU   |                i7-7700(QS) QKHA                | $ NTD: 1400      |
|   RAM   |                 32G DDR4 2400                  | $ NTD: 760 + 835 |
|   GPU   |                     HD630                      | $ NTD: 0         |
| Storage | MX500 2.5 sata ssd 256g + intel 670p SSD  512g | $ NTD: 500+735   |
|  Wi-Fi  |  Boardcam bcm943224pciebt2 with transfer card  | $ RMB: 60        |
|  DELL   |        OptiPlex 3050m barebone computer        | $ RMB: 280       |
## ➡️ Step 1 Bios setting：

- Secure Boot: OFF
- Launch CSM (or Legacy Mode): OFF
- Boot Operation (or Boot Mode): UEFI
- DVMT Pre-allocated: 64MB
- Fast Boot: OFF
- XHCI Pre-boot Mode (or XHCI Operation): ON
- SATA Operation: AHCI
- Legacy USB Support: OFF
- VT-d: OFF


## ➡️ Step 2 Disable cfg-lock：
1. Download GRUB file and put into yor usb
2. Enter  (change dvmt to 64MB)
   ```
   setup_var 0x795 0x2 
   ```
3. Enter  (Disable cfg-lock)
   ```
   setup_var 0x4ed 0x0
   ```

## ➡️ Step 3 Make booting usb：
1. [MacOs images : Olarila | The Real Vanilla Hackintosh - Vanilla macOS Images](https://linkvertise.com/462274/olarila-ventura-1311/1)
2. use [balenaetcher](https://www.balena.io/etcher) to create booting usb
3. use [diskgenius](https://www.diskgenius.cn/download.php) to put efi to booting usb
4. enjoy your hackintosh on DEll OptiPlex 3050m !
