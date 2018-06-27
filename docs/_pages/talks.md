---
permalink: /talks-2018/
title: ""
excerpt: "Recon Village Talks DEFCON 26"
header:
  image: assets/images/unsplash-image-11.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
last_modified_at: 2018-06-05T14:28:13-05:00
---

{% include toc title="RV DEFCON 26 Talks" icon="file-text" %}

We have received a huge number of awesome talks this year and it was super difficult for our review panel to select the ones which fits best into Recon Village


# Comprehensive Talks

## Adventures in the dark web of government data - [Marc DaCosta](https://twitter.com/marc_dacosta)

Government bureaucracy is your friend. The US federal government alone produces tens of thousands of different forms that collect information on everything from the owner and location of every oil well in the country, to the VIN number of every car that's imported, the location and height of every cell phone tower, and much more. While most of this data is locked behind clunky 1990s-era search forms, or in exports of antiquated database formats, the enterprising researcher will find a treasure trove that exists outside the indexes of Google and LexisNexis.

I have written scrapers and parsers for 100s of these databases and will share with you what I've learned about coaxing OSINT out of some of the messiest and hard to find data out there.

The talk will specifically feature a deep dive into the data produced by the US Federal Communications Commission. The FCC has issued over 20 million licenses for transmitting on regulated parts of the electromagnetic spectrum. The data residue of this process can be used for everything from geo-locating electronic border surveillance infrastructure to discovering the location and transmission frequency of every McDonald's drive-thru radio. In the second portion of the talk, I will discuss how various protocols for data transmission can be decoded and joined with other contextual public data. For instance, every cargo ship emits an ""Automated Identification System"" signal that can be joined with shipping records to understand what the ship is carrying. 

By the end of the talk, I hope attendees will develop new intuitions and techniques for finding and working with government data, and specifically have the tools to run their own investigations using FCC data.


## Applied OSINT For Politics: Turning Open Data Into News - [Lloyd Miller](https://twitter.com/lloydamiller)
"How do you apply open source intelligence techniques to politicians, candidates, and others holding the public trust? It's easier than you think. This talk will outline the general principles for investigating public figures, how to take information and data and turn it into a news story even when the story is (often) incomplete, and then review several case studies that demonstrate the effectiveness of combining these techniques.

* Case Study #1: Selling Out Before The Financial Crisis: politicians using their positions and insider knowledge to profit and sell stocks before regulatory actions and major events like the 2008 financial crisis

* Case Study #2: Family Money Laundering Campaign Contributions: politician, who lacks the means themselves, illegally fund their campaigns with hundreds of thousands of dollars from family members

* Case Study #3: How To Save $300,000 On A Home: politician purchases a home at a steep discount from a major campaign donor

* Case Study #4: Downton Abbey On Capitol Hill: politicians use public funds to decorate their offices in ostentatious and wasteful ways

* Case Study #5: Voter Fraud Is Real: political candidate actually commits voter fraud"


## Bug Bounty Hunting on Steroids - [Anshuman Bhartiya](https://twitter.com/anshuman_bh) and [Glenn 'devalias' Grant](https://twitter.com/_devalias)
Bug bounty programs are a hot topic these days. More and more companies are realizing the benefits of running a program, and researchers are jumping at the opportunity to grab some swag and make some extra cash from the bugs they find. Reporting security issues has never been as easy, open, and risk-free as it is right now. Everybody wins!

Though that doesn't mean we should stop there. As researchers, we spend a lot of time doing the same menial tasks for each program: monitoring for new targets, checking for common issues, remembering just which flags you needed to pass to that tool (or even which tool is best for that job). We build new tools, hack together shell scripts, and generally make small incremental changes to our process. But surely there's a better approach?

Are you sick of repeating the same tedious tasks over and over? Wouldn't it be nice to have your own bug hunting machine? One that -
* Is always watching
* Reacts as soon as a new target becomes available
* Takes care of those tedious repetitive steps for you
* Makes life easy when you want to integrate a new tool/workflow
* Doesn't cost the world to run, and trivially scales
* Leverages lessons and technologies battle tested in the dev world to improve your offensive capacity, capability and productivity
* Monitors your own infrastructure and reacts before hackers can (while saving you the cost of those Bug Bounty payouts in the meantime)
 
We call this approach Bug Bounty Hunting on Steroids. We will discuss our research and approach to building such a machine, sharing some of the lessons we learned along the way.	x


