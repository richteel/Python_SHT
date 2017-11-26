TeelSys Python SMT
===================

Python library for accessing the Sensirion SMT series temperature and humidity sensors like the SMT21, SHT25, and SMT31 on a Raspberry Pi or Beaglebone Black.

Designed specifically to work with:

- Adafruit SMT31-D Temperature and Humidity sensors ----&gt; https://www.adafruit.com/products/2857

#Installation#

To install, run one or both of the following commands from a terminal window on the Raspberry Pi or Beaglebone Black:

## Installation - Python ##

<pre>sudo pip install git+git://github.com/richteel/TeelSys_Python_SMT.git</pre>

## Installation - Python 3 ##

<pre>sudo pip3 install git+git://github.com/richteel/TeelSys_Python_SMT.git</pre>


Make sure you have internet access on the device so it can download the required dependencies.

# Examples #

See examples of usage in the examples folder.

Written by Richard Jaques
Packaged and modified by Richard Teel for TeelSys LLC.
MIT license, all text above must be included in any redistribution

# NOTES #

- The code here is not my own. I simply packaged the original code to allow installation from pip and pip3. I also made some modifiecations to allow the package to work for Python 2 and 3.
	- https://github.com/jaques/sht21_python
- Testing Notes
	- Tested using Python 2.7 & 3.5
	- Platform Raspberry Pi Zero running Raspbian Version: Stretch 2017-09-07
	- Adafruit 2857 (SMT31-D)
	- Not tested with other Sensirion SMT sensors - Please comment if you use it for the SMT21 or SMT25 sensor

