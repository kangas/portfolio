# Matt Kangas

email: kangas@gmail.com  
github: [@kangas](https://github.com/kangas)  
twitter: [@mattkangas ](https://twitter.com/mattkangas)  
cell: 718-812-6542

**Objective: Build amazing teams and ship revolutionary products.**

## Employment History

### MongoDB (Formerly 10gen)

> MongoDB is the most widely adopted open-source "NoSQL" database.  ([mongodb.com](http://www.mongodb.com))

**Engineering Manager**, March 2013 - September 2016. New York, NY

*Compass team: 3.4 cycle, Jan-Sep 2016*

- Co-authored a patent, "SYSTEMS AND METHODS FOR MODELLING VIRTUAL SCHEMAS IN NON-RELATIONAL DATABASES". US Patent filed July 2016. This describes innovations created for MongoDB Compass 1.0
- Grew my team to 6 direct reports
    - Hired two junior developers in Sydney, Australia, working with recruiters in Dublin, Ireland
    - Onboarded one internal transfer (remote)
- Led a geographically distributed team:
    - 3 in Sydney, Australia
    - 2 in Europe: Berlin and Stockholm
    - 2 in USA: Philadelphia plus myself in NYC
- Worked directly with product manager and design lead to define the product roadmap and deliver an industry-leading UI experience
- Delivered 4 major (stable) releases. 20 distinct releases completed January-September 2016
- Implemented beta/stable channel release methodology and a 6-week release cadence
- Conference: MongoDB World 2016 (June, NYC)
     - Planned and staffed a booth at the conference to promote Compass product
     - Delivered a "treasure hunt" gameified product experience for conference attendees
     - Rewarded with a stock bonus for outstanding team performance at the conference

*Integrations team: 3.2 cycle, Feb-Dec 2015*

- Booted up new team, focused on commercial software to complement our open-source database
- 3 senior engineer direct reports
- Project: APM integration with New Relic and AppDynamics
    - Goal: provide complete solution for monitoring MongoDB-based applications
    - Initiated outreach to partner companies, led weekly meetings with them for 5 months
    - Successfully motivated teams at partner companies to work our project
    - Project featured by New Relic in keynote of their developer conference, Nov 2015
- Project: MongoDB Compass
    - Goal: Win hearts & minds of Enterprise DBAs by helping them understand data in MongoDB
    - New desktop GUI application delivered on Windows and OS X
    - Unique innovation: samples a database collection to infer a probabilistic schema, then presents a query builder based on schema/data visualization
    - Led team of 3 that conceived, designed, implemented, released from March-December 2015
    - First demo in keynote at MongoDB World, June 2015
    - Launched 1.0 release December 2015
    - Implemented entirely in Javascript using Electron framework

*Kernel team: 3.0 cycle, May 2014-Jan 2015*

- Leading new "Kernel Community team". A more hands-on role
- Three direct reports: two senior, one junior
- Goal: Drain the pull request backlog on [github.com/mongodb/mongo](https://github.com/mongodb/mongo)
    - 250+ neglected open-source contributions in C++ codebase of highly visible project
    - We analyzed and responded to each one, clearing path for new contributors without trampling on old, often bitter contributors
- Goal: Deliver server log subsystem improvements
    - Designed [log components/filtering capability](https://docs.mongodb.com/manual/reference/log-messages/) in MongoDB 3.0. Implemented functionality and tests in C++
- Goal: Deliver two contracted enhancements for In-Q-Tel
    - Multilingual full-text enhancements to MongoDB Enterprise. Wrote spec. Vetted 3rd party linguistic tokenization libraries
- Goal: Improve performance of MongoDB on Microsoft Azure
    - My team identified a bug in Azure VM host block device driver. Microsoft acknowledged and resolved.
- Supervised source contributions from Facebook and WiredTiger
    - Facebook: Created code review workflow that satisfied peculiar legal requirements
    - WiredTiger: From initial open-source contributions through MongoDB acquisition in late 2014

*Kernel team: 2.6 cycle, May 2013-April 2014*

- I was hired to provide additional management bandwidth
- Directly managed 20 engineers throughout the 2.6 release cycle
- Responsible for 1:1s, performance reviews, promotion nominations, compensation review
- Defused personnel crises


### Squarespace

> Squarespace is a website hosting service with a sophisticated website builder UI and strong design emphasis.
> [squarespace.com](http://www.squarespace.com)

**Engineering Manager**, August 2012 - March 2013. New York, NY

- Reported to VP of Engineering
- Delivered new real-time site performance monitoring capability
    - Implemented & configured Graphite time-series metrics database
    - Implemented performance metrics collection from their primary Java web applications
    - Led evaluation of APM solution from AppDynamics

### Daylife

> Daylife was a cloud publishing service used by 200+ commercial media organizations.
Launched 2006. Raised $15 Million. Acquired by NewsCred in 2012.
> (Formerly: __daylife.com__. Wikipedia: [Daylife](https://en.wikipedia.org/wiki/Daylife))

**Director of Engineering**, November 2011 - August 2012. New York, NY

- Delivery of next-generation media delivery platform
- Implementation of HBase to consolidate our persistence layer
- Due diligence with potential aquirers

**Senior Infrastructure Engineer**, June 2008 - November 2011. New York, NY

Platform: CentOS, Python, some Java and C, many databases. 100+ machines serving > 1 billion API calls/month by 2010

- Upgraded front-end MySQL databases to keep up with traffic growth
- Full system audit to eliminate single points of failure
- Implemented RPM-based deployments to ensure transactional rollouts and rollback
- Implemented runnable unit and integration test suites
- Implemented consistent developer environments
- Rewrote build system & implemented continuous integration using Hudson (aka Jenkins)
- Centralized log collection
- Implemented scalable log processing using Hadoop and Pig
- Prototyped clickstream log analytics
- Researched scalable key-value datastores to replace MySQL, Postgres, BerkeleyDB, cdb+rsync, flatfile
- SVN to Git (Github) migration

### Flix55

> Flix55 was a project by WLNY-TV to create a crowdsourced streaming video destination site competitive with YouTube. (Formerly: __flix55.com__)

**Lead Technical Consultant**, February 2007 - June 2008. Melville, NY.

- Implemented video transcoding using On2 Flix Engine for Linux, including work queue and bulk media storage
- Implemented search engine for videos/users based on Apache Solr (Lucene). Designed full indexer, incremental indexer, search schema, installation/upgrade process
- Setup of Xen/CentOS domains, Subversion, Trac, yum repository, security audits

### Team Gigabyte, Inc. (DBA BusyTonight)

> BusyTonight was a search engine for events: things happening at a place and a time.  
> Formerly: __busytonight.com__

**Cofounder and CTO**, May 2005 - June 2007. New York, NY

- Founded company with two partners to create a “vertical search” portal for events
- Primary designer of all subsystems. Used cheap x86 hardware, Java code, Ubuntu Linux. Debian package deployment, continuous integration, Trac/SVN
- Web Crawler: 6 machines crawled 30k websites, 15M URLs refreshed every 2 weeks. Nutch 0.7 plus custom “crawl trap” avoidance
- Feature Detector: Natural language detection of dates+places in normal HTML. Recognizes 50+ date formats, 10+ address, all in plain English
- Auto-Extractor: extraction of event listings from “dirty” HTML. Stateless algorithm analyzes location of “features” within HTML document structure. Listings include “sanitized” HTML summaries, image thumbnails (when found in original listing)
- Indexer: Daily full reindex cycle. Scaled to 5M listings, 2M unique
- Front End: Java search server feeding a PHP UI

### HotJobs, acquired by Yahoo, Inc

> HotJobs was one of the top-three trafficked employment websites in the USA. It was acquired by Yahoo! in 2002 and renamed Yahoo! Hotjobs. Later acquired by Monster.com in 2011.  
> Formerly: __hotjobs.com__, __hotjobs.yahoo.com__. Wikipedia: [Yahoo!_HotJobs](https://en.wikipedia.org/wiki/Yahoo!_HotJobs).

**Technical Yahoo!**, August 2001 - April 2005. New York, NY

- __hotjobs.com__ was one of the top-three trafficked employment websites in the USA
- I rebuilt a mission critical back-end system for bulk data imports by large customers.
    - Achieved total backwards compatibility via extensive reverse engineering and a rigorous QA cycle.
    - Result was an order-of-magnitude win in reliability and manageability.
- Created resume/job-apply import processor within an extremely compressed schedule (one month) to support careers.yahoo.com during the Y!/HJ merger
- Debugging and diagnosis of nearly all back-end systems
- Developed in Java, Python, C on Solaris and FreeBSD

### DME Networks

**Co-Founder and CTO**, March 2000 - May 2001. New York, NY

- Started company with two partners to provide B2B services + solutions
- Built client API, web app, fulfiller-side GUI app for drop-shipping of goods, printing packing lists, and updating order status
- Application stack implemented in Java (J2EE, Swing)
- Co-wrote a full business plan, pitched to VCs and potential clients
- Folded operations due to market conditions

### MCY

**Lead Programmer and E-Commerce Architect**, August 1998 - January 2000. New York, NY

- __mcy.com__ was an online music service which sold encrypted MP3 files and CDs
- Team leader from startup to IPO
- Designed & implemented online music sales system, including credit card processing via Cybercash
- Designed relational database (70+ tables, 1M+ records) for sales, inventory data, using Informix, object-relational mapping to business logic
- Objective-C, Webscript, SQL development

### Cybergrrl

**Assistant Technical Director**, July 1997 - August 1998. New York, NY

- __cybergrrl.com__ was a community website to support women in technology
- Responsible for running ~100 email mailing lists (Webgrrls)
- Java, Perl, SQL, HTML template development for re-launch of cybergrrl.com
- Solaris server administration

## Education

CORNELL UNIVERSITY, COLLEGE OF ENGINEERING. Ithaca, NY  
Bachelor of Science in Electrical Engineering, May 1997

CORNELL UNIVERSITY, COLLEGE OF ARTS AND SCIENCES. Ithaca, NY  
Bachelor of Arts in Theatre Arts, Cinema Studies. May 1997.
