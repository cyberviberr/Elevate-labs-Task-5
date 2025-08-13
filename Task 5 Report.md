#Task 5: Capture and Analyze Network Traffic Using Wireshark.

Objective: Capture live network packets and identify basic protocols and traffic types.
Tools: Wireshark

1. Started capturing my network traffic/interface

![wireshark network traffic image](images/Task_2_Wireshark_Traffice_Capture.png)

3. Browsed the website flipkart.com and filtered & observed HTTP, DNS, and TCP responses using Wireshark.
![HTTP response](images/Task_3_HTTP_Response.png)
![DNS response](images/Task_4_DNS_Response.png)
![TCP response](images/Task_5.5_TCP_Response.png)

4. Also identified and learnt about ARP, MDNS & LLMNR protocol responses
![ARP response](images/Task_5.6_ARP_Response.png)
![MDNS response](images/Task_5.7_MDNS_Response.png)
![LLMNR response](images/Task_5.8_LLMNR_Response.png)

5. Exported the capture as .pcap file
![.pcap ss](images/Task_pcap.png)

6. Summary During the capture, I identified the following protocols: HTTP, DNS, and TCP.
   HTTP traffic included GET and response packets between my browser and the web server.
   DNS queries resolved domain names to IP addresses, with multiple responses from the DNS server.
   TCP packets showed the three-way handshake and data transmission, with no retransmissions or errors observed. The capture involved traffic between my local IP and the server IPs, primarily using ports 80 (HTTP) and 53 (DNS).         Overall,the traffic appeared normal, with no signs of anomalies or performance issues.
