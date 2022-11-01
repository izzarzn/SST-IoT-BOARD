# SST-IoT-Board

### Arduino IDE
   [Click Here](https://drive.google.com/drive/folders/1x9qoiOMDgKwajX3VDGFtvEBk1yoENJ2A?usp=sharing)
   
   ------
   
### Arduino IDE Installation Guide 
   [Click Here](Arduino_Installation.md)
   
   ------

### ESP8266 Setup Guide
   [Click Here](Esp8266.md)
    
  -------
  
### Blynk Account Setup Guide
   [Click Here](Blynk_Setup.md)
   
   -------

### Libraries Riquired 
   [Click Here](Libraries)
   
   --------
   ## SST IoT Board Pin Description

| **Components** | **GPIO PIN DESCRIPTION** |
|:----:|:----:|
| ON Board LED | 2, 16 |
| LDR | A0 |
| LCD | SCL - 5, SDA - 4 |
| OLED | 4, 5 |
|DC Motor | Motor 1- 16, 5 Motor 2- 4,2|
|Servo Motor | S1 - 5, S2 - 4 |
|Ultra Sonic Sensor | Trigger-12, Echo-14 |
|Bluetooth| RX-14, TX-12 |
|DHT 11| 2 |
| RELAY | 13 |

--------------------

 ### 1. Program to Print Hello World
 
   [Source Code](1_Hello_World/1_Hello_World.ino) 
   
   -----
 
 ### 2.Program for On Board LED 
   
   [Source Code](2_Blink_Led/2_Blink_Led.ino)
   
   -----
   
 ### 3.Program for RGB LED Common Cathode
 
   [Source Code](3_RGB_Led/3_RGB_Led.ino)
   
   ------
   
 ### 4.Program for Buzzer
 
   [Source Code](4_Buzzer/4_Buzzer.ino)
   
   -------
   
 ### 5. Program for Toggle Switch
   
   [Source Code](5_Push_Buzzer/5_Push_Buzzer.ino)
   
   [Procedure](https://github.com/izzarzn/RVCE-Manual/blob/37e183f1b3ca749f93e21dc971b0513503ead100/1.md)
   
   ------

### 6. Program for LDR Interface
  
   [Source Code](6_LDR_LED/6_LDR_LED.ino)
   
   [Procedure](https://github.com/izzarzn/RVCE-Manual/blob/37e183f1b3ca749f93e21dc971b0513503ead100/2.md)
   
   -------
   
### 7.Program for Bluetooth Interface

   [Source Code](7_Bluetooth/7_Bluetooth.ino) 
   
   [Procedure](https://github.com/izzarzn/RVCE-Manual/blob/37e183f1b3ca749f93e21dc971b0513503ead100/7.md)
   
   ------
   
### 8.Program for LED using Blynk Server
   [Click Here For Setup Guide](Blynk_Led.md)
   
   [Source Code](8_Blynk_LED/Blynk_LED.ino)
   
   -------
   
 ### 9. Program for DHT11 Sensor using Blynk Server
   [Click Here For Setup Guide](Blynk_DHT.md)
   
   [Source Code](9_Blynk_DHT/Blynk_DHT.ino)
   
   [Procedure](https://github.com/izzarzn/RVCE-Manual/blob/37e183f1b3ca749f93e21dc971b0513503ead100/9.md)
   
   ------
   
  ### 10. Program for DHT11 Sensor using Serial Monitor
  
   [Source Code](10_DHT11_Serial/10_DHT11_Serial.ino)   
   
   ------
   
  ### 11. Program for DHT11 and LED Using Firebase
   [Click Here For Setup Guide](FireBase_Setup.md)
  
   [Source Code](12_Firebase_DHT/11_Firebase_DHT.ino)
   
   -------
   
  ### 12. Program for User 1
  
   [Source Code](11_Firebase_User1/firebase_chat.ino) 
   
   ------
   
 ### 13. Program for User 2
 
   [Source Code](13_Firebase_User2/firebase_chat_user_2.ino)
   
   -----------
   
 ### 14. Firebase IoT MIT App
 
   [Click Here For Setup Guide](Mit_App_Inventor.md) 
   
   [Source Code](14_Firebase_IoT_MIT_App/firebase.ino) 
   
   ---------------
   ### 15. Smart Drip Irrigation
 
   [Source Code](https://github.com/SKsaikiran/SST-IoT-BOARD/blob/41dc5c527b7ff7722486cbed00f80a3fbdab004d/15_Smart_Drip_irrigation/15_Smart_Drip_irrigation.ino)
   
   -----------
   ### 16.Smart Irrigation
 
   [Source Code](https://github.com/SKsaikiran/SST-IoT-BOARD/blob/b0af84bc1d0a53235aca6bba04eb6f49547f5e62/16_Smart_Irrigation/16_Smart_Irrigation.ino)
   
   -----------
   
   ### 17. Program to interface I2C LCD
   
   [Source Code](https://github.com/izzarzn/RVCE-Manual/blob/3781764f5d55111b18df9ce8dc5e8f6276ddd58c/3_LCD/3_LCD.ino)
    
   Libraries Required :[LiquidCrystal I2C](https://drive.google.com/file/d/1HvLhhUfPdMpollQjFgATW0Y9pEnIQhQr/view?usp=sharing)
    
   [Procedure](https://github.com/izzarzn/RVCE-Manual/blob/37e183f1b3ca749f93e21dc971b0513503ead100/3.md)
   
  -----------
   
  ### 18. Program to interface DC Motors
  
 [Source Code](https://github.com/izzarzn/RVCE-Manual/blob/3781764f5d55111b18df9ce8dc5e8f6276ddd58c/5_DC_MOTOR/5_DC_MOTOR.ino)
 
 [Procedure](https://github.com/izzarzn/RVCE-Manual/blob/37e183f1b3ca749f93e21dc971b0513503ead100/5.md)
    
  ------------
  
 ### 19. Program to interface OLED 
 
 [Source Code](https://github.com/izzarzn/RVCE-Manual/blob/3781764f5d55111b18df9ce8dc5e8f6276ddd58c/4_OLED/4_OLED.ino)
 
 Libraries Required : [U8g2]()
 
 [Procedure](https://github.com/izzarzn/RVCE-Manual/blob/37e183f1b3ca749f93e21dc971b0513503ead100/4.md)

 --------------
 
 ### 20. Ultrasonic Sensor
 
 [Source Code](https://github.com/izzarzn/RVCE-Manual/blob/3781764f5d55111b18df9ce8dc5e8f6276ddd58c/6_ULTRASONIC/6_ULTRASONIC.ino)
 
 Libraries Required : [New Ping](https://drive.google.com/file/d/1eh5Y6EqwtD2sXDX7yacBk1t8MQLcMzoj/view?usp=sharing)
 
 [Procedure](https://github.com/izzarzn/RVCE-Manual/blob/37e183f1b3ca749f93e21dc971b0513503ead100/6.md)

 --------------  
   
   |**External Drivers**| **Links** | **MC's** |
|:-------:|:-------: | :--------: |
|CP210x Driver | [Click Here](CP210x_Windows_Drivers.zip)| ESP8266 & ESP32 |
|CH340 Driver (Windows) | [Click Here](CH341SER.zip)| Arduino |
|CH340 Driver (Mac) | [Click Here](CH341SER-MAC.zip)| Arduino |

----------------
   
   <h3 align = "center">Don't forget to ⭐ this Repo <h3>
   
