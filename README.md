# ESP32 Wi-Fi sniffer

This project aims at listening to Wi-Fi packets traffic.

## Prerequisites

* Install ESP-IDF: https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/#step-2-get-esp-idf
    * Make sure to use at least idf `v4.4` (which officially includes `esp32s3` support)
* Have an `ESP32-S3` board

## Run project

```
## Build
idf.py build

## Flash 
idf.py -p PORT flash

## Monitor
idf.py -p PORT monitor
```

You can also execute all above commands at once: `idf.py build flash monitor`

## Miscs

```
## Clean build folder
idf.py fullclean

## Set target
idf.py set-target esp32s3

## Configure board features
idf.py menuconfig
```
