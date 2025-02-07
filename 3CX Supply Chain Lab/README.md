[3CX Supply Chain Lab](https://cyberdefenders.org/blueteam-ctf-challenges/3cx-supply-chain/)

![image](https://github.com/user-attachments/assets/1ed46638-2331-4473-b2bc-dd17f897bd90)

![image](https://github.com/user-attachments/assets/e324ef94-0bb1-466c-be09-f4cbb0a33d10)

https://www.virustotal.com/gui/file/59e1edf4d82fae4978e97512b0331b7eb21dd4b838b850ba46794d9c7a2c0983

![image](https://github.com/user-attachments/assets/60fe0821-ee79-447b-a073-36f9a9edcda4)

Q1. Understanding the scope of the attack and identifying which versions exhibit malicious behavior is crucial for making informed decisions if these compromised versions are present in the organization. How many versions of 3CX running on Windows have been flagged as malware?

https://www.sentinelone.com/blog/3cxdesktopapp-exposes-supply-chain-attack-risk/

![image](https://github.com/user-attachments/assets/4e76844c-691e-413a-9dc9-0befaf8f9541)

Q2. Determining the age of the malware can help assess the extent of the compromise and track the evolution of malware families and variants. What's the UTC creation time of the .msi malware?

![image](https://github.com/user-attachments/assets/ee020f25-691c-4910-891d-a7ad3917c82a)

Q3. Executable files (.exe) are frequently used as primary or secondary malware payloads, while dynamic link libraries (.dll) often load malicious code or enhance malware functionality. Analyzing files deposited by the Microsoft Software Installer (.msi) is crucial for identifying malicious files and investigating their full potential. Which malicious DLLs were dropped by the .msi file?

![image](https://github.com/user-attachments/assets/73f85cca-372a-4f9d-a915-83f91635d406)

Q4. Recognizing the persistence techniques used in this incident is essential for current mitigation strategies and future defense improvements. What is the MITRE sub-technique ID employed by the .msi files to load the malicious DLL?

![image](https://github.com/user-attachments/assets/7128d267-357b-42c8-ac10-aed9b41ac521)

https://attack.mitre.org/techniques/T1574/002/

![image](https://github.com/user-attachments/assets/5b50164c-1489-4041-a5a1-30d9fa07b811)

Q5. Recognizing the malware type (threat category) is essential to your investigation, as it can offer valuable insight into the possible malicious actions you'll be examining. What is the threat category of the two malicious DLLs?

![image](https://github.com/user-attachments/assets/5e19c4df-0c1c-4816-8a8d-9cbf30f800d3)

Q6. As a threat intelligence analyst conducting dynamic analysis, it's vital to understand how malware can evade detection in virtualized environments or analysis systems. This knowledge will help you effectively mitigate or address these evasive tactics. What is the MITRE ID for the virtualization/sandbox evasion techniques used by the two malicious DLLs?

https://attack.mitre.org/techniques/T1497/

![image](https://github.com/user-attachments/assets/8e677588-775a-4376-b06f-6c06fb786a43)

Q7. When conducting malware analysis and reverse engineering, understanding anti-analysis techniques is vital to avoid wasting time. Which hypervisor is targeted by the anti-analysis techniques in the ffmpeg.dll file?

![image](https://github.com/user-attachments/assets/c092fd5e-9044-4b80-8877-0dea7bad8c86)

https://attack.mitre.org/techniques/T1497/003/

![image](https://github.com/user-attachments/assets/6bd949b5-6e4f-4176-9669-141ec6c10378)

Q8. Identifying the cryptographic method used in malware is crucial for understanding the techniques employed to bypass defense mechanisms and execute its functions fully. What encryption algorithm is used by the ffmpeg.dll file?

![image](https://github.com/user-attachments/assets/097723c0-ea50-42a7-9452-8478c36d8438)

Q9. As an analyst, you've recognized some TTPs involved in the incident, but identifying the APT group responsible will help you search for their usual TTPs and uncover other potential malicious activities. Which group is responsible for this attack?

https://blog.qualys.com/vulnerabilities-threat-research/2023/04/03/3cxdesktopapp-backdoored-in-a-suspected-lazarus-campaign

![image](https://github.com/user-attachments/assets/92fd081c-6a61-4264-8655-3620f122c778)

![image](https://github.com/user-attachments/assets/5ae47283-d3b9-47b9-acf8-bd3853bffa87)
