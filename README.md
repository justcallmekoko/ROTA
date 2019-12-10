# ROTA
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/rota.PNG?raw=true" width="450"></p>
<p align="center">
  <b>A WiFi enabled Xbox One rapid-fire mod</b>
  <br><br>
  <a href="https://www.tindie.com/stores/justcallmekoko/rota-controller-mod/? ref=offsite_badges&utm_source=sellers_justcallmekoko&utm_medium=badges&utm_campaign=badge_large"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-larges.png" alt="I sell on Tindie" width="200" height="104"></a>
</p>

# Table of Constants
- [About](#about)
  - [YouTube](#youtube)
- [Installation](#installation)
- [Usage](#usage)
  - [First Use](#first-use)
    - [Default Username and Password Settings](#default-username-and-password-settings)
  - [Configuring Rapidfire](#configuring-rapidfire)
  - [Recovering Forgotten Password](#recovering-forgotten-password)
- [Updating Firmware](#updating-firmware)
- [FAQ](#faq)
  
# About
ROTA is a WiFi enabled rapidfire modification designed to function with the Xbox One controller. Rather than pressing a combination of buttons to change modes and rates of fire with no GUI, the user can configure ROTA's rapidfire settings over WiFi via web app. Installation is simple and there are no extra buttons required. While this modification works properly in all version of the Xbox One controller, this repo will discuss ROTA's installation and functionality with the Xbox One S controller.

## YouTube

# Installation
_The following instructions assume you already own and are proficient with a soldering iron, solder, and hot glue gun._

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
First Use Instructions

##### _Default Username and Password Settings_

| Field                    | Value                |
| ------------------------ | -------------------- |
| Admin Username           | ROTA                 |
| Admin Password           | ROTA                 |
| WiFi Connection SSID     | ROTA                 |
| WiFi Connection Password | ROTA                 |
| Access Point SSID        | ROTA                 |
| Access Point Password    | ROTA12345678         |
| mDNS Domain Name         | rota-rapidfire.local |

**1.** Power the controller on. The controller light should blink ten times to indicate ROTA has configured its WiFi access point

**2.** Connect to the **ROTA** WiFi access point using the default password **ROTA12345678**

<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/WebAppEdited/rota_ap_edited.png?raw=true" width="450"></p>
 
**3.** In your web browser, navigate to [http://192.168.4.1](google.com)

**4.** When prompted for credentials, enter **ROTA** for the Username and Password

<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/WebAppEdited/username_passw_cropped.png?raw=true" width="450"></p>
 
**5.** On the **Home** page, click **Settings** to configure your personal admin settings for ROTA

<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/WebAppEdited/main_page_settings_button.png?raw=true" width="450"></p>
 
**6.** Using the settings page, you can configure your personal usage settings for ROTA. 

**Note:** To save any changes made, you must click **Apply**. For changes to take effect, you must click **Restart**

<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/WebAppEdited/admin_settings.png?raw=true" width="450"></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/WebAppEdited/wifi_connection_settings.png?raw=true" width="500"></p>
<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/WebAppEdited/access_point_settings.png?raw=true" width="600"></p>
   
**Note:** If ROTA is configured to connect to your home network, you will need to use the URL shown under **mDNS Settings** to access ROTA from your web browser shown here

<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/WebAppEdited/mdns_settings_3.png?raw=true" width="750"></p>
 
**7.** Use the **Home** page to adjust fire rate and mode of the mod and use the controller sync button to toggle the mod on and off

**Note: If you have forgotten any usernames or passwords, you can force ROTA to apply its default factory settings by double pressing the controller sync button within the first five seconds of the controller powering on. Refer to [this](#recovering-forgotten-passwords)**



## Configuring Rapidfire
The mode and fire rate for the mod are configured using the main page of ROTA's web application.
The mod can be toggled on and off using the Xbox controller's Sync button.

| Setting                 | Description                                               | Type         |
| ----------------------- | --------------------------------------------------------- | :----------: |
| Full Auto Right Trigger | Only the right trigger will fire fully automatic          | Radio Button |
| Full Auto Akimbo        | Both the left and right trigger will fire fully automatic | Radio Button |
| Rounds Per Minute       | The rate at which the rounds are fired                    | Integer      |

After adjusting the rapidfire settings to your preferred configuration, you need to click **Apply** for the changes to take effect

<p align="center"><img alt="Marauder logo" src="https://github.com/justcallmekoko/ROTA/blob/master/Images/WebAppEdited/main_page_edited.png?raw=true"></p>

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

# FAQ
