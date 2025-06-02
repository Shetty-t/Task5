📂 Overview
This report summarizes the analysis of network packets captured using Wireshark. The analysis includes DNS, ICMPv6, and HTTP protocols.

🔍 Captured Packets
Here’s the breakdown of the captured packets:

💻 DNS (Domain Name System) Analysis
Source IP: 192.168.248.108
Destination IP: 192.168.248.12
Packet Details:
Total Packets: 11
Notable Responses: A notable response with CNAME records from digicert.com.
Key Observations:
Frame Count: 240 bytes on wire captured
Protocols Involved: DNS, UDP
Highlighted Response:
CNAME record for crl3.digicert.com with a response code indicating success.
🚀 ICMPv6 (Internet Control Message Protocol)
Source IP: 2404:6800:4007:835::200e
Destination IP: 2401:4900:91e0:26f8:: (PING)
Key Observations:
Frame Size: 98 bytes on wire.
Request ID: Sequence numbers show multiple ping requests and responses.
🌐 HTTP (Hypertext Transfer Protocol) Analysis
Source IP: 23.201.55.145
Destination IP: 192.168.248.12
Packet Details:
Total Packets Analyzed: 5
Notable Response: HTTP/1.1 200 OK received from the server.
Key Observations:
Frame Count: 245 bytes on wire.
Content-Type: Text/plain returned from the web server.
Response Codes: Various GET requests with 200 status indicating successful retrieval.
