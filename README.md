## Anbefalt git mappe på din PC:

 C:\CiscoPacketTracer

## DHCP_and_DNS.pkt løsning:

Diagnostics: 
Lsia can not ping any computers on the network

Fix:

1. Lisa needs to enable DHCP 
2. DHCP needs to be turned on in the DHCP server
3. Default Gateway needs to be set to 10.1.1.1 in the DHCP server
4. DNS server needs to be set to 10.1.1.50 in DHCP server

## DenyJohnyAccessToNyhet.com.pkt solution:

Oppgave: 
Johny har tilgang til Nyhet.com, men skal ikke ha det. De andre datamaskinene på nettverket skal fortsatt ha tilgang etter at Johny har blitt nektet tilgang. 

Fix:

1. Aktiver firewall på Server.
2. Legg til "deny" regel med Johny sin IP
3. Legg til "allow" regel med 10.1.1.0 nettverket

![](images/firewall.png)

## DenyJohnyAccessToNyhet.com.pkt solution:

Oppgave: 
Johny har tilgang til Nyhet.com, men skal ikke ha det. De andre datamaskinene på nettverket skal fortsatt ha tilgang etter at Johny har blitt nektet tilgang. 

Fix:

1. Aktiver firewall på Server.
2. Legg til "deny" regel med Johny sin IP
3. Legg til "allow" regel med 10.1.1.0 nettverket



