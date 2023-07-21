# The-Ultimate-Device
The car displayed is only a miniscule landmark to the infinitely technical device that one like me is going to assemble. Once the first milestone is achieved, I will be able to rule... <!--- Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! -->

# Intro
The project is a wireless and serial connection and creates a branch of communication between computers and other advanced components and utilizes very strong potential energy. Making it semi-autonomous, or in other words a robot car. But to leave behind the first shed of skin to move on to the second, I suppose I will rely the exponential height of this work. So listen closely, or process it closely. To begin, we have two parts here. The transmitter and the reciever. To start, the transmitter which is going to send the data of our hands to the reciever is all powered with a 9v battery. What takes that power is all the other components in the transmitter which are the MPU6050 motor servo sensor, an arduino micro 5v, and lastly HC-05 bluetooth module. Housing a microcontroller, which is basically a mini computer equipped with RAm, a micro-processor, and a bunch of other computer components, the MPU6050 is able to communicate with the arduino 5v using the i2c protocol. Which is a serial communication bus. If you still don't know what it is, check in the bill of materials to learn more. It is connected to the Arduino via the 2 and 3 pins on the Arduino micro from the SDA and SCL pins on the accelerometer. After that, the bluetooth module has been used to create wireless serial communication between transmitter and reciever. We have a HC-05 in both transmitter and reciever and we must pair them. To do this, we set one as master and one as slave; once done, either module, slave or master, can be in either part, transmitter or reciever. That is it for the transmitter, now we have the reciever. The reciever has a total of 4 components and is powered by 6 double A batteries, which outputs a total of 9V. The battery powers the Arduino Uno R3, the L298 motor driver, and the other HC-05 bluetooth module. First, the L298 motor driver supplies a surplus of voltage to the 4 dc motors that are connected to the L298 H-bridge connection which is able to turn 2 motors clockwise or counter-clockwise. The left motors are connected to the out 1 and 2 pins. While the right motors are connected via the out 3 and 4 pins. To get power, the voltage goes into the Vin pin of the L298, while the ground goes into the ground pin. L298 has 6 input pins which 3 of them controllingthe left side motors and the other 3 for the right side motors. Pins 5, 6, 7 of the Arduino Uno are connected to the L298 inputs pins to control the left side motors. While 8, 9, 10 pins of the Arduino Uno are connected to the L298 to control the rightside motors. Pin 5 - ENB, Pin 6 - IN3, Pin 7 - IN4/ Pin 8 - In2, Pin 9 - In1, Pin 10 - EnA. Whithout going to much into it , pins 6 and 7 control left side motors to go counterclockwiseor clockwise, while pinand8 and 9 control the right side motors to go counterclockwise or clockwise. Pins 5 and 10 enable the motors for each side. Lastly, but never the least is the other bluetooth module for the reciever. 

<!---You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:-->

I love rice

Anything that has chicken in it I will eat. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Kebba J | Lafollette HS | Electrical Engineering | Incoming Sophmore


![Headstone Image](logo.svg)

# Latest Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my third milestone, I have paired the bluetooth modules together, and successfully got the reciever communicating to the transmitter. To do this, we had to pair the HC-05 bluetooth modules by putting them both in AT command mode by holding the reset button before plugging them into power, and then put one on each microcontroller, both arduino micro and uno. From there I sent the AT commands to the Bluetooth modules and configured them both, setting one as frame(master) and another as wheel(slave). After that, I paired or binded the frame to the wheel by sending the command to the frame (AT+BIND=(address of wheel). This commands binds the frame to the wheel by locking the frame to the address of the wheel. This successfully pairs the bluetooth modules, and all that was left was to connect the HC-05's to the original breadboards and connect the tx and rx pins of the microcontrollers to the bluetooth modules. 




