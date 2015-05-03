# prescription-drug-guide
A tool to help physicians prescribe less-expensive drugs for patients (#appsforphilly health hackathon, 2015)

At the Code for Philly 2015 #AppsForPhilly Health hackathon, a homeless person wrote, on a board, "It feels like the doctors don't care how expensive the drugs they are prescribing are." They didn't stay, but that expression of frustration inspired a team of doctors & developers to attack that problem.

Doctors often prescribe drugs without a resource to help them understand patient costs. In addition to the economic impact on people, the inhibitive costs creates an additonal barrier to patient compliance with medication. Many doctors do want to be able to help their patients with this, but may not be able to easily find alternatives at the time of diagnosis. Doctors are busy - they need a tool built for them specifically, that has a minimum of fuss. It should let them enter a drug & what pharmacies the patient can access, and provide immediate response about where those drugs can be purchased cheaply, how much they'll cost (reducing nasty surprises) and suggesting cheaper generics when possible.


---

Some potentially useful links for later development:


Pillbox is a pill identification API!
https://github.com/HHS/pillbox_docs/wiki/Pillbox-API-documentation#2-example-api-calls

https://developer.pillfill.com/apis/?url=/service/api-docs?group=drug-info-api-v1#!/drug-information-service/searchDrugProductInfo

GoodRx - app/site that provides a lot of drug pricing information; does 90% of what we want to do, but is presented in a very consumer-centric form. Physicians on our team found it really tedious to deal with for their use case: just punching in a list of medications & getting back a list of where they can be purchased, inexpensively, with possible alternatives, and restricted to pharmacies their patient can get to easily.

Team:
====
* Arif Billah
* Jorge Feria
* Ted Fujimoto
* Ben Novack
* Jeff Sloan

Special thanks to [Miguel Grinberg](http://blog.miguelgrinberg.com/) and his Flask tutorials for inspiring this framework.
