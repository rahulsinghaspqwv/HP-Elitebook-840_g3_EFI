# HP-Elitebook-840_g3_EFI
<p> Author - <b> Rahul Singh. </b> 
</p>This is the working EFI for HP_Elitebook_840_g3 for MacOS Monterey 12.7.3 and you can update it to 12.7.6 with this EFI. </p>

# SMBIOS
In this EFI, My Machine SMBIOS is USED, So please change SMBIOS acording to your Machine or your choice. 
I am using Macbook pro(13, 1) 2016 SMBIOS for My Machine.
# Release 
version - 1.0 

# Image Src


# Specification of My Machine is:
* Processor (CPU) :- Intel Core i5-6300U Dual Core 4 Thread with 3 MB Intel Smart Cache 
* GPU                     :- Intel HD Graphics 520 (Shared Memory 8GB) 
* RAM Unit                :- 16GB DDR4-2133
* SSD                     :- Micron MTFDDAV256GB PCI m.2ssd
* Audio                   :- Conexant CX20724 HD
* Wi_Fi/Bluetooth         :- Intel Wireless-AC 8260 
* Ethernet                :- Intel l219-LM 

# MacOS Downloads - 
Download MacOS - [Monterey 12.7.3](https://drive.google.com/file/d/1b0Ts5K1nkGgZefp4-Bm58Ebfk3PLPT6W/view) -- Use this link to Download MacOS Monterey 12.7.3 | 

## Set Bios Settings to These Settings 
* Security -> Intel Software Guard Extensions (SGX) -> Disable
* Advanced -> Boot Options -> Check "UEFI Boot Order"
* Advanced -> Boot Options -> Unckeck "Legacy Boot Order"
* Advanced -> Secure Boot Configuration -> Configure Legacy Support and Secure Boot -> Legacy Support Disable and Secure Boot Disable
* Advanced -> System Options -> Check "Hyperthreading"
* Advanced -> System Options -> Check "Virtualization Technology (VTx)"
* Advanced -> System Options -> Uncheck "Virtualization Technology for Directed I/O (VTd)"
* Advaced -> Build-In Device Options -> Video memory size -> 64MB or anything higher 

# Installation
After installation - please use [MountEFI](https://github.com/corpnewt/MountEFI) link to Download MountEFI from github or mount the installed SSD EFI and then replace the EFI folder from your installation disk 
EFI. 
 
 Congratulations - You have successfully installed Mac Monterey 12.7.3 on your Machine.

# Credits 
* [Dortania](https://github.com/dortania) -- Opencore EFI Build
* [Opencore-simplify](https://github.com/lzhoang2801/OpCore-Simplify) -- Build with ACPI    tables and Hardware Report. 
* [Hardware-Sniffer](https://github.com/lzhoang2801/Hardware-Sniffer) -- Generate ACPI tables and Hardware Report.
* [SSDTTime](https://github.com/corpnewt/SSDTTime) -- Generate ACPI tables (Use Linux for Better Result).
* [MountEFI](https://github.com/corpnewt/MountEFI) -- Build by Corpnewt.

