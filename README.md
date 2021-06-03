# Cheap LoRa Messanger

In this project you can assemble a cheap LoRa connection to your smartphone, and be able to transmit to all surrounding phones also using this project.



## still under work will be finish till 30.7.21

hi thank you for looking in my github :)

we will send a massge from a phone to anthor phone using lora conncted with bluetooth to the esp32 "wifi lora 32"

# The Hardware Needed: 


1) Antena * 2 + esp32 with built in bluetooth * 2
2) Android Smartphones * 2
3) Cables (OTG) * 2
4) Power source for esp32 (Battery, Computer, Phone) * 2


## esp32 + Antena

The Devices should all be configured to communicate on the same frequancy. In our project we used frequancy 433Mhz.

<p align="center">
  <img width="320" height="300" src="/images/esp32front.jpeg">
  <img width="320" height="300" src="/images/esp32back.jpeg">
</p>
esp32 can be bought here: https://heltec.org/project/wifi-lora-32/

## Smartphones
 2 Smartphone operating android system

we used A70 sumsung and s20+ sumsung
<p align="center">
  <img width="320" height="300" src="/images/phones&esp32.jpeg">
</p>

This Project will work on android Smartphones that have BlueTooth.


## Cables

we used 2 micro usb to usb to connect the esp32 to the computer and  the power supply

<p align="center">
  <img width="320" height="300" src="/images/cable.jpeg">
</p>

## Power source for esp32

we used 2 power bank to give power to the esp32

you can use other methed like connect to the computer or to the smartphone

<p align="center">
  <img width="320" height="300" src="/images/power_front.jpeg">
</p>

# The Software Needed: 


1) Android Terminal App 
2) Arduino IDE
3) The .ino files in this repository



## Android Terminal App 
  the app "Serial Bluetooth Teminal"
you cab download it from here: https://play.google.com/store/apps/details?id=de.kai_morich.serial_bluetooth_terminal&hl=en_US&gl=US

or look in the phone in google play: "Serial Bluetooth Teminal"
<p align="center">
  <img width="320" height="300" src="/images/app.jpeg">
</p>

## Arduino IDE
 a computer with ardouino IDE to put the code on the esp32 
 you can download it from here: https://www.arduino.cc/en/software
 <p align="center">
  <img width="320" height="300" src="/images/ArduinoLogo.png">
</p>


## The .ino files in this repository
import then to your comupter and upload them to the devices.


# Step by Step Walkthrough

1) Install app on Smartphone
2) Install Arduino IDE
3) import Additional Boards Manager URLs
4) Insall Board from Board Manager
5) Include Libraries from Manage Library
6) Import and open files from this repository
7) Edit the file to your needs
8) Compile and upload to esp32
9) Pair Smartphone to esp32 via Bluetooth
10) Open App and Connect to esp32

## Install app on Smartphone

Open Play Store on your Smartphone, Search for "Serial Bluetooth Terminal", and install.

<p align="center">
  <img width="320" height="300" src="/images/install_app.jpeg">
</p>

Other Apps may work, we used this one.

### Install Arduino IDE

Open https://www.arduino.cc/en/software , select and click on your operating system, this will lead you to the following page:

<p align="center">
  <img width="320" height="300" src="/images/ide_donating.PNG">
</p>

You can donate, or click just download.
Then you can agree to all.
If any problems occur, you can follow: https://www.circuitbasics.com/arduino-basics-installing-software/

### import Additional Boards Manager URLs


### Insall Board from Board Manager
### Include Libraries from Manage Library
### Import and open files from this repository
### Edit the file to your needs
### Compile and upload to esp32
### Pair Smartphone to esp32 via Bluetooth
### Open App and Connect to esp32
