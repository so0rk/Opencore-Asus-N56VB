<h1 align="center">
  <br>ASUS N56VB Hackintosh<br>
</h1>

<div align="center">
   <img src="assets/about.jpeg"> 
</div>


Configuration files, that allow me to run macOS on my laptop. Based on [OpenCore](https://github.com/acidanthera/OpenCorePkg).

- OpenCore [0.9.8](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.9.8)
- macOS Big Sur 11.7.10

---

### **¡Disclaimer!**

The files are meant for my personal reference. I've also modified my laptop firmware which can potentially cause the laptop to become unaccessible.
<span style="color:red"> You are free to use and modify these files, but do so at your own risk </span>
Just because this works for me doesn't guarantee it will work for you.

---

I own an _ASUS N56VB_, more specifically:
| Component | Description |
| --------: | :---------- |
| CPU | Intel Core i7 3600QM (Ivy Bridge) |
| iGPU | Intel® HD Graphics 4000 |
| dGPU | Nvidia GeForce GT 740M |
| RAM | 8GB DDR3L 1600MHz |
| HDD | HITACHI HTS545032B9A300 |
| WLAN & BT | ATHEROSAR9485 |
| ETHERNET | ATHEROS8161 |
| AUDIO | ALC663 |

The subwoofer the laptop came with doesn't work and I haven't tried to make it work. I've replaced the optical drive with a hard drive to get more storage space. 
## What is working?

<span style="color:green;margin-left:1rem">&#9745;</span> Power management  
<span style="color:green;margin-left:1rem">&#9745;</span> iGPU. (HDMI with audio)  
<span style="color:green;margin-left:1rem">&#9745;</span> WiFi & Bluetooth  
<span style="color:green;margin-left:1rem">&#9745;</span> Battery read outs  
<span style="color:green;margin-left:1rem">&#9745;</span> Sleep  
<span style="color:green;margin-left:1rem">&#9745;</span> Audio  
<span style="color:green;margin-left:1rem">&#9745;</span> Touchpad with gestures  
<span style="color:green;margin-left:1rem">&#9745;</span> FN Keys    
<span style="color:green;margin-left:1rem">&#9745;</span> USB3.0 Ports  
<span style="color:green;margin-left:1rem">&#9745;</span> Ethernet port  
<span style="color:green;margin-left:1rem">&#9745;</span> CFG register unlocked  
<span style="color:green;margin-left:1rem">&#9745;</span> NVRAM

<span style="color:red;margin-left:1rem">&#9746;</span> Nvidia dGPU (disabled as switchable graphics are not supported)  
<span style="color:red;margin-left:1rem">&#9746;</span> External subwoofer

<span style="color:orange;margin:0 .25rem 0 1.25rem">?</span> Card Reader ... _Detected as USB2.0-CRW, but not reading anything_  

- Booting with an external display plugged in turns of the internal display, so during boot I keep any display cables unplugged.

## Special Thanks

[**Apple**](http://apple.com/)

[**Dortania**](https://dortania.github.io/getting-started/)

