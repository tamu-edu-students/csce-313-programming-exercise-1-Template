# <p align="center">PA1: Client-Server IPC using Named Pipes<p>

**Introduction**

In this assignment, you will write a client program that connects to a given server. 
The server hosts several electrocardiogram (ECG) data points of 15 patients suffering from various cardiac diseases. The client has to communicate with the server such that it can fulfill two main objectives:

1. Obtain individual data points from the server.
2. Obtain a whole raw file of any size in one or more segments from the server.

The client has to send properly-formatted messages to the server using a communication protocol that the server defines to implement this transfer functionality. 

**Tasks**

- [ ] Run server as a child of the client
- [ ] Request data points
  - [ ] a single data point
  - [ ] 1000 data points
- [ ] Request files (with and without differing buffer capacity)
  - [ ] CSV file
  - [ ] binary file (of differing sizes)
- [ ] Request a new channel
- [ ] Close channels

See the PA1 module on Canvas for further details and assistance.
