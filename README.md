# Sissi-Xu_CCA_Digital-Electronics_2020
Digital Electronics HW&amp;Exercise

# Week 15 (Final Project Presentation)
-----------------------------------------------------
## "Hello ～ From The Other Side!"
- In the current situation, we are staying safe to keep a distance from other people, and even roommates are no exception. Without any internet, do you feel lonely living without communication day by day? People usually express their emotions through facial expressions, but if we don't see each other, what should we do? My design concepts have considered today’s special circumstances of COVID-19 and aim to help people communicate under quarantine through images. The Remote control communicator ("Hello～From The Other Side")  allows the user to express emotion across the other side of the room. 

![TCS](/images/Cover_heart.JPG)

###  Schematic:

![TCS](/images/Schematic_Final.png)

- An Arduino board
- A breadboard
- An IR remote Transmitter & a receiver
- 3 LEDs & 220 ohms resistor
- A 8*8 LED Matrix

### Breadboard:

![TCS](/images/Breadboard_Final.png)

### Code:
-  Locate in "FinalProject-Final" Folder

### HOW IT WORKS:
- The user in the room needs to use the remote control to press the corresponding expression button on the remote. At the same time, the LED matrix in their roommates' room will receive an image the user sends. It allows their roommates across the room will see the user's current mood without contact; they will immediately understand the user's feelings and reply by doing the same thing.

- Video Link: https://vimeo.com/411977547

![TCS](/images/Remote_emoji.GIF)

# Week 14 (Final Project Part 2)
- This week through online research I learned how to write code in the ardurino to display images on the 8*8 LED Matrix. After reading some articles, I found a software called "Pixel To Matrix," which allows me to design the image I want on the computer and get the corresponding code that I can input to the Arduino. I drew three different expressions: smile😊, neutral😔,and frown😫 on the computer. I asked them to be displayed on my matrix in the loop. My next step is to connect and control the three expressions through the IR remote.

### Software:

![TCS](/images/PixelToMatrix.PNG)

### Schematic:

![TCS](/images/Schematic_2.png)

### Breadboard:

![TCS](/images/Breadboard_2.png)

### Code:
- Locate in "FinalProject-Part 2" Folder

### HOW IT WORKS:

![TCS](/images/Matrix.GIF)

### Resources: 
- 8*8 LED Matrix Tutorial: https://www.youtube.com/watch?v=vI3ipE2Wj8Y


# Week 13 (Final Project Part 1)
- This week, I searching online on how to use and collect basic data from IR remote and use it to control what you want to turn on and off. By watching the online tutorial, I learned how to read the receiver's data through the serial monitor and use the data to turn on and off of the led light from a distance. My next step is to learn how to use the 8*8 LED matrix with the Arduino and program the first emoji (A Happy face ˆ_ˆ).

### Schematic:

![TCS](/images/Fritzing2.png)

### Breadboard:

![TCS](/images/Fritzing1.png)

### HOW IT WORKS:

![TCS](/images/IRcontrol.GIF)

### Code:
- Locate in "FinalProject-Part 1" Folder

### Resources: 
- IR Receiver Electronic Brick : http://arduinoinfo.mywikis.net/wiki/IR-RemoteControl

# Week 12 (Final Project Proposal)
### Final Project Proposal
-----------------------------------------------------
### Remote Communicator (Hello from the other side):
- During this final project, I'd like to learn about how to use the IR Remote & Receiver. Because of the coronavirus, we were told to keep in distance with each other. For long-distance communication, I'd like to use the remote to play my roommate a particular melody that can make her day. And also, send messages (text/ voice/ or play a song) to my roommate living next to me (such as "Hi, Zoe ˆ-ˆ" ). We can communicate with 6 feet distance.This device can also be used outside for communication because we will be covered with the mask so we cannot see each other's face so we will need a device that can print my emotion or mood on the screen (8*8 LED Matrix)

![TCS](/images/Communicator.JPG)

### How it works: 
- When I push "1" on the remote, the first LED will light up to tell my roommate we will be communicated on Channel 1. Each channel will be different messages such as text message ("Hello Zoe!" "How's your day?"), When I push "2" on the remote, the second LED will light up to tell my roommate we will be communicated in Channel 2 which allow me to send her an emoji and she can use the remote to replay.

![TCS](/images/flow.JPG)

### Must have:
- IR Remote control with the led light
- 8x8 LED Matrix (Print emoji)
- Message sent via the LCD Screen.


### Nice to have:
- Speaker to play the music or melody.
- Able to switch the melody. 
- Connect to computer processing to send images.

