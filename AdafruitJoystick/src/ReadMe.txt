/* Matthew Moravec
   Adafruit 2-Axis Joystick Utility
   9/28/2012
*/

***********Hardware Setup************
Pins 36 and 38 I have wired to the 0-1.8V analog inputs. I have wired VCC to the Beagle's 1.8V analog VCC output(pin 32).
The ground wire from the joystick is wired to the analog ground on the beagle(pin 34). The select GPIO signal I have routed to the GPIO_7 pin(pin 42). 

*********How the program works******

after making the executable and running the program, the terminal should display: "y-axis #### x-axis ####" where #### is a number between 1-4096.
The #### displays the current incoming analog value. When in its resting position, the analog number for both axis should be 2020 or so.

