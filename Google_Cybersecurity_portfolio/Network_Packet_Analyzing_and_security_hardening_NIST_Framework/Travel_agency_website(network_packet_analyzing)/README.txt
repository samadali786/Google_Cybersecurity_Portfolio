In this part of my portfolio I as a Securtiy Analyst used Wireshark tool for Network Packet Analyzing of fictional Travel agency company that have a alert from the monitoring system about the webserver, after trying to attempt the the web site of the traveling agencey company I recieved the "Connection Timed Out" error message from the server, following are the steps that I took to monitor the Network Traffic and to find the problem causing the error message.


1) I used the Wireshark tool to capture the Data packets.
2) After capturing the Data packets I go over the log files to analyze the packets that are captured 
3) After carefully analyzing the TCP handshake connections, I figure out the attacker IP address of "203.0.113.0" that keeps sending the 
   [SYN] request to the server many times causing the server to overload and giving the "Connection Timed Out" error message.  