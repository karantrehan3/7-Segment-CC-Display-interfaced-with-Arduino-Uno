# 7-Segment-CC-Display-interfaced-with-Arduino-Uno
The 7 Segment CC Display is interfaced with Arduino Uno in such a way that when a command(consisting of numbers from 0 to 15) is input through the serial monitor , the 7 segment display , displays the same.

-----------------------------------------------------------------------

Firstly a string "num" is declared globally.
Then , pin numbers 13 to 7 are assigned to variables of integer type a,b,c,d,e,f,g respectively.
After that , the connection between the pc and arduino is setup using "Serial.begin(9600)" command where 9600 is the baud rate.
Then the program makes use of "Serial.readString()" function to read the input from the user through Serial Monitor.
As soon as the user enters any value between 0 to 15 , the "Serial.readString()" function reads the value and stores the value in string "num".
Then , the program checks for the number entered and turns on the leds of the 7 segment display in a way that the so formed pattern displays the number entered by the user.
If the user enters "Off" , all the leds are turned off.

--------------------------That's about the program------------------------

For the hardware connections , make use of the proteus simulation.

For any further query, mail me at: karantrehan3@gmail.com
Thank You
:)
