[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  

---

# Anycubic Trigorilla Mainboards
Here you'll find some information about Trigorilla mainboards that Anycubic used in their 3D FDM printers (since Kobra 1st gen.).  

---

## Mainboards And Respective Printer Models 

The following table gives an overview about the printer models where the specific mainboards have been used.  
If there's an Insights page I created about the specific model, I linked to it.   

| Board Label | Version | Printer |
|:-----------:|:-------:|:-------:|
| Trigorilla Gen | V3.0.6 <br> V3.0.7 | [Kobra Go](https://1coderookie.github.io/KobraGoNeoInsights/hardware/mainboard/#trigorilla-v_306-stock) <br> [Kobra Neo](https://1coderookie.github.io/KobraGoNeoInsights/hardware/mainboard/#trigorilla-v_306-stock) |
| Trigorilla Gen | V4.0.1 | [Kobra 2 Neo](https://1coderookie.github.io/Kobra2NeoInsights/hardware/mainboard/#trigorilla-v_401-stock) | 
| Trigorilla Pro A | V1.0.4 | Kobra <br> Kobra Plus <br> Kobra Max <br> Vyper | 
| Trigorilla Pro B | V1.0.2 | [Kobra 2](https://1coderookie.github.io/Kobra2Insights/hardware/mainboard/#trigorilla-pro-b-v_102-stock) | 
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
| Trigorilla Gen | V3.0.6 <br> V3.0.7 |  HC32F460 | TMC2208 <br> GC6609 | Yes | Yes | No |
| Trigorilla Gen | V4.0.1 | GD32F303 | TMC2208 <br> GC6609 |  Yes | Yes | No |
| Trigorilla Pro A | V1.0.4 | HC32F460 | TMC2208 <br> GC6609 |  Yes | Yes | No |
| Trigorilla Pro B | V1.0.2 | HC32F460 | TMC2208 <br> GC6609 |  Yes | Yes | No |
| Trigorilla Spe A | V1.0.0 | ARM Cortex-A7 | TMC2209 |  No | Yes (no PC connection) | Yes |
| Trigorilla Spe B | V1.0.4 <br> V1.0.5 | HC32F460 | TMC2209 |  No | Yes (no PC connection) | Yes |
| Trigorilla Spe B | V1.1.3 | HC32F460 | TMC2209 | No | Yes (no PC connection) | Yes |

---

## Firmware

The following table gives an overview about the firmware the boards are running as well as alternative firmware compatibility.  


| Board Label | Version | Stock Firmware | Stock FW Mods | Klipper |
|:-----------:|:-------:|:--------------:|:-------:|:-------------:|
| Trigorilla Gen | V3.0.6 <br> V3.0.7 | Marlin | [Yes](https://1coderookie.github.io/KobraGoNeoInsights/firmware/fw_marlin/#mods) | [Yes](https://github.com/1coderookie/Klipper4KobraGoNeo) - w/o mod |
| Trigorilla Gen | V4.0.1 | Marlin | [Yes](https://1coderookie.github.io/Kobra2NeoInsights/firmware/fw_marlin/#mods) | [Yes](https://github.com/1coderookie/Klipper4Kobra2series/tree/main/Kobra2Neo) - w/o mod |  
| Trigorilla Pro A | V1.0.4 | Marlin | unknown | Yes - *with mod*: <br> [Solder R65 to R66](https://klipper.discourse.group/t/support-for-hdsc-chips-hc32f460/2860/54) *or* use [catboat](https://github.com/printers-for-people/catboat)! |
| Trigorilla Pro B | V1.0.2 | Marlin | unknown | [Yes](https://github.com/1coderookie/Klipper4Kobra2series/tree/main/Kobra2) - w/o mod |
| Trigorilla Spe A | V1.0.0 | KobraOS | No | No |
| Trigorilla Spe B | V1.0.4 <br> V1.0.5 | KobraOS | Yes: [Rinkhals](https://github.com/jbatonnet/Rinkhals) | unknown | 
| Trigorilla Spe B | V1.1.3 |KobraOS | Yes: [Rinkhals](https://github.com/jbatonnet/Rinkhals) | unknown | 


---

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  

