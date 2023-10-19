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
