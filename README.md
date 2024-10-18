Network Traffic Analysis with NetworkMiner

Description

This repository showcases a successful network traffic analysis using NetworkMiner, a powerful network forensics tool. The attached image highlights the process of extracting credentials (username and password) from a .pcap file, illustrating how sensitive information can be analyzed from network packet captures.

The tasks performed in this exercise comes from TryHackMe's NetworkMiner room. The extracted credentials indicate the use of NTLMv2, a protocol commonly associated with Microsoft environments. The exercise emphasizes the importance of network security and the risks associated with intercepted network traffic.

Screenshot Overview:

The included image shows the following steps:

1. Extraction of the Username and Password: Successfully extracted credentials from the mx-4.pcap file. 
    - Username: `B\Administrator`
    - Password: `$NETNTLMv2$#B$136B077D942D9A63$FBFF3C`
   
2. NetworkMiner Interface: The NetworkMiner tool interface displays various network traffic details, such as IP addresses, hostnames, servers, and client details, emphasizing intercepted NTLM challenge-response passwords.

3. Correct Answer Confirmation: After submitting the extracted credentials in the TryHackMe environment, the "Woop woop! Your answer is correct" message confirms the accuracy of the findings.

4. TryHackMe Task Progress: I have completed tasks related to username and password extraction, as shown in Task 5 and Task 6. The progress is tracked in real-time on the platform, with badges awarded for streaks.

Tools Used:

- NetworkMiner: A passive network traffic analysis tool used for packet capture (PCAP) parsing and data extraction.
- TryHackMe: An online cybersecurity learning platform where this exercise was performed, focusing on network forensics.

 Steps to Reproduce:
 
1. Download NetworkMiner from [NetworkMiner Official Site](https://www.netresec.com/?page=NetworkMiner).
2. Open a .pcap file in NetworkMiner.
3. Analyze the captured traffic for credential extraction.
4. Follow similar TryHackMe network analysis exercises for guided hands-on learning.

 Learning Outcomes:
 
- Understanding the importance of securing network traffic.
- Familiarity with network packet analysis using NetworkMiner.
- Ability to extract sensitive information such as NTLMv2 credentials from captured traffic.

