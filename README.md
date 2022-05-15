# Install-OS-in-Rpi4

## Task number: 08
## Task name: Installing OS on Raspberry pi4

## Reference
https://www.circuitbasics.com/how-to-install-the-raspberry-pi-operating-system/

For basics: https://www.circuitbasics.com/getting-started-with-the-raspberry-pi/

## Components used
MicroSD card, Raspberry pi board, HDMI cable, USB keyboard, mouse, power supply for board.

## Connections
1. Insert microSD card to CPU or laptop using a card reader.
2. Format the SD card, if necessary.
3. Download OS(Raspberry pi imager)  into the microSD from Raspberry Pi OS – Raspberry Pi
4. After completing download, run the executable file and install the software.
5. Choose OS- select the first option, 32 bit(recommended)
6. Select the appropriate microSD card.
7. Write OS image file to microSD.
8. Once writing and verifying completes, enter continue.
9. Go to file explorer, open the disk folder. 
10. Search for config file, uncomment the #hdmi_force_hotplug=1 line. Save the change, and close the file.
11. Insert this SD card into a Raspberry pi board, connect HDMI cable to desktop, connect keyboard and mouse.
Username is pi, and the password is raspberry.
12.Finish setup.


## Problems faced
Some microSD cards were corrupted, so there was a problem with formatting them, so I just changed the SD card.
Monitor going to sleep, because of no signal: make sure power is supplied for the board. Also, check if the hdmi line in config file (#hdmi_force_hotplug=1 line) is uncommented.

## Output


