LAB INSTRUCTIONS:

1. Check the routing tables of R1 and R2.  
    i) Which dynamic routing protocol is Enterprise A using?
	OSPF
    ii) Which route will be used if PC1 tries to access SRV1?
	R2
	
    iii) Which route will be used if PC1 tries to access remote server 1.1.1.1 over the Internet?
	 ISPBR1
	

    Test by pinging SRV1 and 1.1.1.1

2. Configure floating static routes on R1 and R2 that
    allow PC1 to reach SRV1 if the link between R1 and R2 fails.
    Do the routes enter the routing tables of R1 and R2?
	
	No the routes are not added 

3. Shut down the G0/2/0 interface of R1 or R2.
    Do the floating static routes enter the routing tables of R1 and R2?
    Ping from PC1 to SRV1 to confirm.
	The floating static route is added when the G0/2/0 is down
     
    