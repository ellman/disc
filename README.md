#D.I.S.C
========

##DISC rating system for opensource projects

**Explanation:**

Does it work (Delivers on promises)
Issues (Are issues handled or are they neglected)
Support (Is support available from the maintainers or parent company)
Community (Is there an active community and community contribution)

Future home for the project is discit.org (as in rate it)

**Motivation:**

Being a developer working on a number of dynamic open source projects both in terms of contribution and usage poses a massive difficulty to today's developers.

We are in constant need of new libraries and have a vibrant exciting community that is constantly pushing code developing new exciting projects

When it comes time to make use of open source projects be in for a POC (proof of concept) or a production app, having a working stable project with active development, issue management and support is absolutely crucial.

Most importantly a developer cannot afford to waste hours upon hours of testing and debugging countless libraries and services in the hopes of finding one that works with the right licensing and has the legs to carry him into production.

**How it works:** (Proposed ideas, these will probablly be adjusted/changed)

The DISC rating system is simple, from rating to understanding the score and reports. The base score is automatically generated per project according to defined criteria with additional rating done by the board of raters (the community)

The base rating is recalculated each day allowing for long term assessment of the project which helps developers find consistent projects that have performed well over the long term as well as providing feedback and suggestions to the project maintainers.

The system will provide graphs and metrics allowing one to easily see the stabillity of a project over time. In addition an embeddable widget will be provided allowing sites and pages such as modules on npm and github to embed the rating widget.


**The rating system:**

Projects who’s score exceeds a certain threshold will be added to the user testing queue and will be assigned to one of the testers for evaluation. In addition projects can request a user review and it will be added to a public queue for review


1. Does it work: 

 Automatic Tests:

 1. Travis-ci, is there a project
 2. Travis-ci, does the build pass
 3. Are dependencies defined
 4. License (is there a valid open source license)

 Manual Tests:

 1. Documentation clarity
 2. Code review
 3. Installing
 4. Uninstalling
 5. Error handling

2. Issues: 

 Automatic Tests
 1. Open to closed issue ratio
 2. Last issue opened to last issue closed ratio
 
 Manual Tests:

 1. Review recent issues for quality of response
 2. Review of issue severity

3. Support:
 
 Automatic Tests:
 1. Automatic open issue on behalf of the system to detemine if responded to
 
 Manual Testing:
 1. Open new issue as random user to determine response
 2. Do they have premium support services

4. Community:
 
 Automatic Tests:
 1. Number of stars
 2. Number of forks
 3. Number of commit contributors
 4. Number of open pull requests
 5. Number of closed pull requests
 
 Manual Tests
 1. Social network presence. Twitter, facebook, irc etc
 2. Stackoverflow tags


A full DISC score would be A4.0/M4.0 indicating indicating full point for automatic and full points for manual. A good score might be [3.0,3.0] while a [2.0,2.0] might indicate a young project with promise for the future . Anything below [2.0,2.0] would be a significant risk.

Once a project has been automatically evaluated a widget may be embedded in the projects readme as well as a graph displaying the fluctuations in the score.

In addition the DISC rating site will provide a search option which will bring up the relevant data of the project in question including the full evaluation report.

