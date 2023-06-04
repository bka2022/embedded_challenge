# RTES-Challenge
 Final Project for NYU Tandon EC-GY-6483 Real-Time Embedded Systems

This project utilizes the integrated gyro sensor on the STM32F429 Discovery microcontroller to develop a mechanism that records and replicates a hand movement sequence for unlocking a resource. The recorded sequence is saved using a "Record Key" feature. Users replicate the sequence within specified tolerances to unlock the resource. Overall, the project meets requirements and provides a functional solution with an intuitive LCD display indicator.

## How to Use:

- Compile and upload code to the board.
- Two buttons "Record" and "Unlock" will show on the LCD screen.
- Click on the "Record" button to record a gesture key sequence.
- Follow the prompt on the LCD screen. 
- Wait until "**Recording...**" is shown at the bottom of the screen.
- Perform the gesture to input the key within **5** seconds.
- Click on the "Unlock" button to unlock the device.
- Follow the prompt on the LCD screen. 
- Wait until "**Recording...**" is shown at the bottom of the screen.
- Perform the same gesture to unlock the device.
- Unlocking fail will light the red LED, ulocking succeed will light the green LED
- Press the blue user button will clear everything recorded. 

##  References:

https://github.com/STMicroelectronics/STM32CubeF4
https://bpb-us-w2.wpmucdn.com/sites.uwm.edu/dist/0/236/files/2016/09/IUI13-Combining-1hz6aya.pdf
https://github.com/cjekel/DTW_cpp