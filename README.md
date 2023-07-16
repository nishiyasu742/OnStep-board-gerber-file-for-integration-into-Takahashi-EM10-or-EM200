# OnStep-SHC-IntegratedController

The gerber files for OnStep circuit board that can place inside the EM200 or EM10　were uploaded. There are two types of circuits, and each MPU is Teensy or ESP32S. WROOM02 or 02D is used as Wi-fi module. A board using ESP32S can be connected to OnStep via Bluetooth without using a Wi-fi module. If you use Teensy you need to use WROOM02 or add another Wi-fi or Bluetooth module. WROOM02D is not an easy-to-use part compared to WOMOS D1 mini. In order to connect to Wi-fi in Japan where there are special laws, using this module is the first choice in terms of cost. See the attached image for details.

The motor that originally came with the EM200 and EM10 is not suitable for high-speed driving, so please change the motor if possible. However, the spur gear used in EM200 and EM10 has a hole diameter of 4mm or 6mm, so there are few stepping motors that can be used due to the shaft diameter. I ordered a gear with a hole diameter of 5mm for a Japanese manufacturer, and installed a stepping motor capable of high speed rotation.
Try different methods.

![Image mounted on a telescope 01](https://github.com/nishiyasu742/OnStep-board-gerber-file-for-integration-into-Takahashi-EM10-or-EM200/blob/main/Photo/EM10%20%201.JPG)
![Image mounted on a telescope 02](https://github.com/nishiyasu742/OnStep-board-gerber-file-for-integration-into-Takahashi-EM10-or-EM200/blob/main/Photo/EM10%20%201.JPG)
