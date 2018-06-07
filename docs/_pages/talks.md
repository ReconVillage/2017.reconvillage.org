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

We have received a huge number of awesome talks this year and it's been super difficult for our review panel to select the best ones. If you don't see your talk here, it can still be selected in final list of talks.  

While the CFP is still [OPEN](https://docs.google.com/forms/d/e/1FAIpQLSeSwGh2fs-53nlHE7A6Sv1eeYRLXyFd7vW4ZS6LIiOj5t4-OA/viewform?usp=sf_link), our first round of speaker/talk list is out. 

# Comprehensive Talks

## Bug Bounty Hunting on Steroids - [Anshuman Bhartiya](https://twitter.com/anshuman_bh) and [Glenn Grant](https://twitter.com/_devalias)

Bug bounty programs are a hot topic these days. More and more companies are realizing the benefits of running a program, and researchers are jumping at the opportunity to grab some swag and make some extra cash from the bugs they find. Reporting security issues has never been as easy, open, and risk-free as it is right now. Everybody wins!

Though that doesn't mean we should stop there. As researchers, we spend a lot of time doing the same menial tasks for each program: monitoring for new targets, checking for common issues, remembering just which flags you needed to pass to that tool (or even which tool is best for that job). We build new tools, hack together shell scripts, and generally make small incremental changes to our process. But surely there‚Äôs a better approach?

Are you sick of repeating the same tedious tasks over and over? Wouldn't it be nice to have your own bug hunting machine? One that -
* Is always watching
* Reacts as soon as a new target becomes available
* Takes care of those tedious repetitive steps for you
* Makes life easy when you want to integrate a new tool/workflow
* Doesn't cost the world to run, and trivially scales
* Leverages lessons and technologies battle tested in the dev world to improve your offensive capacity, capability and productivity
* Monitors your own infrastructure and reacts before hackers can (while saving you the cost of those Bug Bounty payouts in the meantime)
 
We call this approach Bug Bounty Hunting on Steroids. We will discuss our research and approach to building such a machine, sharing some of the lessons we learned along the way.	x

## Emergent Recon - fresh methodology and tools for hackers in 2018 - [Jason Haddix](https://twitter.com/jhaddix)

Recon is an art AND an science. The landscape for methods of finding hosts to attack is constantly changing. Whether you call it "Asses Discovery" or something else, it remains a core part of bounty hunter and red teaming life. Join Jason as he expands on his ever changing recon methodology. This talk will focus on what tools to incorporate (and which tools not to). It will outline new methods coined in 2018,  plus frameworks to automate and document your workflow. Topics include: brand/TLD discovery, host enumeration,  application threat modeling, and more!

## Mapping wifi networks and triggering on interesting traffic patterns - [Caleb Madrigal](https://twitter.com/caleb_madrigal)

Sure, WiFi hacking has been around for a while, and everyone knows about tools like airmon-ng, kismet, et al. But what if you just want to view a list of all networks in your area AND see all devices connected to each network? Or maybe you want to know who's hogging all the bandwidth (and maybe deauth them if they use too much)? Or, what if you want to know when a certain someone's cell phone is nearby. Or perhaps you'd like to know if your Airbnb host's IP Camera is uploading video to the cloud?

For all these use-cases, I've developed a new tool called "trackerjacker". In this talk, we'll use this tool to explore some of the surprisingly-informative data floating around in the radio space, and you'll come away with a new skill point or two in your radio hacking skill tree, as well as a new magical weapon... I mean tool.

## Stalker In A Haystack - [MasterChen](http://twitter.com/chenb0x)

In 2015, I did a Skytalk called "Automate Your Stalking". In that talk, I used Twitter to follow my Target's followers in an effort to monitor the target without following them directly and arousing suspicion. I'm the end, I felt like I released a method that may be dangerous in the hands of the wrong people. Now, "Stalker In A Haystack" is the antidote to my first talk. I will be putting the power back into the hands of the people who need it. 

In this talk, I will demonstrate how you can determine if you are being monitored via Twitter, and by who. Isn't it suspicious when that one handle is following everyone but you? What does that mean? Stalkers can hide in your sea of followers, and the aim of this talk is to uncover those who lie in the shadows.

## Using Deep Learning to uncover darkweb malicious actors and their close circle - [Rod Soto](https://twitter.com/rodsoto) and [@josephzadeh](https://twitter.com/josephzadeh)

This presentation shows how data driven techniques can be used to provide vision and establish  relationships between users and participants of DarkWeb forums. These relationships can provide clues to uncover and reveal tracks of malicious actors. Things such as chat room transcripts and forum data are used can be used to build graphical relationships. 

This provides a context where it is possible to use machine learning algorithms to unmask relationships and profile users of these dark forums. Some of the methods used include Machine Learning Algorithms such as Googles PageRank. 

Once these users are profiled it is possible to predict behaviors, gaining further understanding of actors using these forums to obfuscate and evade attribution. 

# Lightening Talks

## Mapping Social Media with Facial Recognition - [Jacob Wilkin](https://twitter.com/Jacob_Wilkin)

Performing intelligence gathering on targets is a time consuming process, it typically starts by attempting to find a persons online presence on a variety of social media sites. What if it could be automated and done on a mass scale with hundreds or thousands of targets? 

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

 
<br>
<h1><center>CFP Timeline</center></h1>

| What?                                        | When?	                                           |
| ------------------------------------------- | ----------------------------------------------------- |
| CFP DEFCON 26 Las Vegas OPEN | 26th April 2018 |
| CFP First Round Notifications | 5th June 2018| 
| CFP DEFCON 26 Las Vegas CLOSE| 15th June 2018 |
| Notification to Speakers | 25th June 2018|
| Recon Village DEFCON 26 Schedule Announcement | 1st July 2018|
| Recon Village DEFCON 26 | 10th - 12th August 2018 |