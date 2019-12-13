# ESP32-CAM Security Camera

This project is based on two articles so all credits to the authors.

[ESP32-CAM Video Streaming Web Server Camera](https://randomnerdtutorials.com/esp32-cam-video-streaming-web-server-camera-home-assistant/)

[Micro-RTSP](https://github.com/geeksville/Micro-RTSP)

To build:

* Copy include/wifikeys_template.h to include/wifikeys.h
* Edit wifikeys.h and enter the correct wifi credentilas
* Rename microRTSP.RENAME_ME (or webserver.RENAME_ME) as main.cpp
* To build Micro-RTSP server: clone [Micro-RTSP](https://github.com/geeksville/Micro-RTSP) and make it available in esp-security-camera/lib by copying or creating a softlink.
* Import in platform.io and build

On HA:

* Configure the UI and add a picture glance card with the ip address of the device.
