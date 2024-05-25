# Installing Arduino Plugin for SaberProp
1. Open Arduino, go to 'Preferences' and add the following Board Manager URL: https://espressif.github.io/arduino-esp32/package_esp32_index.json
2. Go to 'Boards Manager' and install the 'esp32' version 2.0.17
3. Go to Arduino package location ...\Arduino15\packages\esp32\hardware\esp32, backup and remove the installed version (folder 2.0.17)
4. Clone this repository in the esp32 folder:git clone https://github.com/RSX-Engineering/arduino_saberprop-esp 2.0.17
5. Download the [ProffieOSxs source code](https://github.com/RSX-Engineering/ProffieOSxs) and open ProffieOS.ino
6. Select the 'SaberProp' board in Ardunio     
7. Verify and upload as usual.

More info on the Arduino core for the ESP32, ESP32-S2, ESP32-S3, ESP32-C3, ESP32-C6 and ESP32-H2, [here](https://github.com/espressif/arduino-esp32/blob/master/README.md)

