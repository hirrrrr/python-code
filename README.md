WIRESHARK IMPLEMENTATION USING PYTHON.
MODULES USED- SCAPY

This is a Python script that simulates a simple version of Wireshark. It uses the Scapy library to sniff packets on a network interface, apply a filter to the packets, and display the captured packets' details. Here is the overview of the script:

It imports the necessary libraries, including Scapy and OS, for capturing packets and performing system-related tasks.


FUNCTION WELCOME SCREEN():

It defines several functions, including the main function, which is called welcome_screen(). This function displays the welcome screen with three options: to start a new capture, to load a saved session, or to exit.

FUNCTION INTERFACE():

Depending on the user's input, it calls the interface() or load() function, which asks the user to select a network interface for capturing packets or to load a saved session, respectively.
The interface() function displays a list of network interfaces and asks the user to select one. After selecting the interface, the function calls the snip_page() function, which starts capturing packets using Scapy and displays them on the screen.

FUNCTION SNIP PAGE():

The snip_page() function captures packets on the selected interface and applies a filter to the packets based on the user's input. It then displays the packet details on the screen and offers four options: to capture packets again, to examine a captured packet, to save the captured packets, or to exit the session.

FUNCTION EXAMINE():

The examine() function examines a captured packet and displays its details on the screen.

FUNCTION SAVE():

The save() function saves the captured packets to a file.




