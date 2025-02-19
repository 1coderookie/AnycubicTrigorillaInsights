<link rel=”manifest” href=”docs/manifest.webmanifest”>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  

---  

# Type "Pro"


---

## Mainboards And Respective Printer Models 

The following table gives an overview about the printer models where the specific mainboards have been used.  
If there's an Insights page I created about the specific model, I linked to it.   

| Board Label | Version | Printer |
|:-----------:|:-------:|:-------:|
| Trigorilla Pro A | V1.0.4 | Kobra <br> Kobra Plus <br> Kobra Max <br> Vyper | 
| Trigorilla Pro B | V1.0.2 | [Kobra 2](https://1coderookie.github.io/Kobra2Insights/hardware/mainboard/#trigorilla-pro-b-v_102-stock) | 

---

## Hardware

The following table gives an overview about the imho most important-to-know hardware specs.  

- All mainboards run on 24V DC and have the stepper drivers soldered right onto the PCB.  
- None of the mainboards has a fuse that could be changed in case of damage due to high voltage.  
- PWM is being achieved by switching GND 

| Board Label | Version | MCU | Stepper Drivers | mSD | USB | WiFi | 
|:-----------:|:-------:|:---:|:---------------:|:---:|:---:|:----:|
| Trigorilla Pro A | V1.0.4 | HC32F460 | TMC2208 <br> GC6609 |  Yes | Yes | No |
| Trigorilla Pro B | V1.0.2 | HC32F460 | TMC2208 <br> GC6609 |  Yes | Yes | No |


---

## Firmware

The following table gives an overview about the firmware the boards are running as well as alternative firmware compatibility.  


| Board Label | Version | Stock Firmware | Stock FW Mods | Klipper |
|:-----------:|:-------:|:--------------:|:-------:|:-------------:|
| Trigorilla Pro A | V1.0.4 | Marlin | unknown | Yes - *with mod*: <br> [Solder R65 to R66](https://klipper.discourse.group/t/support-for-hdsc-chips-hc32f460/2860/54) *or* use [catboat](https://github.com/printers-for-people/catboat)! |
| Trigorilla Pro B | V1.0.2 | Marlin | unknown | [Yes](https://github.com/1coderookie/Klipper4Kobra2series/tree/main/Kobra2) - w/o mod |

---

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  
 
