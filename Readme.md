#Introduction
The scripts in this repository is used to control the access use of a 3D printer.

The printer power supply cable connecter to a controled power bar.
the power bar on/off is controlled by the script.
the user must scan a code bare to open a browser window to enter following informations :
 - First Name
 - Last Name
 - email
 - time needed to print

then, if all information is ok, script will power on the printer for the time need + 30 minutes margin.


#How to?
- Hosts a webpage to collect user input (name, email, BL, and printing duration).
- Checks if the required fields are filled out.
- Sends an email notification if required fields are missing.
- Calculates the duration, including the 30-minute additional buffer.
- Displays a "machine in use" message along with a countdown.
- Releases the machine for the next user after the countdown ends.
