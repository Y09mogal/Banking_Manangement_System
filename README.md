## Banking_Manangement_System
I have built a console based operable online banking management system using low-level C programming and system calls as a part of a mini-project in the Operating System course. 

#Steps:
To run the system
Firstly, run the program Sign_In.c to fill in the new data for accounts.

-> gcc Sign_In.c -o Sign_In

-> ./Sign_In

Then Run the Server

-> gcc -pthread Server.c -o Server

-> ./Server

Then Run the client

-> gcc Client.c -o Client

-> ./Client
