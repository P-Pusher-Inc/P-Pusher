# P-Pusher
GitHub repository for the software needed to run the P-Pusher device using the STM32F401RE microcontroller.

The P-Pusher is a a device that allows user to eject their device after a user-inputted time in order to prevent a phone from remaining plugged in longer than needed, preventing damage through overheating and extending the lifetime of a device's battery. 

<img src="https://upload.wikimedia.org/wikipedia/en/thumb/b/b6/Toronto_Maple_Leafs_2016_logo.svg/1200px-Toronto_Maple_Leafs_2016_logo.svg.png" height="300" > 

To use the device, simply insert the charge through the inside of the P-Pusher, leaving the prongs sticking out through the other end. The device is flexible and the device can be extended to make room for the charger. Fasten the hatch at the back in order to secure the system. Plug the system into an outlet. 


<img src="https://upload.wikimedia.org/wikipedia/en/thumb/b/b6/Toronto_Maple_Leafs_2016_logo.svg/1200px-Toronto_Maple_Leafs_2016_logo.svg.png" height="300">   

Using the STM32 Microcontroller, press the blue button n times where n is the number of minutes the user would like the device charged for. For any 10-second interval where the blue button is not pressed following the initial input, the timer will automatically start. 
