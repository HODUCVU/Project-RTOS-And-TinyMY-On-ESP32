# Frameworks like TensorFlow Lite and TiniML for Microcontrollers are designed to run on small devices and can be used with the ESP32.
# Topic: Smart home use FreeRTOS and TinyML on ESP32
Short-explain: Implement smart home, training tiniML module to control light and fan by voice. Use temperator and smoking sensor to control light and fan.

# Check ESP32 board version
* [esptool-js](https://espressif.github.io/esptool-js/)
* [repository](https://github.com/espressif/esptool-js)
* [Datasheet](https://products.espressif.com/#/product-selector?names=&filter={%22Series%22:[%22ESP32%22]})

# Documents
## Papers
* [Analysis of Free RTOS Vs Bare Metal using ESP32](https://www.iosrjournals.org/iosr-jeee/Papers/Vol16-Issue2/Series-1/E1602013968.pdf)
* [Formally verifying FreeRTOS’ interprocess communication mechanism](https://www.amazon.science/publications/formally-verifying-freertos-interprocess-communication-mechanism)

## Tutorial FreeRTOS on ESP32
* ESP32 with RTOS: [Youtube.com](https://www.youtube.com/watch?v=LLp9T3rgea8)
* Tutorial FreeRTOS: [github.com/neibalch](https://github.com/neilbalch/ESP32-FreeRTOS-Tutorial) **have videos**
* Tutorial 2: [github.com/DiegoPaezA](https://github.com/DiegoPaezA/ESP32-freeRTOS?tab=readme-ov-file)

## Framework train model
* [Tensorflow Lite for microcontroller](https://github.com/eloquentarduino/EloquentTinyML.git)
* [TinyML for ESP32](https://github.com/HollowMan6/TinyML-ESP32.git)
* [ESP32_MICROPHONE](https://github.com/0015/ThatProject/tree/master/ESP32_MICROPHONE)
## Videos tutorial train ML on board:
### Video 1
* [Video tutorial train machine learning for Arduino board](https://www.youtube.com/watch?v=BzzqYNYOcWc&list=RDCMUCclJCqMDAkyVGsm5oFOTXIQ&start_radio=1)
* [Detail project in website](https://www.digikey.com/en/maker/projects/intro-to-tinyml-part-1-training-a-model-for-arduino-in-tensorflow/8f1fc8c0b83d417ab521c48864d2a8ec)
* [code colab](https://gist.github.com/ShawnHymel/79237fe6aee5a3653c497d879f746c0c)
### Video 2
* [Video tutorual train recognition speech  with Arduino](https://www.youtube.com/watch?v=fRSVQ4Fkwjc)
* [repo code](https://github.com/ShawnHymel/ei-keyword-spotting)
## Run platformio on terminal
* Build: 
  ```
   /mnt/c/Users/<name>/.platformio/penv/Scripts/platformio.exe run
  ```
* Upload:
  ```
  /mnt/c/Users/<name>/.platformio/penv/Scripts/platformio.exe run --target upload
  ```
* Monitor:
  ```
  /mnt/c/Users/<name>/.platformio/penv/Scripts/platformio.exe device monitor
  ```
<!--
## Notes work:
```
Note: Programming follow OOP
Function
Primary:
1. Led on/off
2. Fan on/off
4. On/off Fan/Led with DHT
5. On/off Fan with Smoke sensor
Extra:
 On/off with voice
--------------------
Step work:
Xây dựng khung code -- Done
Code module step by step use FreeRTOS api -- Done
Test code -- testing 
Voice regconization -- Doing
Test code
Complete project
Write Report (slide)
``` -->
