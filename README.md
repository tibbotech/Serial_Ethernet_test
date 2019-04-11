# Serial_Ethernet_test

This project implements the simplest "serial device server" possible. There is a single TCP
'connection (passive opens only). Once this connection is established, whatever is received
'through TCP is sent out via the serial port and vice versa.
'
'	ATTENTION! READ THE COMMENTS IN CODE! YOU MIGHT NEED TO CHANGE THE PROGRAM! For example,
'you may need to set correct IP address, baudrate, etc.
