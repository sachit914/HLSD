# HLSD


# Networking Protocol

### 7 layers of network protocol  (osi model)

1) Physical Layer: Transmits raw bits over a physical medium like cables or wireless.
2) Data Link Layer: Provides error-free transmission of frames between devices on the same network and manages access to the shared medium.
3) Network Layer: Determines the best path to route data packets from the source to the destination across the network.
4) Transport Layer: Ensures reliable data transfer between two devices on different networks, managing error detection, correction, and flow control.
5) Session Layer: Manages and controls the dialog between two devices, ensuring communication is organized and synchronized.
6) Presentation Layer: Translates data between the application and transport layers, handling data encryption, compression, and translation services.
7) Application Layer: Provides end-user services and interfaces, enabling communication between software and lower OSI layers.


                                               application layer
                                                      /\
                                                     /  \
                                                    /    \
                                                   /      \
                             client server protocol       peer to peer protocol
                                                  |          |
                                            - http            -web RTC 
                                            - Ftp             
                                            - smtp
                                            - web socket


### client server archictecture

![1](https://github.com/sachit914/HLSD/assets/137917052/84afb168-a2e6-4312-a4c2-256f3cfd7959)

its one way communication

Note: always client makes the initialization to talk with server (http,ftp,smtp)

but web socket is different 

web socket is bi-directional both client and server and can initialize to talk   (used on messaging app like whatapp,telegram)
![1](https://github.com/sachit914/HLSD/assets/137917052/24b9e4e5-8721-4d0e-8df9-70cd6eed90bb)

### peer to peer 

every thing can talk with each other

![1](https://github.com/sachit914/HLSD/assets/137917052/dd570897-389b-44e5-911b-ed44460e9a00)



### Transport layer

                                    transport
                                        /\
                                       /  \
                                      /    \
                                     /      \
                               tcp/ip       udp/ip

web rtc uses udp 

video chat feature uses web rtc