#### Week One: Get the IR Remote & Receiver work, and be able to control the LED light on the Breadboard.
#### Week Two: Able to Print emoji on an 8x8 LED Matrix and program to control by the remote. 
#### Week Three: Connect the LCD screen to the project and send the message control by the remote.

### Sources: 
- IR Remote Tutorial:https://www.youtube.com/watch?v=3jeSfsnQOWk&t=1s
- 8x8 LED Matrix:https://www.hackster.io/SAnwandter1/programming-8x8-led-matrix-23475a

# Week 7 (Midterm)
-  My Project is to design a Mento's flavor separator. I use a color sensor to sense the color of the Mentos and reflect the same color on the RGB LED, and then print the flavor to the LCD screen. The Potentiometer will control the light of the LCD. Through this project, I learned how to use the hardware I needed and completed most of the code writing independently.  

![TCS](/images/Picmachine2.jpeg)
![TCS](/images/Orange.GIF)
![TCS](/images/Lemon.GIF)
![TCS](/images/Strawberry.GIF)

- Components needed for this Mento's flavor separator

  - Arduino Board
  - Breadboard and Jump Wires 
  - Potentiometer (Adjust the brightness of the LCD Screen)
  - RGB LED (Sense the color of the candy and change the light)
  - Color Sensor TCS34725 (Sense the color and get its RGB value)
  - The LCD Screen (Print each candy flavor to the screen)
  
- Video Link for project demo :https://youtu.be/MQCG0-THZQE

# Week 6
-  This week I have combined the two parts of the code into one file. My goal is for this week is to let the LCD screen to display candy flavors when sensing different colors of each piece of the candy. One of the problems I had was that every time I got the sensor data, the LCD would flash, and I couldn't see any words on the screen.
![TCS](/images/lcdwithsensor.gif)

# Week 5
-  This week I tried a new color sensor TCS34725 to identify the color of RGB, and my goal is to display the color on the led. But I face some connection problem, the light of my RGB did not light up. After several attempts, I still don't know where the issue is.
![TCS](/images/TCS.JPG)

- In class, I found the problem by changing the type of led, and finally successfully transferred the color to RGB Led.
![TCS](/images/TCSsensor.GIF)

# Week 4
- Step one: This week, I learned how to connect Arduino with the LCD and display the words I wanted on the LCD screen.
- Next Step: Learn the color sensor and able to recognized its RGB values and then printed on the LCD screen.
![LCD](/images/Hellosissi.GIF)
![LCD](/images/LCCSceendraw.JPG)

# Week 3
-  My design concept is based on the story that happened around me. I bet some times in your life want to have to eat a certain flavor of candy, but because mentos multi-flavor is a tube, you can not choose the order in which flavor of the candy appears, so what should you do when you only want grape flavor candy.
![Mentos Machine](/images/Mentos.JPG)
- Electric M

- Code: My code will transmit the color recognized by the sensor to the motor so that it can change the direction correctly and accurately to drop the candy into the correct container.

- First Step: Sketch out the machine and use cardboard to make a prototype.
- Second Step: Refine the Prototype using better materials.
- Final Step: Refine again to be well accomplished.
- Add on: "Nice to have"

- "Must have"
  - The TCS3200 color sensor. (Sense and recognize the color of the candy)
  - Able to separate colored candies into different container.
  
- "Nice to have"
  - Different colors of led represent different colors of candy.
  - Digital Counter
   
- Research on Sensors:
  - The TCS3200 color sensor: https://howtomechatronics.com/tutorials/arduino/arduino-color-sensing-tutorial-tcs230-tcs3200-color-sensor/
  - Touch Sensor: https://www.adafruit.com/product/1375
  - 1x4 Keypad: https://www.adafruit.com/product/1332
  - These three sensors I had most interesting by its use, I will try to include in my midterm project. The color sensor sensed the color and separated them, and then transmitted the information into the computer and output to use to control any product on their motion. The touch sensor can be used in a touchpad to turn on and off the switch for a device or powerful a machine. 1*4 ket pad each button can use as a single switch to program and control different outputs.
  
# Week 2
-  I found this video, which I feel it's interesting. It is An Arduino-powered Egg Printer that made from the ELEKS team. This machine can print the digital graphic on the surface of the egg, and it controls the direction of the pen to draw the design figure along the curve of the egg smoothly. You end up with a specially designed egg. https://www.youtube.com/watch?v=B9fdly5wphA
- Light & Sensor Porject:https://youtu.be/jjz_whcOGKY 
       
    ![LightandSensor](/images/Light.GIF)

# Week 1
-  Processing Sketch

![ProcessingSketch](/images/ProcessingSketch.png)



