## Count People IN

## code source - 
- https://community.particle.io/t/tutorial-spark-variable-and-function-on-one-web-page/4181
- https://community.particle.io/t/reading-spark-variables-with-your-own-html-file/4148

## libraries used - 
- jquery-3.1.0.min.js - https://jquery.com/
- http://paperjs.org/tutorials/
- jquery-3.1.0.min.js - https://jquery.com/
- paperjs-v0/dist/paper-full.js - http://paperjs.org/tutorials/animation/creating-animations/

## 2nd tutorial - 
- https://docs.particle.io/tutorials/topics/maker-kit/
## Two libraries taken - 
- https://build.particle.io/build/57f5828b36e51f2d0700097d/lib/57564201d100a7f0f6000952/tab/a-rainbow.cpp
- https://build.particle.io/build/57f5828b36e51f2d0700097d/lib/5397d8d028979ed3cc000731/tab/Adafruit_GFX.cpp

first library is for neopixel. it was used in the code to light up the pixel as per requirements.
second library is for OLED. it is used to code the OLED in way where i can display the incoming data from the cloud.

## visualization - 
it was done in paper.js using the animation with animation path segment. data displayed was called in as a string, this string is split and then parsed. instead of using ajax call. i have called the data in the function.  with the device id and access token. this time instead of three.js i have used paper.js.
i have used two proximity sensors. each sensor will give a output in the form of voltages. i have taken that voltages to determine how many people are coming in. i have used OLED and neopixel to see the reading from the sensors and the counter, which i am using to check people coming in.

## youtube links for videos - 
- https://youtu.be/txcYWmwifYE
- https://youtu.be/9AeFHJYHD8g
- https://youtu.be/f3KUH1jb3j0
- https://youtu.be/Jv7tvrx4BTk
- https://youtu.be/C_nqWOqI9Io

## Images
![neopixel](https://github.com/abhisheksuhasmhatre/Project-2/blob/master/IMG_8924.jpg)
![sensor](https://github.com/abhisheksuhasmhatre/Project-2/blob/master/IMG_8925.jpg)
![output](https://github.com/abhisheksuhasmhatre/Project-2/blob/master/IMG_8926.jpg)
