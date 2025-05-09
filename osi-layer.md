# OSI Layer

## Introduction
The OSI (Open Systems Interconnection) model is a framework for describing how various systems communicate over a network. It divides the communication process into seven tiers, each with a different role. This makes it easier to construct and troubleshoot networks.

## Layers of OSI

1. **Physical Layer**
   This is the first layer, which deals with physical equipment such as cables and switches. It transfers raw data over a physical medium.

2. **Data Link Layer**
   The second layer ensures that data is transmitted without errors. It manages MAC addresses and includes the essential tests to detect and repair communication issues.

3. **Network Layer**
   This layer uses IP addresses to determine the optimum path for sending data. It handles the routing of devices across multiple networks. Routers operate at this layer.

4. **Transport Layer**
   It guarantees that data is provided complete and in the correct order. It makes use of protocols such as TCP and UDP to provide dependable or rapid delivery.

5. **Session Layer**
   This layer manages application sessions. It initiates, maintains, and terminates connections, ensuring that data flows seamlessly between systems.

6. **Presentation Layer**
   This layer prepares data for use by the application layer. It can handle data format translation, compression, and encryption.

7. **Application Layer**
   This is the layer that people engage with directly. It includes web browsers, email clients, and other network-based programs.

## Conclusion
The OSI model enables engineers to comprehend network processes in an organized manner. Each layer plays an important role in transmitting data across systems.

## References
* https://www.youtube.com/watch?v=vv4y_uOneC0  
* https://www.geeksforgeeks.org/layers-of-osi-model/