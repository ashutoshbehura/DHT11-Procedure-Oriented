# DHT11-Procedure-Oriented
The DHT11 is an inexpensive sensor for measuring temperature and humidity.

This library can be used for reading both values from these DHT sensors.
The DHT11 only returns integers (e.g. 20) and does not support negative values.
The others are quite similar and provide one decimal digit (e.g. 20.2)
The hardware pins of the sensors and handshake are identical so ideal to combine in one lib.

The library (0.1 version) is confirmed to work on:

UNO (tested myself)
MEGA2560
DUE


### Pins :-

|  DHT11  | Arduino |
| ------------- | ------------- |
| 1 | 5V (Vcc)  |
| 2 | D5 (digital I/O)  |
| 3 | NC |
| 4 | GND |

Please refer to the manual named as DHT11_Manual.pdf.For detail refer to the following link

https://akizukidenshi.com/download/ds/aosong/DHT11.pdf
