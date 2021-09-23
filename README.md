# Network-Infrastructure
The aim of this project is to develop a network infrastructure for Lithan academy, We have to plan and design a network in which 30 devices will be connected to each other and they will be able to access several servers like Email server, FTP Servers and Internet servers.


## Project Background
The requirement which we received from our client Lithan academy is that they need a network in which they can share files, communicate through emails, have their own internet servers and 30 of the users should get external internet access along with the connection with all those servers.

So overall the requirements are:
* Sharing of files
* Email Communication.
* Internet Servers (Web & DNS Servers).
* Manage 30 devices from Different Departments.
* Grant external internet access to those 30 users.

## Rough Network Design
![image](https://user-images.githubusercontent.com/91181779/134574912-6f875c06-d1f3-4139-ba10-8f2ad26fa2d0.png)

## Network Design
![image](https://user-images.githubusercontent.com/91181779/134574993-2f7b771d-3158-4d5a-80c8-2505089767c0.png)

## Network Diagram
![image](https://user-images.githubusercontent.com/91181779/134575041-5fa7e59b-12cf-495b-83e0-06b516f174b0.png)

* Once the network design which was created using a network designing tool was approved the same was implemented in a simulation tool.
* The network diagram was made based on the requirements which we had received from our client. 
* There are nine different departments in the network including one for the printers and one for the servers. Each department is connected to a switch, then that switch is     connected to a main switch. 
* Main switch then connects to the router which provides the access to the external Internet.
* To simulate the use of external internet access I have created a external server which is hosting W3schools website, that sever is being accessed by a router in its network (external network).
* Then we connect our network with that network which simulates the use of internet.





