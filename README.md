
## EE_180_Activity_1  

:computer: Groupwork:  With your group, create a c or c++ program that sets the ADC to right adjust. Attach a 10kohm to 25kohm potentiometer on ADC channel 3 and an LED on PORTD pin 2. Make your program such that the LED is if and only if when the resistance of the of the potentiometer is between 4kohms to 7kohms. Transmit via uart (9600, 8n1)also the adc value followed by a newline. 
**BONUS** : transmit the resistance value via UART    

You are not allowed to use existing functions except for the delay function.     
Deadline Sept 27, 2016. Defend by group.  

**Task List**  :smiley:
- [ ] Set ADC, UART, PORTD *since digital pin 2 is in PORTD* and other Registers
- [ ] Set ADC to right adjust *ADLAR = 0*
- [ ] Transmit via UART (9600 , 8n1) *9600 baud rate and 8bit data, no parity bit, 1 stop bit*

Useful websites :
- [For UART Configuration](http://www.electroschematics.com/10385/avr-uart-configuration/)
- [For ADC Configuration] (http://maxembedded.com/2011/06/the-adc-of-the-avr/)
- [Getting Started with Arduino] (https://drive.google.com/open?id=0B5zK2A31iDUvdDRpS0RFaVpwOUk)
