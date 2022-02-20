# ESP32-CAM Traffic Violation Detection System
Traffic Violation Detection System is a system that utilizes machine learning and embedded device to detect a traffic violation, especially on a traffic light. The system would/should notify the authorities if it detects an object inside the caution area.

this project is an Embedded System Final Project developed by **Group 18**
<p align="center">

Group Member | Student ID
------------- | -------------
Fahri Novaldi  | 119140205
Iqbal Amrulloh | 119140161

</p>

## Preview

Real-Life Demo on Motorcycle:

https://user-images.githubusercontent.com/25357458/147871933-c87be292-8da1-4728-bfdb-cac8288eda02.mp4


## Requirements & Dependencies
This Project is build over giant shoulder such
* ESP32-Cam library by espressif
* Tensorflow lite by google
* coco-ssd pretrained model by tf community

## How does it works?
![Architecure System](https://raw.githubusercontent.com/gremlinflat/ESP32-CAM---Smart-Traffic-Violation-System/master/%5Breadme%5D/System%20Architecture.png)


Wiring diagram

![wiring diagram](https://raw.githubusercontent.com/gremlinflat/ESP32-CAM---Smart-Traffic-Violation-System/master/%5Breadme%5D/wiring%20diagram.jpg)
## Instalations
//dont forget to downgrade esp32 to version 1.0.4

## Known Issue/Bug
- Wifi SSID Configuration doesn't support space character (ssid that contain any space)
- Apple's Safari doesn't trigger the alarm when an object anchor passing the boundary (javascript related)
## References
[Pretrained Machine Learning models (COCO-SSD)](https://github.com/tensorflow/tfjs-models)

[fustyles arduino project repository](https://github.com/fustyles/Arduino)(as our coding references, big thanks to fustyles 🤩)

