# Anycubic Trigorilla Boards
Here I'll give an overview about (some) Trigorilla mainboards that Anycubic used in their 3D FDM printers.  


## Printer Models 

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

All mainboards run on 24V DC and all mainboards have the stepper drivers soldered onto them. 


| Board Label | Version | MCU | Stepper Drivers | 
|:-----------:|:-------:|:---:|:---------------:|
| Trigorilla Gen | V3.0.6 <br> V3.0.7 |  HC32F460 | TMC2208 <br> GC6609 | 
| Trigorilla Gen | V4.0.1 | GD32F303 | TMC2208 <br> GC6609 | 
| Trigorilla Pro A | V1.0.4 | HC32F460 | TMC2208 <br> GC6609 | 
| Trigorilla Pro B | V1.0.2 | HC32F460 | TMC2208 <br> GC6609 | 
| Trigorilla Spe A | V1.0.0 | ARM Cortex-A7 | TMC2209 | 
| Trigorilla Spe B | V1.0.4 <br> V1.0.5 | HC32F460 | TMC2209 | 
| Trigorilla Spe B | V1.1.3 | HC32F460 | TMC2209 |

---

## Firmware

| Board Label | Version | Stock Firmware | Stock FW Mods | Klipper |
|:-----------:|:-------:|:--------------:|:-------:|:-------------:|
| Trigorilla Gen | V3.0.6 <br> V3.0.7 | Marlin | [Yes](https://1coderookie.github.io/KobraGoNeoInsights/firmware/fw_marlin/#mods) | [Yes](https://github.com/1coderookie/Klipper4KobraGoNeo) - w/o mod |
| Trigorilla Gen | V4.0.1 | Marlin | [Yes](https://1coderookie.github.io/Kobra2NeoInsights/firmware/fw_marlin/#mods) | [Yes](https://github.com/1coderookie/Klipper4Kobra2series/tree/main/Kobra2Neo) - w/o mod |  
| Trigorilla Pro A | V1.0.4 | Marlin | unknown | Yes - *with mod*: <br> Solder R65 to R66 *or* use [catboat](https://github.com/printers-for-people/catboat)! |
| Trigorilla Pro B | V1.0.2 | Marlin | unknown | [Yes](https://github.com/1coderookie/Klipper4Kobra2series/tree/main/Kobra2) - w/o mod |
| Trigorilla Spe A | V1.0.0 | KobraOS | No | No |
| Trigorilla Spe B | V1.0.4 <br> V1.0.5 | KobraOS | Yes: [Rinkhals](https://github.com/jbatonnet/Rinkhals) | unknown | 
| Trigorilla Spe B | V1.1.3 |KobraOS | Yes: [Rinkhals](https://github.com/jbatonnet/Rinkhals) | unknown | 

