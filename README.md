# P-Pusher
GitHub repository for the software needed to run the P-Pusher device using the STM32F401RE microcontroller.

The P-Pusher is a a device that allows user to eject their device after a user-inputted time in order to prevent a phone from remaining plugged in longer than needed, preventing damage through overheating and extending the lifetime of a device's battery. 

To use the device, simply insert the charge through the inside of the P-Pusher, leaving the prongs sticking out through the other end. The device is flexible and the device can be extended to make room for the charger. Fasten the hatch at the back in order to secure the system. Plug the system into an outlet. 

Using the STM32 Microcontroller, press the blue button n times where n is the number of minutes the user would like the device charged for. For any 10-second interval where the blue button is not pressed following the initial input, the timer will automatically start. 
