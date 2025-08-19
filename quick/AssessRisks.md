# <img src="AssessRisks.png" style="float:right; width:25%"/>Quick-Start: Risk Assessment

Let's have a quick look at 'risk' and what we mean by it.

Generally a 'risk' combines how **likely** something is to happen, with how **severe** the impact would be if it did. 

For example, stubbing your toe is **unlikely** (hopefully!) and although it hurts at the time, the impact is **minor** (again, hopefully). The risk is **low**.

Falling off a ladder is also unlikely (very hopefully), but the impact can be **severe**, so the risk is **medium**.

Sometimes this is given as a multiplication:

> Risk = Likeliness of successful attack  x  Severity of impact

...and we will look at this in the 'Smart' and 'Deep Dive' sections. However to keep things simple, we suggest using only three levels of likeliness and severity at this stage and use the following table to lookup the overall risk:

| Likeliness \ Impact | Minor  | Significant | Severe |
| ------------------- | ------ | ----------- | ------ |
| Unlikely            | Low    | Low         | Medium |
| Possible            | Low    | Medium      | High   |
| Likely              | Medium | High        | High   |

Here the **likeliness** is a combination of how motivated the adversaries are to attack an asset, how skillful they are, and how easy it is to reach that asset (its vulnerability). You can then use your asset registry to tell you how severe the **impact** would be if that asset was successfully attacked. 

You will already have most of this from your **courses of action** that you worked out in the Security Picture section earlier. Now you can use the table above to lookup the overall Risk for each one to compare them with the others.

As well as giving you an overall priority list, this will start you thinking about whether the costs of putting defences in for a particular course of action are worth it.  We will look at doing that more rigorously later in the 'Smart' section. 

> [!WARNING]
>
> Don't try and work out exactly the probability of an attack on an asset at this stage. The table helps you *compare* risks with each other in this assessment in order to find where the main risks are (ie the 'high' ones), if any.
>
> Also be wary of using these risk descriptions, impact severity terms or likeliness terms to compare with other risks calculated elsewhere using different systems. We will cover terminology in the 'Smart' and 'Deep Dive' sections.

---

[Back to Playbook](./Playbook.md)  ●  [Home Example](examples/Home.md#AssessRisks)  ●  [Next: Quick-Start Action Plan](./ActionPlan.md)  ●  [Smarter Risks](../smart/AssessRisks.md)
