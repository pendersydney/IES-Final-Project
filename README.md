## **C and C# code from ECE09342: Intro to Embedded using the MSP430**

This project works to explore the use of digital communications by integrating the MSP430 and the online Internet of Things (IoT) development environment ThingSpeak. The raw ADC light, temperature, motion data values go through UART conversion (smartHome.c, smartHome.c/GUI) and are sent into ThingSpeak to be visually interpreted into a graph.

## **smartHome.c:** 
This C program compiled in CCS works to convert the sampled data into 8-bit ASCII form. 
```
  input: sampled date 
  output: 8-bit ASCII sample
```

## **smartHome.c:** 
This C# program compiled in Visual Studios works to convert the 8-bit ASCII sample date into interger form. The program creates a GUI (graphical user interface). 
  ```
  input: 8-bit ASCII sample
  output: Integer 
  ```
  
  A deeper understanding of microcontrollers, specifically the MSP430, and their behavior was gained through the implementation of sensors, a C# GUI, and ThingSpeak. The reading and conversion of the light, temperature, and motion analog sensor data goes through the serial port to the correct ThingSpeak channel and then is finally displayed visually on a graph.
