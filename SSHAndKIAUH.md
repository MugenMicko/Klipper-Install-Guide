#SSH

For SSH, I recommend a wonderful little free program called PuTTy

https://www.putty.org/

Download the version you need for your computer and install it. It's all good, I will wait! :)
Done? Awesome!! Lets fire PuTTy up!!
Create a new connection and pop the IP address for your Raspberry Pi in.
It will do its connection thing and ask your for your username and password, which if you followed the previous page should be 'pi' and 'raspberry'.
The first command we are going to enter is to check for updates on the Raspberry Pi OS
```
sudo apt update
```
The second command is to actually grab the updates
```
sudo apt upgrade
```
Now we are going to install the Git Software
```
sudo apt install git
```
Follow the bouncing ball and you should be now able to pull stuff from Github!! Yaaay!!!

For the next step, we are going to install this amazing script called KIAUH.  KIAUH is Klipper Installer And Update Helper.  It makes it really easy to installer Klipper, Moonraker, the interface you want to use like Mainsail or Fluidd, etc Written by a champ that goes by @th33xitus! You can have a peep at his Github page 
at https://github.com/th33xitus/kiauh

To do that we run the command below
```
cd ~
git clone https://github.com/th33xitus/kiauh.git
./kiauh/kiauh.sh
```
Once git has done its thing and downloaded the script (it doesn't take long) it will show a nice little ascii menu.
For starters you want to install Klipper (When given the option, choose Python 2.7)
Then you want to install Moonraker
Now you take your pick between Mainsail and Fluidd (Personal preference here is Mainsail, however they are very similiar, you do what you want champ!)
Now this is where we get to the point that you need to decide what webcam platform you want to use, it will give you the option to run MPGStreamer, or alternatively you can use the system I prefer called [Crowsnest](https://github.com/mainsail-crew/crowsnest).
If you want to run MPGStreamer, let KIAUH install it, if you want to run Crowsnest, don't install MPGStreamer
Now we go back a select the update option and it will show you the current version of software installed and the current version.  I go through each individually and update them including the system to prevent any conflicts
Once this is done, exit out
At the prompt, type ```sudo shutdown -r now```
