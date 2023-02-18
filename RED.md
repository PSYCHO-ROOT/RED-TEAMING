# RED TEAMING
## INTRODUCTION
Cybersecurity is a constant race between white hat hackers and black hat hackers. As threats in the cyber-world evolve,so does the need for more specialized services that allow companies to prepare for real attacks the best they can.

It may seem counterintuitive to pay someone to tell you your shortcomings, but smart companies today are shelling out dollars and resources to do just that, in the form of ***red teaming*** .
## What is Red Teaming ?
Red teaming is the practice of testing the security of an organization’s systems by emulating a malicious actor and hacking into secure systems or data. 
A red team can be an externally contracted group or a team within your own organization, designed to hack your system to prepare for a wide variety of cyberattacks and breach scenarios before they occur.

Red teaming is a multi-layered, full-scope cyberattack simulation designed to test the effectiveness of an organization’s security controls. This includes networks, applications, physical safeguards, and even employees.
Red teaming is similar to ethical hacking, during which actors don’t attempt any actual harm but instead hack into systems to uncover vulnerabilities with the goal of improving defenses. 
Red teaming is based on the idea that a company can’t really know how secure its systems are until they are attacked. Simulating an attack first via red teaming will uncover an organizations vulnerabilities so they can be addressed before it’s too late. 
## How does red teaming work ?
A core function of the red team is adversary emulation. While not mandatory, it is commonly used to assess what a real adversary would do in an environment using their tools and methodologies. The red team can use various methodologies
but we can take the kill chain as an example to summarize and assess the steps and procedures of an engagement. Each kill chain follows roughly the same structure, with some going more in-depth or defining objectives differently.

![net](https://i.imgur.com/JopqA4m.png)

Let's broke down the component of the kill chain :

* ***Reconnaissance*** - Once the red team is clear on their objectives, they will begin mapping out the systems to be targeted, including networks, web applications, employee portals, and even physical spaces.

* ***Weaponization*** - Once the red team knows which attack vectors they’ll use, they will employ tactics such as backdoor, malicious office document and also custom payloads to access your systems.

* ***Delviery*** - Delivery may involve sending phishing emails containing malware attachments with subject lines that prompt users to click through. Delivery can also take the form of hacking into an organization’s network and exploiting a hardware or software vulnerability to infiltrate it.

* ***Exploitation*** - The red team take advantage of the vulnerabilities they have discovered in previous stages to further infiltrate a target’s network and achieve their objectives.

* ***Installation*** - The red team attempt to install malware and other cyberweapons onto the target network to take control of its systems and exfiltrate valuable data. RT may install cyberweapons and malware using Trojan horses, backdoors, or command-line interfaces.

* ***Command & Control*** - The red team communicate with the malware they’ve installed onto a target’s network to instruct cyberweapons or tools to carry out their objectives. They could use tools such as Empire, Cobalt Strike, etc.

* ***Actions on Objectives*** - After cybercriminals have developed cyberweapons, installed them onto a target’s network, and taken control of their target’s network, they begin to carry out their cyberattack objectives. some examples include weaponizing a botnet, a Distributed Denial of Service (DDoS) attack, stealing sensitive data, or using ransomware as a cyber extortion tool.

The final attack may look something like this:

* A list of company employee email addresses is obtained from social media and other open-source intelligence (OSINT) sources. A crafted phishing email is then sent to these addresses containing a lure and an attached document. When opened, this drops custom malware on the victims’ machines providing the red team with access to the corporate network.

* Obtaining persistence through exploiting common machine misconfigurations/outdated software and hiding the custom malware somewhere where it is unlikely to be noticed by the security operations centre (SOC).

* Exploiting and mapping the network, escalating privileges where required to grant further access while evading detection.

* Identifying paths to predetermined objectives (e.g. a finance database) using privileged credentials to achieve those objectives.

* Exfiltration of data from the target network to demonstrate the ways an attacker could remove sensitive information.

