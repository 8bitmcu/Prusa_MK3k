# Prusa MK3k

Prusa MK3k - My conversion of a Prusa MK3s+ clone to Klipper.

I've been running this [Fysetc Prusa MK3s+ clone](https://s.click.aliexpress.com/e/_oB2yb0x) for a few years now. I've always been tinkering with it from the beginning. Here is how it stands now with mods and upgrades.

![slicer](assets/slicer.png)


# Installing Klipper

I've followed [charminULTRA's Klipper guide](https://github.com/charminULTRA/Klipper-Input-Shaping-MK3S-Upgrade) to get going initially. Recently I've pulled some changes from [project802's updated guide](https://github.com/project802/Klipper-Input-Shaping-MK3S-Upgrade)


# Additional Mods and Upgrades

### ~~Nylock~~ Silicone Bed Level Mod

I followed this [Silicone Bed Level Mod](https://www.schweinert.com/silicone-bed-level-mod-prusa-mk3/) guide. I'm using these [silicone tubes](https://s.click.aliexpress.com/e/_oCNcppl) with good success. I'm sure these [bed leving columns](https://s.click.aliexpress.com/e/_olThvdz) would work too if cut to length.

### Raspberry Pi 4 and 5" Touch Screen

Before Klipper, I was very happy with OctoPrint which ran great on a Pi4. Klipper does requires a [Raspberry Pi](https://s.click.aliexpress.com/e/_on8JnaX). Another alternative would be this [BTT Pi 2](https://s.click.aliexpress.com/e/_oEV29sb) which can be powered from screw terminals. I've used various displays and finally settled on this [5" MIPI Display](https://s.click.aliexpress.com/e/_onpiPqB) with a [longer DSI cable](https://s.click.aliexpress.com/e/_oB68LnZ). 5-7" seems like a good sweet spot in screen sizes for klipperscreen.

### Meanwell LRS-350-24 350w Power Supply

The power supply on my machine crapped out pretty early after installing Klipper. Likely unrelated, but I decided to upgrade to a bigger [Meanwell 350w](https://s.click.aliexpress.com/e/_oExWxLh) unit just in case. The 350w power supply now powers the Pi4, LED lights and my MMU.

### KMMP Power-off Module

This [Melllow Fly KMMP](https://s.click.aliexpress.com/e/_oBRjS79) module converts the 24v into 5v that the Pi needs and also doubles a safety power down for the raspberry pi.

### TZ 2.0 v6-style hotend

Rated at twice the flow rate of a normal v6 hotend, I opted to try out this [TZ 2.0 V6 hotend](https://s.click.aliexpress.com/e/_oofLEeJ).

### MK4 0.9 degree steppers

As per Prusa, the [MK4 steppers](https://s.click.aliexpress.com/e/_ok2TuVv) should reduce VFA's, altough I haven't really tested that.

### ERCF v2 MMU

I went with the [Fysetc ERCF v2 12-channel kit](https://s.click.aliexpress.com/e/_opTF3ZV) and the [Seleadlab Filament Cutter](https://s.click.aliexpress.com/e/_okhysFz) kit. But I never took the time to get the MMU fully configured and running smoothly.

### Input Shaping module

I'm a big fan of any RP2040 based mcu for klipper because of how easy they are to flash. I'm using this [BTT S2DW](https://s.click.aliexpress.com/e/_okpRPtH) which claims to be more accurate than an ADXL345, although I'm sure both would work great.

### LED Light bar

I'm using a similar kit to this [MK4 Dual LED Light Bar 24v](https://s.click.aliexpress.com/e/_opsoeDh) kit.

### Filament Storage

I'm using these [vacuum seal bags](https://s.click.aliexpress.com/e/_ooiCgQT) and the included automatic pump

### Filament drying and MMU bays

I'm running 3 [Sovol SH01](https://s.click.aliexpress.com/e/_oFkCFo7) units for general drying and two [Prusa drybox enclosure](https://s.click.aliexpress.com/e/_oBO5Jmf) connected to my MMU.

### Build plates

Out of my collection of 20+ build plates, my favorite is this [JUUPINE PEI Sheet](https://s.click.aliexpress.com/e/_oEQbZIX). 
