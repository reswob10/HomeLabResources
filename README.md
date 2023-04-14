# HomeLabResources
List of resources for buiding a home lab

Shout out to Omar Santos (@santosomar) who has 1000s of resources here
- https://github.com/The-Art-of-Hacking/h4cker

Another great collection of tools and such
- https://github.com/fabacab/awesome-cybersecurity-blueteam


## Blogs and Videos that walk through setting up labs
Pay what you want book
Building Virtual Machine SECOND EDITION! by Tony Robinson 
Learn everything there is to know about building and maintaining your own home or workplace virtual lab environment on the most popular hypervisors today!
https://leanpub.com/avatar2

Great run through of building a lab influenced by Tony above.  Lots of links and suggestions and lessons learned.
https://www.netsecfocus.com/home/lab/2020/09/21/Tjnulls_guide_to_building_a_Home_Lab.html

[How to Build a Home Lab](https://www.youtube.com/watch?v=_Ih_wjHafrM)
Black Hills Information Security webcast

[Blog from Black Hills instructions and information for building a lab environment](https://www.infosec.com/how-to-deploy-windows-optics-commands-downloads-instructions-and-screenshots/)

[How to Build a Cloud Hacking Lab](https://youtu.be/4s_3oNwqImo) by [@dafthack](https://twitter.com/dafthack)


SANS webcast: [Building an Enterprise Grade Home Lab](https://youtu.be/jnotvkoUF9U)

SANS webcast: [Extending Your Home Lab to include Cloud](https://youtu.be/j69DRB4WGeY)

SANS webcast: [Building Your Own Super Duper Home Lab](https://youtu.be/uzqwoufhwyk)

SANS webcast: [Building an Azure Pentest Lab for Red Teams](https://www.sans.org/webcasts/sans-workshop-building-azure-pentest-lab-red-teams/)

HAK5 video: [Building a Home Lab Virtual Server Quick and Dirty - Hak5 1819](https://youtu.be/9SpQ1fRQAto)

Videos by Tyrone E. Wilson

[Building an Effective Cybersecurity Learning Environment](https://www.youtube.com/watch?v=ZYAgyZ7RZm8)

[Hands-On Learning: How and Why You Should Build a Home Lab](https://www.youtube.com/watch?v=CL2Ng191KQE)

Great instructions for building ELK and Wazuh home lab:  
https://github.com/watsoninfosec/ELK-SIEM

Justin Henderson, the author of SANS SEC555, SEC530 and other courses is doing a series on [building a home lab](https://youtube.com/playlist?list=PLIQlcXRut9IPF8cJSSf0-BsoFy_1SOGYQ)

A guide on building a DIY SIEM at home by James Smith @DFIRmadness
https://dfirmadness.com/building-a-siem-at-home/

Here is the beginning of a [series of blogs](https://facyber.me/posts/blue-team-lab-guide-part-1/) for building a Blue Team home lab

Another set of blogs for building a home lab.  This one is from Red Siege and will be more offensive focused:
- Part 1:  https://redsiege.com/blog/2022/06/simpledomainp1/
- Part 2:  https://redsiege.com/blog/2022/06/simpledomainp2/
- Part 3:  https://redsiege.com/blog/2022/06/simpledomainp3/
- Part 4:  https://redsiege.com/blog/2022/06/creating-a-simple-windows-domain-for-offensive-testing-part-4/

From [@secopsgeek](https://twitter.com/Secopsgeek), how to [ElasticXDR 8.2.0](https://youtu.be/NLdPE4erV5c) Gitbook Build Overview


## Automated lab creation tools

GOAD is a pentest active directory LAB project. The purpose of this lab is to give pentesters a vulnerable Active directory environment ready to use to practice usual attack techniques.
- [Main page](https://github.com/Orange-Cyberdefense/GOAD)
- [Tools to help deploy GOAD](https://github.com/lkarlslund/deploy-goad)
- [Walk Through](https://mayfly277.github.io/)

Alternative to GOAD by @MJHallenbeck
- https://github.com/Marshall-Hallenbeck/red_team_attack_lab

[AutomatedLab](https://github.com/AutomatedLab/AutomatedLab)
is a provisioning solution and framework that lets you deploy complex labs on HyperV and Azure with simple PowerShell scripts. It supports all Windows operating systems from 2008 R2 to 2019, some Linux distributions and various products like AD, Exchange, PKI, IIS, etc. 

[Splunk Attack range](https://github.com/splunk/attack_range)

[Purple Cloud](https://github.com/iknowjason/PurpleCloud) - An Infrastructure as Code (IaC) deployment of a small Active Directory pentest lab in the cloud. The deployment simulates a semi-realistic corporate enterprise Active Directory with a DC and endpoints. Purple team goals include blue team detection capabilities and R&D for detection engineering new approaches. 

Cyb3rWard0g has [Microsoft-Sentinel2Go](https://github.com/OTRF/Microsoft-Sentinel2Go) which contains scripts in github for multiple configurations to build an entire lab in Azure

[MS Defender Evaluation lab](https://techcommunity.microsoft.com/t5/microsoft-defender-for-endpoint/evaluation-lab-expanded-os-support-amp-atomic-red-team/ba-p/2993927) which includes Red Canary's atomic red team.

Microsoft Simuland complete lab environment with lessons
- https://simulandlabs.com/README.html

Automated build of Azure attack and detect lab by Roxana Kovaci (@RoxanaKovaci)
- https://github.com/mandiant/Azure_Workshop

[Websploit](https://websploit.org/) by @santosomar

## How to's and Building Home Lab references

The [UK National Cyber Security Center](https://github.com/ukncsc/lme) has a great project for small/home offices to help them get started with logging.  This can be used for home labs as well. Not a full SIEM solution, but a start.

Offensive Security has a [great blog](https://www.offensive-security.com/offsec/tjnulls-guide-to-building-a-home-lab/)  with lots of details and links with a video [here](https://youtu.be/Ed1ujM3xWNg)

Monitoring your Proxmox environment with Security Onion by @null@puddle.town (on Mastodon)
- https://blog.puddle.town/proxmox-span/

Building ELK SIEM in in two videos, [part 1](https://youtu.be/HI072Rkthoc) and [part 2](https://youtu.be/mIXf2k9BQ3k)

Building ELK SIEM in [blog format](https://www.hackingarticles.in/threat-hunting-log-monitoring-lab-setup-with-elk/)

Cyberrange options to deploy in Azure: https://levelup.gitconnected.com/building-azure-cyber-ranges-for-learning-and-fun-9df1debb2eae?gi=e662f36c25fb

Series of videos for [building a home lab](https://youtube.com/playlist?list=PLDqMNdDvMsRkmtiKcZwbhOz7MeLQE0r3G) by @DayCyberwox:

[Watch this talk](https://youtu.be/EtlI04dJWX4) with SANS Certified Instructor and course author Justin Henderson, as he shares what the steps are in building out a detection oriented blue team lab.

[AWS Pen-Testing Laboratory](https://www.kitploit.com/2021/06/aws-pen-testing-laboratory-pentesting.html) - Pentesting Lab With A Kali Linux Instance Accessible Via Ssh And Wireguard VPN And With Vulnerable Instances In A Private Subnet 

Here is a [video](https://www.youtube.com/watch?v=X3TyFji-jEw) from Black Hat Trainings in 2020

Video https://youtu.be/yDWug2zhjyA

From [@HBRH_314](https://twitter.com/HBRH_314), a [video of Malware Analysis](https://youtu.be/whApbC5OvOs) Fundamentals to create an analysis environment for safe inspection of malware utilizing Remnux and FLARE VM.

Video from [@watsoninfosec](https://twitter.com/watsoninfosec) on his [home lab build](https://youtu.be/-1kwszraub0)

A (very short) introduction to [kne](https://blog.itsalwaysthe.network/posts/kubernetes-based-network-emulation/) from [@supertylerc](https://twitter.com/supertylerc), a project from Google that lets you run virtual network topologies in Kubernetes. 

This repo from Black Hills contains guidance on setting up [event logging](https://github.com/blackhillsinfosec/EventLogging).

Building a SOC lab at home
- https://app.letsdefend.io/training/lessons/building-a-soc-lab-at-home

Buidling an infosec home lab from scratch
- https://youtube.com/playlist?list=PLyJqGMYm0vnP9sgEGRxmhUKFQVVz68Cbh
This guy has a TON of videos that can help with your home lab
- https://www.youtube.com/@ITSecurityLabs/videos

 Blog series for building a home lab. First post here
 - https://facyber.me/posts/blue-team-lab-guide-part-1/

## Tools and configurations to build your home lab

Creating a vulnerable Active Directory to test attack tools and detections
https://github.com/WazeHell/vulnerable-AD
Here is the video explaining it's use @steelcon 2022 by @myexploit2600 and @ZephrFish (mature language)
https://youtu.be/8VvLJfAFGcA

Filtering DNS and HTTPS Traffic on pfSense
https://docs.diladele.com/tutorials/filtering_https_traffic_squid_pfsense/index.html

BadBlood - BadBlood by @davidprowe, Secframe.com, fills a Microsoft Active Directory Domain with a structure and thousands of objects:  
https://github.com/davidprowe/BadBlood

Powershell script to create AD Domain Controller and Workstation     
https://browninfosecguy.com/Active-Directory-Lab-Setup-Tool

From Wazehell, Create a [vulnerable active directory](https://github.com/WazeHell/vulnerable-AD) that's allowing you to test most of active directory attacks in local lab

From [@ajpc500](https://twitter.com/ajpc500), a quick and dirty [PowerShell script](https://gist.github.com/ajpc500/3a86ba1741d4868b69be5ce3a142d527) to install Sysmon (SwiftOnSecurity config), SilkService and Winlogbeat, and forward the logs on to HELK. Might be useful for those looking to quickly configure endpoint logs in a lab environment

[Laurel](https://github.com/threathunters-io/laurel) turns Linux auditd logs into JSON format for easier ingestion into SIEM


## Attacker Simulation / Emulation

Atomic Red Team

- [Homepage](https://redcanary.com/atomic-red-team/)
- [Explore Atomic Red Team](https://atomicredteam.io/)
- From Swimlane, [Automating Red Canary's atomic-red team](https://www.atomic-operator.com/)

Stratus Red Team is "Atomic Red Team™" for the cloud, allowing to emulate offensive attack techniques in a granular and self-contained manner. Uses AWS and Sumo Logic
- [Main Page](https://github.com/DataDog/stratus-red-team)
- [Extra Documentation](https://github.com/sbasu7241/AWS-Threat-Simulation-and-Detection)

Florian Roth's [@cyb3rops](https://twitter.com/cyb3rops) company released a [ransomware emulator](https://github.com/NextronSystems/ransomware-simulator)

Black Hills has [tools](https://www.activecountermeasures.com/threat-simulation-overview-and-setup/) to generate suspicious activity

Swimlane released [Atomic-Operator](https://www.atomic-operator.com/0.8.5/)

## Free/demo software:

[Cribl](https://cribl.io/download/) is an awesome data router/parser/mover/enhancer   

Rapid7 [InsightIDR](https://www.rapid7.com/try/insightidr/) Free Trial (SIEM)

Other resources for free/cheap software referenced in the SANS webcasts:   https://github.com/aboutsecurity/blueteam_homelabs

Direct link to download free [Microsoft Hypber-V](https://www.microsoft.com/en-us/evalcenter/evaluate-hyper-v-server-2019) server   

Splunk Free 500MB/day, 50 GB/day during trial. Or apply for a developer license. Or use a limited Splunk Cloud free license

ELK  Open source is free.

Sumo Logic  Free account for 1 GB/day

Panther is a modern SIEM built for security operations at scale. Code is [here](https://github.com/panther-labs/panther-analysis)

[Tidal](https://www.tidalcyber.com/blog/announcing-general-availability-of-the-tidal-community-edition) is a threat intel platform

## Generating data for you lab

Cyb3rWard0g and Cyb3rPandaH have a great site with [malicious data sets](https://securitydatasets.com/introduction.html)

Sample MS Windows [logs in evtx format](https://github.com/NextronSystems/evtx-baseline) from Nextron Systems 
    
A github repository by @ubeeri to [generate fake user activity](https://github.com/ubeeri/Invoke-UserSimulator)

A quick and dirty HTTP/S "organic" [traffic generator](https://github.com/philhagen/web-traffic-generator)

Swimlane has open sourced a [tool](https://github.com/swimlane/soc-faker) to generate a lot of different types of data

[ntTraceControl](https://github.com/airbus-cert/ntTraceControl) is a set of Powershell commands to forge/generate Windows logs

Here are some other ways to generate data to be collected by your SIEM

https://pypi.org/project/log-generator/

https://logs.to/

https://nxlog.co/documentation/nxlog-user-guide/generating-test-data.html

https://github.com/tdunning/log-synth

Create network traffic to stress test network devices:  https://www.candelatech.com/downloads.php

Scripts to configure windows logging at different levels
- https://github.com/blackhillsinfosec/EventLogging

Here are some good MS logs to baseline your environment
- https://github.com/NextronSystems/evtx-baseline


## Other resources

Installing Let's Encrypt on your PFSense firewall
- https://gainanov.pro/eng-blog/linux/installing-lets-encrypt-pfsense/

Podcast/Videos on various topics for building stuff for your lab:
- [Homepage](https://thehomelab.show/)
- [Videos](https://youtube.com/playlist?list=PLjGQNuuUzvmtAzqgH7PVvnF_v0X9ZKMeA)

Justin Henderson from SANS SEC555 has a couple [free labs](https://t.co/pLipGouXDj)

User: student Password: sec555

And of course there is at least one [homelab reddit](https://www.reddit.com/r/homelab/)

Here is a whole thread on labs.  Including networking, not just security
- [Original](https://twitter.com/JBizzle703/status/1433953668148219906?s=20)
- [Threadripped](https://threadreaderapp.com/thread/1433953668148219906.html)

Some great resources from Jeff McJunkin
[kickasslab](https://bit.ly/kickasslab) and [video](https://www.youtube.com/watch?v=KogdkuEbfwc)

A Guide to log formats from [Greylog](https://www.graylog.org/post/log-formats-a-complete-guide)

Attacking AD [cheat sheet](https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet)

Blog series by [Josh Wright](https://twitter.com/joswr1ght) on working with event logs in powershell
- https://www.sans.org/blog/working-with-event-log-part-1/
- https://www.sans.org/blog/working-with-event-log-part-2-threat-hunting-with-event-logs/
- https://www.sans.org/blog/working-with-the-event-log-part-3-accessing-message-elements
- https://www.sans.org/blog/working-with-the-event-log-part-4-tweaking-event-log-settings/

## Other Platforms for learning

Blue Team Labs as free and paid plans
- https://blueteamlabs.online/

As does Cyberdefenders
- https://cyberdefenders.org/
- 

