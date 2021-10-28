FS-DRA4 FileSender strategic roadmap and budget
=============================================

https://www.markdownguide.org/basic-syntax/
https://www.markdownguide.org/cheat-sheet/
https://guides.github.com/features/mastering-markdown/
https://stackoverflow.com/questions/17097894/markdown-tag-for-document-title


document editing style guide:
- two blank lines before a header, one between header and section text

This document is the strategic roadmap for the FileSender Programme as established in The Commons Conservancy foundation.

It needs to be read in tandem with 


If you want to add something to the roadmap, want to discuss priorities and 
cost estimates or have other roadmap suggestions, please either:
	* preferred method: create a governance issue ticket in the governance repository 
			on Github https://github.com/filesender/governance/issues
	* start a discussion on the filesender-dev mailing list. (link)



## Contents
- [Roadmap responsibility and updates](https://github.com/meijer/closed/blob/main/roadmap.md#roadmap-responsibility-and-updates)
- [Filesender Vision](https://github.com/meijer/closed/blob/main/roadmap.md#filesender-vision)


# Roadmap responsibility and updates
As stated in the [FileSender Statutes](https://dracc.commonsconservancy.org/0017/ ), the FileSender Board is responsible for defining and maintaining this roadmap.

The FileSender Board will update this roadmap regularly, consulting with the wider community. 

If you want to propose a change or addition to the strategic roadmap, please:
- submit an issue ticket to the [FileSender governance repository on Github](https://github.com/filesender/governance/issues)
- label the issue with the “Strategic roadmap” label


# FileSender Vision

FileSender aims to be a **widely deployed** platform
 enabling **anyone** 
to **easily and securely** transfer files of **any size**
from **any person or machine** to **any person or machine**.

**FileSender explicitly targets mass-usage and is built to service the 99% 
of users who have better things to do with their time than figuring out 
how to do large file transfer**


# FileSender governance and legal home
The FileSender Programme is an open collaborative software development effort 
with community governance provided by the FileSender Board of Directors.

FileSender’s legal-administrative home is with The Commons Conservancy, 
a Netherlands-based foundation for creating and fostering a technology commons in Europe. 

The Commons Conservancy is a multi-tenant “foundation-as-a-service” provider hosting 
virtual not-for-profit organisations in the field of open source software, 
design and hardware development. 

Relevant links:
- The Commons Conservancy: [https://commonsconservancy.org/](https://commonsconservancy.org/)
- FileSender in The Commons Conservancy: https://commonsconservancy.org/programmes/
- FileSender Statutes: https://dracc.commonsconservancy.org/0017/
- FileSender Regulations: <link to doc in TCC DRACC>
- FileSender Board: <link to board doc in FS repo>


# The FileSender software product 

To implement the vision the FileSender Programme produces open source software 
which can be installed by anyone. This allows any organisation or individual to 
spin up a FileSender service for their community, using the operational model 
that best fits their context and purposes. 


# The FileSender roadmap ambition

The roadmap supports the vision by ensuring continued support, maintenance, and 
further development of the FileSender open source software with features so 
relevant that the product is and remains widely deployed in the Target Groups


# Target Groups

Currently the main target group for the FileSender platform is 
the global Research & Education sector. FileSender is known to be used in other sectors. 

Future target groups being considered are government, health, NGOs, 
commercial service providers.


# Funding strategy

Since its inception in 2009, FileSender has been developed using paid-for contributions
supplemented with in-kind contributions.

FIleSender’s funding strategy is:
- large installed base allows sharing the development cost over many at low support cost per contributor (financial or in-kind contribution)
- low financial/other contribution per contributor


# Sourcing strategy
To support our strategic aim of continuous software production and community development (as opposed to start - bigger effort - stop), we prefer long-term engagements for key roles. It takes time to learn the code, the organisational context and the rhythm of the community.

Examples of such key roles are:
- lead developer
- community lead
- open source secretariat
- managing a public demonstrator installation

Short term engagements may be used for:
- specific, not continuously occurring tasks that typically are well (enough) standardised to capture in a simple description of work.
- tasks requiring specialised skills and knowledge we can not or do not want to maintain in the Programme
- tasks that require a big one-off effort on a specific area we don’t have resources for

Examples of such tasks are:
- code security audits, crypto security audits
- designing a new UI
- creating promotional material

Currently the majority of effort spent on FileSender is through paid-for contributions, complemented by in-kind contributions. 

Note that some tasks occur with steady intervals, e.g. security audits have been contributed as in-kind contributions by SURF over the years, though the firms used vary. We prefer such repeated in-kind contributions to be governed by MoUs. This allows for smooth integration of the in-kind contributions in the FileSender effort. It also gives predictability over time to the contributions, especially in times when the person responsible at the contributor’s organisation leaves.  

Long term engagements are typically organised through MoU-relationships between the person(s) engaging and the NLnet foundation. Short term engagements often take the form of contracting. 


# Strategic roadmap larger new developments
To achieve the ambition sketched above the long term budget needs to cover:

*A healthy minimum level of activity:*
- a well-maintained, secure product
- a well documented product
- minimise support overhead with a large installed base
- target frictionless installation and operations at service provider side
- adhering to universal access standards
- with a UI that is sufficiently modern and easy to use
- a minimum of continuous improvement
- ability to absorb community contributions and address community reported issues in a timely fashion
- a minimum of community-management activity to ensure
- fund-raising

*Advancing the strategic roadmap with larger new features*
There are two ways to achieve larger new developments of the roadmap:
1. divide them in smaller pieces to be realised in the time available for “a minimum of continuous improvement”
2. split such a development out as a separate activity with its own budget and e.g. do a kickstarter-style process: development starts once the necessary budget is collected, a budget that comes in addition of that required for the minimum healthy level of activity.

Experience shows larger items can be achieved using the first method, but with a long lead time. 

# Roadmap and budget for healthy minimum level of activity
The following activity is required to sustain FileSender as a usable, production-grade software product capable of sustaining a widely deployed installed base.

The governance framework has highest priority, as without it no funds will be raised and none of the other activities can take place.

| Priority | Work item | Annual Budget |
|---|---|---|
|1| Governance (board work) | In-kind contribution |
|2| Ensuring maintained code and a minimum of continuous improvements| € 20.000 |
|2| External security audits and implementation of required fixes | € 25.000 (fixes only, audits in-kind) |


### Governance (board work)
- description
	- operating FileSender’s decision making body
	- maintain governance process documentation to ensure the project can survive board members, key people and key organisations dropping out
- budget
	- in kind contribution

### Ensuring maintained code and a minimum of continuous improvements
- priority: 2
- description:
	- continuous reactive basic software maintenance
	- triage and address reported bugs, including urgent security issues
	- triage and implement small improvements
	- triage and merge community contributions
	- execution of the above in continuous open dialogue with the wider developer and deployment community
	- this item is known as “System Improvements” in current MoUs with tech lead dr. Martin
	- Based on historical data no extremely urgent issues have surfaced so far, hence no arrangement for rapid response to bugs has been needed, e.g. for the times the lead maintainer is on holiday.

- Annual budget:
	- current level: €20.000
		- allows proactive response
			- on scale from reactive-- to proactive++, indicating responsiveness to community dynamics
		- proactive++ response requires an estimated €30.000 anually
		- amount will increase as community activity increases, to support the resulting increase in community dynamics, requests etc.


### External security audits to ensure we know the security state of the software, and implementation of fixes
- Priority: 2
- Description: 
	- 
	- at a minimum an annual external code security audit is conducted to ensure
		- we know the security state of the softwar
		- the software is not open to any obvious attacks
		- new attack vectors are regularly taken in to account
		- we can document the state of software security, supporting compliance processes at FileSender deployers
	- ideally additional audits would be executed in the process of major code additions or changes
- Annual budget: 

Proposed annual budget: 
€25K
so far in-kind

Audits: in-kind contribution by SURF of one annual security audit, timing not coordinated with project








# Roadmap and budget for larger new developments

# Roadmap for project infrastructure








