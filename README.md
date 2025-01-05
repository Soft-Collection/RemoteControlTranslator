[![WiFi Clock LED Matrix](http://img.youtube.com/vi/qhvd6wGgwzA/0.jpg)](http://www.youtube.com/watch?v=qhvd6wGgwzA "WiFi Clock LED Matrix")

# Remote Control Translator
Translates signals from unoriginal Remote Control to your TV

## Parts
| Qty | Product                                                                  | Description             |
| --- |--------------------------------------------------------------------------|-------------------------|
|1 | [Arduino Nano](https://www.aliexpress.com/item/1005007066680464.html?spm=a2g0o.order_list.order_list_main.81.184c18028IEQMF) | Main board |
|1 | [IR LED](https://www.aliexpress.com/item/1005003852381793.html?spm=a2g0o.productlist.main.1.798c22459JzWjx&algo_pvid=85318a1a-8cc1-4731-95d6-a4eff31d04ae&algo_exp_id=85318a1a-8cc1-4731-95d6-a4eff31d04ae-0&pdp_npi=4%40dis%21ILS%212.91%212.80%21%21%210.78%210.75%21%402141122217361043205207414e152d%2112000027809445076%21sea%21IL%21140732279%21X&curPageLogUid=FTK3Pwly3RGM&utparam-url=scene%3Asearch%7Cquery_from%3A) | IR LED |
|1 | [IR Receiver](https://www.aliexpress.com/item/32970639635.html?spm=a2g0o.order_list.order_list_main.114.184c18028IEQMF) | PC-838 |

## Notes
[Adafruit GFX Library](https://github.com/adafruit/Adafruit-GFX-Library) must be installed.

[Adafruit NeoMatrix](https://github.com/adafruit/Adafruit_NeoMatrix) must be installed.

[Adafruit NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel) must be installed.

[Adafruit BusIO](https://github.com/adafruit/Adafruit_BusIO) must be installed.

In the file Config.h you must set:
```
//Your WiFi SSID and Password
#define STASSID "YourSSID"
#define STAPSK  "YourPassword"
```
```
//Your Time Zone
#define MYTZ YourTimeZone
```
[See all time zones here](https://github.com/esp8266/Arduino/blob/master/cores/esp8266/TZ.h)

Set desired **upload_port** in the file **platformio.ini** file.

## Connection Diagram
![Connection Diagram](Images/Connection%20Diagram.png)
