---
layout: page
title: Institutional Web Management Workshop
shorttitle: iwmw
topnavigation: true
permalink: /notes/iwmw/
---
## Summary 

This year I attended the Institutional Web Management Workshop. Here are my thoughts followed by the my rough notes I made during the talks. I'm happy to talk at length about anything mentioned here.

I've linked to the presentations where these were shared. 

I found the conference to be an interesting event and it was good to meet people from other university web teams. We all shared a familiar mix of issues and worries. Things like Web transformation projects, cms migrations, responsive re-designs etc. 

### Good Ideas which I think we should adopt

#### Bath

I found [Bath's approach](#2-2) of thinking about their work as _products_ rather than _pages_ each with their own backlog to be very compelling. 

They hold "Show and Tell" sessions where team members demonstrated their work to their colleagues. This looked like an effective way of keeping everyone informed and to consolidate their own understanding of the work. I'd like to see us do that here in Lancaster. 

It's worth looking at their [blog](http://blogs.bath.ac.uk/digital/).

### Things which I think were useful


#### SiteManager 8

The presentation by T4 about the progress of version 8 of SiteManager was promising but it also looked like a lot of work remained. 

They are moving the product to a RESTful architecture with a more modern user interface. We'll be able to communicate with the web services so that opens the possibility of us creating bespoke interfaces for things, perhaps simple interfaces for certain content etc.

Publishing was improved as was the ability to import and export content between SiteManager instances. 

We can join the beta programme if we wish by contacting their service desk.

#### Scripting Analytics

The demo session on how to write Google Apps scripts and hook that into Google Analytics looked like an interesting way to generate custom analytics reports. Might be worth looking at this approach rather than giving everyone access to Analytics.

## Notes

Day One

- [SiteManager Version 8 Preview](#1-1)
- [Welcome presentation by Brian Kelly](#1-2)
- [Why you don’t need a social media plan and how to create one anyway presented by Tracy Playle](#1-2)
- [Digital Adaptation: Time to Untie Your Hands presented by Paul Boag](#1-3)
- [Hyper-connectEd: Filling the vacuum by switching from blow to suck presented by Martin Hawksey](#1-4)

Day Two 

- [Building cost-effective, flexible and scalable education resources using Google Cloud Platform presented by Sharif Salah](#2-1)
- [Using the start-up playbook to reboot a big university website presented by Ross Ferguson](#2-2)
- [Marketing is dead, long live UX presented by Bruce Darby and Neil Allison](#2-3)
- [Birds of a Feather Sessions](#2-4)
- [“You are ALL so weird!” University sector analysis and trends presented by Ranjit Sidhu](#2-5)
- [What Does The Data Tell Us About UK University Web Sites? presented by Andrew Milsted and Christopher Gutteridge](#2-6)
- [Rapid Development: Analytics reporting powered by Google Apps Scripts presented by Martin Hawksey](#2-7)

Day Three

- [Rebooting MyEd - Making the Portal Relevant Again presented by Martin Morrey](#3-1)
- [Allocating Work: Providing Tools for Academics presented by Hiten Vaghmaria](#3-2)
- [What is Our Vision for the Institutional Web and Can We Implement the Vision?](#3-3)
- [Conclusions presented by Brian Kelly](#3-4)

---

## SiteManager Version 8 Preview <a name="1-1"></a>

*Not for public viewing (internal notes only)*

### People 
* Laura Murphy
* Paul Kelly
* Barry 
* Colin

### Clients
* St Andrews - Gareth Saunders, Duncan Stephen
* York - Dan Wiggle, Paul May
* University of Liverpool - Sam Trafford 
* others ...

### Basics 
* Early access programme on going
* beta programme happening in the next few months - log an issue if we want access

### Interface
* Navigation is in a left sidebar 
* Bootstrap based
* Responsive
* Everything is searchable 

### Publishing And Transfer
* Happen in the background - logs can be viewed
* Publishes are queued up :-)
* Transfers also run in the background 

### Infrastructure
* RESTful everything (JSON)

### Assets
* Really obvious when you delete something
* inline search for content types (Id, group name, content name etc)
* navigation objects which are similar (related content and advanced versions etc) are now merged

### Configuration 
* Grouped logically rather than by which handler they are implemented by

### Packages
The goal (perhaps not version 8 first release) is to enable assets to be transferred from one instance to another and it will keep track of versions. Something can be developed on a development server and then easily transferred to a production server.

* Bundles are now called "packages"
* Format is XML 
* Can be downloaded directly from the web interface
* entire package imports can be 'rolled back'

---

## Rebooting The Web. What Is The Purpose Of This Conference And What Do We Do In The Future? <a name="1-2"></a>
**Brian Kelly** [@briankelly](https://twitter.com/briankelly)

### Meet Up Ideas
* Tanners arms
* Cumberland arms

## Why You Don't Need A Social Media Plan And How To Create One Anyway <a name="1-3"></a>
**Tracy Playle**  [@tracyplayle](https://twitter.com/tracyplayle) - picklejar communications

### A Military Approach To Social Media.

#### Start With A Cause (have Objectives: What Do You Want People To Think, Feel And Do)
* ask 'so what?' until you reach solid objectives. (Business goals)

#### Define Your Target
* what are they saying about us
* who else are they talking to? (What are they saying about us could be very different to what they tell us)
* what are their wants, needs and distractions? (Social technographics)
* who do they follow? (How do you compare to the people they follow?)
* what sort of cultural relationship does the audience have to you?
* audience attributes of people:
	*  creative (bloggers etc)
	*  conversationalist (commenters)
	*  critic 
	*  collector (Pinterest people, storify)
	*  joiner (people who join up to services to be a part of it)
	*  spectator
	*  inactive (most are spectators or inactive - lurkers)
* different audiences need different approaches. Creators/conversationalists/critics require community management. 
* use your observations to form your personas

#### Plan
* what journey is the audience going to take to get them to where you want them to be?
* advocacy - action - desire - credibility  - interest - awareness
* the journey shows the context. What do you talk to them about at a given time? 

#### Munitions
* **the content**

#### Artillery
* platforms
* channels 
* analytics - measurement and evaluation (best value spend) - things like radion6, hootsuite, search metrics etc

#### Troops (the People You Need)
* senior managers
* strategists
* creative
* content creators
* learning technologists
* lecturers and researchers
* students
* web editors
* developers
* community manager communications professionals 

#### Balls
* "benign violation" - comedy 
* don't be afraid to be funny or poke fun of yourself
* the danger of committees is that they tend towards the benign and therefore the boring and safe things
* talk sense but hidden in comedy is a powerful tactic

---

## Digital Adaptation: Time To Untie Your Hands <a name="1-4"></a>
**Paul Boag** [@boagworld](https://twitter.com/boagworld)

* [Copy of the talk plus goodies](http://boagworld.com/iwmw14/)
 
How digital technology has changed the world. 

How do we and how does digital change the institution? How do we stop ourselves being instutionalised?

What is the case for change? And what is the plan for implementation?

### Create A Case

* Highlight the opportunities
	* can we reorganize ourselves to achieve faster results? (Business case)
* Focus on the threats
	* if we do nothing we do not stand still we get swept away
* Use data 
	* analytics
	* student intake
	* student engagement
* Appeal to  the selfish gene
	* internal politics - appeal to the needs of middle-management
	* if it gets it done then let them take the credit (taking the credit is the same as them taking ownership and therefore making it in their interest)
* Cost savings 
	* remove inefficiencies - example: improving conversion rather than increasing advertising spend
* Get outside help
	* outside credibility
	
### Set The Direction

* give management something to agree to - then they do not have to come up with the idea
	* term "digital transformation team" rather than "web transformation team" - communicate the remit clearly
	* Map user journeys to show where the transformation should take place
* Prototype the new vision
	* give people something to agree or disagree with
	* prototypes leads to frameworks and tools to carry out transformation
* Educate and disband
	* show and educate people
	* when transformation has occurred then disband the team - move on

---

## Hyper-connectedEd: Hyper-connectEd: Filling the vacuum by switching from blow to suck <a name="1-5"></a>
**Martin Hawksey** [@mhawksey](https://twitter.com/mhawksey)

* [slides and goodies](http://bit.ly/iwmw14-p3)

Digital networks have moved from centralised to decentralised to distributed. Education is still decentralised at best and centralised at worse. How do we advance?

Decentralised education looks like educators using their own choice of tools in their own way. 

Really is this better??

It can be ... using existing services gives you a leg up, a university does not have to reinvent all of the wheels. Existing tools are known to students. 

Create a collection site, a "domain of one's own", to harvest all the stuff from the different networks. A personal / class based knowledge graph.  This is a challenge creating different interfaces between the sites to collect the information. 

Create digital profiles for students. Creating a low-tech social network. 

### Creating Education That Is
* Decentralised
* Networked 
* Peer driven 

### Links And Tools
* [PHONAR](http://phonar.covmedia.co.uk/) - Photography class
* [DS106](http://ds106.us/) - Digital Storytelling Class
* [A domain of one's own](http://umw.domains/)
* [BuddyPress](http://buddypress.org/) - for creating a social network layer in Wordpress
* [BadgeOS](http://badgeos.org/) - a Wordpress plugin for [Mozilla Open-Badges](http://www.openbadges.org/) 

---

## Google Cloud Platform
**Sharif Salah** - University of Portsmouth 

* [The Slides](http://goo.gl/No9gFM)

### Cloud Platform Overview
* Software as a service
* Platform as a service
* Infrastructure as a service 

* Why 
	* Integration with google apps
	* variety of PaaS and laaS
	* auto scaling - monitoring
* Compute
	* compute engine
		* analysis 
		* vm hosting
		* node.js, Ruby on Rails etc
	* app engine
		* platform as a service (java, python, php and go)
		* can use traffic splitting for simple A/B testing
		* can be used to host things like Wordpress etc 
* Storage 
	* cloud database
	* cloud storage
		* good cdn like capabilities 
		* multi petabyte storage!!
		* good for unstructured large blobs of data (PDFs etc)
	* cloud SQL 
* Services
	* cloud endpoints (sit on top of app engine - allows you to create own api)
	* BigQuery (good for storing logs for analysis)

* How to interact with these
	* Cloud console
	* cloud sdk
	* cloud api

### Existing Usage 
(Sample infrastructure: student records --- middleware --- cloud storage --- the web)
Portsmouth use this to host and scale their web site and applications 

### Potential Future Usage
* Offering VMs for each student. Less than $0.50 per person per hour. 
* Using Docker to move web app instances to and from the cloud as required. 
* Kubernetes - can automatically migrate load between Docker apps for scalability. 

### Lessons Learnt
* Billing support is really important to address early on
* use auth is really simple
* web apps require a small amount of ongoing development work
* the platform is growing very rapidly 
* app engine is super reliable 
* buy a support contract! 
* Get offline billing via premier status - better for invoicing
* create a new domain for google apps so you can control who has access (otherwise you give access to everyone and they can have billing issues)
* by default compute engine instances block port 25 (mail) - you can ask for this to be removed
* if you need to restrict data to the EU - this can be done but best to talk to the support

### Resources
* [The Google Help](Http://.cloud.google.com/developers)
* [Google Cloud Starter Pack](http://g.co/cloudstarterpack)

---

## Using The Startup Playbook To Reboot A Big University Website
**Ross Ferguson** - [@rossferg](https://twitter.com/rossferg) - Head of Digital  - Bath University - rf396@bath.ac.uk

Transforming a university website in 24 months!!
This team is focused on developing rather content generation. 

### Fuck Yeah Startups (advantages Over Large Instutions)
* Problem-solving
* creative
* practical 
* disruptive
* replicatible 

## What Else Can Be Run As A Startup?
* Dating
* [Taxi services](https://www.uber.com/)
* energy supply
* [parliamentary records](http://www.theyworkforyou.com/)
* diplomacy 

### Gds Is A Startup By Government
* Alphagov
* changed gov.uk
* changing the civil service

### Can Bath.ac.uk Be Run As A Startup?
* What's the opportunity?
* are the right people in place?
* do the methods transfer? 

### Got A Problem?
All university websites seem to be the same. Dull. Same. 

* Same old, same old
* usage is 'meh'
* tired tech
* sell, sell, sell
* de-motivated teams

### New Goals
* Devolve publishing and engagement (experts writing the content not the web team)
* Make the tasks easier
	* what do visitors want - not all visitors want to be sold a course; at least apart from a few key times of the year
* make the work meaningful
	* the goal is for his team to be desirable to other places
* be known for delivery

### New Old Team

Team of 14!!!

* One team, multiple functions
* HE veterans and n00bs
* producers, not managers
* trusted to self-facilitate
	* direction by presenting problems to solve NOT solutions to implement
* new governance

### Delivery Principles Over Process
1. Put user ends first
2. Make decisions based on date
3. Release iteratively and often
3. Keep things simple and consistent
4. Provide ongoing support
5. Work in the open

### Products, Not Pages

Products are things like: the site, the CMS, templates etc. Everything is on the roadmap and everything has a backlog

* Roadmap
* backlogs
* agile delivery

### The Users Made Me

Always ask 'what does the user need, what are you trying to solve'
* Self-initiated
* user research (over marketing messaging)
* no client work

### Tools of the Trade
* [Slack](https://slack.com/) - chat
* [Trello](https://trello.com/) - planning
* [heroku](https://www.heroku.com/) - prototyping
* [foundation](http://foundation.zurb.com/) - prototyping
* [bamboo](https://www.atlassian.com/software/bamboo)
* [GitHub](https://github.com/bathweb)

### Fail Fast, Lower Risk

Shipping stuff and a weekly and daily basis. 

* MVP
* Show and Tell sessions (every other Friday morning to demo to each other what is happening)
* weeknotes
* pivots
* retrospectives 

### The Downsides
* Agile vs waterfall
* too much product (there's too many things to work on, too much work)
* burn out
* sprinting alone
* autonomously aligned
* discipline is hard (it's hard not to just do what the higher ups say they want)

### The Upsides
* Always be shipping
* meeting everyday needs
* bring up problems
* monitoring performance
* on the panels (as in the team is often invited to sit on interview panels. Sign of trust)
* seeing ourselves in others

### Is It Replicable and Scalable?
Aim is devolve more and encourage other digital teams around the university. 

* University of Bath
* university of whatever
* mentality, methods, model

### We Will Transform The Model, Spin Out A Product Or Fail

### Try It

Open invitation. Come visit, see how we work, help out for a week! 

### Resources
* [Spotify videos on how teams are managed](http://labs.spotify.com/2014/03/27/spotify-engineering-culture-part-1/)
* [Bath Web Team - the blog](http://blogs.bath.ac.uk/digital)

---

## What's with UX In HE
**Neil Allison [@usabilityed](https://twitter.com/usabilityed)** - UX - Edinburgh 

Make the UX of the web site part of the overall student experience.  Then it can be governed by our pro vc for student experience.  

* Is ux not a differentiator?
* is the nature of the product is such that customers tolerate poorer ux?
* is it because it's just too hard? 
	* no - everyone can make a slight attempt (everyone cooks even if they are not a chef)

### Links
* path  - degree creation tool (module selection) at Edinburgh 
* www.ed.ac.uk/website-programme

---

## You are all so Weird!
**Ranjit Sidhu [@rssidhu](https://twitter.com/rssidhu)**

Not all that is measurable is important and not all that is important is measurable 

## Assumptions 
* Can be powered by data 
* however data can lead to bad decisions (financial crisis)
* university websites have a lot of data

Humans can make personal decisions which can be better than assumptions based just on faceless data. 

By its nature, left alone, data is emotionless

Web managers can use large amounts of data BUT also know the audience. They combination can lead to better assumptions. 

Too much data can lead to indecision because it's just too much to care about and understand. 
Data should be used to create useful things, not be something by itself. Take the data and make it into useful information to help decision makers make decisions. 

### Trends
* Home pages are much less important. Seeing much less traffic. 
* People are more focused on the course pages. 

### Summery 
* Create useful things 
* context is everything
* use your weird position to your advantage
* make exciting things

---

## Data.ac.uk
**Christopher Gutteridge [@cgutteridge](https://twitter.com/@cgutteridge)** & Andy Milsted
University Of Southampton

Taking 'open data' from across the sector to make useful things. 

Someone is doing is at Lancaster but it's not us. Find them and see how you can help. 

### Equipment
Uniquip - structured standards (RDF) for publishing this open data. 
Using a link rel on the homepage of the domain to advertise what open data is provided

### The Observatory
Looking at all the .ac.uk homepages and collects information such a technologies in use etc. We can add our own plugins to do a regexp on our domain via a pull request. 

### RSS
A collection of all ac.uk RSS feeds linked to on the homepages. 

### Links And Examples
* [Equipment](http://equipment.data.ac.uk)
* [the observatory](http://gitHub.com/data-ac-uk/observatoryCrawler)
* [RSS](http://rss.data.ac.uk)
* [opd.data.ac.uk](http://opd.data.ac.uk/)
* [observatory.data.ac.uk](http://observatory.data.ac.uk/)

---

## Scripting Google Analytics
**Martin Hawksey** 

### Google Analytics - Beyond Page Views 

*  demographics
	*  overview
	*  age
	*  gender
	*  remember that google does not allow you to track individuals 
*  collection
	*  tracking how long people are watching your videos with *google tag manager*
	* code added to the page which then gives you a cloud interface to changing that code (so it's embedding that remote snippet from the cloud)
	* you can therefore vary that code depending on the content of the page (eg pages with YouTube etc)
		* examples:
			- YouTube  tracking
			- kindle it function for blog post pages
* Connection
	* APIs for web, android, ios 
	* superProxy - app engine app by google to allow users access to a view of the data

### Google Apps Script

Google drive based scripting language for manipulating drive data. Syntax like js. Script editor is in the cloud. Supports 11 google apps. 

*Examples*: 
* Tony Hirst - populating a calendar from a spreadsheet
* emailing trigged from a form submission

Get started at *GoogleDrive > Create > Script*

Jobs can be scheduled, like cron, via *triggers*

*Add-ons:*

* Address labels from avery
* citations via EasyBib
* mailchimp 

### The Fun Bit!

*Add-ons for Analytics:*

* Google Analytics
* Analytics canvas
* supermetrics

Some of these allow you to distribute access to views to your Analytics easily.  

Demo shows using the google Analytics add on to google sheets to create a custom Analytics report as a spreadsheet. 

Using supermetrics to grab tweets and then search those for mentions of a given domain or hashtag. In his resources he has a basic script for making a dashboard. You could create a script which generates reports as new docs or emails wi th charts etc. 

### Resources And Links 
* [Slides and resources](http://bit.ly/iwmw14-a1)
* [Personal site](http://hawksey.info)
* [SuperProxy](URL)
* google+ communities 
* [google Analytics query explorer](http://ga-dev-tools.appspot.com) - for generating the function call arguments in the ga query *Anaytics.Data.Ga.get*
* [import.io](http://import.io) - scrape websites into structured data which can be absorbed in scripts

---

## Rebooting MyEd - Making The Portal Relevant Again
**Martin Morrey** - Web Integration Manager, University of Edinburgh


### Portals

A single interface for students and staff to internal systems 

* MyEd
	* the web portal 
	* launched 2004
	* 200 channels (portlets) of content
	* based on uPortal
	* difficult to upgrade
* U@Ed - app
	* Like iLancaster app 
		* Same platform, same sort of functionality
		
### Why Portals?

> a portal is like a website ... except it takes five times as long to develop

* Who is it for?
	* links to other services 
	* live info from other services
	* communications
	* support material
* Why
	* one place you can go to find everything about you
		* personalised
	* provide a consistent user interface to backend systems
	* be the prefferred medium for personalised communication to students
	* a place for all the links?
		* an increasing amount of personalisation leads to complexity
* UX platform
	* portlet based
		* unread email
		* upcoming events
	* personalised layouts
		* these house the portlets
		*different page layouts for different users/tasks
		* customisation by users for their own layouts
			* not very popular (5% usage) but very useful to a small amount of people
	* what are people using the portal for?
		* Anaytics is tricky because...
			* the unit of content is a portlet or a channel rather than a page
			* so they are using jQuery to create events for ga which can be tracked
	* What do the users want from the portal?
		* survey
			* the portal fares better than the app in user satisfaction 
			* portal gets more usage - even on mobile 
				* fewer features on the app - lots of linking out from the app to the web
				* it's hard to keep the two different systems up to date
		* what we think they want
			* survey of task requirements
				* with desktop and mobile environments 
				* comparison with these to the Anaytics to see if they map to what people actually do
		* conclusion 
			* the mobile app wasn't worth continuing 
			* make the portal better on mobile
			* supplement with task based apps when needed
	* next steps
		* retire mobile app
		* restructure portal layouts to match ga usage
			* using twitter bootstrap - much better mobile experience
		* new features
			* better email
			* better calendar 
		* better mobile
			* jQuery mobile
			* task based (like the mobile app)
				* with the popular tasks from the survey and Anaytics 

---

## Allocating Work: Providing Tools For Academics
**Hiten Vaghmaria** - Head of Digital Development at the University of Westminster

* Work load allocation
	- How is this planned
	- how is it reported
	
* how was this reported
	- Different groups has different spreadsheets
	- the spreadsheet was eventually standardised 
		- which was complex and difficult to maintain
		- and then broke
* how should this be reported
	- It should be web based! 
	- top down - approach
		- union involvement 
		- management 
		
 
## What Is Our Vision For The Institutional Web And Can We Implement The Vision?

---

## Conclusions 
**Brian Kelly** - Innovation Advocate at Cetis. Recent content at http://www.rebelmouse.com/briankelly/


# People I Talked to 
* Alister - ghostly - framework for spinning up web app installs as a service
* Ross Ferguson - Bath University - digital team manager
* Chris Beard - Keele 
* Mark Johnson - OSS watch - Oxford
* Chris Gutteridge - Southampton - eprints (open data)
* Amy Chamier - Institute of Education
* Mike - ocean stuff Southampton 
* Morag - University of Dundee - Web Designer
* Dave Bailey - Web Editor - Bath Spa
* Scott Sweeting - Web Developer - University of Sunderland (scott.sweeting@sunderland.ac.uk)