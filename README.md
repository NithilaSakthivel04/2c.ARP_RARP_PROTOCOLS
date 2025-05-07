# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
P
## PROGRAM - ARP
![Screenshot 2025-04-13 034552](https://github.com/user-attachments/assets/e43e9135-6d66-43c4-a3ba-12b8efa540dd)

## OUPUT - ARP
![Screenshot 2025-04-13 034604](https://github.com/user-attachments/assets/ea931fa4-a81b-497c-a9e9-23dbca354f73)

## PROGRAM - RARP
![Screenshot 2025-04-13 040218](https://github.com/user-attachments/assets/bca57a37-aa0b-4bd6-a2b6-e4f99725b5fc)

## OUPUT -RARP
![Screenshot 2025-04-13 040218](https://github.com/user-attachments/assets/378bd7c8-f9df-4fa3-b11f-a9579ed16479)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
