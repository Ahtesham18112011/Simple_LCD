# Simple LCD displaying using Arduino UNO R3




## Connection 

Connect the Arduino's SCL and SDA pins to the I2C module's SCL and SDA pins. and then connect or solder the module to an LCD display.


## What is I2C

I2C (Inter-Integrated Circuit) is a two-wire, synchronous, serial communication protocol used to enable communication between devices over short distances, such as between a microcontroller and peripheral devices like sensors or memory chips. It's widely used in embedded systems and other applications due to its simplicity and efficiency. 

![image](https://github.com/user-attachments/assets/afbae635-817d-4e77-9ec5-ee7330943500)

## Set Slave address and size 

```c++
LiquidCrystal_I2C lcd(0x27, 16, 2); // set the LCD address to 0x27 for a 16 chars and 2 line display
```

Set the Slave address and the LCD display size here. In place of 0x27 write your Slave's(I2C module) address, to find out the address compile [this](https://github.com/Ahtesham18112011/Simple_LCD/blob/main/12c_scanner.ino) program and test it through the serial monitor in Arduino IDE. And set your LCD's size in place of 16 and 2. In this case its mean the display has 16 charachters and 2 lines.

## Compile and simulate

Compile by just going to Arduino IDE, setting the COM number, downloading the Liquid Crystal_12C library, writing the LCD code and then uploading. 

## Connect with me 
Connect with me in


[<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="30"/>](https://www.linkedin.com/in/ahtesham-ahmed-779845365/)
