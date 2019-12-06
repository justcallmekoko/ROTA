# ROTA
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/rota.PNG?raw=true" width="450"></p>
<p align="center">
  <b>A WiFi enabled Xbox One rapid-fire mod</b>
  <br>
</p>

# Table of Constants
- [About](#about)
  - [YouTube](#youtube)
- [Installation](#installation)
- [Usage](#usage)
  - [First Use](#first-use)
  - [Configuring Rapidfire](#configuring-rapidfire)
  - [Recovering Forgotten Password](#recovering-forgotten-password)
- [Updating Firmware](#updating-firmware)
  
# About
ROTA is a WiFi enabled rapidfire modification designed to function with the Xbox One controller. Rather than pressing a combination of buttons to change modes and rates of fire with no GUI, the user can configure ROTA's rapidfire settings over WiFi via web app. Installation is simple and there are no extra buttons required. While this modification works properly in all version of the Xbox One controller, this repo will discuss ROTA's installation and functionality with the Xbox One S controller.

## YouTube

# Installation
**1.** Remove the two plastic grip covers, battery cover, and battery

**2.** Remove the five outer screws that hold the case together

<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/IMG_0155.jpg?raw=true" width="450"></p>

<p align="center"><i>Figure 1</i></p>

**3.** Flip the controller onto its front and remove the back panel
 
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/IMG_0156.JPG?raw=true" width="450"></p>

<p align="center"><i>Figure 2</i></p>

**4.** Remove the two screws that hold the upper and lower boards together shown in <b><i>Figures 3 and 4</b></i>

<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/IMG_0160.jpg?raw=true" width="450"></p>

<p align="center"><i>Figure 3</i></p>

<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/IMG_0162.jpg?raw=true" width="450"></p>

<p align="center"><i>Figure 4</i></p>


**5.** Disconnect the pigtail cable from the upper board shown in <b><i>Figure 5</b></i>

<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/IMG_0157.jpg?raw=true" width="450"></p>
<p align="center"><i>Figure 5</i></p>

**6.** Disconnect the upper board from the lower board. Be careful not to lose the headphone jack

**7.** Using hot glue, fix ROTA to the controller's upper board as shown in <b><i>Figure 2</b></i>

**8.** Solder the six connections shown in <b><i>Figures 6-14</b></i>

**9.** Press-fit the upper and lower boards back together

**10.** Reconnect the pigtail cable to the upper board from <b><i>Figure 5</b></i> 

**11.** Secure the upper and lower boards with the two smaller screws from <b><i>Figures 3 and 4</b></i>

**12.** Close the controller case with the back panel and the five larger screws from <b><i>Figure 1</b></i>

**13.** Snap the two plastic grip covers, battery, and battery cover back into place

<p align="center"><i>Figure 6-14</i></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/segment_1.jpg?raw=true" width="450"></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/segment_2.jpg?raw=true" width="450"></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/segment_3.jpg?raw=true" width="450"></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/VCC2.jpg?raw=true" width="450"></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/GND2.jpg?raw=true" width="450"></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/RT2.jpg?raw=true" width="450"></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/LT2.jpg?raw=true" width="450"></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/SYN2.jpg?raw=true" width="450"></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/Edited/LED2.jpg?raw=true" width="450"></p>

# Usage

## First Use

## Configuring Rapidfire

## Recovering Forgotten Passwords
If you have forgotten the web page password, admin password, or access point password, you can double tap the controller sync button within the first five seconds of powering your controller on which will cause ROTA to apply it's default credential settings. You can then use the default credentials to connect to the ROTA access point and reconfigure it to your personal settings.

# Updating Firmware
ROTA comes with an automatic update feature. If this feature is enabled in your configuration settings and ROTA is connected to a network with internet connectivity, it will attempt to download and install the latest firmware release from this repo. If this feature is disabled in your configuration settings, you will need to follow these steps to update the ROTA firmware.

**1.** Download the [latest release](https://github.com/justcallmekoko/ROTA/releases/latest) of the ROTA firmware

**2.** Navigate to the firmware update page on ROTA
  - `http://192.168.4.1/update` if you are on the ROTA access point
  - `[domain name].local/update` if ROTA is connected to your local network
**3.** `browse` for the firmware .bin file you downloaded

**4.** Click `update`

ROTA will install the new update and automatically restart.
