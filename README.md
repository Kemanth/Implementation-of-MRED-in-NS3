# Implementation-of-MRED-in-NS3
## Course Code: CS704
## Mini Project
## Overview

Modified RED (MRED) [1] is a variant of Random Early Detection (RED) [2] in which the packets are dropped aggressively only when average queue size and instantaneous queue size is greater than Maxth . This repository provides an implementation of MRED in ns-3.26 [3]. 

## Simulating MRED

To simulate NLRED algorithm, the attribute MRED must be set to true, as shown below:

Config::SetDefault ("ns3::RedQueueDisc::MRED", BooleanValue (true));

## References

[1] Gang Feng, A. K. Agarwal, A. Jayaraman, and Chee Kheong Siew (2004). Modified RED: Modified RED Gateways Under Bursty Traffic.

[2] Floyd, S., & Jacobson, V. (1993). Random early detection gateways for congestion avoidance. IEEE/ACM Transactions on networking.

[3] https://www.nsnam.org/ns-3-26/
