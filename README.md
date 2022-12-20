# Klipper-Install-Guide
Micko's Guide to Installing Klipper on to a Raspberry Pi

What you will need:
  - A Raspberry Pi
  - A computer
  - A SD Card for the Pi (Preferably a Class 10 A1, A2 or A3 Card of 16Gb or bigger)
  - A SD Card Reader
  - An internet connection that can be used for the computer and the Raspberry Pi
  
 On the computer, browse to https://www.raspberrypi.com/software/ and download the latest version of Raspberry Pi Imager and install it
 Once installed, put your SD Card in your SD Card Reader and connect it to your computer.
 Open the Raspberry Pi Imager app and select 64 bit RasPi OS Lite from the options
 Next Click on the the Gear Icon and set the settings as:
 
    Username: pi
    Password: raspberry
    Enable SSH
    Your WiFi network name in SSID
    Your WiFi password
    Your WiFi location (Helps your Pi WiFi function on the right channels for your router)
    Your Language
    Your Time Zone  (So you get the right times in Klipper)
 
 Click Save and then Click Write Image
 Once this is complete, click on the eject usb and eject the card safely
 Insert the SD Card into your Pi, Plug it in to the power and turn it on! (I always find a little smooth talking helps turn things on!)
 
 Huzzah!! Your Pi should be all aroused and its little lights twinkling!!
 Now, regardless of if you are using WiFi or Ethernet cable, you need to find out what its IP address is, but this isn't the guide for that, I would suggest googling a how to on that, and then we can move on to using SSH to connect to your Pi

(SSH and KIAUH) [Next Page]([https://www.putty.org/](https://github.com/MugenMicko/Klipper-Install-Guide/blob/main/SSHAndKIAUH.md))
