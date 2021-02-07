# esp-idf-voice-control
Demonstration of voice control of esp32.   
No hardware other than ESP32 and smartphone is required.   

# Installation for ESP32

```
git clone https://github.com/nopnop2002/esp-idf-voice-control
cd esp-idf-voice-control/
idf.py set-target esp32
idf.py flash monitor -p PORT
```

# Installation for ESP32-S2

```
git clone https://github.com/nopnop2002/esp-idf-voice-control
cd esp-idf-voice-control/
idf.py set-target esp32s2
idf.py flash monitor -p PORT
```


# Installation of smartphone app

- Install [this](https://play.google.com/store/apps/details?id=appinventor.ai_cempehlivan92.Arduino_Sesli_Kontrol) app on your smartphone.   
 This app is an app that converts voice to text and sends it by Bluetooth2.0 SPP.   

- After installing the app on your smartphone, add ESP_SPP_ACCEPTOR to your pairing device.

- After launching the app, select "ESP_SPP_ACCEPTOR" from the CONNECT menu to pair.
![Arduino_Voice_Control-1](https://user-images.githubusercontent.com/6020549/107132341-64bedf80-6921-11eb-99d7-e6e032c78b3a.JPG)
![Arduino_Voice_Control-2](https://user-images.githubusercontent.com/6020549/107132344-67b9d000-6921-11eb-8824-8e6515a8d025.JPG)

- From the LANGUAGE menu, select your country so that you can recognize your native language.
![Arduino_Voice_Control-3](https://user-images.githubusercontent.com/6020549/107132346-6a1c2a00-6921-11eb-88f2-981d418b582f.JPG)

- When you tap the microphone and speak, the spoken words will be displayed on the ESP32.
![Arduino_Voice_Control-4](https://user-images.githubusercontent.com/6020549/107132349-6dafb100-6921-11eb-8a85-5a6c40896086.JPG)
![esp-idf-voice-control](https://user-images.githubusercontent.com/6020549/107132361-920b8d80-6921-11eb-800f-58bdb1ad5963.jpg)


