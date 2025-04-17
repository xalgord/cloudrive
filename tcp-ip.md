+-----------------+     +-----------------+     +-----------------+     +-----------------+
|   Application   | <--> |    Transport    | <--> |     Internet    | <--> |    Network      |
|     Layer       |     |      Layer      |     |      Layer      |     |     Interface   |
+-----------------+     +-----------------+     +-----------------+     +-----------------+
        |                       |                       |                       |
        |   (e.g., HTTP, FTP,   |   (e.g., TCP, UDP)  |   (e.g., IP, ICMP)  |   (e.g., Ethernet,|
        |    SMTP, DNS, SSH)   |                       |                       |     Wi-Fi, PPP)   |
        v                       v                       v                       v
+-------------------------------------------------------------------------------------+
|                                   Link Layer                                      |
|                               (Physical Layer + Data Link Layer)                  |
|   (Handles the physical transmission of data and provides error detection/correction)|
+-------------------------------------------------------------------------------------+

                                    Network Medium
                                    (e.g., Copper Wire, Fiber Optic Cable, Radio Waves)




+-----------------+
|   Application   |  (HTTP, FTP, SMTP, DNS, etc.)
+-----------------+
        ^
        | Data
        v
+-----------------+
|    Transport    |  (TCP, UDP) - Provides reliable/unreliable,
+-----------------+    connection-oriented/connectionless data transfer
        ^
        | Segments/Datagrams
        v
+-----------------+
|     Internet    |  (IP, ICMP) - Handles addressing and routing
+-----------------+
        ^
        | Packets
        v
+-----------------+
|   Network Access|  (Ethernet, Wi-Fi, PPP) - Physical connection
+-----------------+    to the network medium
        ^
        | Frames
        v
+-----------------+
|    Physical     |  (Cables, Connectors, Radio Waves) - Transmits
+-----------------+    raw bits
