LAB INSTRUCTIONS:

1. Use the CLI to check the current STP topology.  What is the current root bridge?
    What is the STP role/state of each port on each switch?

	SW1 - Non- root , fa0/3 root port
	SW2 - Root Switch , all destination ports
	SW3 - Non - root , fa0/2 root port
	SW4 - Non- root , fa0/1 root port

2. Configure SW1 as the primary root for VLAN1 and the secondary root for VLAN2.
    Configure SW2 as the primary root for VLAN2 and the secondary root for VLAN1.
    What is the STP role/state of each port on each switch now?


3. Increase the VLAN1 cost of SW4's F0/2 interface to 100.
    Does SW4 select a different root port?  Why/why not?

    It did change from f0/2 to f0/1 since the cost increase of f0/2

4. Increase the VLAN1 port priority of SW1's F0/1 to 240.
    Does SW3 select a different root port?  Why/why not?
   
    It did not change. F0/1 still is the root port 
	

5. Configure PortFast and BPDU Guard on the F0/3 interfaces of SW3/SW4.
 