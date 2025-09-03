LAB INSTRUCTIONS:



Subnet the 192.168.5.0/24 network to provide sufficient addressing for each LAN.
(Also, the point-to-point connection between R1 and R2).

Assign the first usable address to the PC in each LAN.

Assign the last usable address to the router's interface in each LAN.

Configure static routes on each router so that all PCs can ping eachother.


## Solution


LAN 1 - NETWORK -> 192.168.5.128/26
	BROADCAST -> 192.168.5.191/26
	1ST IP -> 192.168.5.129/26
	LAST IP -> 192.168.5.190/26
--------------------------------------------------

LAN 2 - NETWORK -> 192.168.5.0/25
	BROADCAST -> 192.168.5.127/25
	1ST IP -> 192.168.5.1/25
	LAST IP -> 192.168.5.126/25
--------------------------------------------------

LAN 3 - NETWORK -> 192.168.5.192/28
	BROADCAST -> 192.168.5.207/28
	1ST IP -> 192.168.5.193/28
	LAST IP -> 192.168.5.206/28
--------------------------------------------------

LAN 4 - NETWORK -> 192.168.5.208/28
	BROADCAST -> 192.168.5.223/28
	1ST IP -> 192.168.5.209/28
	LAST IP -> 192.168.5.222/28

--------------------------------------------------


P2P   - NETWORK -> 192.168.5.224/30
	BROADCAST -> 192.168.5.227/30
	1ST IP -> 192.168.5.225/30
	LAST IP -> 192.168.5.226/30