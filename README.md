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
Import then to your comupter and upload them to the devices.


# Step by Step Walkthrough

1) Install app on Smartphone
2) Install Arduino IDE
3) import Additional Boards Manager URLs
4) Insall Board from Board Manager
5) Import and open files from this repository
6) Include Libraries from Manage Library
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

First we will need to get the URL for installing the Board.
Click file -> Preferences

<p align="center">
  <img width="320" height="300" src="/images/preference.jpeg">
</p>

Now the following will open, click the edit URLs and add the following link to it.

<p align="center">
  <img width="320" height="300" src="/images/board_import.PNG">
</p>

click OK, and OK.

<p align="center">
  <img width="320" height="300" src="/images/ok_ok.PNG">
</p>

### Insall Board from Board Manager

Now we will need to install the Board.
Click Tools -> Boards -> Boards Manager

<p align="center">
  <img width="320" height="300" src="/images/board.jpeg">
</p>

Search for "esp32"

<p align="center">
  <img width="320" height="300" src="/images/install_board.PNG">
</p>

Click install (it may take a few minutes to download)

Now we need to choose that board.
Click Tools -> Board -> ESP32 Arduino -> Heltec WiFi LoRa 32 (scroll down)

<p align="center">
  <img width="320" height="300" src="/images/wifi_lora.jpeg">
</p>

### Import and open files from this repository

Download the .ino file, open it via the Arduino IDE.

### Include Libraries from Manage Library

Click Sketch -> Include Library -> Manage Libraries

<p align="center">
  <img width="320" height="300" src="/images/import_library.jpeg">
</p>

The following will open and search for "lora sandeep" and install
Then search for "ssd1306" (scroll down) and install

<p align="center">
  <img width="320" height="300" src="/images/sandeep.PNG">
  <img width="320" height="300" src="/images/ssd1306.PNG">
</p>




### Edit the file to your needs

will come later


### Compile and upload to esp32
Click verify to make sure the code compiles:

<p align="center">
  <img width="320" height="300" src="/images/verify.PNG">
</p>

#### Make sure your device is connected!!!

<p align="center">
  <img width="320" height="300" src="/images/plug_esp32.jpeg">
</p>

The port may alter from computer to computer!

Now Upload

### Pair Smartphone to esp32 via Bluetooth

With Smartphone turn on Bluetooth, and search for the esp32 device to pair (in default case it is named "LoRa-01")

<p align="center">
  <img width="320" height="300" src="/images/pair.jpeg">
</p>

### Open App and Connect to esp32

Open The App and click the settings button:

<p align="center">
  <img width="320" height="300" src="/images/open.jpg">
</p>

Click Devices:

<p align="center">
  <img width="320" height="300" src="/images/devices.jpg">
</p>

Choose your device:

<p align="center">
  <img width="320" height="300" src="/images/choose_device.jpg">
</p>

make sure your you are connected:

<p align="center">
  <img width="320" height="300" src="/images/connect.jpg">
</p>

Your first input will be your nickname that will be shown ass the sender by all other devices:

<p align="center">
  <img width="320" height="300" src="/images/nickname.jpeg">
</p>

## Comments

