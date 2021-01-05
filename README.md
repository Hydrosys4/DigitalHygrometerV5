# DigitalHygrometerV5

The SlowWire.py files is a python module to read the data from the Digital Hygrometer. The module is written in python3.
First of all connect the Digital soil moisture sensor to one of the Raspberry Pi GPIO pin. Let's assume the Sensor is now connected to GPIO17.
Then download the SlowWire.py from this Githuyb folder to a Raspberry PI folder. 
To read the sensor data, open the terminal in the raspberry, go to the folder with the SlowWire.py file and type the following command:

python3 SlowWire.py 17

This will read the data from the sensor connected to GPIO 17.
