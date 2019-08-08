# HLK-RM04

Original Backup Flash (Firmware(V1.78(Jul 23 2013)))

**Partitions Flash**<br>
**W25Q32BV : 00 0000h - 3F FFFFh**<br>
0x000000 - 0x0**2FFFF** : "u-boot"<br>
0x0**30000** - 0x0**3FFFF** : "u-boot-env"<br>
0x0**40000** - 0x0**4FFFF** : "factory"<br>
0x0**50000** - 0x**12FFFF** : "kernel"<br>
0x**130000** - 0x**3FFFFF** : "rootfs"<br>

## **Restore original firmware**

With a bin file processor we get the backup flash HLK_RM04 W25Q32.bin
u-boot + u-boot-env and kernel + rootfs in two files.

We install the u-boot from here https://github.com/smarpl/hlk-rm04_u-boot because it also has UART media image installation by pressing '0'.

**Steps after successfully installing u-boot.**

**1.** Install the file we have created by editing the backup flash HLK_RM04 W25Q32.bin kernel + rootfs. With UART “pressing 0” or TFTP “pressing 2”.

**2.** Install the file we have created by editing the backup flash HLK_RM04 W25Q32.bin u-boot + u-boot-env. With UART “pressing 7” or TFTP “pressing 9”.

**Επαναφορά πρωτότυπου firmware**

Με ένα επεξεργαστή αρχείον bin παίρνουμε από το backup flash HLK_RM04 W25Q32.bin
το u-boot + u-boot-env και το kernel + rootfs σε δύο αρχεία.

Εγκαταστούμε το u-boot από εδώ https://github.com/smarpl/hlk-rm04_u-boot γιατί έχει και εγκατάσταση εικόνας μέσο UART πατώντας το ‘0’.

**Βήματα μετά την επιτυχείς εγκατάσταση του u-boot.**

**1.**	Εγκαταστούμε το αρχείο που έχουμε δημιουργήσει από την επεξεργασία του backup flash HLK_RM04 W25Q32.bin το kernel + rootfs. Με UART “ πατώντας 0 ” ή TFTP “ πατώντας 2 ”.

**2.**	Εγκαταστούμε το αρχείο που έχουμε δημιουργήσει από την επεξεργασία του backup flash HLK_RM04 W25Q32.bin το u-boot + u-boot-env. Με UART “ πατώντας  7 ” ή TFTP “ πατώντας  9 ”.

## The easiest way is with a universal programmer, **'without removing the eeprom'**

![001 (2)](https://user-images.githubusercontent.com/17230472/62714951-2d0f6880-ba08-11e9-9134-414785454324.jpg)
