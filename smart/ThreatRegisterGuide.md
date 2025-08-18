# Guide to the Threats Register

We provide a 'starter' threats register as a [Google Sheet](https://docs.google.com/spreadsheets/d/1unUfUc3bq9z9VWIVTx-gYYEH4Vt3ZgSxlYTeJhFLh-Y) by Holly and as a local [Excel Sheet](ThreatsRegister.xlsx). This is based on the NIST Guide to Risk Assessments (SP 800-30) and has been tailored to be more systematic, remove duplicates and add explanation.

It consists of two main lists: 

* **Adversaries** (called "Threat Actors" or "Threat Sources" in some material)
* **Attacks** (called "Threat Events" or "Threat Actions" in some material)



### Adversaries

This a list of the different types of people and organisations that might attack your systems. For the first pass you might just pick out the "obvious" ones such as script kiddies, criminals, and insiders.

* **Capability** is a rough indicator of how good that type of adversary is at attacking. This has already been filled in, but you might have an unusual circumstance where these are different.
* **General Intent** is a rough indicator of how likely that adversary is to go out and attack.  

* **Targeted Intent** describes how likely that adversary is to attack your systems specifically. 

If you have a public retail site, for example, then script kiddies have the capabilities to attack such sites, have a general motivation, and the specific motivation to attack public sites such as yours. On the other hand, terrorist organisations less so.

If you run a military software house, then script kiddies likely have no capabilities to reach your air-gapped systems, but terrorist organisations and foreign intelligence services may do and will be motivated to attack your systems specifically.

Multiplying the capability by intent gives a score, which is a guide to which adversaries are more **relevant** than others, and which you may need to focus on. As always, use these to guide you rather than instruct you.

## Attacks

In your first pass ignore this list as it will immerse you in semi-technical clutter and make it harder to get the big picture.

In the second or so pass, you can add an 'Impact' to each one, to say what impact that attack might have. This is a temporary shortcut - the impact will depend on which assets have been affected in what way, not on the attack - but it might be a useful intermediary step before diving into the full situation picture detail.

When you understand more about your environment this can help you see what Courses of Action the adversary might take, along which parts of your Network, and these can be used to tell you which security protections you would put in place and where.

## Developing Adversaries

Once you have grip on the assessments you can start to develop your Threat Registry by profiling adversaries in more detail. [Developing your own register](ThreatsProfiling.md)

