# Deep Dive into Threats

*To develop:*

## Why?

To understand our security we must understand our adversary[^1]. More specifically we need sufficient evidence about relevant threats, in enough time, to allow for good, informed decisions.

Successful threat intelligence helps security teams to better understand previous, existing, and emerging threats; encouraging them to shift from reactive to proactive responses. 

Identifying and profiling potential threats effectively leads to better detection, prevention, and remediation, because security teams can then put in place the most effective solutions for those particular threats.



## Profiling Threats

This provides some guidance to examining threats in more detail

### Identifying Threat Actors

[TBC] Actuals vs Categories



### Threat Capabilities

We borrow from other threat assessments, for example the UK Military use
the mnemonic COWARD:

* Capabilities,
* Organisation
* Weapons & equipment (software tools, skills)
* Activities (how do they attack)
* Reserves (how can they reinforce attack)
* Doctrine (what are the playbooks they use)



Tactical, theatre, strategic levels

also recruitment, finance, training, resources, influence, effectiveness, serviceability,
readiness, rehearsals, precedent 

and our favourite servants what, when where who how and why)

For many this will be a defensive assessment, only considering Threat
Actors ability to harm. For some this should include offense; in what
ways can Threat Actors be harmed or at least diverted, decoyed, trapped,
disabled, etc. 

### Threat Motivations



To break that down and extend it, consider:

- **Motive & Target:** Why are they attacking? What assets are they
  targeting and why? What established relationships do they have with
  the target?

  - Opportunistic hackers may target any and every device which flags as
    potentially vulnerable. Disgruntled employees may only target
    devices within their own company. Hacktivists will target devices
    that will give them leverage in espionage.

- **Location & Routes:** Where are they based? In cyber space as well as
  geographical? What routes are available to them from there to our
  systems, considering their capabilities? What surfaces are exposed to
  them?

- **Opportunity:** Circumstances that make certain attacks possible or
  easier to execute (e.g., Cryptographic downgrade attacks/ Staff
  handover on physical entry).

- **Intent:** The intended outcomes of an attack and expected level of
  damage if successful. Include exploitation (e.g., to publicize a
  breach, sell information on black market).

- **Capability:** The extent of the threat actor's ability - sectioned
  into the following:

  - **Technical Strength** -- Technical knowledge, skills, ability.
    (E.g., can the threat actor write zero-day attack scripts, or are
    they reliant on pre-existing scripts?)

  - **Social Strength --** non-technical areas of expertise (e.g.,
    interpersonal skills used in social engineering).

  - **Resources:** Information, time, teams, tools etc. Consider:

    - **Support --** Are they sponsored by political, or government
      states with access to political/financial resources?

    - **Limitations --** Limitations in time and manpower then we can
      expect this to affect their stealth and persistence.

- ![flatorganizationtypes-slide03-hires(D:\code-workspace\SbD-Playbook@sbd\QuickPlaybook\assess\media\image1.jpeg)](media/image1.jpeg){width="2.9055555555555554in"
  height="1.8229166666666667in"}**Organisation:** Flat, hierarchical,
  holocratic, what combinations? How is it distributed? What positions
  are important? Where does direction come from? What are good target
  points?

- ![holacratic-org_image01(D:\code-workspace\SbD-Playbook@sbd\QuickPlaybook\assess\media\image2.jpeg)](media/image2.jpeg){width="4.74068460192476in"
  height="2.760751312335958in"}**Order of Battle**: How is group
  organized when operating? What do they connect to? What do they use
  (space, power, etc)

- **(Weapons) Equipment and Tools**: Serviceability, Training, Range,
  Effectiveness, Targets, common employment, locations, identifying
  signatures

- ![flatorganizationtypes-slide01-hires(D:\code-workspace\SbD-Playbook@sbd\QuickPlaybook\assess\media\image3.jpeg)](media/image3.jpeg){width="1.9680555555555554in"
  height="1.53125in"}**TTPs: Training, Techniques, Processes:** What
  methods do we expect the threat actor to use. (E.g., phishing emails).
  Integrated complex attacks, slow attacks, subtle or brute force, quick
  drive bys or deliberate focused penetration?

- **Reserves:** Who can support in what way? Other groups, protection,
  sympathisers: size, strength, location just as with main force. How
  long to access, spin up. Recruiting? Threatening, revenge, finance,
  ideology, persuasion, how long?

- ![holacratic-org_image01(D:\code-workspace\SbD-Playbook@sbd\QuickPlaybook\assess\media\image4.jpeg)](media/image4.jpeg){width="2.6527777777777777in"
  height="1.5451388888888888in"}**Doctrine / Behaviour patterns --**
  characteristics and habits (e.g., What might a sophisticated
  attacker's bash history look like compared to a newbie 'Script
  Kiddie'), not just for individuals but groups; how do they form, work,
  pass tasks around, etc.

- **Exposure --** What traces do we expect the threat actor to leave
  behind? (e.g., a chain for communication between organised criminal
  group members)

...and of course do not limit yourself to the above, nor try and
comprehensively study each. These are guidelines to help think around
Threat Actors and help prepare for them.

Creating profiles or portraits of typical threat actors in your domain
can help to create rapid security control profiles and response
playbooks.

## Insiders, Outsiders and Bystanders

Proximity

## Motivations

Provides indicators and warnings and subjects to monitor for what.

- Money: this may be an end in itself, but there is usually a purpose.
  Gambling, security, 'high life', sex, showing off, etc.

- Reputation or notoriety 

- Curiosity & Hoarding: gaining long-term access to sensitive data

- Revenge

- Sabotage -- attempting to steal business secrets to gain advantage on
  competitors, or denying service to competitor devices

- To practice - or just for fun!

- Hacktivism -- to make a social or political point / encouraging
  political, ideological or social change 

- Ideological or ethical disagreement.

# References

[Know Your Enemy: Understanding Threat Actors \| CSO Online](https://www.csoonline.com/article/3203804/know-your-enemy-understanding-threat-actors.html)

[What Is A Threat Actor? \| Cyber Threat Actors \| Blog \| Nexor](https://www.nexor.com/what-is-a-threat-actor/#:~:text=What%20are%20the%20threat%20actor%20types%3F%201%20Cyber,4%20Script%20kiddies.%20...%205%20Disgruntled%20employees.%20)

[Creating a Threat Profile for Your Organization (giac.org)](https://www.giac.org/paper/gcih/1772/creating-threat-profile-organization/110995)



1 Sun Tzu "Art of War" and pretty much every other classical book on conflict since