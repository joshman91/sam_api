---
published: true
layout: default

---

<h1>News and Updates</h1>

SAM only supports the latest 2 versions of the APIs.  The currently supported versions are:
* GetData V8 (latest version)
* GetData V7
* Search V3
* Search V2

Legacy versions of the API may be sunset soon. Review the change versioning documentation and migrate your applications to the latest versions of the SAM APIs.

**Updated March 14, 2019.** - SAM is releasing updated versions of the GetData API and Search API.  You may view the specific changes on the SAM API Versioning page.  On May 1, 2019, SAM will remove the links for the unsupported API versions (GetData V6 and below, Search V1).  If you have clients using these deprecated API versions, you will need to migrate to the latest versions (GetData V8, Search V3). 

**Updated February 20, 2019.** - Effective February 1, 2019 SAM APIs will only return registration data which is fully complete. If a registration is in the beginning stages of the registration process and has not been validated by outside data sources such as DLA and IRS, it will not be returned or searchable by API.  This improves data quality and performance by preventing incomplete, possibly incorrect, registrations from the return set.

**Updated February 6, 2019.** - We are moving from the GitHub support model to our Federal Service Desk for any issues. If you experience difficulty or have questions, your best course is to contact the Federal Service Desk (www.fsd.gov) and open a service ticket. This will get you funneled to the correct technical team who can troubleshoot and help you resolve any issues you may have. 

**Updated March 30, 2018.** - We completed our transition to email-verified API keys. If your existing API key no longer works, please submit a new request at [http://gsa.github.io/sam_api/sam/key](http://gsa.github.io/sam_api/sam/key).

**Updated on October 23, 2017.** - Based on usage analysis, we recently modified the rate limits for the SAM APIs. The standard rate limits for the SAM APIs are now 1,000 calls per API key in a 24 hour-period, 5,000 calls per IP Address in a 24-hour period, and 5 calls per 5 seconds. If you need to have higher, customized rate limits, please submita request to our supporting Federal Service Desk at [www.fsd.gov](http://www.fsd.gov). Title it "SAM API Rate Limit Increase" and provide the email address you used to create the API Key, your Account ID, your IP Address, and a description of how you use the SAM APIs requiring a higher limit.

**Updated on October 30, 2015.** - The SAM team is happy to introduce v4 of the standard API and some updates to the v2 of the Search API. The updated field references for v4 can be found [here](fields4.html). We are also announcing that support for v1 and v2 will cease as of this release. We will continue to support only the latest 2 current versions of the API (v3 and V4). That being said, v1 and v2 will still be available for use, but we cannot provide resources for ongoing support as we would like to enhance the system for everyone’s availablilty and not dwell on outdated versions. If there are any questions or issues, please visit the [Support and Feedback](issues.html) to open a ticket.

**Updated on June 26, 2015.** - The SAM API has a release of v3 of the standard API and release of v2 of the [search](search.html) API. The updated field references can be found [here](fields3.html). Another new page which contains a better overview of the changes can be found in our [Versioning](versioning.html) document.The latest version of our Data Dictionary is available for download which will give a deeper look into the SAM system and how it functions.

The latest version of our [Data Dictionary](https://www.sam.gov/sam/transcript/SAM_Functional_Data_Dictionary.pdf) is available for download which will give a deeper look into the SAM system and how it functions.

<h1>Background</h1>
<p>The SAM API is a  RESTful method of retrieving public information about the businesses or  individuals (referred to as &ldquo;entities&rdquo;) within the SAM data set. The entities  publicly available data set can currently be retrieved on an entity-by-entity  basis. The initial SAM API release was introduced in June 2014 and allowed  users of the API to retrieve publicly available entity data. The next iteration  of the API, released in fall 2014, provided the ability to search SAM to find  an entity based on the search criteria submitted.<br />
  In  addition to the entity information, we also provide status and progress  information. This information is also included as part of the front end feature  for the SAM Status Tracker. The status refers to the status of the entity&rsquo;s  registration - whether they are working on their registration, waiting for a  validation from the IRS or the DoD (CAGE), or are active, as an example. The  progress is most relevant for those who are working on their registration; it  indicates whether a user has finished filling out different sections of their  registrations, as well as the progress of their validations with external organizations  such as the IRS or DoD. This should indicate how far along in the process a  user is in completing the work they need to do in order to successful be  registered in SAM.<br />
  Access  to the SAM API is administered through the API.Data.Gov which is an API  management service federal agencies.&nbsp; Consumers  of the SAM data must first register and obtain a key from the site.&nbsp; The key will allow users to access the SAM  APIs.</p>
