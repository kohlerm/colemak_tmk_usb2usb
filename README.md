# colemak_tmk_usb2usb


````
Arduino_Loader/reset.py /dev/ttyACM0 ;  sleep 1.5 ; avrdude -patmega32u4 -cavr109 -b57600 -Uflash:w:unimap.hex :i -P/dev/ttyACM0 3
````