## Core OSINT: Keeping Track of and Reporting All the Things - [Micah Hoffman](https://twitter.com/WebBreacher)
"Your client gives you their requirement, ""find the social media accounts of the target person and any friends they may have"". Simple enough. You execute your Standard Operating Procedures (you DO have a SOP, right?) and begin running tools, using your sock puppets, scraping web sites, and finding a ton of data. You've got CSVs, text output, images, URLs....OH MY! How do you keep track of all this data and, more importantly, how do you ensure that you can report on it and have covered all the pivot points for the OSINT investigation?

As OSINTers, pentesters, defenders, PIs, and others, we can easily get swamped in data. Join me as we look at some bad, some good, and some amazing methods of keeping your investigation on track."


## Emergent Recon - fresh methodology and tools for hackers in 2018 - [Jason Haddix](https://twitter.com/jhaddix)
Recon is an art AND an science. The landscape for methods of finding hosts to attack is constantly changing. Whether you call it "Asset Discovery" or something else, it remains a core part of bounty hunter and red teaming life. Join Jason as he expands on his ever changing recon methodology. 

This talk will focus on what tools to incorporate (and which tools not to). It will outline new methods coined in 2018,  plus frameworks to automate and document your workflow. Topics include: brand/TLD discovery, host enumeration,  application threat modeling, and more!


## Hacking the international RFQ Process #killthebuzzwords - [Dino Covotsos](https://twitter.com/telspacesystems)
Thanks to the ‚Äúboom‚Äù in the information security industry combined with the latest buzzwords, more and more large corporate companies are looking for the latest ‚Äúnext gen‚Äù anti-haxor services and technologies. In doing so they often go out publicly on tender and / or issue an RFP/RFQ in order to obtain the best possible solution to meet their requirements and budget (usually cost *wins*). 

Due to this and a lack of maturity in the field, companies issue public RFQs / RFPs that contain classified and confidential / secret information such as network diagrams, architectural designs, software versions etc.  This type of information would usually require that an attacker spend an extensive amount of time performing enumeration and / or gaining access to the internal network first and taking a significant amount of time to learn about that environment.  Targeting the procurement process of an organisation exposes a largely unexplored attack surface. 

This new research and presentation aims to demystify the above and give practical examples of large international organisations, which unfortunately fail at the RFP/RFQ process badly. This opens a ‚Äúfree and easy‚Äù attack vector for attackers to exploit without even conducting extensive enumeration and fingerprinting, or anything close to intrusive attacks.  As a result, an attacker often has access to an extensive amount confidential information about the organisation, which could be utilised to launch more targeted attacks.  Depending on the type of information gathered, such attacks, could be likened to an attacker that has insider knowledge. 

I will also be demonstrating, via real world examples, the dangers of going out blindly and looking for specific services and products in the information security industry, with real life networks being shown on stage.

A short breakdown of what will be presented is as follows:

* An explanation of what is wrong with the RFQ/RFP process worldwide including proof of these issues.
* Multiple attack avenues of real hackers taking advantage of the process / information leaked.
* Scenarios where attackers would be in an advantageous position.
* Personal examples that I've seen over the last 16 years (I've contributed towards over 4000 responses to RFQs/RFPs over the years!).
* Real life examples that we've seen and found publicly online, including private information that attackers could utilise.
* Some advice on solving this difficult issue."


## I fought the law and law lost - [Mauro Caseres](https://twitter.com/mauroeldritch)
"I fought the law and the law lost" is a series of talks that aims to collect vulnerabilities in the field of Argentine Security forces. 
This chapter focuses on both Federal and Buenos Aires City Police, which according to the Head of Government Horacio Rodr√≠guez Larreta, has the ""most modern technology in the world"".

We will analyze four particular cases (two on the lightning talk version), all of them ending in national scandals: 
* The leaking of the Police Reports database. Which led to the disclosure of private information of criminals, informants, involved police agents and even original reporters. This database contained cases related to drug trafficking and proxenetism. 
* The leaking of Proyecto X, a joined intelligence task force composed by members of different forces. 
* The leaking of the SNIC (Criminal Information National System), that led to the disclosure of intelligence information regarding criminal gangs undergoing federal investigation but not prosecuted/captured yet.
* The leaking of Buenos Aires City Police entire database, that led to the disclosure of every agents personal information, including religious and health related concerns, like STDs, clinical and psychological history, and more.

