# Malware-Detection-Lab

## Objective

This Malware Detection Lab uses Oracle VM VirtualBox to emulate two machines, a Linux machine running REMnux and a Windows 10 Enterprise machine running Flare VM. The Windows machine will act as the victim in a malware attack and the detonated malware will be analyzed to further understand its impacts and how it operates. Specifically, this lab will be detonating and analyzing the Zeus Banking Trojan.

### Skills Learned


- Configuring and deploying a locally-hosted virtual network.
- Static analysis of malware.
- Dynamic analysis of malware.
- Identifying and reporting Indicators of Compromise (IoCs).

### Tools Used

- <ins>VirusTotal</ins> will be used to fingerprint potentially malicious files and/or websites.
- <ins>PeStudio</ins> will be used to statically analyze the code of the malicious file.
- <ins>Floss</ins> is a command line utility that will be used to deobfuscate strings from the malicious file. This helps identify strings that malware authers have "packed" into the code.
- <ins>Capa</ins> is a command line utility that detects the capabilities of files and outputs the expected results. 
- <ins>Cutter</ins> will be used to reverse engineer the malware view its decompiled code.
- <ins>INetSim</ins> will be used to impersonate a DNS server, though this utility can simulate a number of internet protocols.
- <ins>Wireshark</ins> is a packet analyzer that will be used to analyze inbound and outbound traffic resulting from the detonated malware.
- <ins>Process Monitor</ins> will be used to monitor activity across the Windows file system that may be a result of the malware.
- <ins>Yara</ins> is a tool used to classify malware based on known patterns. 

## Steps

