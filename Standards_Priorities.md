---
title: Standards Priorities
permalink: /Standards_Priorities/
---

[Category:Data Standards](/Category:Data_Standards "wikilink") Taken and modified from [@octolabs](http://twitter.com/octolabs) brainstorm at <http://etherpad.com/3cI9Dki4X5>

### Open Cities API Data Standards

#### Vision

Open Cities API is an effort to define unified local government platform that can be used by cities to publish their data and services and will be leveraged by civic developers to build innovative applications on top of to deliver better services to residents, visitors, businesses.

To succeed for this effort collaboration and adoption/implementation of this API is required from multiple cities such as Washington DC, San Francisco, Seattle, Boston, Chicago, Los Angeles

##### Components

Those are unified components that will cover common data and services across the cities

##### 311 & Idea Sourcing

Unified way to submit, report, track, analyze service requests (potholes, parking meters) reported to the city 311 call center (or various agencies if city lacks unified 311 system) Open 311 API (http://open311.org) is a baseline specification, that should be imporved to bring all commonalities and differences between cities under single umbrella.

###### Idea Sourcing & Citizen Feedback

Many government entities have begun using idea sourcing platforms like Pligg, Uservoice, or IdeaScale to aggregate and rank ideas from citizens. There should be a common format for collecting this data so that sharing of ideas can be better facilitated. A great case study is the [Open Gov Tracker](http://opengovtracker.com/) that aggregated data from federal government instances of IdeaScale. See also <http://wiki.civiccommons.org/#Idea_Sourcing_for_Data_and_Apps>

##### Directory of Officials, Organization Structure, & Jurisdictions

Unified way to present organizational structure (org chart) of the city government including agencies/departments as well as elected officials and executives with contact information associated with it. It will also include other phone directories like 411 (social services), various gov. units that provide services/phone hotlines, etc. This would also allow citizens to have consistent interfaces to find out who all of their elected officials are for their location. See also: <http://pages.e-democracy.org/DemocracyMap>

##### Crime

Every jurisdictions have different laws and reporting standards. Most cities collect and report crime on daily basis in internal format. Yearly cities report their crime in unified FBI reporting format to federal government. This API should capture both standards to provide ability to compare crime between cities and define baselines on yearly basis as well as provide real-time dashboards and alert for crimes.

##### Transit

Most cities do not own their local transit systems (they belong to regional transit authorities). This should be a way to aggregate such information. GTFS (General Transit Feed Specification). Beyond information that GTFS captures it will also provide walking info (e.g. Walkscore), bike information (routes, racks, storage, rental stations), carshare and parking.

##### Planning & Development

Standards for increasing accessibility to community based planning processes and community feedback for development proposals.

##### Public Meetings and Decision-Making Information

An early effort exploring standards for sharing public meeting notices, agendas, and links to decision-making documents, webcasts, etc. See: <http://pages.e-democracy.org/Public_Meetings>

##### Budget/Financial/Personnel

Unified way to define, publish and track municipal budget (tied to organizational structure) Unified way to represent city employees data. Query budget databases to follow how tax payer dollars are spent. Examples of government spending APIs on the federal level: <http://www.fedspending.org/apidoc.php> <http://www.followthemoney.org/services/>

##### Procurement

Centralized feeds for municipal contracts, spendings, businesses working with government.

##### Open Data

Unified programmatic way to access local data catalogs, metadata information as well as data itself.
