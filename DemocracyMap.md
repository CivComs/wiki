---
title: DemocracyMap
permalink: /DemocracyMap/
---

See: <http://pages.e-democracy.org/DemocracyMap>

**Overview:**

*Plan and build a universal, free, open, shared and continuously updated database of government jurisdictions/entities, their websites, and over time add elected official contact information.*

In the United States there are approximately 30,000 government jurisdictions. There is no official database of the websites tied to each jurisdiction be it a city, school district, or some relatively obscure special district. Business.Gov, an effort of the Small Business Administration, recently released an API with 8,000 or so city and county websites raising interest across many organizations in how to to cover ALL government organizations.

Once collecting and maintaining a directory of all government jurisdiction web addresses and a way to find your jurisdiction by entering a street address or by using a map is addressed, then deepening data collection to elected officials and all government owned or funded websites will be explored.

-   [Join the Online Working Group to get involved](http://forums.e-democracy.org/groups/democracymap)

This initiative is being lead by a non-profit, non-partisan consortium combining the efforts of [E-Democracy.org](http://pages.e-democracy.org/Who_Represents_Me), [OpenPlans.org](http://openplans.org) and the [Sunlight Foundation](http://wiki.sunlightlabs.com/DemocracyMap). A consortium approach is envisioned to involve governments, inter-governmental associations, non-profits, media, online search, and other businesses interested in a sustainable model for gathering and maintaining data for the widest distributed use in the public interest.

This joint effort was launched based on discussions on the [CityCamp Exchange](http://forums.e-democracy.org/groups/citycamp/messages/topic/2ARcNEeK360XPsQo3fq4Jo) and a session at [Transparency Camp 2010 (turn audio way up)](http://www.ustream.tv/recorded/5757067).

### Case Studies

-   [MyRepresentatives.org](http://myrepresentatives.org/) tells you who represents you at all levels of Government in Australia.
-   [Openly Local](http://openlylocal.com/) Openly Local is a new project to develop an open and unified way of accessing Local Government information. See also [OpenlyLocal Ward Maps](http://countculture.wordpress.com/2010/06/02/ward-maps-on-openlylocal-how-i-did-it/)
-   [Freedomspeaks](http://www.freedomspeaks.com/default.aspx) provides representative lookup and an API
-   [RepSheet](http://repsheet.com/) - Representative site for Chicago area. It's [open source](http://code.google.com/p/repsheet/), based on Django.
-   [localpolitics.in](http://localpolitics.in/) - this was just started and recently posted on the [sunlight labs mailing list](http://groups.google.com/group/sunlightlabs)
-   [Civic Footprint](http://www.civicfootprint.org/) - this is a largely defunct project, with data currently for the Chicago area. Because it's a closed database with no user contributions, and it no longer has funding to be improved, this will never get any better.
-   [NY Times Represent](http://prototype.nytimes.com/represent/) - a recent project that covers New York City. This also has voting records and articles that include the representative.
-   [votesmart.org](http://www.votesmart.org/) - includes biographical information and some location information (seems a little rougher on location than some databases). National. Also includes information about candidates, and a voting record. Has some local officials but not local candidates.
-   [American Solutions](http://www.americansolutions.com/) is making some sort of [wiki](http://www.technologyreview.com/web/22025/?nlid=1725&a=f), though it may only allow user editing of contact details.
-   [LittleSis](http://www.littlesis.org) is an involuntary facebook of powerful Americans, collaboratively edited by people like you.
-   [WhoRunsGov.com](http://WhoRunsGov.com) offers a unique look at the world of Washington through its key players and personalities. Our site features profiles of prominent government officials, including members of the Obama administration, U.S. lawmakers and governors, senior congressional aides and committee staff, lobbyists and experts at think tanks and interest groups who comprise the world of unofficial Washington.
-   [Smart Voter](http://www.smartvoter.org/) Local election coverage for candidates and ballot items.
-   [Vote 411](http://www.vote411.org/) Focused on state level elections.

### Open Source Precedents

-   <http://whoismygov.org> ([source](http://bitbucket.org/slinkp/purplevoter/src/))
-   <http://github.com/mcommons/legislative-lookup>
-   <http://demo.geowebdns.org/>
-   <http://wepublic.org/>

### Data/APIs

-   Links to NY specific data on this [entry's discussion page](http://ideas.topplabs.org/wiki/Talk:Who_is_my_government%3F)
-   [Geo2Gov](http://geo2gov.com.au/) - The Geographic Search Engine for Australian Government 2.0 Applications
-   [FreedomSpeaks API](http://content.freedomspeaks.com/api/developers.aspx)
-   <http://www.avencia.com/Products/Cicero/LiveSample.aspx> (not free and maybe spotty data)
-   <http://www.sunlightny.org/snl1/faces/app/browse.html>
-   <http://mcommons.com/developers>
-   <http://maps1.civicid.org/>
-   <http://maps.civicid.org/map.php>
-   [@2gov](http://2gov.org) has a lot of manually-entered local official data, and they might open up an API as per [this thread](http://groups.google.com/group/sunlightlabs/browse_frm/thread/30cc8948fe79f3ce/4c6be847d94eb4c2?show_docid=4c6be847d94eb4c2)

### Data Standards for elections/elected

-   <http://openelectiondata.org/>
-   <http://votinginfoproject.org/>
-   <http://docs.oasis-open.org/election/eml/v5.0/os/EML-Process-Data-Requirements-v5.0.html>

#### Base Data:

Listing sources of data.

##### Entities:

-   2007 Governments Integrated Directory (GID) - <http://harvester.census.gov/gid/gid_07/options.html>
-   Local government entities described:
-   County Governments
-   Municipalities
-   Townships
-   Special District Govts
-   Independent School District Govts
-   Local Dependent School Systems
-   Education Service Agencies
-   State Dependent School Systems

(this appears to be the source data - 2002 & 2007 Data) <http://www2.census.gov/govs/gid/>

-   [School Districts - U.S. Department of Education Common Core Data](http://nces.ed.gov/ccd/) - Note: The Department of Ed. stopped asking state's for web data after an initial attempt was error ridden years ago - particularly with individual schools (which is below the jurisdiction level for us). This field should be put back in and our service used to maintain it for at least school districts.
-   [USGS - Domestic Names - State and Topical Gazetteer](http://geonames.usgs.gov/domestic/download_data.htm)
-   FIPS Unique ID to join data
    -   <http://quickfacts.census.gov/qfd/meta/long_fips.htm>
    -   <http://www.census.gov/geo/www/ansi/ansi.html>
    -   <http://www.geonames.org/export/>
-   State Government Agencies, Service Districts, and Entities - Source(s)?
    -   <http://www.usa.gov/Agencies/State_and_Territories/Agencies_by_Topic.shtml>
-   [Tribal Governments](http://factfinder.census.gov/home/aian/index.html)

##### Mapping Location to Entities

Municipalities & Townships:

-   Incorporated Places/Census Designated Places

Cartographic Boundary Files <http://www.census.gov/geo/www/cob/pl2000.html>

-   [Census.Gov - 2010 Boundary and Annexation Survey (BAS)](http://www.census.gov/geo/www/bas/bashome.html)

###### Key Data About Places

-   <http://www.usa.gov/Government/State_Local/Statistics.shtml>
-   <http://www.census.gov/statab/www/ccdb.html>

##### Connecting Government Jurisdictions/Entities to Websites

-   [2007 Governments Integrated Directory (GID)](http://harvester.census.gov/gid/gid_07/options.html)
    -   Includes web sites for many governments and sometimes the web page for a township as of 2007
-   [U.S. City and County Web Data API - Business.Gov](http://www.business.gov/about/features/api/geodata/)
    -   Not clear who or how the data is maintained, whether it can be downloaded in full, and where to send additions/corrections. (The data is pretty open. I haven't found a comprehensive download, but the API is pretty friendly. The XML is straightforward)
-   [Tribal Governments](http://www.usa.gov/Government/Tribal_Sites/index.shtml)

##### Core Fields

What are the core fields of data to compile/crowd-source?

-   Government Type
-   Government Name
-   Street Address
-   City
-   County
-   State
-   Zip
-   General Telephone
-   311 - Y/N
-   TTD Telephone
-   General E-mail (Web Contact)
-   FIPS Code (is it useful to keep FIPS places that don't have gov't? e.g. towns or unincorporated areas within a county if users want to search by those. Business.gov allows this)
-   Zipcodes Served (maybe use ext. source for this? commercial or geonames)
-   Long/Lat of main HQ building
-   Geo/Boundaries
-   Primary Website URL
-   If none, Primary Webpage URL (for really small government, often unreliable)
    -   Active/Broken
    -   Home Page Last Updated Date
    -   Web Feeds Available from Home Page

##### Additional Fields

-   Multi-lingual Main Page(s) - Language, Link
-   Accessibility Validation (508)
-   Calendar/Events/Meeting Page URL - iCal Feeds
-   Information Elements - Checklists ...
-   Organization Twitter Handle: @something
-   Organization Facebook Fan Page URL:
-   Organization YouTube Account URL:
-   Wikipedia Page About Organization:
-   Wikipedia Page About Placename:
-   Newspaper of Record (where government notices are printed) Name:
-   Newspaper of Record URL:
-   Registered Government Jurisdiction Record "Owner" for direct updating of added fields - ability to request additions from the city clerk for example who has opted-in to feed in site data
-   Verified/Unverified links - If you crowd source links to a Facebook Fan page for example, you would need to labeled unverified until is some how is verified.
-   Giving unrestricted data access to gathered e-mail addresses might render general government inboxes unusable. Possible solution - a partnership hosted U.S. version of WritetoThem.com model with a unique URL generated in a web contact field. Through WritetoThem.com you can only contact those (elected officials in their case) governments that serve you. Those wanting to contact governments that do not represent them would need to use current contact methods.

##### '''Proposed Officials Fields '''

Preliminary fields related to elective bodies - information that will assist future incorporation of elected official information:

-   Elected or Appointed Governing Body:
-   Name of Elected Body:
-   At-Large: Y/N
-   Term of Service:
-   Partisan: Y/N
-   Staggered Terms:
-   Judges (Retention Style?):

*This section needs work!*

-   Public Positions
-   Mayor
-   City Council Member
-   County Board Member
-   Township Board Member
-   Special District Board Member
-   School Board Member
-   Treasurer
-   Tax Collector
-   Auditor-Controller
-   Sheriff
-   Constable
-   District Attorney

'''Proposed Staff/Quasi-Govt. Head Fields ''':

-   City Secretary
-   City Manager
-   City Public Information Officer
-   City Planning/Development Director
-   City Parks and Recreation Director
-   Police Chief
-   Police Public Information Officer
-   School District Superintendent
-   School District Public Information Officer
-   Chamber President
-   Economic Development Director
-   Council of Neighborhood Association Chair
-   Council of PTA/PTO President
-   County Board Member Chief of Staff
-   County Public Information Officer

Agency Heads

##### Microformats?

-   Can hCard or other [microformat](http://microformats.org/code-tools) be used or modified to allow political entity websites to post easily parseable information relating to who represents what?
-   What existing spiders can be used to gather data thus posted? (e.g. Yahoo Local supports hCard <http://microformats.org/wiki/implementations> )

Crowd-Sourcing
--------------

-   There are dozens of "silo" directories of government websites of a certain kind. All of them suffer from the challenge of keeping up-to-date. There are also 50 state government portals, most of whom host manually maintained listing of local government websites.
-   "Submit-it" crowd-sourcing would require an encouragement link from the state and major "silo" government link directories. If they do not use the data, they will not likely link to encourage governments to submit new websites via the service.
-   Technology assisted volunteer crowd-sourcing is another option where we leverage search engines to identify possible websites for government jurisdictions without known (or no longer functioning links) websites/pages and streamline the verification process.

Potential Partners and Collaborators
------------------------------------

**In the loop so far:**

-   The Open Planning Project - <http://openplans.org>
-   E-Democracy.org - <http://e-democracy.org>
-   Sunlight Foundation - <http://sunlightfoundation.com>
-   Google
-   e-thepeople
-   ImagineElections
-   Grasshopper
-   Business.Gov/Small Business Administration

**Might be interested:**

-   Project Vote Smart - <http://votesmart.org>
-   ICMA - <http://icma.org/resources/GovSites/>
-   National Association of Counties: <http://www.naco.org/Template.cfm?Section=Find_a_County>
-   National League of Cities: <http://www.nlc.org/inside_nlc/membership/membership_rosters/354.aspx>
-   National Association of Towns and Townships: <http://www.natat.org/>
-   State League of Cities and County Associations
-   State Government Portals with Local Government Web Directories
-   USA.Gov links to state local gov web listings: <http://www.usa.gov/Agencies/Local_Government/Cities.shtml>
-   Sunshine Review - <http://sunshinereview.org>
-   National Association of State Chief Information Officers - <http://www.nascio.org>
-   National Association of Local Government Webmasters - <http://www.nagw.org>