But we'll do it having in mind a special requirement: passive action. We'll use Recon & OSINT at it's best in order to reconstruct how the leaks were carried from start to end. A police chief using his daughter's name as a password? A Police CIO using his own National ID Number as recovery question? Public databases exposing too much information? Reused passwords across every site on the internet? Sure, but it's not the worst. We'll use hand crafted DIY tools and without compromising a single system, reveal a lot of bugs and vulns. This talk is heavily focused on obtaining OSINT from public sources (specially in countries with weak or ambiguous laws, like Argentina) 

This talk aims to demonstrate various flaws with a critical, technical and impartial approach to bring to the public a prevailing reality: First, argentine law allows a lot of compromising data to be used as ""public"" (thus leaving the place for OSINT based attacks to occur), and second... we are not safe against computer threats, and those who take care of us, neither are.


## Mapping wifi networks and triggering on interesting traffic patterns - [Caleb Madrigal](https://twitter.com/caleb_madrigal)
Sure, WiFi hacking has been around for a while, and everyone knows about tools like airmon-ng, kismet, et al. But what if you just want to view a list of all networks in your area AND see all devices connected to each network? Or maybe you want to know who's hogging all the bandwidth (and maybe deauth them if they use too much)? Or, what if you want to know when a certain someone's cell phone is nearby. Or perhaps you'd like to know if your Airbnb host's IP Camera is uploading video to the cloud?

For all these use-cases, I've developed a new tool called ""trackerjacker"". In this talk, we'll use this tool to explore some of the surprisingly-informative data floating around in the radio space, and you'll come away with a new skill point or two in your radio hacking skill tree, as well as a new magical weapon... I mean tool.



## Stalker In A Haystack - [MasterChen](https://twitter.com/chenb0x)
In 2015, I did a Skytalk called "Automate Your Stalking". In that talk, I used Twitter to follow my Target's followers in an effort to monitor the target without following them directly and arousing suspicion. I'm the end, I felt like I released a method that may be dangerous in the hands of the wrong people. Now, "Stalker In A Haystack" is the antidote to my first talk. 

I will be putting the power back into the hands of the people who need it. In this talk, I will demonstrate how you can determine if you are being monitored via Twitter, and by who. Isn't it suspicious when that one handle is following everyone but you? What does that mean? Stalkers can hide in your sea of followers, and the aim of this talk is to uncover those who lie in the shadows.


## Supercharge Your Web Recon With Commonspeak and Evolutionary Wordlists - [Michael Gianarakis](https://twitter.com/mgianarakis) and [Shubham Shah](https://twitter.com/infosec-au)

When conducting a web application penetration test understanding and extending the attack surface is an exercise that is critical for success. Having a large wordlist of realistic directories, files and domains is assists immensely with this process.

Commonspeak is a wordlist generation tool that leverages public datasets from Google's BigQuery platform. By performing queries on large datasets that are updated frequently, commonspeak is able to generate wordlists that are "evolutionary", in the sense that they reflect the newest trends on the internet.

This presentation will discuss the concept of evolutionary wordlists and how Commonspeak parses URLs from various BigQuery datasets including HTTPArchive, Stack Overflow and HackerNews to build current, consistently evolving and realistic wordlists of directories, files, parameter names for specific technologies, and subdomains.

We will also introduce Commonspeak 2 and discuss the additions to the tool including scheduled wordlist creation, comprehensive GitHub queries a permutation engine for subdomain discovery and asynchronous wordlist generation.


## Using Deep Learning to uncover darkweb malicious actors and their close circle  - [Rod Soto](https://twitter.com/rodsoto) and [josephzadeh](https://twitter.com/josephzadeh)
This presentation shows how data driven techniques can be used to provide vision and establish  relationships between users and participants of DarkWeb forums. These relationships can provide clues to uncover and reveal tracks of malicious actors. Things such as chat room transcripts and forum data are used can be used to build graphical relationships. 

This provides a context where it is possible to use machine learning algorithms to unmask relationships and profile users of these dark forums. Some of the methods used include Machine Learning Algorithms such as Googles PageRank. Once this users are profiled it is possible to predict behaviors, gaining further understanding of actors using these forums to obfuscate and evade attribution. 


# Live Demo


## Introducing YOGA: Your OSINT Graphical Analyzer - [Micah Hoffman](https://twitter.com/WebBreacher)
"If you have ever performed reconnaissance on a target or conducted an OSINT investigation you know that there are a huge number of places to gather OSINT data. One of the biggest challenges is in taking the next steps with that data once you have it. How do you take what you have and transform use it to get more? For instance, if you found email addresses, where do you search to find other data about those accounts? We have excellent resources such as [http://osintframework.com)[http://osintframework.com] and [https://bit.ly/technisette](https://bit.ly/technisette) that are huge lists of well-organized bookmarks which can be overwhelming. That is why I created YOGA.

