
## Purpose and Scope

The purpose of this project is to implement TCP. 

Phase 2 will be to tweak TCP for better metrics.

Phase 3 is to build my own protocol from scratch using what I have learned.

## Learn about OSI + TCP

I need to learn about the following:

* Layers of the OSI Model
* How TCP works
* Socket programming in python

## -- Decide on Protocol Features

* Connection-based?
* Reliability and flow-control?
* Packet structure?

## Write the Protocol Specification

* Packet Format
* Sequence Numbers
* Control Flags
* Checksum

## Choose Language + Libraries

* C/C++?
* Python?
* Rust?

## Implement Prototype

### Socket Programming

Server: waits for connections
Client: connects to the server and sends data

### Custom Packet Structure

## Add Features Gradually

* Reliability
* Sequence Numbers
* Timeouts + Retransmission
* Congestion Control

## Test + Debug

Test on localhost first, then try different network setups.

Use tools like Wireshark to inspect the packets being sent to verify they match your protocol.

Simulate packet loss and delays to ensure your protocol handles edge cases.

## Documentation

## Testing Tools

Wireshark: packet inspection + analysis
Netcat: quick testing of basic network communication
Iperk: test network throughput
