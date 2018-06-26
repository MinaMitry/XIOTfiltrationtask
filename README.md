# XIOTfiltrationtask
  Prerequisites:
  i have choosen ATMEGA328p to deal with for this project, At the first lines you will see #define for every pin and its location     
  for hardware installation. Also, the calculation of ADC for the temperatue sensor (LM35) is only working for the lm35dz 
  temperature sensor.
  INSTALLATION
  1* for switch connect it with the ground and PORTD pinD2 (i activated internal pull up resistor)
  2* for the led connect it with Resistor (Recommended value = 330 ohm) to the ground With pinD4
  3* For serial monitor the Tx at atmega328p pinD1 
  4* The temperature Sensor is output pin is connected through port C PINC0
  Author : Mina J. Mitry
