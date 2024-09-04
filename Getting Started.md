# Setting Up Your Arduino

## Install Arduino IDE
Arduino IDE 2.X is recommended

- Install Arduino IDE from here [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software), you can skip the donation by clicking _Just Download_ at the bottom, or feel free to support if you like!
- Open Arduino IDE, it should automatically prompt to install some drivers, appect and install them. 
  - _(Windows Users Only)_ Install theCp 210x USB driver from here [https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads)
  - _(Windows Users Only)_ Restart your computer
- Install the ESP 32 Board driver following this guide [https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html)
  - You will paste a link from the site into the _Additional Boards Manager URLs_ entry in the _Preference_ tab in the Arduino IDE
  - Open _Boards Manager_ in the Arduino IDE
  - Search for _ESP32_ and install the one from Espressif
  - Select Adafruit ESP32 from _Boards Manager_
