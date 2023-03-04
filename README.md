
# Remote_controll_car_with_NF
🆅🅴🆁🆂🅸🅾🅽 𝟭.𝟬

🔍Controll car by joystick with communicate NF {Radio}

---
### 👌Requirement
####  ⚙️Hardware
##### 🧩Car
- Arduino Uno
- Arduino Motor Shield L293D
- Display oled 128x32
- Module NRF24L01
- Module shows battery level
- Motor DC 12V
- Robot Tank Crawler Chassis DIY
- Plastic Battery Holder Storage Box Case with Leads
- Pin 18650
##### 🧩Controller
- Arduino Nano
- Joystick
- Display oled 128x64
- Module NRF24L01
- Switch
- Plastic Battery Holder Storage Box Case with Leads
- Pin 18650
#### 💾Software

#####  <img src="https://github.com/ThaiThanhDuy/Write_something_4_fun/blob/main/ICON/iconImage/arduino_logo_icon.png" height="50" width="50px" alt="Arduino"/>

#####  <img src="https://github.com/ThaiThanhDuy/Write_something_4_fun/blob/main/ICON/iconImage/Visual_Studio_Code_logo_icon.png" height ="50" width="50px" alt="Visual_Studio_Code"/>

- [Platformio extension](https://platformio.org/) 

##### 📚Library

- Install library in `platformio`

```C
 //Board Arduino 
#include <Arduino.h>

//Library for motor
//Just for car
#include <AFMotor.h>
#include <Servo.h>

//Library for radio
#include <RF24.h>
#include <nRF24L01.h>
#include <SPI.h>

//library for display
#include <Adafruit_SSD1306.h>
#include <Wire.h>
#include <Adafruit_GFX.h>

```
---
### 📝Documentation 
- [Documentation Pin](./Doc/Pin.docx)


### 🤖Authors 
- [0ᖺ@Ⴘ0](https://github.com/ThaiThanhDuy)

### 🧾License 
- [MIT](./LICENSE)

### 📭Feedback 
If you have any feedback, please reach out to us at just.electric.4.fun@gmail.com

(ง ͡ᵔ ● ͡ᵔ)ง
