# GarageOpener
Seeed Studio ESP32-S3 as Garage Remote

This is a dump for my ESP Home files after making my brothers garage door opener for home assistant

The garage door: https://www.marantec.com/files/eba_sap/A/100316.pdf
Essentially short pins 1-2 with a wire (tested) to create the button press (no need to run power in there, this is what is meant by dry)

Next step - get a 'relay' that i can turn on and off via some kind of microctonrller
The 5v relays are cheaper than the 3v relays, and there is basically no difference between the prices of microcontrollers and i had a seeed studio esp32-s3 laying about. i would love to redo it with an esp32-c6 which would offer zigbee support. but i work, with what i have in the shed.

open home assitant and setup the device with esphome

the pins on the esp32 are
https://core-electronics.com.au/seeed-studio-xiao-esp32c3-tiny-mcu-board-with-wi-fi-and-ble-battery-charge-supported-power-efficiency-and-rich-interface.html
as you can see it has a 5v pin!
yay