# Second Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My second achievement was attaching the dc motors to the frame and connecting them to the L298 motor driver. To attach the motors to the frame, I used stands on both side of each motor and placed the dc motors near the edge of the frame using the stands. To keep the motors in place, I used machine screws and placed them through the holes of the motor and the stands, and then used a nut to secure it in place, preventing it from being loose it any possible way. After that, I attached black and red wires to the already soldered motor tabs and did the same with other 3 motors. Now I had a frame with four motors that were maybe soldered correctly. And it practically looked like a car already. But we needed to connect them to the L298 motor driver. Be if we had 8 wires with only 4 output pins on the L298 board, all pins wouldn't be able to get output from the L298. So we now had to connect the two motors on each side to each other to get the output from L298 to two motors total. So I simply connected the red wires from one motor to the other and did the same with the black wire on each motor. To test if my soldering was reliable, I used a battery holder which held 3 battery cells and connected black to black and red to red wires of the motor. And they worked . Though my soldering needed a bit more work. Lastly, I connected the motors to L298 now that we have the motors connected to each other. Connecting black to out 1 and red to out 2 for the left motors and connecting black to out 3 and red to out 4 of the for the right side motors is what made this connection possible. The task of actually putting  the wire in the screw terminal was quite surprising. Having to fold the stranded core wires so they could fit into the screw terminal was no easy task, but I was able to do it nonetheless. Even though there is the probability that the wire may short circuit because I recklessly placed the wires in the terminals because I was so "excited" to move on to the next step.


Circuit Diagram of Motor Testing 

