# Web-server-compromise-investigation-wireshark-trafffic-analysis
Investigated network traffic using Wireshark to identify a compromised web server, web shell deployment, reverse shell activity, and data exfiltration
# Web Server Compromise Investigation (Wireshark)

## Objective
Analyze network traffic to investigate a suspected web server compromise and identify attacker activity.

## Tools Used
- Wireshark
- PCAP network capture
- HTTP traffic analysis
- Packet inspection

## Lab Activities
• Analyzed captured network traffic using Wireshark  
• Identified suspicious HTTP requests to the web server  
• Detected web shell deployment through abnormal POST requests  
• Observed reverse shell communication between attacker and compromised host  
• Investigated outbound traffic indicating potential data exfiltration  

## Indicators Discovered
- Suspicious HTTP POST requests
- Web shell upload activity
- Reverse shell connection
- Unusual outbound traffic

## Security Concepts Demonstrated
- Network traffic analysis
- Incident investigation
- Web server compromise detection
- Threat hunting

## Lessons Learned
Analyzing packet captures can reveal attacker behavior such as web shell deployment, command execution, and data exfiltration attempts. Tools like Wireshark are critical for incident response and forensic investigations.
