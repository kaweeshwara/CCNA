LAB INSTRUCTIONS:

1. Configure the appropriate hostnames and IP addresses on each device.  Enable router interfaces.
    (You don't have to configure ISPR1)

2. Configure a loopback interface on each router (1.1.1.1/32 for R1, 2.2.2.2/32 for R2, etc.)

3. Enable OSPF directly on each interface of the routers.
    Configure passive interfaces as appropriate.
 
4. Configure the reference bandwidth on each router so a FastEthernet interface
    has a cost of 100.

5. Configure R1 as an ASBR that advertises a default route in to the OSPF domain.

6. Check the routing tables of R4.  What default route(s) were added?
    (watch the video for a brief explanation)

7. Use Simulation mode to view the OSPF Hello messages being sent by the routers.
    What fields are included in the Hello message?