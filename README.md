# HomeLab-Active-Directory
This is the documentation for my Homelab set up of an Active Directory lab. Its run on Virtual Box VM's and run on the Windows 2025 Server version.

First I set up the Windows Defender Firewall and configured each; The Domain, Private and Public profiles with each its own rules depending on how I want each to interact with each provided element.
I am running this lab as if I were to run it as a network administrator for a company looking to keep its network safe and secure.


Domain Profile:

<img width="401" height="392" alt="AD Lab Domain Profile Firewall configurations" src="https://github.com/user-attachments/assets/389ed96b-5588-4a89-b2fe-8f8314f9d718" />

Private Profile

<img width="401" height="386" alt="AD Lab Private Profile Firewall Configurations" src="https://github.com/user-attachments/assets/b206a00b-3a3a-4e55-b7b2-2d92ef5b124c" />

Public Profile

<img width="402" height="453" alt="AD Lab Public Profile Firewall Configuration" src="https://github.com/user-attachments/assets/1719cfd5-5caa-4335-bd60-27bf30ba5142" />

Domain Profile Logging

<img width="784" height="569" alt="AD Lab Domain Profile Logging" src="https://github.com/user-attachments/assets/ea057f59-193f-491d-bf97-42c4b10b4c77" />


For the Private profile for logging, I set it to log any dropped packets and all connections made to it 
For the Public profile for logging, I set it to log all connections made to it 











