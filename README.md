gps-gadgets
===========
This is a python script which parses and prints NMEA strings using the python library pynmea2.
It has two option one with single sentence streaming and the other streaming as chunks of NMEA strings ended with new line

usage

python gps.py -s "NMEA string" or
python gps.py -f "file name"

gps.py is the script name. so download the source and save it as gps.py or give it your preferred name, and use that name when you run the script

note : you can install the pynmea2 library online for linux

sudo apt-get install pip
pip install pynmea2
