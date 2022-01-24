# ESP32 Wi-Fi sniffer

Make sure to use at least idf `v4.4` (which officially includes `esp32s3` support).

## Configure project before running

```
## Set target
idf.py set-target esp32s3

## Configure board features
idf.py menuconfig
```

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