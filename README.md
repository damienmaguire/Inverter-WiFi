# Inverter-WiFi
RaspberryPi based adapter to allow WiFi access to the OpenSource EV Inverter

Uses a RaspberryPi Zero W and a generic RS232 converter to allow wifi access to the Tesla or other inverter boards based on the
Heubner design.

Download the 16gig SD card image here : 
https://www.dropbox.com/s/nj4xrppf1lgmr4n/inverterpizw.img.gz?dl=0

Flash the card with the image.


If you don't know how here is a good starting point : https://www.raspberrypi.org/documentation/installation/installing-images/


Connect the inverter to the Pi serial port. Use an RS232 adapter for Tesla boards or direct connect for Heubner versions.

Connect a power supply.

Boot up the pi and inverter boards.

WiFi access point called "Inverter" will apear.

Connect to this with any device (phone,laptop,tablet,Commodore 64).

Passphrase is "inverter123".

Point a browser to 192.168.42.1 and the web interface should pop up.


Instruction PDFs in the repo.


Enjoy.