![Elzing (2)](https://github.com/AlbertEinsteinSr44/The-Ultimate-Device/assets/138896021/19c86d7e-4b2b-4469-8d4c-d1941b05e081) 

  

# First Milestone
<iframe width="962" height="541" src="https://www.youtube.com/embed/x4_awlkcJw0" title="Kebba J. Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

So, my first shed of skin was actually getting the accelerometer to work. To me, it did not seem like this was such a big problem, and I was only miliseconds away from getting to the dialogue you see above(Intro). I thought at first that maybe the wires to the power rail were reversed, or the pins for the I2C protocol were not in the right place. These were definite problems initially. But numerous displays of the consistent coordinates of 89 on each plane(X,Y,Z) on the serial monitor meant that the accelerometer was either not connected via the I2C protocol, or there was a presence of an opened path for which the current was flowing, and an absence of a closed path for current to flow, or continuity, between the two components. We tested multiple times for continuity with my new best friend, the multimeter. But in the end, continuity was in check. We even checked for dc and ac voltage, (Direct and Alternating current), but still, everything seemed fine. It was then we started to get suspicious of the hardware itself, considering hardwares like the accelerometer are known to very concealing. The LED was on, but something on the hardware could've been destroyed. //So since the Arduino Micro wasn't telling us anything, and there was no way to test the hardware for any problems, I was first tasked to dispose of the first accelerometer and replace it with a new one. It took some time because I had to solder new headers to the MPU6050, a skill that was much faster for me now than before, and then// I connected the acclerometer to the Arduino Micro with the serial protocol and I tested again on the serial monitor. But still, the same result. Fear started to lurk near, but continuity said something about the Micro that may have been useful. Even though continuity was in check, there were numerous times while testing that Multimeter didn't actually beep, but did later, almost like the Micro was hiding something, or not working itself. So we turned to the Arduino UNO R3 which also had a microcontroller housed on its board. I connected both MPU and Uno to the breadboard. The results that the serial monitor displayed were shocking. As numbers ranging from 60-130 in X,Y,Z coordinates tickled my retinas. It was sight never seen before. As a rising engineer, I could never ever see something more beautiful than what I saw on that monitor. It was happy moment, but there were also hard times, sensitive battles, and very personified components. An auspicious experience. And very helpful concepts. Even though continuity was in check, it did contribute greatly to the final conclusion, and now stored in my brain for life. 
Now that the problems are out the way, we can now thrust into finally finishing the car. But just a note is that I am missing some parts. There are some things that I lost, or somehow they broke, Micro, causing physical complexities(and also decrease in self-esteem) with the car. But at this point, I basically finished the beginning of the beginning

  








<!---# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser.--> 

# Code
Code for Transmitter

```c++
#include <SoftwareSerial.h>
SoftwareSerial BT_Serial(0, 1); // RX, TX

#include <Wire.h> // I2C communication library

const int MPU = 0x68; // I2C address of the MPU6050 accelerometer
int16_t AcX, AcY, AcZ;

int flag=0;

void setup () {// put your setup code here, to run once

Serial.begin(9600); // start serial communication at 9600bps
BT_Serial.begin(9600); 

// Initialize interface to the MPU6050
Wire.begin();
Wire.beginTransmission(MPU);
Wire.write(0x6B);
Wire.write(0);
Wire.endTransmission(true);

delay(500); 
}

void loop () {
Read_accelerometer(); // Read MPU6050 accelerometer

if(AcX<60  && flag==0){flag=1; BT_Serial.write('f');}
if(AcX>130 && flag==0){flag=1; BT_Serial.write('b');}
      
if(AcY<60  && flag==0){flag=1; BT_Serial.write('l'); }
if(AcY>130 && flag==0){flag=1; BT_Serial.write('r');}
  
if((AcX>70)&&(AcX<120)&&(AcY>70)&&(AcY<120)&&(flag==1)){flag=0;
BT_Serial.write('s');
}

delay(100);  
}

void Read_accelerometer(){
      // Read the accelerometer data
Wire.beginTransmission(MPU);
Wire.write(0x3B); // Start with register 0x3B (ACCEL_XOUT_H)
Wire.endTransmission(false);
Wire.requestFrom(MPU, 6, true); // Read 6 registers total, each axis value is stored in 2 registers

AcX = Wire.read() << 8 | Wire.read(); // X-axis value
AcY = Wire.read() << 8 | Wire.read(); // Y-axis value
AcZ = Wire.read() << 8 | Wire.read(); // Z-axis value

AcX = map(AcX, -17000, 17000, 0, 180);
AcY = map(AcY, -17000, 17000, 0, 180);
AcZ = map(AcZ, -17000, 17000, 0, 180);

Serial.print(AcX);
Serial.print("\t");
Serial.print(AcY);
Serial.print("\t");
Serial.println(AcZ); 
}
```

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino Uno R3 | Microcontroller for reciever | $27.60 | <a href="https://store-usa.arduino.cc/products/arduino-uno-rev3?selectedStore=us"> Link </a> |
| Arduino Micro 5v | Microcontroller for transmitter | $19.92 | <a href="https://store-usa.arduino.cc/products/arduino-micro?selectedStore=us"> Link </a> |
| MPU6050 3 axis Accelerometer | Measures acceleration of ones hand| $9.99 | <a href="https://www.amazon.com/HiLetgo-MPU-6050-Accelerometer-Gyroscope-Converter/dp/B00LP25V1A/ref=sr_1_1_sspa?crid=3TZA15KTY36AH&keywords=mpu6050&qid=1689698110&sprefix=MPU%2Caps%2C158&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
| L298 Motor Driver Board | Amplifies Voltage going into the DC motors | $11.99 | <a href="https://www.amazon.com/HiLetgo-Controller-Stepper-H-Bridge-Mega2560/dp/B07BK1QL5T/ref=sr_1_3?crid=2HN2Y2XKCBAHR&keywords=SparkFun+Dual+H-Bridge+motor+drivers+L298&qid=1689690988&sprefix=sparkfun+dual+h-bridge+motor+drivers+l298%2Caps%2C243&sr=8-3"> Link </a> |
| Solderless breadboard half-size | Creating connections between components | $6.69 | <a href="https://www.amazon.com/Pcs-MCIGICM-Points-Solderless-Breadboard/dp/B07PCJP9DY/ref=sr_1_1_sspa?crid=3PHS6KU6D48B2&keywords=solderless+breadboard+half+size&qid=1689698322&sprefix=Solderless+breadboard+half+%2Caps%2C124&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1/"> Link </a> |
| HC-05 Bluetooth Module x2 | Admitting radio waves between transmitter and reciever | $19.98 | <a href="https://www.amazon.com/DSD-TECH-HC-05-Bluetooth-Wireless/dp/B074GMQ6G3/ref=sr_1_2_sspa?crid=24LNCC0IP1VA0&keywords=hc-05+bluetooth+module&qid=1689698399&sprefix=HC-05+%2Caps%2C130&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
| Male to Male Jumper Wire kit | Creating connections on a breadboard | $10.99 | <a href="https://www.amazon.com/Preformed-Breadboard-Assorted-Solderless-Prototyping/dp/B07WC3YKGQ/ref=sr_1_8?crid=37HPTMGB6YR8E&keywords=breadboard+male+jumper+wire+kit&qid=1689698782&sprefix=Jumper+wire+kit+male+to+male%2Caps%2C135&sr=8-8"> Link </a> |
| 120pcs,20cm Male to Female Jumper wires | Creating connections from component to arduino | $6.99 | <a href="https://www.amazon.com/EDGELEC-Breadboard-Optional-Assorted-Multicolored/dp/B07GD2BWPY/ref=sr_1_3?crid=1V5Y41GAWKSXO&keywords=male+to+female+jumper+wires&qid=1689699096&sprefix=Male+to+female+jumper%2Caps%2C151&sr=8-3"> Link </a> |
| 4 pc DC electric motor, DigiYes | Motion enabler | $8.99 | <a href="https://www.amazon.com/DiGiYes-Electric-Motor-3V-12V-Shaft/dp/B0BSP7ZG1B/ref=sr_1_42?crid=888U0MM72JZY&keywords=Geared+DC+Motor%2C+Brushed%2C+12+V%2C+180+rpm%2C+500+g-cm&qid=1689699254&sprefix=geared+dc+motor%2C+brushed%2C+12+v%2C+180+rpm%2C+500+g-cm%2Caps%2C164&sr=8-42"> Link </a> |
| Maker focus DIY Robot car | Corps/industry for robot car | $18.59 | <a href="https://www.amazon.com/MakerFocus-Chassis-MEGA2560-MEGA1280-Microcontroller/dp/B01LYZDP9U"> Link </a> |
| Energizer Alkaline Battery Pack, AA| Powering the robot car | $19.62 | <a href="https://www.amazon.com/Energizer-Batteries-Double-Long-Lasting-Alkaline/dp/B09RTVD1GF/ref=sr_1_1_sspa?keywords=Alkaline+battery+pack+AA&qid=1689699842&rdc=1&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
| Battery Holder | Houses Power| $9.98 | <a href="https://www.amazon.com/FOXTIP-Battery-Holder-Bundle-1Slots/dp/B0C5ZY2TRN/ref=sr_1_2_sspa?crid=17DXAJOBXNYAB&keywords=Battery+Holder%2C+18650+x+2&qid=1689700095&sprefix=battery+holder%2C+18650+x+2%2Caps%2C171&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |
| Boat Rocket Switch | Turns on the car | $6.29 | <a href="https://www.amazon.com/Baomain-SOKEN-Light-Rocker-Switch/dp/B01LT3F5B0/ref=sr_1_4?crid=1SS8QN1BQ11K3&keywords=Rocket+Switch&qid=1689700414&sprefix=rocker+switch%2Caps%2C168&sr=8-4"> Link </a> |
| Battery Clip | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Velcro | Holds the transmitter to ones hand | $7.99 | <a href="https://www.amazon.com/Adjustable-Fastening-Reusable-Management-Organizer/dp/B0BZLCX3KY/ref=sr_1_2_sspa?crid=2KYCJUV9D5SU6&keywords=velcro+straps&qid=1689700569&sprefix=Velcro+%2Caps%2C595&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1/"> Link </a> |
| Foam tape, double sided | Adhesive application for connecting components to frame | $6.99 | <a href="https://www.amazon.com/TSSART-2Pack-Foam-Tape-Thickness/dp/B0BZQJ3W5M/ref=sr_1_1_sspa?crid=38Z7IECOWPZ0F&keywords=3m+pe+foam+double+sided+tape&qid=1689700655&sprefix=PE+foam+tape+do%2Caps%2C161&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1/"> Link </a> |



# Other Resources/Examples
- [Example 1](https://www.hackster.io/embeddedlab786/hand-gesture-control-robot-via-bluetooth-94b13d)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
