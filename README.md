# CONTROLLING LED WITH RASPBERRY PI AND PYTHON

## Connections
![](https://github.com/bhooshan11/CONTROLLING-LED-WITH-RASPBERRY-PI-AND-PYTHON/blob/main/circuit%20connections.png)

## Procedure 
*	Install raspberry pi os into Sd card and set up the raspberry pi as show in previous task.
*	Open terminal in raspberry pi.
*	Type “nano led.py” to create a python file.
*	Open the previously created python file.
*	Type the code as shown above.

     code : https://github.com/bhooshan11/CONTROLLING-LED-WITH-RASPBERRY-PI-AND-PYTHON/blob/main/led%20in%20raspberry%20pi.py
*	Build the circuit as shown above.
*	Run the python file by typing “sudo python led.py”.
*	Led will blink and the status of led will be displayed on terminal.

## Explanation of code 

In the above code we import RPi.GPIO to control GPIO pins and import time library to use sleep() function. By “GPIO.setmode(GPIO.BCM)” we are using BCM pin numbering system and “GPIO.setup(14,GPIO.OUT)”this set GPIO pin number 14 as output and
”GPIO.setwarnings(False)” this will disable all the warnings. In while loop we turn on led for one second and turn off led for one second.

## Working

https://drive.google.com/file/d/15134U-3zaxdKZWchM-5j6e_kb8H182Ig/view?usp=sharing

## Reference 
https://www.circuitbasics.com/how-to-control-led-using-raspberry-pi-and-python/ 