Your OSINT Graphical Analyzer (YOGA) seeks to answer that most-common of data-gathering questions, "What do I do now?" It is designed to help when you have one type of data and need to know different actions you can take to get more data. Come to this session and learn how you and your team can use and extend this online tool in your work."


## Prebellico - 100% Passive Pre-Engagement and Post Compromise Network Reconnaissance Tool - [William Suthers](https://twitter.com/VICT0RIS)
When attacking modern internal networks, intelligence is everything.  Understanding the environment you are operating in can be the difference between successfully penetrating your target environment or missing targets of opportunity due to lack of understand about the target environment.

While true, obtaining information about the environment in a stealthy manner, when required, can be difficult within a mature environment. Even during overt engagements, obtaining the information you need within a limited time window can be difficult, especially during engagement delays. 

Further complicating things, often testing scope is based off of poor assumptions about the target environment, often leading unrealistic scope reductions a real-world attacker would not operate out of. 

Over the years internal testing engagements have been operating on various assumptions within switched networks, often driving engagement execution methods, but what if these assumptions were wrong? What if we could utilize the wasted time, even weeks in advance, between deployment and engagement execution, to take the time to understand the network? What if we could leverage the realities of modern networks and the things customers do to ‚Äòprepare' for an engagement (backups, security scans, etc.) through 100% passive methods, challenging your assumptions about the network?

Prebellico is pre-engagement and post compromise intelligence gathering mechanism designed to gather as much information about the target environment through 100% passive methods. Utilizing very few resources, Prebellico permits an attacker the ability to understand the target environment by providing information such as the intent of internal systems, internal network address space, hostnames, egress filtering, TCP trust relationships, as well as map open TCP/UDP ports through reverse port scanning using 100% passive techniques."



## Skiptracer - Ghetto OSINT for broke hackers - [illwill](https://twitter.com/xillwillx)
Initial attack vectors for recon usually involve utilizing pay-for-data/API (Recon-NG), or paying to utilize transforms (Maltego) to get data mining results. Using some basic python webscraping of PII paywall sites to compile passive information on a target on a ramen noodle budget. The modules will allow queries for phone/email/screen names/real names/addresses/IP/Hostname/breach credentials etc.. 

This demo will go over the basic outline of using the script, the problems and pitfalls of dealing with scrapers, and how it will help you collect relevant information about a target to help expand your attack surface. 


## WhiteRabbit: Combining Threat Intelligence Public Blockchain Data and Machine Learning to go Down the "Dirty Money Rabbit Hole" - [Olivia Thet](https://twitter.com/trustartech) and Nicolas Kseib
In this presentation, we will demonstrate how to build a machine learning model that uses a merged dataset combining cyber related contextual information with Bitcoin (BTC) transaction data. The model can be used by both private and public sectors security professionals, working in the cryptocurrency field, to deny business for certain BTC addresses or, build legal cases to return illegally stolen coins.

To build the dataset, we collected a list of BTC addresses involved in illegal activities. Using these addresses as a starting point, we navigated along the chain, and reconstructructed a cluster of connected ‚Äúdirty‚Äù addresses. We used rules such as First-In-First-Out (FIFO) to label them. These labeling techniques can be used to tag certain BTC addresses that fall within this path as ‚Äúdirty‚Äù addresses because they handled money acquired through illegal activities. We can then take this a step further and analyze the characteristic behavioral elements of these addresses. This behavioral analysis will allow us to determine the features representing this malicious behavior and use them within a machine learning model classifying new BTC addresses.

Our model-building approach is based on a three part framework: The first part is to collect a set of  BTC addresses and classify them as ‚Äúclean‚Äù or ‚Äúdirty‚Äù to use them as our ground truth. The second part is to test the classification models using this dataset and propose decision metrics to optimally pick a model. In this part, we will also discuss ideas about how to compute expensive, but important features obtained from transaction data. In the third part, we will show how to use the obtained optimal model to predict if an address is ‚Äúdirty‚Äù.  Finally, we will discuss our challenges when solving this problem and propose solutions to overcome them. 


