<link rel=”manifest” href=”docs/manifest.webmanifest”>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  

---  

# Type "Spe"  


---

## Mainboards And Respective Printer Models 

The following table gives an overview about the printer models where the specific mainboards have been used.  
If there's an Insights page I created about the specific model, I linked to it.   

| Board Label | Version | Printer |
|:-----------:|:-------:|:-------:|
| Trigorilla Spe A | V1.0.0 | [Kobra 2 Pro](https://1coderookie.github.io/Kobra2ProInsights/hardware/mainboard/#trigorilla_spe_a_v100-stock) <br> [Kobra 2 Plus](https://1coderookie.github.io/Kobra2PlusInsights/hardware/mainboard/#trigorilla_spe_a_v100-stock) <br> [Kobra 2 Max](https://1coderookie.github.io/Kobra2MaxInsights/hardware/mainboard/#trigorilla_spe_a_v100-stock) | 
| Trigorilla Spe B | V1.0.4 <br> V1.0.5 | [Kobra 2 Pro](https://1coderookie.github.io/Kobra2ProInsights/hardware/mainboard/#trigorilla_spe_b_v10x-stock-new-revision) |
| Trigorilla Spe B | V1.1.3 | Kobra 3 | 

---

## Hardware

The following table gives an overview about the imho most important-to-know hardware specs.  

- All mainboards run on 24V DC and have the stepper drivers soldered right onto the PCB.  
- None of the mainboards has a fuse that could be changed in case of damage due to high voltage.  
- PWM is being achieved by switching GND 

| Board Label | Version | MCU | Stepper Drivers | mSD | USB | WiFi | 
|:-----------:|:-------:|:---:|:---------------:|:---:|:---:|:----:|
 Trigorilla Spe A | V1.0.0 | ARM Cortex-A7 | TMC2209 |  No | Yes (no PC connection) | Yes |
| Trigorilla Spe B | V1.0.4 <br> V1.0.5 | HC32F460 | TMC2209 |  No | Yes (no PC connection) | Yes |
| Trigorilla Spe B | V1.1.3 | HC32F460 | TMC2209 | No | Yes (no PC connection) | Yes |

---

## Firmware

The following table gives an overview about the firmware the boards are running as well as alternative firmware compatibility.  


| Board Label | Version | Stock Firmware | Stock FW Mods | Klipper |
|:-----------:|:-------:|:--------------:|:-------:|:-------------:|
| Trigorilla Spe A | V1.0.0 | KobraOS | No | No |
| Trigorilla Spe B | V1.0.4 <br> V1.0.5 | KobraOS | Yes: [Rinkhals](https://github.com/jbatonnet/Rinkhals) | unknown | 
| Trigorilla Spe B | V1.1.3 |KobraOS | Yes: [Rinkhals](https://github.com/jbatonnet/Rinkhals) | unknown | 

---

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  
