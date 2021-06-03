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
you cab download it from here:https://play.google.com/store/apps/details?id=de.kai_morich.serial_bluetooth_terminal&hl=en_US&gl=US

or look in the phone in google play: "Serial Bluetooth Teminal"
<p align="center">
  <img width="320" height="300" src="/images/app.jpeg">
</p>

## Arduino IDE
 a computer with ardouino IDE to put the code on the esp32 
 you can download it from here:https://www.arduino.cc/en/software
 <p align="center">
  <img width="320" height="300" src="/images/ArduinoLogo.png">
</p>


## The .ino files in this repository
import then to your comupter and upload them to the devices.
