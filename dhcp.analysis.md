# DHCP Analysis Notes

## Summary:
- Total Packets: 240
- DHCP Queries Observed: 5
- DNS Responses: 5 

## Key Observations:
- Primary Client IP: 192.168.2.244
- Common Query Types: A, AAAA, PTR
- Domains Queried:
  - example.com
  - google.com many more.

## Analysis Tools:
- Wireshark filters: `dns`, `dns.flags.response == 0`, `dns.flags.response == 1`

## QUESTIONS
  - these are the some Questions that can be answeres from this analysis.

  -Q1 what I.P. address is requested by the client.
  - ans 192.168.2.244

     -NOTE  
       for dhcp, client uses 0.0.0.0 as source & 255.255.255.255 as destination (broadcast). until they are assigned by ip in the network.
         boot no = 50 to find client requested i.p.
        boot no = 54 to find source i.p.

  -Q2 what is trsnsaction ID for dhcp release.
  -ans 0x2a7d544b to locatw this find the ack response packet after applying dhcp filter u will find the transaction id in info table.

  -Q3 MAC address of the client/
  - ans 00:0c:29:82:f5:94 in order to find client packet, below open DHCP table u will find out client mac address.
