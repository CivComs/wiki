---
title: Procurement Interview Subject 1
permalink: /Procurement_Interview_Subject_1/
---

**Who: A former staff member of the centralized IT department of a large city**

**Issue: Open Source Not Equally Represented in RFI Responses due to Lack of Awareness of FOSS Solutions**

Typically a Request for Information (an RFI) was issued, which would list the software problem the city had, and for which a solution was needed. Vendors would then respond to the RFI and make suggestions for a solution, although these were typically solutions of software which the vendor themselves licensed. The responses could be skewed to what the vendors could do. Responses would rarely suggest a FOSS solution because there is still a lack of awareness of FOSS solutions by vendors.

**Issue: Professional Services Contracting Process**

Software services are procured via a professional services contracting process. Professional services contracts do not look at the underlying software that is being extended or customized. Therefore, these contracts could just involve configuration changes to a Commercial Off The Shelf (COTS) product with no code changes. The licensing fees are like “subcontracted” through the personal services contract, and it is permissible to add some overhead to these licenses.

Procurement rules required a TCO (Total Cost of Ownership) analysis for projects over 100K, including TCOs for OSS.

This made managers do TCOs which they weren’t doing before. They tried to pass on to Vendors to do a TCO in response to a RFP.

**Issue: FOSS Requires Maintenance/Support agreements**

In the city, many FOSS platforms were used: Sugar CRM, Wikimedia, Subversion, Al Fresco, Drupal, and wordpress. A contract for the deployment of the apps, or for a software license did not have to be contracted because the city IT staff could implement. However, cities need maintenance agreements - often they do not have the people to support FOSS. Where there is FOSS that doesn’t have a commercial support offering (such as SAS or someone who can do configurations) a city is not likely to choose that solution. Cities need the assureance that there is someone they can call if something breaks with their software solution.

**Issue: Burden of Finding Support for In-House Developed FOSS Software**

The Operations group within the city will not accept apps developed in house for various departments because of the administrative responsibilities. Most of the administration was configuration changes. Because the developer team could not get support from operations to maintain/administer the code, they had to assign these tasks to one of the city developers, and the city developer was unhappy with this assignment.

Therefore, even though a FOSS product could be deployed for free within a city, it is still necessary to get a maintenance agreement for support and development of the product.

**Best Practice: FOSS As a Staging Tool to Ease Procurement Hurdles**

In the city, FOSS solutions (such as Sugar CRM) would be deployed in a testing environment, and used for developing processes, workflows, and other content for customization to be entered into the CRM. Once this data has been developed in the cost-free FOSS environment, the data was then exported and moved to another platform (such as Salesforce). This was a best practice employed to help acclimate business users to using an online/web platform and stablize their work process before having to contract to a vendor for support of the CRM platform. In one case, the business user became comfortable enough with the FOSS CRM that a decision was made not to migrate to Salesforce, and rather to continue using the FOSS CRM.

**Issue: Complying with Procurement Requirement to Show Services of a Vendor Were Necessary - “Civic Servants Group”**

One scope of services with a vendor that the city was drafting for customization to a CRM had to go before a “Civic Servants Group” which would question the purchase for its need to use outside labor vs. labor from the IT department. The underlying spirit of this policy was to protect city employees jobs. It would be the task of the Civic Servants Group to identify IT staff capable of doing the proposed work, and the task of the personnel seeking the vendor contract to argue that the identified IT staff would not be capable of completing the work to be vended.

While typically the IT staff said to be capable of doing the work to be vended were in actuality not available to work on the project, convincing the Civic Servants Group of this was not an easy task.

**Best Practice: Consistency in Staff that Work With Each Other Through Procurement**

Once a project would be approved by the Civic Servants Group, the scope of services would be gone through with the vendor, and then handed off to the legal department. The IT department had its own group of lawyers that work with that department only. In this way, the IT staff always worked with the same lawyers and an efficient and trusted relationship would evolve. Further, the set group of lawyers would come to understand the relevant contracting points for the technologies that the IT department were routinely procuring. Any lack of understanding about the technical requirements could often be left unaddressed, as the attorneys would develop a trust for the personnel they were working with.

**Issue: Common Questions on Contracts from City Attorneys**

Regarding pricing structure, the attorney that the city IT staff worked with would often pushback to have cost framed in terms of “time & materials” rather than “lump sum.” Other concerns would be the insurance requirements for indemnity. One interesting request from a city attorney was to have a stipulation that the source code would be put in escrow so that in the case that the developing company went out of business, the city would have access to the source code.

Regarding an app contest where apps were being built on top of a city provided API, one city attorney had the following concerns:

-   What were other cities (or what had other big cities in the past) used in terms of verbiage, contractual language for similar kinds of API based app contests? (Terms of Use). The attorney was interested in the terms of use used in D.C. and the “NYC Big Apps” contest.
-   The city IT staff person would identify samples from other cities, and map back the understood goals of the present API app contest (as described by city staff) and try to construct a custom terms of use for the city.
-   **Trademark issue**: the city attorney provided language in the terms of use that required developers to disclose in the apps they built that their app was not sourced from the government, but was a product of the vendor/developer. Therefore, the citizen using the app would understand that by using the app they were engaging with a private vendor application, and not engaging with the city.
-   **Restriction on Distribution of Data**: The terms of use prohibited information gathered in the application from being sold for commercial use or spam.
-   **Offer and Acceptance Best Practice**: Developers would commit themselves to the terms of use by clicking “I agree” in order to receive an API key.

**
Best Practice: Level of Liability Specified**

Many cities do not require “mutual indemnity” and will accept “hold harmless” indemnity language.

**Best Practice: Addressing Any Perceived Security Risk from FOSS**

Personal data risk can be overcome with a security audit. Typically, security is fine behind a firewall - whether it is FOSS or proprietary. However, security concerns from security staff in a city IT department can often signal some other concern about the deployment, and often security is used as a scapegoat. There is also a position that FOSS may be safer because with more “eyes on the code” the odds of catching security holes are better. Further, when contractors working with government are altering code, it is better to have the code available for community review since many contractors are not adequately trained, and inadvertently open security holes.

**Best Practice: Sequence to Address FOSS Procurement to Reduce Risks**

-   Finding precedence - finding out what was being done in other cities and having examples ready for the lawyers to make them comfortable.
-   Pre-emptive security audits also, and dealing with security up front - Security people often delayed things so - knowing the security concerns of your organizations and involving them early.
-   Bring the lawyers on early when evaluating a project and familarize the lawyers with the product - what it will be used for.
-   Tiered Approach:
    -   Take all of the systems in place, and assign risk levels (privacy risk) by understanding risk level.
    -   For the least risky ones use FOSS or put in the cloud. Like Wordpress - which is mostly content - so its less risky - should be able to be hosted in the cloud - not detrimental to peoples health if it goes down. So go after low risk ones so you do not have to deal with privacy stuff. For public safety, maybe not right away.
