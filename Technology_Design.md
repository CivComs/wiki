---
title: Technology Design
permalink: /Technology_Design/
---

When you're launching a data service, key questions:

-   Is Google or other big guys already building apps that consume this data? If so, how do they want it?
-   Are there other cities that provide similar apps? What data formats do they use?
-   Dan O'Neill: data still balkanized. e.g. NY building permits in excel more frequently updated than the xml feed from bigapps
-   ACTION: Everyblock to work on standards doc: Class A data feed looks like this: frequency, semantics, normalities; if you can't do that, class B looks like this

Standards

-   The importance of conventions. The web worked because www.foo.com was guessable. So let's promote conventions like: apps.dc.gov, data.ny.gov. <http://www.datasf.org/> isn't guessable.
-   Listing of data standards:
    -   See <http://wiki.civiccommons.org> for a good list of the state of the art in standards, case studies etc.
    -   GTFS - General Transit Feed Spec <http://code.google.com/transit/spec/transit_feed_specification.html>
    -   (FusedLogic had some problems with this spec.) There's an active mailing list, room for extensibility.
    -   OGDI - <http://ogdi.sourceforge.net/>
    -   geoweb DNS <http://wiki.open311.org/GeoWeb_DNS>
    -   OAuth/OpenID Best practices
    -   Question of Read/Write APIs?
    -   Missing persons and People Finder Interchange Format <http://zesty.ca/pfif/>

Identify Data Structures

-   Standardized content
-   Metadata - in human readable format
-   Need contact info associated with the feed

<!-- -->

-   Data Types
    -   Crime
    -   Transit
    -   Restaurant inspections
    -   Building permits
    -   Street (potholes, street obstructions) - private company obstructions not covered by 311 requests - 311 associated only with labor on the city side
    -   Legislative testimony, transcripts
    -   Parking
    -   Tax assessments
    -   Demographic data
    -   Statistical transit data
    -   Basemap/geocoding WGS84, KML
    -   Parks - what sports fields
    -   Calendars - event schedules - need better calendaring systems. "Outside.in has its act together here"
    -   Business Licenses
    -   Employee directory/org charts

<!-- -->

-   Missing: Feedback loops: was 311 fixed to your satisfaction?
-   Craigslist a good source for many fundamental datasets (eg waste that isn't really waste); Freecycle

Leverage existing Tools

-   Meetup
-   Twitter - Best practices
-   Twitter API should be cloned by 311
-   Facebook
-   LinkedIn
-   Wordpress, Tumblr on-demand info
-   Gowalla
-   Yelp - now doing check-ins - idea to get women/minority owned data in there
-   Foursquare
-   OpenTable?
-   Craigslist
-   Localdirt, Farmsreach, JustFood in NY to bring fresh food into urban food deserts
-   Walkscore - get more data sets in there
-   What are the best practices and tools for API management? mashery? sonoa?
-   Tools for metrics, measuring engagement
-   FrontlineSMS <http://www.frontlinesms.com/>, also tools like <http://www.textmarks.com/> for group SMS, freejam, forinfo
-   Google Voice - what are good examples of voice integration?
-   Dashboards - GoodData (cloud analytics), Intuit Quickbase
-   Amazon Web Services
-   VMWare
-   UserVoice

What would make city IT more efficient? How do we think about improving city workflow?

-   versioning of datasets
-   interface to systems like Hastis from the new stuff
-   Ward Cunningham's Visible Workings

What does the well-formed future look like? What's the greater vision?

Outcomes

-   Listing of data standards
    -   Recommended
    -   Style/Principles
    -   Frequency/semantics/normalities
    -   Manage need/want
    -   Include narrative
-   Tools that are compliant
-   Tools that munis can use for specific tools
-   Push Craig to better engage muni services
-   If you adopt X, you'll get Y stories: city, IT dept, developer, end-user
    -   like the way citygoround shows value of GTFS
