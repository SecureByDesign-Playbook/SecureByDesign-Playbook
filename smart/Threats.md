# Threats

## Why?

To understand our security we must understand our adversary[^1]. More specifically we need sufficient evidence about relevant threats, in enough time, to allow for good, informed decisions.

Successful threat intelligence helps security teams to better understand previous, existing, and emerging threats; encouraging them to shift from reactive to proactive responses. 

Identifying and profiling potential threats effectively leads to better detection, prevention, and remediation, because security teams can then put in place the most effective solutions for those particular threats.

## Threats

In this case, a threat is an intention to cause harm to your assets. A 'threat' consists of an 'actor' with 'capability', and 'motivation' to attack.  Attacks might be intentional or unintentional, physical or digital.  While we will focus on intentional, digital attacks in this playbook, the others should of course be part of your overall risk assessment.

## What is an Adversary? 

An Adversary (or 'enemy' or threat actor', or 'threat source' in some material) attempts to maliciously attack specific targets.  An adversary may be an individual, a group, or even some semi-autonomous computer systems.

Some risk assessment systems also include natural disasters such as earthquakes under 'threat sources', but these are a very different category of threat that should be approached differently.  We do not include them here.

Even 'unintentional' actors (for example, staff accidentally deleting data) might be better excluded from this particular assessment as they too should be prepared for, monitored for, and responded to differently.

To help simplify the large range of possible combinations, we have a list of Adversary types to provide some templates or stereotypes that we can analyse, for example:  

| Name | Description | Categories | Code|
|-------------|------------------------|-----------|---------|
|  Skilled Hackers  |   Breaks into computer systems for fun or profit; installing  malware, stealing or destroying data, disrupting service, and more. Can be ethical bad and good (eg trying to find software vulnerabilities so they can be fixed). Can be employed by Foreign Intelligence Services or Serious Organised Crime. | Individual  Outsider |     TS-HACKER |
| Script Kiddies | Uses ready-made exploitation code (scripts) to attack systems that have legacy vulnerabilities due to not being updated or otherwise secured | Individual Outsider | TS-SKID |
| Journalists |  interested in information gained through computer breaches, especially those created by public authorities and that could be news worthy. This could include direct or assisted probing of ICT for weaknesses. | Individual Outsider | TS-JOURNA|
| Casual Bystander | Someone who has physical access to the assets without explicit access being granted (eg cleaners, visitors, etc) and internally motivated by money, curiosity, revenge, etc to take advantage of opportunity. | Individual Insider | TS-BYSTAND |
| Deliberate Bystander | Someone who has arranged for physical access to the assets without explicit access being granted (eg cleaners, visitors, etc), or is externally motivated to look for and encourage opportunities to take advantage of | Individual Insider | TS-BYSTAND-EX |
| Trusted Insider | Insider with access to the infrastructure, business processes and physical environment; perhaps motivated by greed, fame, fun, \'whistleblower\' or transient anger | Individual Trusted Insider | TS-INSIDER |
| Trusted Insider | Insider with access to the infrastructure, business processes and physical environment who also have                                                access to external skills and resources | Individual Trusted Insider | TS-INSIDER-EX |
| Privileged Insider | Insiders (eg ITSO, maintainers and Admins) who have privileged access and more knowledge about and access to the infrastructure | Individual Privileged Insider | TS-PRIVINS |
| Partner | An organisation with deep collaboration meshes including access to many internal information systems | Organisation Partner | TS-PARTNER |
| Foreign Intelligence Services |  | Organisation Outsider | TS-FIS |

--------------------------------------------
## Scoring Threats

Adversaries are scored by **Capability** and **Intent** (general and specifically to you).

You can then score which of these actors are more relevant to your situation; which of them essentially are both more capable and more motivated to attack your assets compared to others. This can give you the more relevant and likely threats to focus on.

### Threats Register

We provide a [starter threats registry](ThreatsRegisterGuide.md) which has some adversaries and attacks already listed. 

# References

[Know Your Enemy: Understanding Threat Actors \| CSO Online](https://www.csoonline.com/article/3203804/know-your-enemy-understanding-threat-actors.html)

[What Is A Threat Actor? \| Cyber Threat Actors \| Blog \| Nexor](https://www.nexor.com/what-is-a-threat-actor/#:~:text=What%20are%20the%20threat%20actor%20types%3F%201%20Cyber,4%20Script%20kiddies.%20...%205%20Disgruntled%20employees.%20)

[Creating a Threat Profile for Your Organization (giac.org)](https://www.giac.org/paper/gcih/1772/creating-threat-profile-organization/110995)

[^1]: Sun Tzu "Art of War" and pretty much every other classical book on conflict since
