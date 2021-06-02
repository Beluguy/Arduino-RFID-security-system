# Arduino-RFID-security-system

This is for a school project.

## Program logic (also available in logic.txt):

	If master tag is detected, enter program mode and wait for another tag,

	a. if another tag is detected, read it and determine is it "ON" or "OFF"

		- if it is "ON", clear all the data and write "OFF"
		
		- if it is "OFF", clear all the data and write "ON"

	b. if it is not the master tag, access denied and read it and determine is it "ON" or "OFF"

		- if it is "ON", Serial.print "OFF"
		
		- if it is "OFF", Serial.print "ON"
