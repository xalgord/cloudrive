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
