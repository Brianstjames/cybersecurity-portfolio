Today we covered Lesson 3.1 Configuring Interfaces and Switches. 
Network interface cards (NICs) connects system to the physical or wireless medium.
It's a data link protocol. It's responsible for converting binary data (1s and 0s) into electrical signals (digital signals) that will be transmitted via the medium.
Network interface cards or Network adapters are built into the system board, plugged into an open expansion slot or inserted into existing port (usb).
NICs operate at the first two layers of the Open system interconnection reference model: the physical and data link.
The ethernet frame format: ethernet encapsulates the payload from higher layer protocols within a protocol data unit (PDU)
Media Access Control Address Format: mac address is a physical unique identifier burned into the ROM of every NIC.
MAC addresses have 12 digits, which adds up to 48 bits/6 bytes written hexadecimally. Each number ranges from 0-9 or A-F (10-15).
Each hexa digit equals 4 binary bits.
MAC Broadcast Address: Preamble, SFD, Destination MAC, Soruce MAC, Ether Type, Payload, and FCS.
Frame length shouldn't exceed  1518 bytes.
