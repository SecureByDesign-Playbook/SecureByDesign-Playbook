# Threats

## <img src="Threats.png" align="right" width=30% />The Adversary

An **Adversary** (or 'enemy' or threat actor', or 'threat source' in some material) attempts to maliciously attack specific targets.  An adversary may be an individual, a group, or even some semi-autonomous computer systems.

> [!NOTE]
>
> Some risk assessment frameworks (such as NIST 800 3..) include natural threats such as earthquakes, but these can and should be managed in different ways; leave them out of this assessment. 
>
> Even 'unintentional' actors (for example, staff accidentally deleting data) might be better excluded from this particular assessment as they too should be prepared for, monitored for, and responded to differently.

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

We provide a [starter threats registry](ThreatRegisterGuide.md) which has some adversaries and attacks listed and scored based on the NIST Risk Framework.

---

[Back to Playbook](./Playbook.md)  ●  [Office Example](examples/Office.md#Threats)  ●  [Next: Security Picture](./SecurityPicture.md)  ●  Starter [Threats Register](../smart/ThreatRegisterGuide.md) 
