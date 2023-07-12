# The-Ultimate-Device
The car displayed is only a miniscule landmark to the infinitely technical device that one like me is going to assemble. Once the first milestone is achieved, I will be able to rule... <!--- Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! -->


<!---You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:-->

I love rice
Anything that has chicken in it I will eat. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Kebba J | Lafollette HS | Electrical Engineering | Incoming Sophmore
'''HTML

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- First Milestone: What is it?
- The project is a wireless and serial connection and creates a branch of communication between computers and other advanced components and utilizes very strong potential energy. Making it semi-autonomous, or in other words a robot car. But to leave behind the first shed of skin to move on to the second, I suppose I will rely the exponential height of this work. So listen closely, or process it closely. To begin, we have two parts here. The transmitter and the reciever. To start, the transmitter which is going to send the data of our hands to the reciever is all powered with a 9v battery. What takes that power is all the other components in the transmitter which are the MPU6050 motor servo sensor, an arduino micro 5v, and lastly HC-05 bluetooth module. Housing a microcontroller, which is basically a mini computer equipped with RAm, a micro-processor, and a bunch of other computer components, the MPU6050 is able to communicate with the arduino 5v using the i2c protocol. Which is a serial communication bus. If you still don't know what it is, check in the bill of materials to learn more. It is connected to the Arduino via the 2 and 3 pins on the Arduino micro from the SDA and SCL pins on the accelerometer. After that, the bluetooth module has been used to create wireless serial communication between transmitter and reciever. We have a HC-05 in both transmitter and reciever and we must pair them. To do this, we set one as master and one as slave; once done, either module, slave or master, can be in either part, transmitter or reciever. That is it for the transmitter, now we have the reciever. The reciever has a total of 4 components and is powered by 6 double A batteries, which outputs a total of 9V. The battery powers the Arduino Uno R3, the L298 motor driver, and the other HC-05 bluetooth module. First, the L298 motor driver supplies a surplus of voltage to the 4 dc motors that are connected to the L298 H-bridge connection which is able to turn 2 motors clockwise or counter-clockwise. The left motors are connected to the out 1 and 2 pins. While the right motors are connected via the out 3 and 4 pins. To get power, the voltage goes into the Vin pin of the L298, while the ground goes into the ground pin. L298 has 6 input pins which 3 of them controllingthe left side motors and the other 3 for the right side motors. Pins 5, 6, 7 of the Arduino Uno are connected to the L298 inputs pins to control the left side motors. While 8, 9, 10 pins of the Arduino Uno are connected to the L298 to control the rightside motors. Pin 5 - ENB, Pin 6 - IN3, Pin 7 - IN4/ Pin 8 - In2, Pin 9 - In1, Pin 10 - EnA. Whithout going to much into it , pins 6 and 7 control left side motors to go counterclockwiseor clockwise, while pinand8 and 9 control the right side motors to go counterclockwise or clockwise. Pins 5 and 10 enable the motors for each side. Lastly, but never the least is the other bluetooth module for the reciever. 
- So, my first shed of skin was actually getting the accelerometer to work. To me, it did not seem like this was such a big problem, and I was only miliseconds away from getting to the dialogue you see above. I thought at first that maybe the wires to the power rail were displaced, or the pins for the I2C protocol were not in the right place. These were definite problems initially. But numerous displays of the consistent coordinates of 89 on each plane(X,Y,Z) on the serial monitor meant that the accelerometer was either not connected via the I2C protocol, or there was a presence of an opened path for which the current was flowing, and an absence of a closed path for current to flow, or continuity, between the two components. We tested multiple times for continuity with my new best friend, the multimeter. But in the end, continuity was in check. We even checked for dc and ac voltage, (Direct and Alternating current), but still, everything seemed fine. It was then we started to get suspicious of the hardware itself, considering hardwares like the accelerometer are known to very concealing. The LED was on, but something on the hardware could've been destroyed. //So since the Arduino Micro wasn't telling us anything, and there was no way to test the hardware for any problems, I was first tasked to dispose of the first accelerometer and replace it with a new one. It took some time because I had to solder new headers to the MPU6050, a skill that was much faster for me now than before, and then// I connected the acclerometer to the Arduino Micro with the serial protocol and I tested again on the serial monitor. But still, the same result. Fear started to lurk near, but continuity said something about the Micro that may have been confidential. Even though continuity was in check, there were numerous times while testing that Multimeter didn't actually beep, but did later, almost like the Micro was hiding something. So we turned to the Arduino UNO R3 which also had a microcontroller housed on its board. I connected both MPU and Uno to the breadboard. The results that the serial monitor displayed were shocking. As numbers ranging from 60-130 in X,Y,Z coordinates tickled my retinas. It was sight never seen before. As a rising engineer, I could never ever see something more beautiful than what I saw on that monitor. It was happy moment, but there were also hard times, sensitive battles, and very personified components. An auspicious experience. And very helpful concepts. Even though continuity was in check, it did contribute greatly to the final conclusion, and now stored in my brain for life. 
- Now that the problems are out the way, we can now thrust into finally finishing the car. But just a note is that I am missing some parts. There are some things that I lost, or somehow they broke, Micro, causing physical complexities(and also decrease in self-esteem) with the car. But at this point, I basically finished the beginning of the beginning
- What is your plan is to complete your project: <confidential> (Make a drone using this design you see in the intro.)
  

# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone


# Final Milestone

<**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**>

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE





# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
