# Deep Dive into Action Plans

*To develop* 



When it  comes to ‘Detect’ we can look at what known attacks can be detected, and use rules-based monitors (such as Zabbix, or Security Onion, or a host of others) that  monitor traffic and devices and look for particular patterns of behaviour  that correspond to known attack patterns, and can raise alerts.     

Other  detecting tools include **pattern of life monitors**, that look for sudden  changes in behaviour as likely symptoms of compromise. These can be useful  where there are traffic streams that follow predictable patterns, at least in  aggregate, such as an office that communicates using Outlook and writes  documents using Word. They are less useful when the behaviour changes  frequently and sporadically. Indeed they themselves can be a threat in  particular circumstances. For example, a system that switches from peacekeeping  to combat is likely to strongly change behaviour, and a pattern of life  monitor raising alerts will be distracting at best, and debilitating at worst  if it tries to shut down components that it believes have been compromised.     

We also  intend to use ‘trip wires’, such as **honeypot traps**. These are, for  example, devices or communication routes that are available but we do not  use, and may be attractive to threat actors who are exploring systems and so  sending data to devices and down routes that are normally dormant. Any  traffic detected there can then alert us to their presence. |



Cyber security controls are broken down into technical controls to protect the software systems through gateways and authenticators, and administration controls to protect the people through training and procedures. These are then monitored to check they work, and we feed the outputs of that back into the security evaluation

![Controls](D:\code-workspace\SbD-Playbook@us\SecureByDesign-Playbooks\explain\Controls.png)



