# ESP32_Dorbellcam
A Dorbellcam build with an ESP32Cam microcontroller
##What do you need?
1. ESP32-Cam                           https://www.amazon.de/dp/B08FDFHHB7?ref_=cm_sw_r_cp_ud_dp_T2_0KPG3X72B3MKFDEX4YBE
2. FT232RL USB to TTL Serial           https://www.amazon.de/dp/B01N9RZK6I?ref_=cm_sw_r_cp_ud_dp_T2_2HJ96DEDZ08G4HRPRJCB
3. Jumper wire
(optional) 4. OV2640 Camera Module     https://www.amazon.de/dp/B07YXYHNN9?ref_=cm_sw_r_cp_ud_dp_T2_M8F7FTF5XMTDRKKRS9YK

##How to use?

1. Change SSID and passwort at line 23-24
2. Download all libarys that are in use
    https://github.com/me-no-dev/ESPAsyncWebServer
    https://github.com/me-no-dev/AsyncTCP
3. Add ESP32 as an Board -->
    https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-windows-instructions/
4. Select Port and upload the sketch
