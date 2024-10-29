# h1 - Adversarial Mindset

## Summarizations of articles
Hutchins et al 2011: Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains:

- Introduces a new class of threats: "the APT's" (Advanced Persistent Threat), which are more dangerous than automated viruses or worms, since they have human intelligence actively working behind them.
- Places emphasis on the mitigation of threats before the intrusions ever happen.
- Describes the cyber kill chain, which consists of Reconnaissance, Weaponization, Delivery, Exploitation, Installation, Command and Control, and Actions on Objectives. The adversary has to follow all of these steps to succeed in his/her objective.
- Also describes how to utilize and review the indicators in intrusion attempts to identify similarities and therefore increase one's defensive capabilities.

  Episode 141: The Pig Butcher

  - Episode described BEC, Business Email Compromise, which had been the number one cyber crime based on losses from 2015 to 2021. The episode also described the crime of pig butchering, which is a romance scam done in order to milk money from the victim via "catfishing".
  - Episode had an expert, Ronnie Tokazowski, telling about his work which was related to both of the crimes.
  - Also contained information about an African cult,the Black Axe, which is one of the largest contributors in the scamming business worldwide, and their stealing from the US treasury by using unemployment fraud.
 
  MITRE ATT&CK explanations

  - Tactic: The "why" of a technique. Describes the reasoning or the objective behind the attack. Example: Gaining access to a company's network.
  - Technique: The "how" of a tactic. Describes how the attack is able to fulfill the objective. Example: Drive-by compromise.
  - Procedure: Describes the whole method of the attack. How it is done, using which techniques and what is the outcome. Example: Using a drive-by compromise via a compromised legitimate website to gain access to the desired system.
 
## Comparing MITRE ATT&CK Enterprise Matrix and The Cyber Kill Chain

The cyber kill chain is more focused on the necessary process which needs to be done in some way to execute an attack, whether knowingly or not, the adversary utilizes it. But it is more useful for the defender, since they can model the attack threats before they happen
and after they happen, they can analyze the attack by using the model. The Enterprise Matrix is more useful to the adversary than the kill chain, as they can learn new exploits or techniques to broaden their skill set in performing attacks. The Matrix might also encourage
new-and-upcoming scammers to gain more information on possible attack patterns. It does help the defender too, so that the defender can see possible attack angles, and learn more from different exploitation techniques.

## Security incident: The Scattered Canary steals 400 billion from the Us treasury via unemployment fraud

A Nigerian cyber-fraud group used the google dot bug to steal 400 billion US dollars from the US treasury.
Threat Actor: Scattered Canary, an organized cyber-fraud group
Exploit: Google dot bug. (j.o.h.n.doe@gmail.com and johndoe@gmail.com are the "same account")
Vulnerability: Background checks were low-to-nonexistent during the COVID Pandemic for which the extra unemployment funds were meant to be used.
Business impact: Upward to 400 billion USD lost.

## Installing Debian on VirtualBox

Followed the instructions given in https://terokarvinen.com/2021/install-debian-on-virtualbox/. First problem was when trying to boot up the Linux it said "Not in a hypervision partition error". So I went to BIOS and enabled my CPU to boot up multiple systems at once. Next error was hen the system booted and I chose the live version, it said that the kernel doesn't recognize my CPU, which was i686. After this I found a helpful solution to change the Type of the Debian 32-bit to 64-bit and then it opened. Also it didn't let me login via the first install, guess I messed up the password, but the 2nd install it worked and everything went smoothly until the end. Also did a few push-ups while installing the Linux!

## References
https://terokarvinen.com/trust-to-blockchain/#homework
https://recoverit.wondershare.com/partition-tips/not-in-a-hypervisor-partition.html
https://adamlevin.com/2018/04/11/gmails-dots-are-a-bug-not-a-feature/
https://attack.mitre.org/resources/faq/
https://darknetdiaries.com/transcript/141/
https://cdimage.debian.org/debian-cd/current-live/amd64/iso-hybrid/
https://terokarvinen.com/2021/install-debian-on-virtualbox/
Hutchins et al 2011: Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains
