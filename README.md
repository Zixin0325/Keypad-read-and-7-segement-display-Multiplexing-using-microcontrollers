# Multiplexing-using-microcontrollers

Using input multiplexing and output multiplexing technique on MPLAB to drive a PIC24 microcontroller. 

![image](https://user-images.githubusercontent.com/88007099/127592418-42ea284f-69d8-485d-a61a-13cf9ac53b7b.png)

In this laboratory, we are going to build a nearly-trivial application which will accept characters from the keypad and display them, two at a time, on the display. To reduce the number of digital I/O pins required, the keypad and display will be driven in a multiplexed manner.

the program should be able to do the following:
      ● Start with all segments off
      ● Every <30ms, rapidly stimulate in sequence all 4 lines of keypad while continuously reading and recording the column values, then decode those values to determine which key has been pressed.
      ● For every keypress, shift the rightmost displayed value to the left seven-segment digit (most significant), then display the key pressed on the rightmost digit(least significant).
      ● The display should be multiplexed and show both digits simultaneously (at least to the human eye).
      
 ![image](https://user-images.githubusercontent.com/88007099/127702868-9ce9d1c3-873b-43a6-8cc4-90baea8b8669.png)
