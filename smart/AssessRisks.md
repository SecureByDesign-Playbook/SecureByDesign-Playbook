# Assessing Risks

We can use our assessments of adversaries, networks and asset impacts to prioritise which of these we need to work on first. The highest risks are those with the most **capable** and **motivated** adversaries able to reach the most **vital spaces**  using routes through the network that are the **least defended**. 

> [!TIP]
>
> Eliminate particular combinations and possibly even adversaries where appropriate. For example if you are building a standalone system that will not be connected to anything else, you can eliminate script kiddies *for the built system*; they may still be a threat to your development team.

These are our greatest **vulnerabilities**; the easiest **courses of action** for these adversaries to **affect our assets**. We can then rate these by those that would cause us most **harmful impacts**. 

This is our basic risk formula:

> Risk = likelihood x harm

In some cases we may even be able to calculate this. If we can judge a likelihood of 50% per year that someone is likely to succeed an attack on our website, and it will cost us £1,000 to fix our website, then that's a **risk** of 50% x £1,000 = £500.

We are left with all the other vulnerabilities, ie which courses of action do not have sufficiently good protection to deal with them. This is likely to be large. Look also for bottlenecks in the routes available to the adversaries and see what defences can be put in place. 

(Why do we suggest assessing the risks like this? See [our explanation](../smart/SecurityPicture.md) )

#### Trade Offs

It can be tempting to just slam defences in everywhere you can see a vulnerability. 

But defences have costs; you need to weight those costs against the impacts of assets being affected.  If the cost of defending an asset is greater than the impact of that asset being affected then the defence is self-defeating.  You will need to talk to your technical people to understand what defences will be appropriate for each vulnerability, what single defences might cover many vulnerabilities, and how much they will cost.

This might be operational rather than money; if you shut down your own people's ability to work, you essentially "self-brick" your own operations. 

You might even find examples of existing defences in place that cost more than the assets they now protect.

This is not clear cut. You might know the costs of defences reasonably well,  but these need to be weighed against the *likelihood* of adversaries successfully affecting  your assets combined with the *likely* impacts of those effects on those assets.  That uncertainty can make this tricky. In the first passes, you can use the indexes in the sheets we provided to calculate the trade-offs, but be wary of 'crap rigour'; use the indexes to guide you, do not treat them as rigorous. 

These trade-offs will give a list of '**residual risks**'; these are the risks still left over once we have considered the existing defences and which assets are not worth spending significant defences on.  

Convert these residual technical security risks into business security risks (usually in the form of business costs) and add them to the general project or company risk register. The risk owners look over all of these to decide if these are acceptable or not according to the business **risk appetite**, and to make a call on whether to continue operating even if some risks still require treating or transferring.  



---

[Back to Playbook](./Playbook.md)  ●  [Office Example](examples/Office.md#AssessRisks)  ●  [Next: Action Plan](./ActionPlan.md) 
