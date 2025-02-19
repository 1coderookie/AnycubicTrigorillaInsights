<link rel=”manifest” href=”docs/manifest.webmanifest”>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  

---  

# Type "Gen"


---

## Mainboards And Respective Printer Models 

The following table gives an overview about the printer models where the specific mainboards have been used.  
If there's an Insights page I created about the specific model, I linked to it.   

| Board Label | Version | Printer |
|:-----------:|:-------:|:-------:|
| Trigorilla Gen | V3.0.6 <br> V3.0.7 | [Kobra Go](https://1coderookie.github.io/KobraGoNeoInsights/hardware/mainboard/#trigorilla-v_306-stock) <br> [Kobra Neo](https://1coderookie.github.io/KobraGoNeoInsights/hardware/mainboard/#trigorilla-v_306-stock) |
| Trigorilla Gen | V4.0.1 | [Kobra 2 Neo](https://1coderookie.github.io/Kobra2NeoInsights/hardware/mainboard/#trigorilla-v_401-stock) | 

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

---

## Firmware

The following table gives an overview about the firmware the boards are running as well as alternative firmware compatibility.  


| Board Label | Version | Stock Firmware | Stock FW Mods | Klipper |
|:-----------:|:-------:|:--------------:|:-------:|:-------------:|
| Trigorilla Gen | V3.0.6 <br> V3.0.7 | Marlin | [Yes](https://1coderookie.github.io/KobraGoNeoInsights/firmware/fw_marlin/#mods) | [Yes](https://github.com/1coderookie/Klipper4KobraGoNeo) - w/o mod |
| Trigorilla Gen | V4.0.1 | Marlin | [Yes](https://1coderookie.github.io/Kobra2NeoInsights/firmware/fw_marlin/#mods) | [Yes](https://github.com/1coderookie/Klipper4Kobra2series/tree/main/Kobra2Neo) - w/o mod |  


---

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/U6U5NPB51)  
 
