# Behind the Scenes: The Security Picture

The part of the playbook where we assemble the security picture is a mashup of NIST CSF, RMF, 'traditional' security analysis and military assessments.  Why did we do it this way?

Breaking it down into manageable chunks helps us to take apart the complex problem, and then reassemble the chunks for a specific situation - the one we are wanting to secure.

The cyber security frameworks we have selected don't tend to have the useful step-by-step detail that helps us to create the right chunks.  There is such a process in military ground assessments which we can borrow from; while ‘cyberspace’ might have a different form to the real world ground, there are still many similar aspects  that we can use.  

## UK Gov's Secure By Design

The Secure By Design page provide a list of questions to answer that are overlaid on whatever framework you use, it's not a process in itself although we can derive something like this:

```mermaid
  stateDiagram
     Used : How it's used
     Boundaries : Boundaries
     Assets : What you protect
     Business : What you do and why

   Used --> Context
   Boundaries --> Context
   Assets --> Context
	Business --> Context
	
	Context --> RiskAssessment
	RiskAssessment --> Controls
	RiskAssessment --> Manage
	
	RiskAppetite --> Controls
	
	Controls --> ResidualRisks
	Manage --> ResidualRisks
```



## NIST Cyber Security Framework

The NIST CSF is also essentially a list of lists, organised as high level functions with various categories and subcategories:

![NIST-CSF-Topics.png](D:\code-workspace\SbD-Playbook@us\SecureByDesign-Playbooks\about\NIST-CSF-Topics.png.jpg)



```mermaid
  stateDiagram
     Uses : Users & Users <br/> ID
     Assets : Asset Inventory <br/> ID.AM
     Threats : Threat Assessment <br/> ID.RA-02/03 
     Network : Network Topologies <br/> ID.AM
     Vulnerabilities : Existing Vulnerabilities
     RiskAssessment : Risk Assessment <br/> ID.RA
     ResponsePlan : Plan Response <br/> RS RC
     Protect : Protect <br/> PR
     Detect : Monitor, Detect <br/> DE
     
     classDef ID fill:cyan
     classDef DE fill:yellow
     classDef PR fill:purple,color:white
     classDef RS fill:red,color:white
     
     class Uses ID
     class Assets ID
     class Network ID
     class Threats ID
     class Vulnerabilities ID
     class RiskAssessment ID
     class ResponsePlan RS
     class Protect PR
     class Detect DE
     
     Uses --> RiskAssessment
     Assets --> RiskAssessment
     Threats --> RiskAssessment
     Network --> RiskAssessment
     Vulnerabilities --> RiskAssessment
     
     RiskAssessment --> ResponsePlan 
     RiskAssessment --> Protect  
     RiskAssessment --> Detect 
     
     ResponsePlan --> ResidualRisks
     Protect --> ResidualRisks
     Detect --> ResidualRisks
```

<p align=center><i>The implied NIST CSF process with reference identifiers to the framework topics.</i></p>

While this lists a number of documents to produced, there is little to no support in relating them to each other, or combining them into the Risk Assessment.

## The Military Approach

There are some similarities between military tactical assessments and cyber security assessments. Both look at the space we operate in (the 'ground' for the Army) and the adversary to derive what the situation is that the military force is facing. 

This approach gives us a more clearly defined way of combining the various inputs described above, but it does not include the friendly force picture or what we are protecting and why:

```mermaid
stateDiagram
   IE : Information Environment
   HTA : Human Environment
   PE : Physical Environment
   
   OAE : Operational Area Evaluation
   TA : Threat Evaluation
   TAC : Threat Actors (Who)
   COWARD : COWARD
   TL : Locations
   TM : General Motivations
   TSM : Specific Motivations
   TC : Capability
   
   
   SI : Situation Integration <br/> (Operating Picture)
   Corridors : Movement Corridors
   KeySpaces : Key / Critical points

   COA : Threat Courses of Action
   IW : Indicators & Warnings
   NAI : Monitoring <br/> NAIs & TAIs
   
   CoG : Centre of Gravity
   Targets : Target Lists
   
   classDef Ground fill:green,color:white
   classDef Threat fill:red,color:white
   classDef Sit fill:grey

   class IE : Ground
   class HTA : Ground
   class OAE : Ground
   class PE : Ground
   
   class TA : Threat
   class TAC : Threat
   class COWARD : Threat
   class TL : Threat
   class TM : Threat
   class TSM : Threat
   class TC : Threat
   class CoG : Threat

   IE --> OAE
   HTA --> OAE
   PE --> OAE
   
   OAE --> KeySpaces
   OAE --> SI
   OAE --> Corridors
   
   Corridors --> COA
   KeySpaces --> COA
   
   TL --> TA
   TAC --> TA
   COWARD --> TA
   TM --> TA
   TSM --> TA
   TC --> TA
   
   TA --> SI
   
   SI --> COA
   
   state offense {
      CoG --> Targets
   }
   COA --> IW
   COA --> NAI
   COA --> Targets

   TA --> CoG
 


```





## The SbD Playbook Process

Our approach combines the above in the context of information system security. It includes an assessment of what we are protecting and why. It should give you some ways to understand how we integrate the various lists. And finally we have tried to make the terminology reasonably clear for business users, so that our technical risks can be translated into business ones reasonably easily. 

See the Playbook



