---
layout: single
permalink: /devices/meters/
title: "Meters"
excerpt: "Omega, Center,.."
header:
  overlay_image: /assets/images/meters-logo.jpg
  image: /assets/images/meters-logo.jpg
  teaser: assets/images/meters-logo.jpg
toc: true
toc_label: "On this page"
toc_icon: "cog"
---
Artisan implements the communication protocols of a number of handheld meters that can operate autonomous, run on their own power source (battery or power-plug), come with a display and feature a serial interface to communicate with an external software.

Some of these devices come with an internal serial-2-USB interface, while others require an external serial-2-USB interface.

Any of these meters require a serial device driver installed that allows the computer to communicate with the serial-2-USB chip implemented by the hardware interface. Most common are

+ [VCP from FTDI](http://www.ftdichip.com/Drivers/VCP.htm)
+ [CP210x from Silicon Labs](http://www.silabs.com/products/mcu/Pages/USBtoUARTBridgeVCPDrivers.aspx)
+ [PL2303 from Prolific](http://prolificusa.com/pl-2303hx-drivers/)

**Watch out!** The FTDI driver is preinstalled on virtually all Linux distributions as well as all OS X versions supported by Artisan. Installing an additional FTDI driver on those operating system might lead to instabilities!
{: .notice--primary}

## Temperature Meters

### Single Channel

The single temperature meters listed above are rather simple and cost-efficient. If it is only the BT curve you are interested and don't want to spent too much money they are a good option. Note that the CENTER 300 is also on the market under the label VOLTCRAFT K201 and 300K with minor differences.

* [CENTER 300](http://www.centertek.com/products_con.aspx?cid=C_00000011&cpid=C_00000002&pid=P_00000033&pn=proT) / VOLTCRAFT K201 / VOLTCRAFT 300K
  - Single K-Type
  - RS232 Interface (9600-8N1)
  - 9V Battery only
  - Software optional
* [CENTER 302](http://www.centertek.com/products_con.aspx?cid=C_00000011&cpid=C_00000002&pid=P_00000035&pn=proT)
  - Single K/J-Type
  - RS232 Interface (9600-8N1)
  - 9V Battery only
  - Software optional
* [CENTER 305](http://www.centertek.com/products_con.aspx?cid=C_00000011&cpid=C_00000002&pid=P_00000038&pn=proT)
  - Single K-Type
  - RS232 Interface (9600-8N1), cable included
  - 9V Battery only
  - Software included
* [Apollo I DT301](http://www.ueitest.com/products/temperature-humidity/dt301) (discontinued)
  - Single K/J-Type
  - Built in USB to serial converter (9600-8N1)

### Dual Channel

The dual temperature meters are perfect for the standard use of Artisan to log the BT and ET temperature curves. If your probe is a K-Type, which is the standard for measuring BT/ET in a coffee roaster, you can choose from any of the above meters. The Amprobe is especially interesting due to its competitive price tag (see [this post](http://artisan-roasterscope.blogspot.de/2013/06/artisan-monitoring-londinium.html) to learn how the Amprobe and Artisan helped to investigate the Londinium group temperature stability). The Omega HH506RA (or its EXTECH variant) is interesting for its optical-isolated serial2USB converter. However, this converter is an add-one that has to be purchased separately and the fixed serial speed of that device is quite low (although it works well with Artisan). All of the devices listed here exclusively run from battery, but for the last one which does not need any external power but for the USB connection

* [CENTER 301](http://www.centertek.com/products_con.aspx?cid=C_00000011&cpid=C_00000002&pid=P_00000034&pn=proT)
  - Dual K-Type
  - RS232 Interface (9600-8N1)
  - 9V Battery only
  - Software optional
* [CENTER 303](http://www.centertek.com/products_con.aspx?cid=C_00000011&cpid=C_00000002&pid=P_00000036&pn=proT) / VOLTCRAFT 302KJ / VOLTCRAFT KJ202
  - Dual K/J-Type
  - RS232 Interface (9600-8N1)
  - 9V Battery only
  - Software optional
* [CENTER 306](http://www.centertek.com/products_con.aspx?cid=C_00000011&cpid=C_00000002&pid=P_00000039&pn=proT) / VOLTCRAFT K202
  - Dual K-Type
  - RS232 Interface (9600-8N1), cable included
  - 9V Battery only
  - Internal memory
  - Software included
* [Omega HH506RA](http://www.omega.com/pptst/HH506A_HH506RA.html) / [EXTECH 421509](http://www.extech.com/instruments/product.asp?catid=64&prodid=410)
  - Dual K/J/T/E/R/S/N-Type
  - RS232 Interface (2400-7E1)
  - Internal memory
  - 9V Battery only
  - Optional optical-isolated serial2USB converter
* [Amprobe TMD-56](http://www.amprobe.com/amprobe/usen/HVAC-Tools/Thermocouple-Thermometers/TMD-56.htm) / [Omega HH806AU](http://www.omega.com/ppt/pptsc.asp?ref=hh806) / [Mastech MS6514](http://www.mastech-group.com/products.php?PNo=89)
  - Dual K/J/T/E/R/S/N-Type
  - Built in USB to serial converter (19200-8E1)
  - Internal memory
  - 4 x 1.5V AAA Batteries or external power
* [Omega HH802U](http://www.omega.com/pptst/HH802_803.html)
  - Dual K/J-Type
  - Built in USB to serial converter (19200-8E1)
  - 4 x 1.5V AAA Batteries or external power

 
### Four Channel

Those 4 channel meters in the list below are all basically identical. Just that the CENTER 304 (and one of the two VOLTCRAFT K204, no typo here!, does not include any data logging capability. However, that does not matter for its use with Artisan. Therefore, selecting the CENTER 304 over the CENTER309 makes sense as it is usually the cheaper device (so take care, there are two different devices labeled VOLTCRAFT K204, but they can easily be distinguished by price). 

* [CENTER 304](http://www.centertek.com/products_con.aspx?cid=C_00000011&cpid=C_00000002&pid=P_00000037&pn=proT) / VOLTCRAFT K204
  - Four K-Type
  - RS232 Interface (9600-8N1)
  - Software optional
  - 9V Battery or external power
* [CENTER 309](http://www.centertek.com/products_con.aspx?cid=C_00000011&cpid=C_00000002&pid=P_00000042&pn) / VOLTCRAFT K204 / [Omega HH309](http://www.omega.com/pptst/HH309.html) / [General Tools DT309DL](http://www.tequipment.net/GeneralDT309DL.html)
  - Four K-Type
  - RS232 Interface (9600-8N1)
  - Internal memory
  - Software included
  - 9V Battery or external power

## Multi Meters

Multi-meters allow to read different types of sensors by measuring a voltage or current input. Artisan supports two devices that feature a communication interface. The TE VA18B also supports one temperature channel connecting to a K-Type probe.

* [Omega HHM28](http://www.omega.com/pptst/HHM10_20_30.html)
  - AC/DC volts and current
  - RS232 Interface (2400-8N1)
  - 9V Battery only
* [TE VA18B](http://www.mastech.com.cn/html/en/products-va18b.htm)
  - single K-Type
  - AC/DC volts and current
  - optical-isolated USB Interface (2400-8N1)
  - 9V Battery only


## Others

* [Extech 755](http://www.extech.com/display/?id=14489) 
  - Differential Pressure Manometer (0.5psi)
  - USB Interface
  - 9V battery only