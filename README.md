# Anycubic Trigorilla Boards
Here I'll give an overview about (some) Trigorilla mainboards that Anycubic used in their 3D FDM printers.  

All mainboards run on 24V DC and all mainboards have the stepper drivers soldered onto them. 


| Board Label | Version | Printer | MCU | Stepper Drivers | Stock Firmware | Stock FW Mods | Klipper |
|:-----------:|:-------:|:-------:|:---:|:---------------:|:--------------:|:-------:|:-------------:|
| Trigorilla Gen | V3.0.6 <br> V3.0.7 | [Kobra Go](https://1coderookie.github.io/KobraGoNeoInsights/hardware/mainboard/#trigorilla-v_306-stock) <br> [Kobra Neo](https://1coderookie.github.io/KobraGoNeoInsights/hardware/mainboard/#trigorilla-v_306-stock) | HC32F460 | TMC2208 <br> GC6609 | Marlin | [YES](https://1coderookie.github.io/KobraGoNeoInsights/firmware/fw_marlin/#mods) | [YES](https://github.com/1coderookie/Klipper4KobraGoNeo) - w/o mods |
| Trigorilla Gen | V4.0.1 | [Kobra 2 Neo](https://1coderookie.github.io/Kobra2NeoInsights/hardware/mainboard/#trigorilla-v_401-stock) | GD32F303 | TMC2208 <br> GC6609 | Marlin || [YES](https://1coderookie.github.io/Kobra2NeoInsights/firmware/fw_marlin/#mods) | [YES](https://github.com/1coderookie/Klipper4Kobra2series/tree/main/Kobra2Neo) - w/o mod |  
| Trigorilla Pro A | V1.0.4 | Kobra <br> Kobra Plus <br> Kobra Max <br> Vyper | HC32F460 | TMC2208 <br> GC6609 | Marlin | unknown | yes - with mod: <br> Solder R65 to R66 or use [catboat](https://github.com/printers-for-people/catboat)! |
| Trigorilla Pro B | V1.0.2 | [Kobra 2](https://1coderookie.github.io/Kobra2Insights/hardware/mainboard/#trigorilla-pro-b-v_102-stock) | HC32F460 | TMC2208 <br> GC6609 | Marlin | unknown | [YES](https://github.com/1coderookie/Klipper4Kobra2series/tree/main/Kobra2) - w/o mod |
| Trigorilla Spe A | V1.0.0 | [Kobra 2 Pro](https://1coderookie.github.io/Kobra2ProInsights/hardware/mainboard/#trigorilla_spe_a_v100-stock) <br> [Kobra 2 Plus](https://1coderookie.github.io/Kobra2PlusInsights/hardware/mainboard/#trigorilla_spe_a_v100-stock) <br> [Kobra 2 Max](https://1coderookie.github.io/Kobra2MaxInsights/hardware/mainboard/#trigorilla_spe_a_v100-stock) | ARM Cortex-A7 | TMC2209 | KobraOS | NO | NO |
| Trigorilla Spe B | V1.0.4 <br> V1.0.5 | [Kobra 2 Pro](https://1coderookie.github.io/Kobra2ProInsights/hardware/mainboard/#trigorilla_spe_b_v10x-stock-new-revision) | HC32F460 | TMC2209 | KobraOS | [YES](https://github.com/jbatonnet/Rinkhals) | unknown | 
| Trigorilla Spe B | V1.1.3 | Kobra 3 | HC32F460 | TMC2209 | KobraOS | [YES](https://github.com/jbatonnet/Rinkhals) | unknown | 
