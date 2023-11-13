UDP Python Pinger

Cade Thornton

11/12/2023

ENCE 3321

## Table of Contents

-------

+ [Introduction](#Introduction )
+ [main()](#main())
    * [Description](#Description)
+ [socket_create()](#socket_create())
    * [Description](#Description)
+ [ping_client()](#ping_client())
    * [Description](#Description)
+ [ping_statistics()](#ping_statistics())
    * [Description](#Description)
+ [Conclusion](#Conclusion)

--------

## Introduction 

<p align="center"> 
The objective of this project is to develop a UDP client in Python, functioning as a pinger. This client interacts with a designated server using UDP sockets. It operates by sending a UTF-8 encoded message to the server and awaits a response, with the possibility of simulated packet loss being factored in. The assignment involves calculating the round trip time (RTT) for each of the ten transmitted packets, as well as their cumulative RTT. The RTT for each packet is displayed only if the server's response is received. After the transmission of all packets, the client displays pinger statistics, which include the total RTT, packet loss percentage, and the total number of packets transmitted. The program is built using Python packages such as 'time', 'sys', and 'socket'.
</p>


-------

## main()

<p align="center">
    The main function is simply a call to the three functions below:
</p> 

```
if __name__ == "__main__":
    socket_create()
    ping_client()
    ping_statistics()
```

------

## socket_create()

-------

## ping_client

-------

## ping_statistics()


-------

## Conclusion




