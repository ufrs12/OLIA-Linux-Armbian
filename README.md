# OLIA Linux Armbian

<p align="center">
 <img width="250px" src="sources/img/logo/OLIA-Linux.png" alt="qr"/>
</p>


Images based on Armbian Linux for [OLIA](https://github.com/ufrs12/OLIA) and [OLxA](https://github.com/ufrs12/OLxA).  

Building images is carried out in [OLIA-Linux-Armbian-builder](https://github.com/ufrs12/OLIA-Linux-Armbian-builder).

stack.md  - A stack of software that can be included in the image.  
boards.md - List of boards for which development is underway.

# Getting started

## 1. Getting the image

There are two ways to get the image:
* Build with [OLIA Linux Armbian builder](https://github.com/ufrs12/OLIA-Linux-Armbian-builder)
* Download from my [site](https://osjob.ru/) (Currently unavailable)  

## 2. Сreate a bootable sd-card

### From Windows

* I usually use the [Rufus](https://rufus.ie) (not available now).
* But I can also recommend the [balenaEtcher](https://etcher.balena.io/)

### From Linux with GUI

* I use the [balenaEtcher](https://etcher.balena.io/)

### From Linux without GUI

* If you work without a GUI, then I'm sure you know better than me how to do this)))

## 3. Install

### Orange Pi 3 LTS

* Apply power to the board. The SD card should not be in the board.
* If the board starts, turn it off with a button or other means.
* Insert the SD card. 
* Long press the power button. About 5 seconds after the red LED lights up, you can release the button.
* Wait 2-5 minutes. Installation completed.

## 4. Settings

### Orange Pi 3 LTS
* Connect SSH 192.168.1.2:22, root/1234

#### Zabbix-agent
* Open for edit file etc/zabbix/zabbix-agentd.conf
* Add the IP address of the Zabbix-server to the "Server" and "ServerActive" parameters, separated by commas. In my case 192.168.1.1.
* Restart Zabbix-agent  
`systemctl restart zabbix-agent`  


