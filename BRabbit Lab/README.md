[BRabbit Lab](https://cyberdefenders.org/blueteam-ctf-challenges/brabbit/)

![image](https://github.com/user-attachments/assets/72557809-67d2-498a-a127-8738d3246d0f)

![image](https://github.com/user-attachments/assets/731bc40e-d589-48f8-b569-ce3be2c486d1)

Q1. The phishing email used to deliver the malicious attachment showed several indicators of a potential social engineering attempt. Recognizing these indicators can help identify similar threats in the future.
What is the suspicious email address that sent the attachment?

![image](https://github.com/user-attachments/assets/701b437a-aae8-461e-8f9e-8adf16281ed8)

Q2. The ransomware was identified as part of a known malware family. Determining its family name can provide critical insights into its behavior and remediation strategies.
What is the family name of the ransomware identified during the investigation?

![image](https://github.com/user-attachments/assets/6458e4af-563d-4514-ab3c-d361f02b6eca)

https://www.virustotal.com/gui/file/94a27de42da1bfb8a0f8ffe89ce7b1ca6f93e0accc59ad50201ec585940c17fc

![image](https://github.com/user-attachments/assets/d805099a-9e6b-40b8-8477-0b73e03e077b)

![image](https://github.com/user-attachments/assets/a22a33cd-5467-4d9f-b84e-5e621950219b)

Q3. Upon execution, the ransomware dropped a file onto the compromised system to initiate its payload. Identifying this file is essential for understanding its infection process.
What is the name of the first file dropped by the ransomware?

https://any.run/report/630325cac09ac3fab908f903e3b00d0dadd5fdaa0875ed8496fcbb97a558d0da/5179a31a-bd5c-46f9-9aef-71d0cd1ed1fb

https://app.any.run/tasks/5179a31a-bd5c-46f9-9aef-71d0cd1ed1fb

![image](https://github.com/user-attachments/assets/96912d53-56fa-4ba5-a569-a4c88e9a6ad3)

Q4. Inside the dropped file, the malware contained hardcoded artifacts, including usernames and passwords that could provide clues about its origins or configuration.
What is the only person's username found within the dropped file?

![image](https://github.com/user-attachments/assets/4e23181e-ac68-42ec-9858-613e20fbfece)

Q5. After execution, the ransomware communicated with a C2 server. Recognizing its communication techniques can assist in mitigation.
What MITRE ATT&CK sub-technique describes the ransomware’s use of web protocols for sending and receiving data?

https://www.virustotal.com/gui/file/630325cac09ac3fab908f903e3b00d0dadd5fdaa0875ed8496fcbb97a558d0da/behavior

![image](https://github.com/user-attachments/assets/6afeba09-4d92-40ac-ad53-3554a9ee0185)

![image](https://github.com/user-attachments/assets/25c8d6a1-49e6-43e1-8ef5-cf3b49369d4d)

Q6. Persistence mechanisms are a hallmark of sophisticated ransomware. Identifying how persistence was achieved can aid in recovery and prevention of reinfection.
What is the MITRE ATT&CK Sub-Technique ID associated with the ransomware’s persistence technique?

![image](https://github.com/user-attachments/assets/8b98062f-7d3b-413e-ac92-dea314fd5220)

![image](https://github.com/user-attachments/assets/46ffc8e2-5a91-47fb-8b56-270258d9e06b)

Q7. As part of its infection chain, the ransomware created specific tasks to ensure its continued operation. Recognizing these tasks is crucial for system restoration. What are the names of the tasks created by the ransomware during execution?

![image](https://github.com/user-attachments/assets/471c4bd9-da8b-4ce3-b745-7a183f6f072a)

![image](https://github.com/user-attachments/assets/3cb20b6d-2b43-4658-8f96-a20551c6f064)

Q8. the malicious binary dispci.exe displayed a suspicious message upon execution, urging users to disable their defenses. This tactic aimed to evade detection and enable the ransomware's full execution. What suspicious message was displayed in the Console upon executing this binary?

![image](https://github.com/user-attachments/assets/5d70fe40-6caa-4974-a8cf-0bd4fc08df16)

Q9. To modify the Master Boot Record (MBR) and encrypt the victim’s hard drive, the ransomware utilized a specific driver. Recognizing this driver is essential for understanding the encryption mechanism.
What is the name of the driver used to encrypt the hard drive and modify the MBR?

https://blog.qualys.com/vulnerabilities-threat-research/2017/10/24/bad-rabbit-ransomware

![image](https://github.com/user-attachments/assets/8b3cdc14-44c4-4d6a-89b7-5819cea0a5e3)

Q10. Investigators identified a driver file used by the ransomware for encryption. The hash of this file is a vital artifact for correlation with threat intelligence databases.
What is the SHA256 hash of the critical driver file?

![image](https://github.com/user-attachments/assets/c522b5e9-f676-4227-a82d-9383a3582b1e)

Q11. Attribution is key to understanding the threat landscape. The ransomware was tied to a known attack group through its tactics, techniques, and procedures (TTPs).
What is the name of the threat actor responsible for this ransomware campaign?

https://attack.mitre.org/software/S0606/

![image](https://github.com/user-attachments/assets/6244f541-f20e-4079-a8fe-5587e08dd7ae)

Q12. The ransomware rendered the system unbootable by corrupting critical system components. Identifying the technique used provides insight into its destructive capabilities.
What is the MITRE ATT&CK ID for the technique used to corrupt the system firmware and prevent booting?

https://attack.mitre.org/techniques/T1495/

![image](https://github.com/user-attachments/assets/041f467a-9e63-44a8-ac84-0e3f1043a3a7)

![image](https://github.com/user-attachments/assets/8582b8a6-357e-4922-a03e-00ba4c055b56)
