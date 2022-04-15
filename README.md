# Ex3-OS
by Or Cohen & Shlomi Lantser.
             
             
In this project we implemented a server that using threads instead of forks,
We had an example that used forks and changed it to multi threading.
The goal on this project is to show that threading and forks working similar and show that we can reach the same goals by using one or another.
The programm is written on C++ promgramming language.

Classes on this project :
                  
* Server - Implementation of server that handling new connection by threads , each connection has its own thread and its supports many connections.
                  
* Client - The client connecting to the server and recieve message from the server, we used 127.0.0.1 to connect the server.
                 
## Run guide:

Open terminal and run the command "make all". In this way we create two exe files to run.  
We will open another terminal, and simply type in the first terminal " ./Server " and in the other " ./Client 127.0.0.1"  

1.Open the directory and open it in terminal
2.Use the command "make all" to create all the needed files and the executable ones.
3.Use the command "./server" to start server receiving and listening to new connections.
4.Use the command "./client [ipaddr]" ipaddr is the ip address that using to connect the sever aka : 127.0.0.1


##Video of running:



                 
                 