## Winning a SANS 504 CTF without winning a SANS CTF - Wbbigdave
When a security professional who is running a SANS training course challenges you to 'Socially engineer the answer to the CTF' out of him, you have a choice: choose something to make him laugh and garner clues to aid you in owning the network and walking away with a CTF coin, or, take it as a personal challenge and a call to own your instructor. Against better judgement, the advice of his peers ('you shouldn't attack a SANS instructor') and with the threat of an ex Navy Seal above him, wbbigdave took the second path. 

Learn how good reconnaissance, modern technology which is billed as an aid to connectivity and convenience, can be used to fully draw even then most switched on and vigilant of security professionals down the rabbit hole. Including but not limited to Facebook and Google who lost significant sums of money to similar techniques. Learn how to walk away with a challenge coin without winning the CTF.

---------------------------------------------------------------------------------------------

# Lightening Talks


## 1983: I’m born. 2018: I’m taking on the bad guys - Jennifer Roderick
"I'm not a programmer. I'm not a hacker‚Ä¶in the traditional sense. But yet I was born in 1983, so surely that makes me a perfect fit for the DEF CON theme this year. Not enough? Ok, well how about the fact that I'm currently using open source tools, techniques and methodologies to combat modern slavery, wildlife trafficking, terrorism and just about every serious organized crime the world is currently battling from a desk in the middle of the London financial district. Interested in hearing from a different viewpoint and perspective, then this is your talk. While you might not walk away with a new tool for your toolbox, you will gain an understanding into how the smallest contribution can end up the most profound and how combining open source resources can take on much bigger problems that you've maybe never considered. 

During my talk, I will cover a few examples of recent Open Source investigations conducted by myself, including details regarding the methodologies and tools which were used. We actively follow the person not the digital fingerprint to begin to understand and put a face to some of the most prevalent and serious organized crimes facing the world today. 

When I was in the forces I knew what I was facing and had to deal with, as Head of Research at a FinTech company I never expected that transferring my skills would end up uncovering individuals within the financial industry who I've had to report for terrorist activity, human trafficking, wildlife trafficking, drug smuggling, violent crime, fraud (international and domestic), revenge porn, and stalking.

And while I'm not here to save the world, I think we can all do a little bit to contribute to a counter-future in which the good guys are empowered by technology and the bad guys have nowhere to hide.


## Cartoons, Sketchnotes, Bullet Journals and Other Data Visualization Tricks - [Raye Keslensky](https://twitter.com/lastres0rt)
"When it comes to presenting data, it's not WHAT you present, it's HOW you present it! Combining words with pictures has been around for ages. Picking up an understanding of sequential art and how you can use it in your day-to-day life is critical! 

This talk covers a crash course of data science and visualization. Learn what parts of the information you're supposed to keep an eye on! Make better line breaks with your text! Bring clarity to your writing! Good for software design, scrapbooking, OSINT, or keeping your shit together! "


## How WHOIS Data Uncovered $32 Billion Connected to the Mormon Church - [Ethan Dodge](https://twitter.com/egd_io)

It's always been suspected that the Mormon Church is worth billions of dollars and has a sizable amount of investments in the United States stock market. However their finances are almost entirely opaque. In May 2018, MormonLeaks released a compilation of information connecting the dots between the Mormon Church and $32 billion. 

It all started with WHOIS data and was further verified with almost entirely publicly available and open sources. Come hear the entire story in lightning style fashion.


## Mapping Social Media with Facial Recognition - [Jacob Wilkin](https://twitter.com/username)
"Performing intelligence gathering on targets is a time consuming process, it typically starts by attempting to find a persons online presence on a variety of social media sites. What if it could be automated and done on a mass scale with hundreds or thousands of targets? 

Social Mapper is a Open Source Intelligence Tool that uses facial recognition to correlate social media profiles across different sites on a large scale. It takes an automated approach to searching popular social media sites for targets names and pictures to accurately detect and group a person's presence, outputting the results into report that a human operator can quickly review. 

Social Mapper has a variety of uses in the security industry, for example the automated gathering of large amounts of social media profiles for use on targeted phishing campaigns. Facial recognition aids this process by removing false positives in the search results, so that reviewing this data is quicker for a human operator. 

Social Mapper supports the following social media platforms:
        - LinkedIn
        - Facebook
        - Twitter
        - GooglePlus
        - Instagram
        - VKontakte
        - Weibo
        - Douban

Social Mapper takes a variety of input types such as:
        - An organisations name, searching via LinkedIn
        - A folder full of named images
        - A CSV file with names and url's to images online"


## OpenPiMap - Hacking the hackers with OSINT, Raspberry Pis, and Data Analysis - [Mark Klink](https://twitter.com/evilbotnet)
OpenPiMap is the ultimate home/prosumer network utility in order to detect, analyze, and respond to malicious network traffic on a small home or office network.  Get an interactive and dynamic interface to detect and respond to botnets, hackers, and script kiddies on a platform that is powered by just 5v and costs less than $10. Everyday any point of presence on the internet can be faced with thousands of scans, exploit attempts, or malicious probes with almost no signature or notification to the end user. OpenPiMap offers the ability to detect and respond to malicious network traffic that would normally be ignored by traditional anti-virus or consumer firewalls. 

OpenPiMap is an open source Netflow protocol analyzer written entirely in Python3, Flask, Javascript, and SQLite that combines open source intelligence with home/SOHO networking and intrusion detection.  Running on any version of a Raspberry Pi, Linux OS, or Windows, OpenPiMap consists of two parts: (1) Netflow collection service and (2) Database processing service.  The NetFlow service does exactly what it sounds like, it listens on a specified port for Netflow v5 data and logs the data into a local SQL database.  The second part is where the magic happens.  

All of the traffic, both in and out of the network, is compared to dozens of the top IP blacklists for malicious patterns.  Once identified, the malicious suspects are mapped, interrogated via Shodan's Python API for vulnerable services and ownership information, and then staged for exploitation if a readily available exploit exists.  This processing is where the bridge between traditional netflow traffic analyzers and OpenPiMap split.  There are plenty of free tools on the market to monitor incoming and outgoing connections, bandwidth utilization, and common port usage.  However, none of the existing products leverage open source intelligence to the extent of OpenPiMap by providing you with the open ports and services, ownership information, ISP, geographic location, and publically available exploits for the incoming or outgoing IP addresses.  


## Targeted User Analytics and Human Honeypotss - Mbis0n Shador (Not a Real name)
Many significant breaches have resulted from adversaries knowing who to target, how to target them and where to target them.   Most corporations are not effectively using the largest collection of targeting data that is available on the public internet and fail to build and refine data driven threat models using the information that our adversaries are using against us.  Targeted User Analytics and Human Honeypots is a research project I am working on to identify and model targeting methods with the hope of tipping the scales in our favor to defend our networks, users and critical systems.  

LinkedIn is the largest collection of Business Social Networking data available to ‚Äúunathenticated‚Äù persons on the public internet.  With the right techniques this data can be mined to identify and enrich targets.  The purpose of my talk is to present targeting techniques through a use case and to demonstrate the value of other enrichment methods involving data sets that are widely available or collected from corporate security tools.  The end result is analytics that predict who will be targeted and why they are more likely to be compromised if they are targeted. This will allow for proactive action to be taken to defend users and our assets.  

* Background
* Users are still the weakest link
* Seed files
* Sample seed File terms & Query
* Search Engine Query
* Harvest
* External Enrichment
* Internal Enrichment
* Human Honeypots and Operationalizing Defenses
* The Things that we can expect an adversary to do
* How can we disrupt this targeting approach
* Industry trends


# Workshop

# Building visualisation platforms for OSINT data using open source solutions - [Bharath Kumar](https://twitter.com/yamakira_) and [Madhu Akula](https://twitter.com/madhuakula)

"Reconnaissance is about gathering information. The information gathered is only as good as the insights and actionable decisions that we can gain from it. A lot of research is focused on finding OSINT data but little is done towards converting the data into insights and actionable decisions. Visualisation is an easy and efficient way to gain insights from any the data gleaned.

In this workshop, we will look at how we can gather OSINT data and visualise it using free and open source solutions. Visualising data is not enough, we'll also look at how we can use the metrics to answer business questions and lead to actionable decisions.

We'll tackle the problem by breaking it into following steps:

1. Gathering OSINT data
2. Storing the OSINT data
3. Processing & visualising the data
4. Gaining insights and making actionable decisions

Some specific use-cases we'll look at during the workshop includes:

- Monitoring an organisation's SSL/TLS certificates, domains and subdomains in near-real time
-  Creating dashboards using public datasets(scans.io) to gain insights into an organisation's external posture
- Building monitoring and alerting solutions using OSINT data that will help us take business decisions 

Participants will get

- Step by Step Gitbook covering the entire training (html, pdf, epub, mobi)
- Custom scripts, playbooks and tools used as part of the workshop
- Scenarios that can be readily implemented for your use cases
- References to the data used in the workshop"

