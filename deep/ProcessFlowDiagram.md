```mermaid
stateDiagram
   Assets&Uses --> SecurityPicture
   Networks&Access --> SecurityPicture
   Threats --> SecurityPicture
   SecurityPicture --> CoursesOfAction
   CoursesOfAction --> AssessingTheRisks
   AssessingTheRisks --> CurrentRisks
   DefendOptions --> ActionPlan
   RiskAppetite --> ActionPlan
   CurrentRisks --> ActionPlan
   ActionPlan --> ImplementControls
   ImplementControls --> SecurityPicture
```



