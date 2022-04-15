# Ex3-OS
## Or Cohen & Shlomi Lantser.

# Description
In this project we implemented a server that using threads instead of forks,
We had an example that used forks and changed it to multi threading.
The goal on this project is to show that threading and forks working similar and show that we can reach the same goals by using one or another.
The programm is written on C programming language.

Classes on this project :
                  
* **Server** - Implementation of server that handling new connection by threads , each connection has its own thread and its supports many connections.
                  
* **Client** - The client connecting to the server and recieve message from the server, we used 127.0.0.1 to connect the server.
                 
## Running guide:

* Clone this ripository
* Open the directory and open it in terminal
* Use the command `make all` to create all the needed files and the executable ones.
* Use the command `./serverexe` to start server receiving and listening to new connections.
* Use the command `./clientexe [ipaddr]` ipaddr is the ip address that using to connect the sever aka : 127.0.0.1
* Use the command `make clean` to clean all the files after you done.


## Video of running:

https://user-images.githubusercontent.com/92504985/163593148-6602ee97-6115-4985-8b03-418ef618bfbd.mp4

        
                 
