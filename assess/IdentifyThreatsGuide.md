# Why?

To understand our security stance, we must understand our enemy[^1].
More specifically we need sufficient, evidence-based knowledge about
relevant threats, in enough time, to allow for good, informed decisions.
Successful threat intelligence helps security teams to better understand
previous, existing, and emerging threats; encouraging them to shift from
reactive to proactive responses. Identifying and profiling potential
threat actors effectively leads to better detection, prevention, and
remediation - as security teams can engineer the most effective
solutions against identified actors.

# What is a Threat Actor? 

In Information Security, a 'threat actor' is an entity who attempts
malicious activity against a specific target. This includes internal,
external, intentional, unintentional, physical, and digital attacks.
Some risk assessment systems will join these active attackers with
natural disasters such as earthquakes under 'threat sources', but these
are a very different category of threat that should be approached
differently. Even 'unintentional' actors might be better excluded from
this particular assessment as they too should be prepared for, monitored
for, and responded to differently.

# Identifying Threat Actor Categories

We identified a set of threat actors based on NIST SP 800.53 Table D,
and have extracted these as a table of Threat Actor types with examples
and typical capabilities (see SbD-Threats.xls). These include:

  -------------------------------------------------------------------------------------
  Individual       TS-HACKER       Skilled       Someone who breaks into computer
  Outsider                         Hackers       systems for fun or profit; installing
                                                 malware, stealing or destroying data,
                                                 disrupting service, and more. Can be
                                                 ethical bad and good (eg trying to
                                                 find software vulnerabilities so they
                                                 can be fixed). Can be employed by FIS
                                                 or Serious Organised Crime.
  ---------------- --------------- ------------- --------------------------------------
  Individual       TS-SKID         Script        Someone who uses ready-made
  Outsider                         Kiddies       exploitation code (scripts) to attack
                                                 systems that have legacy
                                                 vulnerabilities due to not being
                                                 updated or otherwise secured

  Individual       TS-JOURNA       Journalists   Journalists are interested in
  Outsider                                       information gained through computer
                                                 breaches, especially those created by
                                                 public authorities and that could be
                                                 news worthy. This could include direct
                                                 or assisted probing of ICT for
                                                 weaknesses.

  Individual       TS-BYSTAND      Bystander     Someone who is inside the outer
  Insider                                        perimeters (cleaners, visitors, etc)
                                                 and motivated by money, curiosity,
                                                 revenge, etc to take advantage of
                                                 opportunity.

  Individual       TS-BYSTAND-EX   Bystander     Someone who is inside the outer
  Insider                          (Externally   perimeters (cleaners, visitors, etc)
                                   Influenced)   and externally influenced to take
                                                 advantage of opportunity.

  Individual       TS-INSIDER      Insider       Insider with access to the
  Trusted Insider                                infrastructure, business processes and
                                                 physical environment; motivated by
                                                 greed, fame, fun, \'whistleblower\' or
                                                 transient anger (see motivation table)

  Individual       TS-INSIDER-EX   Insider       Insider with access to the
  Trusted Insider                  (Externally   infrastructure, business processes and
                                   Influenced)   physical environment who also have
                                                 access to external skills and
                                                 resources

  Individual       TS-PRIVIN       Privileged    Insiders (eg ITSO, maintainers and
  Privileged                       Insider       Admins) who have privileged access and
  Insider                                        more knowledge about and access to the
                                                 infrastructure, motivated by greed,
                                                 fame, fun, \'whistleblower\' or
                                                 transient anger (see motivation table)

  Individual       TS-PRIVIN-EX    Privileged    Insiders (ITSO and Adminstrators) who
  Privileged                       Insider       are in a privileged position and has a
  Insider                          (Externally   higher level of knowledge and access
                                   Influenced)   to the infrastructure and have access
                                                 to external skills and resources

  Organisation -   TS-PARTNER      Partner       An organisation with deep
  Partner                                        collaboration meshes including access
                                                 to many internal information systems
  -------------------------------------------------------------------------------------

This list is intended to be scored for a particular application to see
which are the most relevant and likely threats, at least to start with
and/or focus on.

# Profiling Threat Actors

Initial quick threat assessment might consist of identifying (1) Who (2)
Capability and (3) Intent (general and specifically to you).

We can borrow from other assessments, for example the UK Military use
the mnemonic COWARD (capabilities, organisation, weapons & equipment,
activities, reserves and doctrine) that can provide a checklist to
consider. \[From the MIRET IPB, also lists of weaons/attack types,
consider tactical, theatre, strategic levels, also recruitment, finance,
training, resources, influence, effectiveness, serviceability,
readiness, rehearsals, precedent and our favourite servants what, when
where who how and why)

For many this will be a defensive assessment, only considering Threat
Actors ability to harm. For some this should include offense; in what
ways can they be harmed or at least diverted, decoyed, trapped,
disabled, etc. For this see our version of 'Centre of Gravity' analysis
to identify good targets.

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

- ![flatorganizationtypes-slide03-hires(05-21-15)](media/image1.jpeg){width="2.9055555555555554in"
  height="1.8229166666666667in"}**Organisation:** Flat, hierarchical,
  holocratic, what combinations? How is it distributed? What positions
  are important? Where does direction come from? What are good target
  points?

- ![holacratic-org_image01(07-06-15)](media/image2.jpeg){width="4.74068460192476in"
  height="2.760751312335958in"}**Order of Battle**: How is group
  organized when operating? What do they connect to? What do they use
  (space, power, etc)

- **(Weapons) Equipment and Tools**: Serviceability, Training, Range,
  Effectiveness, Targets, common employment, locations, identifying
  signatures

- ![flatorganizationtypes-slide01-hires(05-21-15)](media/image3.jpeg){width="1.9680555555555554in"
  height="1.53125in"}**TTPs: Training, Techniques, Processes:** What
  methods do we expect the threat actor to use. (E.g., phishing emails).
  Integrated complex attacks, slow attacks, subtle or brute force, quick
  drive bys or deliberate focused penetration?

- **Reserves:** Who can support in what way? Other groups, protection,
  sympathisers: size, strength, location just as with main force. How
  long to access, spin up. Recruiting? Threatening, revenge, finance,
  ideology, persuasion, how long?

- ![holacratic-org_image01(07-06-15)](media/image4.jpeg){width="2.6527777777777777in"
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

# Insiders, Outsiders and Bystanders

Proximity

# Motivations

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

# Threat Assessment

See for example

# References

[Know Your Enemy: Understanding Threat Actors \| CSO
Online](https://www.csoonline.com/article/3203804/know-your-enemy-understanding-threat-actors.html)

[What Is A Threat Actor? \| Cyber Threat Actors \| Blog \|
Nexor](https://www.nexor.com/what-is-a-threat-actor/#:~:text=What%20are%20the%20threat%20actor%20types%3F%201%20Cyber,4%20Script%20kiddies.%20...%205%20Disgruntled%20employees.%20)

[Creating a Threat Profile for Your Organization
(giac.org)](https://www.giac.org/paper/gcih/1772/creating-threat-profile-organization/110995)

[^1]: Sun Tzu "Art of War" and pretty much every other classical book on
    conflict since
