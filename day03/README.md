LAB INSTRUCTIONS:


1. Change the hostnames of the router and switch to the appropriate names (R1, SW1)
     ##Use the 'hostname' command in global configuration mode##

2.  Configure an unencrypted enable password of 'CCNA' on both devices

3. Exit back to user EXEC mode and test the password

4.  View the password in the running configuration

5. Ensure that the current password, and all future passwords, are encrypted

6. View the password in the running configuration

7. Configure a more secure, encrypted enable password of 'Cisco' on both devices

8. Exit back to user EXEC mode and then return to privileged EXEC mode.
    Which password do you have to use?

9. View the passwords in the running configuration.
     What encryption type number is used for the encrypted 'enable password'?
     What encryption type number is used for the encrypted 'enable secret'?

10. Save the running configuration to the startup configuration







################################################################################


SOLUTION :

current configuration : 758 bytes
!
version 15.1
no service timestamps log datetime msec
no service timestamps debug datetime msec
no service password-encryption
!
hostname R1
!
!
!
enable secret 5 $1$mERr$Bok4KDfVutXOJolNq009M/
enable password CCNA
!

!
!
ip cef
no ipv6 cef
!

!
license udi pid CISCO2911/K9 sn FTX1524X577-
