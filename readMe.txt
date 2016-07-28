This project demonstrates the virtual com port of the stm32f3Discovery board.
The project is an openStm32 project (http://www.openstm32.org). 

In order to get the programm running, you must use a second USB-cable and 
connect the second usb conector ("USB USER") with the PC. Of cours you can 
also first load the programm on the controller and swithc the USB-cable 
afterwards to the other connector. However, if you also want to debug your 
program, you need a second cable.

Read also the readMe.txt file in the directory inc_peripheral_lib!!!

The program is basically taken from the Nelson Mandela Metropolitan University 

      http://controlsoft.nmmu.ac.za/STM32F3-Discovery-Board 

(Files VCP-Files.zip and Examples-VCP.zip).

You need the VCP-driver on Windows (STSW-STM32102). I did not check it for Linux.

I had a bit a problem when using putty on the PC. I had to use Ctrl-J in order to 
get putty to send a new line character. TeraTerm is a bit easier, you can configure 
it so that by pressing the "Enter" key a new line character is sent too (not only a 
carriage return). I was not able to configure putty in this way. 