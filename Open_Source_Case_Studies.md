---
title: Open Source Case Studies
permalink: /Open_Source_Case_Studies/
---

Europe
------

-   [OSOR - Open Source Observatory and Repository](http://www.osor.eu) - The Open Source Observatory and Repository for European public administrations (OSOR) is a platform for exchanging information, experiences and FLOSS-based code for use in public administrations.
-   [OSOR Case Studies](http://www.osor.eu/studies)
-   [OSOR Forge](http://forge.osor.eu/) - a Repository which provides a set of tools for public administrations to help them collaboratively develop and share of their Open Source Software solutions.
-   [OSOR Projects](http://www.osor.eu/projects) - You can search for 2260 FLOSS projects hosted by the OSOR.eu Repository or one of the federated national forges in Europe. The search engine uses the machine translation service of the European Commission to make searchable, and present all project descriptions in English.

Municipal Open Source
---------------------

See also [\#civicforge + \#civiccommons on Delicious](http://delicious.com/tag/civicforge+civiccommons)

### Municipal Case Studies from OSOR

Select [OSOR Case Studies](http://www.osor.eu/studies/case-studies)

-   [Open Source Software Migration in the Belgian City of Schoten](http://www.osor.eu/studies/open-source-software-migration-in-the-belgian-city)
-   [A sharing attitude: Programverket in Sweden](http://www.osor.eu/studies/a-sharing-attitude-programverket-in-sweden)
-   [Katowice Municipality: saving public money with OpenOffice.org](http://www.osor.eu/studies/katowice-municipality-saving-public-money-with-openoffice.org)
-   [City of Amsterdam investigates the use of Open Source Software within its welfare organisations](http://www.osor.eu/studies/city-of-amsterdam-investigates-the-use-of-open)
-   [Arles (France), in progression towards Open Source](http://www.osor.eu/studies/arles-france-in-progression-towards-open-source)
-   [Dutch Municipality of Haren Migrating to Open Source Software](http://www.osor.eu/studies/dutch-municipality-of-haren-migrating-to-open)
-   [Municipality Terneuzen: “open source is not a choice between all or nothing”](http://www.osor.eu/studies/municipality-terneuzen-201copen-source-is-not-a)
-   [Migration of the German City of Schwäbisch Hall](http://www.osor.eu/studies/migration-of-the-german-city-of-schwabisch-hall)
-   [Balkan cities become e-municipalities with open source](http://www.osor.eu/studies/balkan-cities-become-e-municipalities-with-open)
-   [Case Study – Linux Server for the City of Salzburg](http://www.osor.eu/studies/test-case-test)
-   [London Borough of Camden: public procurement of open source software development](http://www.osor.eu/studies/london-borough-of-camden-public-procurement-of)
-   [Open source in five municipalities in Groningen](http://www.osor.eu/studies/open-source-in-five-municipalities-in-groningen)
-   [IJsselstein municipality: open source is not an end in itself, but it is an important means to an end.](http://www.osor.eu/studies/ijsselstein-municipality-open-source-is-not-an-end)

<div id="Government-to-Government_Re-use_Examples">
Gov-to-Gov Re-use Examples
--------------------------

Examples of government-to-government re-use: cases where one government or agency released code as open source, and another then re-used that code. This is not a complete list, and it is inherently anecdotal. Please add more examples.

-   [OpenTripPlanner](http://opentripplanner.com/): Open-source multi-modal trip planning software (rail, bike, bus). Started by Portland, Oregon [TriMet](http://trimet.org/) agency, developed and open-sourced in cooperation with [OpenPlans](http://openplans.org). Now has production deployments in Portland, Valencia (Spain), and Poznan and Lublin (Poland), plus demo deployments in New York City, Tampa, Ottawa, Pune, Bilboa, Granada, Gipuzkoa, Dublin, Budapest, and Tel Aviv, as of Nov 2011. See the [deployments page](https://github.com/openplans/OpenTripPlanner/wiki/Demos) for more. Original cost to develop approximately $300,000 USD. Savings to other jurisdictions: about that much per jurisdiction, since they didn't have to rewrite or re-purchase the software. Savings to original jurisdiction: *probably considerable, now that project has active participation from non-Portland developers, but still finding out nature and degree*. See [2011 report from TriMet](https://raw.github.com/wiki/openplans/OpenTripPlanner/Reports/OTP%20Final%20Report%20-%20Metro%202009-2011%20RTO%20Grant.pdf), starting at the "Executive Summary" on page 8. Note especially the implicit comparison (on page 17) with earlier non-open-source gooroo.com system from Chicago, which cost $1,000,000, with proprietary MDV component subsequently purchased by San Francisco for use in the Bay Area: *"Multi-modal routing is not yet functional in the Bay area."*.
-   [OneBusAway](http://onebusaway.org/) Bus arrival-time tracker. Originally built by a computer science grad student for Seattle (so not a pure case of gov-to-gov reuse, but note that the developer was able to do this because Seattle and other regional governments were already making an effort to support open technology by publishing transit information in [GTFS](http://code.google.com/transit/spec/transit_feed_specification.html) and other standard formats), it was [picked up](http://openplans.org/projects/an-open-platform-for-real-time-bus-tracking/) by OpenPlans at the behest of [New York MTA](http://bustime.mta.info/), which will now get bus-tracking for 1/4 the estimated cost of a proprietary solution. From [bustime.mta.info/wiki/Technology](http://bustime.mta.info/wiki/Technology): *"The MTA BusTime server is powered by the [OneBusAway](http://www.onebusaway.org/) Open Source software package. This software was originally developed to aggregate real-time information from multiple bus and ferry operators in the Seattle area and make it available to Seattle's transit users in a range of internet and mobile interfaces. OneBusAway uses as its baseline information transit schedules published in the [GTFS](http://code.google.com/transit/spec/transit_feed_specification.html) format, which the MTA is [already publishing](http://mta.info/developers/download.html) for all of its bus and rail services. [...] Since OneBusAway is [Open Source](http://en.wikipedia.org/wiki/Open-source_software), the MTA is able to use it free of charge. This pilot project required a number of improvements and customizations to OneBusAway, for which the MTA partnered with [OpenPlans](http://openplans.org/). All of these improvements have been contributed back to the OneBusAway project, and are now free for any other developer or transit agency to use."*
-   [Adopt-a-Hydrant](http://adoptahydrant.org/) / **Adopt-a-Thing**: Started as a [project](http://codeforamerica.org/?cfa_project=adopt-a-hydrant) to enable citizen monitoring and access maintenance for civic infrastructure (e.g., digging out fire hydrants in snowy Boston), developed cooperatively between City of Boston and Code For America; [see demo video](http://vimeo.com/31459095). We don't have cost savings figures yet *(TBD)*, but as the project was designed to be retargetable (the word "hydrant" was only stored in one place, so it could easily be reconfigured for, e.g., tsunami sirens), cities like Honolulu are not paying anywhere near the cost to develop a new application from scratch. Some of the places looking at reusing the app include:
    -   Honolulu: for similar maintenance of tsunami sirens.
    -   Bloomington, Indiana: for storm drains
    -   Seattle, Washington: also for storm drains
    -   Chicago: "Adopt-a-Sidewalk" (for snow-shoveling)
    -   Boston: also hydrants?
    -   Buenos Aires: ?
-   [Open311](http://open311.org): Tons of deployments of Open311-related apps (at least in pilot phase; some may be in production deployment, not sure). Look for Open311 Dashboard in particular *(TBD: Needs more research.)*
-   [Bluebird](https://github.com/nysenate/Bluebird-CRM) Constituent Relationship Management (CRM) software from the New York State Senate. Fully open source, built on Drupal; [deployed here](http://crm.nysenate.gov/). Now being piloted by other government agencies *(TBD)*.
-   **CaBIG precursor.** U.S. Department of Energy workshop funded precursor to CaBIG system for exchanging clinical trial data, now at National Institutes of Health / National Cancer Institute Center for Bioinformatics (NCICB)'s [open source site](http://gforge.nci.nih.gov/). See [this thread](http://groups.google.com/group/mil-oss/browse_thread/thread/71da5abad6c47541/133bc18c4e42d234) for more details, in particular [this message](http://groups.google.com/group/mil-oss/msg/133bc18c4e42d234) and [this reply](http://groups.google.com/group/mil-oss/msg/626ffc20fceabd6d).
-   **The Internet (no, seriously)**. TCP/IP, BIND DNS, etc: funded by U.S. Defense Advanced Research Projects Agency (see [BIND history](http://www.isc.org/software/bind/history), for example). Return on investment: immeasurable (literally).

Projects To Watch for Re-use:

-   [NYC Bike Share Map](http://nyc.gov/bikeshare) Built for NYC, coming soon to other cities; [OpenPlans](http://openplans.org) has details.
-   [uReport Open311 CRM](http://marketplace.civiccommons.org/apps/ureport-open311-crm). Initially developed by and for Bloomington, but others are looking at reusing
-   [data.gov](http://data.gov) - The US and India are partnering to develop an open source version of data.gov that they'll both use and make available for others to use
-   [We The People](http://whitehouse.gov/wethepeople) - the White House has committed to release the source code for the We The People petitions platform so that other governments can reuse it. There's already been some interest.

And some things to take a closer look at:

-   [CONNECT](http://www.connectopensource.org/adopters) - an open source software solution that supports health information exchange – both locally and at the national level.
-   [The Direct Project and open source](http://wiki.directproject.org/Implementation+Source+Code) - The Direct Project develops specifications for a secure, scalable, standards-based way to establish universal health addressing and transport for participants
-   [Magnolia Data Share](http://magnoliadatashare.org/) Federally funded, shared among cities in Mississippi. Appears to be run by University of Mississippi. *Not open source, but still gov-to-gov.* Web site appears to be not fully functional yet: no matter which nav tab you click on, you get the same summary information. Contact them and find out what's going on, and whether they have plans to open source the code?
-   New York State Office of Temporary Disability Assistance, myBenefits.ny.gov, [shares business logic](http://gcn.com/Articles/2011/05/30/Profile-New-York-CIO.aspx) for Federal entitlement rules with other states on an open source platform.
-   [Open Public](http://openpublicapp.com/) Gov-specific customizeable Drupal distribution: "OpenPublic is an open-source, content management system (CMS) based on Drupal and tailored to the needs of government." *Not completely sure of origin, but believe it emerged from gov-funded work; need to find out details.*

### Sources

-   [List of software released as open source by U.S. Federal, state, or local governments](https://docs.google.com/a/civiccommons.org/spreadsheet/ccc?key=0AlXDdNQEU-8fdDI0OFJEVXRYNGhDNVRrVDhUS19LVVE&hl=en&pli=1#gid=0). (Compiled by Scott Goodwin, with help from many.)
-   [<http://groups.google.com/a/civiccommons.org/group/discuss/browse_thread/thread/c885a710b33de86c>\# Thread about re-use examples] (2011-10-27) (re-posted on [govloop](http://www.govloop.com/forum/topics/what-s-the-best-example-of-gov-to-gov-software-reuse) and [mil-oss](http://groups.google.com/group/mil-oss/browse_thread/thread/71da5abad6c47541))

By Application Type
-------------------

### Office Productivity

#### OpenOffice

-   See [Major OpenOffice.org Deployments for Government](http://wiki.services.openoffice.org/wiki/Major_OpenOffice.org_Deployments#Governments)

### Content Management

#### Drupal

-   Local gov - <http://groups.drupal.org/node/24119>
-   Federal & State - <http://groups.drupal.org/government-sites>

### GIS

-   [OpenGeo at NYC DoITT](http://opengeo.org/publications/nyc-doitt/)
-   [OpenGeo at Portland Trimet](http://opengeo.org/publications/trimet/)

### Operating Systems

#### Linux

-   See [Linux for Government at Linux.org](http://www.linux.org/info/linux_govt.html)
-   [Largo, Florida](http://www.linux.com/archive/feed/119109) case study
-   [2003 article on Linux in municipalities](http://www.cioupdate.com/trends/article.php/2237451/Across-the-Country-Local-Governments-Are-Giving-Linux-a-Hard-Look.htm)

### Data catalog platforms

See [Data platform list](/Data_Platform#Data_Platform_Survey "wikilink").

### Project Catalog Applications

See [App catalogs](/App_catalogs "wikilink").

Other Resources:
----------------

-   [Open Source Policy](/Open_Source_Policy "wikilink")
-   [Case Studies of a number of Open Source implementations both in Local Government, schools and business in the UK and Europe](http://www.opensourceacademy.org.uk/solutions/casestudies)

### Working Groups

See the Open Source [Mailing Lists & Working Groups](http://wiki.civiccommons.org/Organizations/Open_Source#Mailing_Lists_.26_Working_Groups)

[Category:Open source](/Category:Open_source "wikilink") [Category:Case studies](/Category:Case_studies "wikilink")
