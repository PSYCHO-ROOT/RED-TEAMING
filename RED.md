# RED TEAMING

![net](http://preview.turbosquid.com/Preview/2014/05/24__20_49_08/Chess-CU-Red.jpge9312dd5-9d57-4986-96a2-f5fe3ec10fd1Original.jpg)

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
## Red teaming benefits
At the broadest level, the value of red teaming is that it provides a comprehensive picture of cybersecurity within your organization. Red teams should be as creative and resourceful as real-life malicious actors who will inevitably probe and test every square inch of the potential attack surface. 

The assessment doesn’t conclude after initial vulnerabilities are discovered and exposed, however. The exercise will extend towards re-testing, lateral movement, and remediation phases that will test just about every aspect of your cybersecurity strategy. You’ll be able to completely assess your capability to detect, remediate and prevent targeted attacks.
In fact, the real work typically begins after a red team intrusion, when you’ll perform forensic analysis of the attack and formulate ways to mitigate vulnerabilities.
## Red teaming vs. penetration testing
Though pen testing is important, it is only one part of what a red team does. Red team operations have broader objectives than pen testers, whose goal is often just to get access to a network.

Red team exercises are designed to emulate a more real-world advanced persistent threat (APT) scenario and result in reviewing defensive strategies and detailed risk analysis. Penetration testing is only a small part of red teaming. Red teaming includes evasion and persistence, privilege escalation, and exfiltration, whereas penetration testing exercises only the first part of the cyber kill chain.
#### Time box
This is the time frame in which each activity is conducted. For pen testing, the time box is extremely narrow – typically less than one day. For red teaming, the time box can be extended over multiple days, weeks, and even months.
#### Tooling
Pen testing and red teaming also employ different tools and technologies. Employees will typically conduct a pen test using commercially available software. Red teams are encouraged to use any tool, trick, or tactic in their arsenal and think creatively while attempting to breach systems.
#### Awareness
This is one of the most distinct differences between Pen Testing and red teaming. With Pen Testing, most of your employees are aware of what’s taking place. But red teaming exercises require that your organization is completely unaware to get a real picture of your cyber defenses.
#### Vulnerabilities
Which vulnerabilities are attacked will also differ. In pen testing, known vulnerabilities are specified and targeted to see how well-defended they are. Red teams won't just exploit a single vulnerability, however. They’ll also seek out new ones in your network and attempt to move laterally.
#### Targeting
When conducting penetration testing, your test target vulnerabilities will be narrow and pre-defined. You’ll target a specific firewall or password system, for instance. Red team targets are more fluid, ranging across multiple domains and networks.
#### Testing
Penetration testing involves testing each system independently, one at a time, and is a much more siloed approach than red teaming. When implementing red teaming, all your systems are targeted simultaneously throughout the time box, giving you a better idea of your plan of defense and response to a real hack.
## Red Team Engagement
Engagements can be very complex and bureaucratic. The key to a successful engagement is clearly defined client objectives or goals. Client objectives should be discussed between the client and red team to create a mutual understanding between both parties of what is expected and provided. Set objectives are the basis for the rest of the engagement documentation and planning.

The key to a successful engagement is clearly defined client objectives or goals. Client objectives should be discussed between the client and red team to create a mutual understanding between both parties of what is expected and provided. Set objectives are the basis for the rest of the engagement documentation and planning.

***Rules of Engagement (RoE)*** are a legally binding outline of the client objectives and scope with further details of engagement expectations between both parties. This is the first "official" document in the engagement planning process and requires proper authorization between the client and the red team. This document often acts as the general contract between the two parties; an external contract or other NDAs (Non-Disclosure Agreement) can also be used.
