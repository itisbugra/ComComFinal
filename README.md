# Final Exam for Computer Communication

#### (10 points) For the network below, calculate _Distance_ and _NextHop_ values for Node e based on the vectors arriving from Node c, Node d and Node f.

|   | C | D | F | e |
| --- | --- | --- | --- | --- |
| A | 10 | 6 | 12 | Distance: 12, NextHop: c |
| B | 6 | 8 | 8 | Distance: 8, NextHop: c |
| C | 0 | 2 | 5 | Distance: 2, NextHop: c |
| D | 2 | 0 | 7 | Distance: c, NextHop: 4 |
| E | 2 | 6 | 4 | Distance: 0, NextHop: c |
| f | 5 | 7 | 0 | Distance: 4, NextHop: f |

#### (10 points) In the figure below, considering the IP address and port numbers written, complete the NAT translation table, the headers at Step 2, Step3, and Step 4.

| NAT translation table |
| --- |
| WAN side addr | LAN side addr |
| 138.76.55.7:5005 | 10.0.0.1:3350 |

| Source | Destination |
| :-- | :-- |
| 2) 138.76.55.7.5005 | 128.119.40.50:80 |
| --- | --- |
| 3) 128.119.40.50:80 | 138.76.55.7:5005 |
| 4) 128.119.40.50:80 | 10.0.0.1:3350 |

#### (10 points) Assume that the IP packet below enters to a network of which MTU is 1000 Bytes fragments are formed? Draw and fill the fields shown below for each fragment header.

|   | Length = 2500 | ID = x | Fragflag = 0 | Offset = 0 |   |
| --- | --- | --- | --- | --- | --- |
| Answer | Length = 1000 | ID = x | Fragflag = 1 | Offset = 0 |   |
|   | Length = 1000 | ID = x | Fragflag = 1 | Offset = 122.5 |   |
|   | Length = 540 | ID = x | Fragflag = 0 | Offset = 245 |   |

#### (10 points) In the table of an IP router, 58.11.32.60/22, 58.11.32.48/22 and 58.11.32.56/22 are using outgoing links. It is possible to aggregate these addresses? If yes show. If no explain.

#### (10 points) In the link state routing method, explain the way the routing tables are formed in three steps (core basic operations).

#### (40 points) Answer the following question shortly.

1. A datagram queued at front of a switch input port prevents the others from moving forward, this is called …………………………………….
2. In Network 1, most of application are generating real time high priority packets to be transmitted. In Network2, only a few applications are generating real time high priority packets. In which network do you suggest the use of priority queueing? Why?
3. How does &quot;hot potato routing&quot; work at the AS based routing?
4. In the sliding window protocol employing selective repeat, if the distance between the sender and the receiver is 2500 km: the propagation speed is 200 000 km/sec: the frame size is 500 bytes: and the date rate is 1.6 Mbps, what should be the minimum timer value?
5. For the subnet 22.0.0.0/20, find the number of hosts that can be addressed (disregarding the special address), subnet mask, and subnet broadcast address and give the necessary explanation.
6. What is flow management? How does it work in TCP?
7. What is ARP? Explain its use. At which layer does it work?
8. In a sliding window based protocols, what is the effect of increasing RTT on utilization? Explain. (Assume that all the other parameters are kept as the same).
