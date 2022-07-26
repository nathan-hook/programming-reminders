Things to keep track of as a professional application developer and consultant...

A lightly currated list.

# Programming is Hard

[Every Programmer Should Know](https://github.com/mtdvio/every-programmer-should-know)

[Curated list of falsehoods programmers believe in.](https://github.com/kdeldycke/awesome-falsehood)

[Let’s talk about usernames](https://www.b-list.org/weblog/2018/feb/11/usernames/)

[Personal names around the world](https://www.w3.org/International/questions/qa-personal-names)

[Personal names around the world 1](https://r12a.github.io/blog/200610#20070709)

[Personal names around the world 2](https://r12a.github.io/blog/200707#20070716)

[Falsehoods Programmers Believe About Search](https://opensourceconnections.com/blog/2019/05/29/falsehoods-programmers-believe-about-search/)

[Why are the username and password on two different pages?](https://www.twilio.com/blog/why-username-and-password-on-two-different-pages)

[Everything you ever wanted to know about building a secure password reset feature](https://www.troyhunt.com/everything-you-ever-wanted-to-know/)

[The Tech Lead’s New Project Checklist](https://insimpleterms.blog/the-tech-leads-new-project-checklist)

[The traits of a proficient programmer](https://www.oreilly.com/ideas/the-traits-of-a-proficient-programmer)

[The fine art of fast development](https://hackernoon.com/the-fine-art-of-fast-development-f3b1abb509da)

[7 Skills of Highly Effective Programmers](https://medium.com/better-programming/7-habits-of-highly-effective-programmers-563ee3b63f33)

[Humility in Software Development](https://www.mattblodgett.com/2016/09/humility-in-software-development.html)

[The mythical 10x programmer](http://antirez.com/news/112)

[Laws, Theories, Principles and Patterns that developers will find useful.](https://github.com/dwmkerr/hacker-laws)

[big-list-of-naughty-strings](https://github.com/minimaxir/big-list-of-naughty-strings)

[All software advice is wrong](https://mdswanson.com/blog/2020/10/31/every-article-about-software-is-wrong.html)


# Security

[OWASP Top 10 Vulnerabilities](https://snyk.io/learn/owasp-top-10-vulnerabilities/)

[10 Java security best practices](https://snyk.io/blog/10-java-security-best-practices/)

[Security Headers](https://securityheaders.com/)

[HTTP Security Headers](https://www.loginradius.com/blog/async/http-security-headers/)

[SSL Server Test](https://www.ssllabs.com/ssltest/)


# Clean Code / Code Quality

[How To Write Unmaintainable Code](https://github.com/Droogans/unmaintainable-code)

[Guide: Writing Testable Code](http://misko.hevery.com/code-reviewers-guide/)

[S.O.L.I.D. Software Development, One Step at a Time](https://www.codemag.com/article/1001061)

[Test-Driven Development: Really, It’s a Design Technique](https://www.infoq.com/articles/test-driven-design-java/)

[Test-driven development: Theory and Practice](https://blog.codecentric.de/en/2019/06/test-driven-development-theory-practice/)

Emphasis is mine.
> In fact, these two concerns (test coverage and product quality) are independent: one can easily imagine a high-quality system running in production, delivering a lot of value to its users, and not having a single automated test at all – just delete all the tests after deploying and completing extensive validation of the system. On the other hand, **it is conceivable to achieve 100% test coverage and have an extremely brittle or unusable system; in this case the tests do not provide any value at all, and are just as useless as the system itself.**

[Technical Debt](https://martinfowler.com/bliki/TechnicalDebt.html)

[Code Smells](https://blog.codinghorror.com/code-smells/)

[A Taxonomy for "Bad Code Smells"](http://mikamantyla.eu/BadCodeSmellsTaxonomy.html)

[Refactoring Guru](https://refactoring.guru/)
> Refactoring.Guru makes it easy for you to discover everything you need to know about refactoring, design patterns, SOLID principles, and other smart programming topics.

# How to Write Code

[Learning Writing and Coding from a Con Artist](https://www.bitquabit.com/post/learning-writing-and-coding-from-a-con-artist/)

> Get something that works, no matter how silly and brittle. Don’t think too hard about it: don’t worry about it being DRY, or being as fast as possible, or properly encapsulated, or anything else. Just get something that works. If it’s garbage, throw it out and start over; you barely spent any time on it anyway. Once it’s mostly not garbage, begin a refactoring pass. Make sure that what the code is doing is clear, concise, efficient, and above all, *makes sense to read* — because you *will* forget where your head was at in six months when you inevitably have to do some maintenance on this code.

# Consulting

[Never say “no,” but rarely say “yes.”](https://blog.asmartbear.com/how-to-say-yes.html)

> So the principle is easy: Set the conditions of “yes” such that:
>
> 1. If they say “yes,” you’re happy because the terms or money are so good, it more than compensates for the distraction, possibly even funding the thing you really want to do.
> 1. If they say “no,” you’re happy because it wasn’t a great fit anyway, so it’s not worthwhile for a small return on your time and effort.

[How to Get Lucky: Focus On The Fat Tails](https://taylorpearson.me/luck/)

# UML / Database Design Tools

[yUML](https://yuml.me/diagram/scruffy/class/draw)

[LucidChart](https://www.lucidchart.com/)

Documenting your relational database using SchemaSpy

This is kind of cool because there is a docker image that allows you to run all the tools without having to install any of the tools.
https://tech.asimio.net/2020/11/27/Documenting-your-relational-database-using-SchemaSpy.html


# Architecture Diagrams and Tools

[draw.io](https://app.diagrams.net/)

[The 5 Types of Architecture Diagrams](https://betterprogramming.pub/solutions-architect-tips-the-5-types-of-architecture-diagrams-eb0c11996f9e)
The flow, service, persona, infrastructure, and developer diagram


# Hibernate

[Spring Transactional Pitfalls [Spring & JPA Pitfalls Series]](https://codete.com/blog/5-common-spring-transactional-pitfalls)

> The @Transactional annotation is probably the most randomly used annotation in the whole Java development world - and it’s terrifying! 

Caching is harder than expected to setup:
[Hibernate EhCache Configuration Tutorial](https://howtodoinjava.com/hibernate/hibernate-ehcache-configuration-tutorial/)

[Caching](https://docs.jboss.org/hibernate/orm/5.1/userguide/html_single/chapters/caching/Caching.html)

[When and how to use hibernate second level cache?](https://stackoverflow.com/questions/7058843/when-and-how-to-use-hibernate-second-level-cache)

[Hibernate Second Level Cache](https://www.javatpoint.com/hibernate-second-level-cache)

A database connection does not equal a hibernate session:

This stack overflow post states that there is one database connection per hibernate session, but I believe that is no longer true.  The accepted answer was written in 2013.
Number of Hibernate Sessions Per Request or Per User?
https://stackoverflow.com/questions/19180358/number-of-hibernate-sessions-per-request-or-per-user

However, after 2013 hibernate introduced a more aggressive database release mode.  AFTER_STATEMENT

[hibernate.connection.release_mode](https://www.roseindia.net/hibernate/hibernate4/hibernate_connection_release_mode.shtml)

# Scrum/Scrum Master/Agile

Backlog Grooming Bugs Me
https://www.jpattonassociates.com/backlog-grooming-bugs-me/

How ICE Score Method Helps to Choose Better Product Features
https://hygger.io/blog/ice-method-helps-choose-better-product-features/

RICE Scoring: Quick Prioritization for Product Managers
https://hygger.io/blog/4-powerful-factors-rice-scoring-model/

[On the importance of a Team Manifesto](https://blog.scottlogic.com/2021/01/26/on-the-importance-of-a-team-manifesto.html)

[Failure on demand – Scenes from an agile transformation](https://blog.codecentric.de/en/2021/07/failure-on-demand-agile-transformation/)

> The credo must be: Everything and everyone in the company must work toward enabling developers to work effectively and without disruption. Only then can developers focus on creating value for the company and advance the company’s product.

## Retro Ideas

[Uncovering Better Ways](https://benjiweber.co.uk/blog/2021/07/03/uncovering-better-ways/)

# Mentoring

The Art of Scholarly Mentoring
https://www.insidehighered.com/advice/2021/01/26/nobel-laureate-shares-10-rules-being-effective-mentor-young-research-scholars

# HTTP

HTTP headers for the responsible developer
https://www.twilio.com/blog/a-http-headers-for-the-responsible-developer

HOW HTTPS WORKS
https://howhttps.works


# Web Development

Certificates for localhost
https://letsencrypt.org/docs/certificates-for-localhost/

Do You Really Know CORS?
http://performantcode.com/web/do-you-really-know-cors

API Practices If You Hate Your Customers
https://queue.acm.org/detail.cfm?id=3375635

Scaling to 100k Users
https://alexpareto.com/scalability/systems/2020/02/03/scaling-100k.html

Web Architecture 101
https://engineering.videoblocks.com/web-architecture-101-a3224e126947

Smart PNG and JPEG compression
https://tinypng.com/

Hemingway App makes your writing bold and clear.
http://www.hemingwayapp.com/


# Mock Data

[mockaroo](https://www.mockaroo.com/)
> Need some mock data to test your app? Mockaroo lets you generate up to 1,000 rows of realistic test data in CSV, JSON, SQL, and Excel formats.

[Generate test data. Quickly.](https://generatedata.com/)

# Web Api Design



# Web Design

Adobe Color
https://color.adobe.com/create/color-wheel

Color Brewer 2.0
http://colorbrewer2.org/#type=sequential&scheme=OrRd&n=9

Things I Wish I’d Known About CSS
https://cssfordesigners.com/articles/things-i-wish-id-known-about-css

Learn CSS
https://web.dev/learn/css/

HTML 5 Cheat Sheet
https://websitesetup.org/html5-cheat-sheet/

# API Design

Java API Design Checklist
https://theamiableapi.com/2012/01/16/java-api-design-checklist/

API Design With Java 8
https://dzone.com/articles/the-java-8-api-design-principles

This article references the Java API Design Checklist above.

# Java Flight Recorder

https://github.com/wkorando/taking-off-with-jfr

# Deployment

12 Factor Apps with Spring Boot
https://reflectoring.io/spring-boot-12-factor-app/

Java Microservices: A Practical Guide
https://www.marcobehler.com/guides/java-microservices-a-practical-guide


# Database

About Pool Sizing
https://github.com/brettwooldridge/HikariCP/wiki/About-Pool-Sizing

Hacker News Discussion
https://news.ycombinator.com/item?id=18425923

How to Manage Connections Efficiently in Postgres, or Any Database
https://brandur.org/postgres-connections

MY ADVICE TO DEVELOPERS ABOUT WORKING WITH DATABASES: MAKE IT SECURE
https://techblog.bozho.net/my-advice-to-developers-about-working-with-databases-make-it-secure/

Things I Wished More Developers Knew About Databases
https://rakyll.medium.com/things-i-wished-more-developers-knew-about-databases-2d0178464f78

# Git

[Github Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[Basic writing and formatting syntax](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)

[Git rebasing: What is it and how can you use it?](https://blog.scottlogic.com/2020/01/09/git-rebasing.html)

[Commit Often, Perfect Later, Publish Once: Git Best Practices](https://sethrobertson.github.io/GitBestPractices/)

[Tips for a disciplined git workflow](https://drewdevault.com/2019/02/25/Using-git-with-discipline.html)

[More productive Git](https://increment.com/open-source/more-productive-git/)

[Oh shit, git!](https://ohshitgit.com/)

[Cheat sheet: How to use Git](https://codevog.com/de/blog/2016-03-24-cheat-sheet-how-to-use-it)

[Git Cheat Sheet](https://gist.github.com/jedmao/5053440)

[Git Cheat Sheet: Commands and Best Practices](https://jrebel.com/rebellabs/git-commands-and-best-practices-cheat-sheet/)

https://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf

[Write good git commit message](https://juffalow.com/other/write-good-git-commit-message), [Hacker News Discussion](https://news.ycombinator.com/item?id=18663032)

XKCD: [1296](https://xkcd.com/1296/), [1597](https://xkcd.com/1597/)


# Docker

Broken by default: why you should avoid most Dockerfile examples
https://pythonspeed.com/articles/dockerizing-python-is-hard/

Intro Guide to Dockerfile Best Practices
https://blog.docker.com/2019/07/intro-guide-to-dockerfile-best-practices/

Hacker News Discussion
https://news.ycombinator.com/item?id=20381388


# User Interface/User Experience

10 Usability Heuristics for User Interface Design
https://www.nngroup.com/articles/ten-usability-heuristics/

Fundamental design principles for non-designers
https://www.freecodecamp.org/news/fundamental-design-principles-for-non-designers-ad34c30caa7/

Remove password masking
http://passwordmasking.com/

Rules for Autocomplete
http://jeremymikkola.com/posts/2019_03_19_rules_for_autocomplete.html

Public Sans
https://public-sans.digital.gov/

Public Sans - Github
https://github.com/uswds/public-sans/blob/master/README.md#design-principles


# Javascript Charts

[CHART.XKCD](https://timqian.com/chart.xkcd/)

[roughViz - Reusable JavaScript library for creating sketchy/hand-drawn styled charts in the browser](https://github.com/jwilber/roughViz)


# Website Accessability

[The easiest way to keep your web apps accessible: Just use text](https://blog.logrocket.com/the-easiest-way-to-keep-your-web-apps-accessible-c2b57506cc2a)


# Distributed Systems

[Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/), [Hacker News Discussion](https://news.ycombinator.com/item?id=12245909)

# Cheat Sheets

Cheat Sheets to link to:
- maven (rebellabs)
- sql (rebellabs)
- intellij idea mac os x keymap ([JRebel (pdf)](https://www.jrebel.com/system/files/cheat-sheet-rebel-intellij-idea-web.pdf), [JetBrains](https://www.jetbrains.com/help/idea/reference-keymap-mac-default.html), [ShortcutFoo](https://www.shortcutfoo.com/app/dojos/intellij-idea-mac/cheatsheet))
- git (nina jaeschke ninagrafik.com, jrebel, atlassian)
- Java Streams ([JRebel (pdf)](https://www.jrebel.com/system/files/java-8-streams-cheat-sheet.pdf))
- Java 8 Best Practices ([JRebel (pdf)](https://www.jrebel.com/system/files/java-8-best-practices-cheat-sheet.pdf))
- [HTML5](https://websitesetup.org/html5-cheat-sheet/)


# Being Interviewed

[Interview Cake](https://www.interviewcake.com/)

[The two questions I ask every interviewer](http://blog.wesleyac.com/posts/two-interview-questions)
[Harker News Discussion](https://news.ycombinator.com/item?id=15599111)

[Ask a Manager](https://www.askamanager.org/topics)

[Why I Don't Prepare For Job Interviews](https://dev.to/pbeekums/why-i-dont-prepare-for-job-interviews)
[Harker News Discussion](https://news.ycombinator.com/item?id=14219500)

[Ask HN: What are good software architecture interview questions?](https://news.ycombinator.com/item?id=13472279)

[Hacker Rank](https://www.hackerrank.com/)

[HackerRank-Solutions](https://github.com/glenmccallumcan/HackerRank-Solutions)

[Job negotiation for programmers: the basic principles](https://codewithoutrules.com/2019/11/27/job-negotiation-for-programmers/)

[Pramp](https://www.pramp.com/#/) - An interview prep website.

# Interviewing Others

[The Science Behind Making Software Engineering Interviews Truly Predictive of Job Performance](https://www.qualified.io/blog/posts/truly-predictive-software-engineering-interviews)

[Refactoring Backend Engineering Hiring at Slack](https://slack.engineering/refactoring-backend-engineering-hiring-at-slack-b53b1e0e7a3c)

[Hacker News Discussion](https://news.ycombinator.com/item?id=19564786)

[How NOT to hire a software engineer](https://tonsky.me/blog/hiring/)

[How to Hire](https://hbr.org/2018/01/how-to-hire)

[What we've learned about hiring engineering managers](https://circleci.com/blog/what-we-ve-learned-about-hiring-engineering-managers/)

[How we interview engineers at CircleCI](https://circleci.com/blog/how-we-interview-engineers-at-circleci/)

[Why we re-designed our engineering career paths at CircleCI](https://circleci.com/blog/why-we-re-designed-our-engineering-career-paths-at-circleci/)

Send interview questions about 1 hour to 1/2 hour before the interview.

Look for smaller 

# Work Life Balance

[It is perfectly OK to only code at work, you can have a life too](https://zeroequalsfalse.com/posts/it-is-ok-to-only-code-at-work/)

# Quick Company Links

[My Brand New Logo](https://mybrandnewlogo.com/)

[HOW TO REGISTER A COMPANY IN THE USA: COMPREHENSIVE GUIDE FOR FOUNDERS](http://aynuriev.com/how-to-register-company-usa/)


# Links to Other Folk's Curated Links

[My Personal Linklog](http://msaavedra.com/posts/my-personal-linklog/)

[The Motherboard Guide to Not Getting Hacked](https://www.vice.com/en_us/article/d3devm/motherboard-guide-to-not-getting-hacked-online-safety-guide)
