ESP-IDF template app
====================

This is a template application to be used with [Espressif IoT Development Framework](https://github.com/espressif/esp-idf).

Please check [ESP-IDF docs](https://docs.espressif.com/projects/esp-idf/en/latest/get-started/index.html) for getting started instructions.

*Code in this repository is in the Public Domain (or CC0 licensed, at your option.)
Unless required by applicable law or agreed to in writing, this
software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied.*


Attempt to load png images from SD Card using lvgl framework on Waveshare ESP32 7 inch Display.
Link to product: https://www.waveshare.com/wiki/ESP32-S3-Touch-LCD-7

What works:
* mounting SD card at boot
* reading files from sd card, example in: ui_events.c [static esp_err_t read_binary_file(const char *path)]

What I want to achieve:
* correctly load png files from SD to display on screen  
