# Dell Vostro 5370 KabyLake
Dell Vostro 5370 with OpenCore<br>
Part Number : xxxxxxxx



```diff
- Last working Bios version is currently 1.22.0

```


<img src="/Pictures/reserved.png" alt="My cool HackBook"/>


In work with a multi boot Oparating System  |°|°|°|°
------------- | ------------- | ------------- | -------------| -------------
Windows  | Windows 10 Pro  | Windows 11 Pro  |  
Linux  | Ubuntu 21.10  |   |
MacOS  | Catalina  | Big Sur  | Monterey| Ventura
ChromeOS  | ChromeOS "Volteer"  |   |

*TPM 2.0 chip is enabled for Windows 11, does not affect MacOS versions.<br>
SecureBoot is disabled but can be enabled and rolled out for OpenCore drivers if needed.


<br>
<br>
<br>

The specs of the machine are:

Specifications  | Details
------------- | -------------
Processor  | Intel Core i5-8250u KabyLake-R (4C / 8T, 1.6 / 3.4GHz, 6MB)
RAM  | 8GB SO-DIMM DDR4-2666 + 8GB SO-DIMM DDR4-2666 (Total 16GB)
Storage  | 500GB SSD M.2 SATA
Graphics  | Integrated Intel® UHD-Grafik 620 (KabyLake-R)
Monitor  | 13.3" FHD (1920x1080) IPS 250 nits Anti-glare
Sound Card  | reserved (ALC 257 layout-ID 11 (0B000000))
Card reader  | Working
Network Card  | BCM94360NG
TouchPad  | Fully Fuctional

There are still a few small blemishes that I haven't been able to solve yet.
see Issues.

<br>
<br>
<br>
<br>




Then go to;<br>
Advanced → Power & Performance → CPU-Power Management Control → CPU Lock Configuration → CFG Lock → Disabled<br>

Then go to;<br>
Advanced → System Agent (SA) Configuration → Graphic Configuration → DVMT Pre-Allocated Selection → DVMT Pre-Allocated → Set to 160MB<br>

save and exit.<br>

There is a lot of customizable in the Debug Bios, just change the two points CPU-Lock & Graphic DVMT !!!!<br>
With other points you break the system.

<br>
<br>


## <p align="center"> Pictures</p>

  <p align="center"><img src="/Pictures/reserved.png" width="700" title="OpenCore Menu"></p>
  <p align="center"><img src="/Pictures/reserved.png" width="700" title="OpenCore Menu"></p>
  
    
  ##### <p align="center"> Grub menu only for ChromeOS, Ubuntu is launched directly from OpenCore</p>
  <p align="center"><img src="/Pictures/reserved.png" width="250" title="Grub Menu only for ChromeOS"></p>
  <p align="center"><img src="/Pictures/reserved.png" width="350" title="Ubuntu 21.10"></p>
     <p align="center"> ChromeOS</p>
  <p align="center"><img src="/Pictures/reserved.png" width="350" title="ChromeOS Volteer"></p>
  <p align="center"><img src="/Pictures/reserved.png" width="150" title="ChromeOS Volteer"> <img src="/Pictures/reserved.jpg" width="150" title="ChromeOS Volteer"> <img src="/Pictures/reserved.png" width="150" title="ChromeOS Volteer"> <img src="/Pictures/reserved.png" width="150" title="ChromeOS Volteer"></p>
     <p align="center"> Windows 10 & 11 Pro</p>
  <p align="center"><img src="/Pictures/reserved.PNG" width="250" title="Windows 10 Pro"> <img src="/Pictures/reserved.png" width="250" title="Windows 11 Pro"></p>
     <p align="center"> MacOS Catalina, BigSur & Monterey</p>
  <p align="center"><img src="/Pictures/Areserved.png" width="250" title="About this Mac"> <img src="/Pictures/reserved.png" width="250" title="About this Mac"> <img src="/Pictures/reserved.png" width="250" title="About this Mac"></p>


<p align="center"><img src="/Pictures/reserved.png" width="700" title="Graphic"></p>
<p align="center"><img src="/Pictures/reserved.png" width="700" title="Audio"></p>
<p align="center"><img src="/Pictures/reserved.png" width="700" title="Bluetooth"></p>
<p align="center"><img src="/Pictures/reserved.png" width="700" title="USB"></p>
<p align="center"><img src="/Pictures/reserved.png" width="700" title="Batterie"></p>
<p align="center"><img src="/Pictures/reserved.png" width="700" title="TouchPad"></p>

