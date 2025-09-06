LAB INSTRUCTIONS:


1. Configure the switch interfaces connected to PCs as access ports in the correct VLAN.

2. Configure the connection between SW1 and SW2 as a trunk, allowing only the necessary VLANs.
    Configure an unused VLAN as the native VLAN.
    **Make sure all necessary VLANs exist on each switch**

3. Configure the connection between SW2 and R1 using 'router on a stick'.
     Assign the last usable address of each subnet to R1's subinterfaces.

4. Test connectivity by pinging between PCs.  All PCs should be able to reach each other.