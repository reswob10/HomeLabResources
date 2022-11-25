# HomeLabResources
List of resources for buiding a home lab

## Blogs and Videos that walk through setting up labs
Pay what you want book
Building Virtual Machine SECOND EDITION! by Tony Robinson 
Learn everything there is to know about building and maintaining your own home or workplace virtual lab environment on the most popular hypervisors today!
https://leanpub.com/avatar2

Great run through of building a lab influenced by Tony above.  Lots of links and suggestions and lessons learned.
https://www.netsecfocus.com/home/lab/2020/09/21/Tjnulls_guide_to_building_a_Home_Lab.html

[How to Build a Home Lab](https://www.youtube.com/watch?v=_Ih_wjHafrM)
Black Hills Information Security webcast

[Blog from Black Hills instructions and information for building a lab environment](https://www.blackhillsinfosec.com/how-to-deploy-windows-optics-commands-downloads-instructions-and-screenshots/)

SANS webcast: [Building an Enterprise Grade Home Lab](https://youtu.be/jnotvkoUF9U)

SANS webcast: [Extending Your Home Lab to include Cloud](https://youtu.be/j69DRB4WGeY)

SANS webcast: [Building Your Own Super Duper Home Lab](https://youtu.be/uzqwoufhwyk)

HAK5 video: [Building a Home Lab Virtual Server Quick and Dirty - Hak5 1819](https://youtu.be/9SpQ1fRQAto)

Videos by Tyrone E. Wilson

[Building an Effective Cybersecurity Learning Environment](https://www.youtube.com/watch?v=ZYAgyZ7RZm8)

[Hands-On Learning: How and Why You Should Build a Home Lab](https://www.youtube.com/watch?v=CL2Ng191KQE)

Great instructions for building ELK and Wazuh home lab:  
https://github.com/watsoninfosec/ELK-SIEM

Justin Henderson, the author of SANS SEC555, SEC530 and other courses is doing a series on [building a home lab](https://youtube.com/playlist?list=PLIQlcXRut9IPF8cJSSf0-BsoFy_1SOGYQ)

A guide on building a DIY SIEM at home by James Smith @DFIRmadness
https://dfirmadness.com/building-a-siem-at-home/

Another set of blogs for building a home lab.  This one is from Red Siege and will be more offensive focused:
part 1:  https://redsiege.com/blog/2022/06/simpledomainp1/
part 2:  https://redsiege.com/blog/2022/06/simpledomainp2/
If I'm slow putting up 3 and 4 which will probably come out in July 2022, just modify the above urls or google

## Automated lab creation tools


[AutomatedLab](https://github.com/AutomatedLab/AutomatedLab)
is a provisioning solution and framework that lets you deploy complex labs on HyperV and Azure with simple PowerShell scripts. It supports all Windows operating systems from 2008 R2 to 2019, some Linux distributions and various products like AD, Exchange, PKI, IIS, etc. 

[Splunk Attack range](https://github.com/splunk/attack_range)

[Purple Cloud](https://github.com/iknowjason/PurpleCloud) - An Infrastructure as Code (IaC) deployment of a small Active Directory pentest lab in the cloud. The deployment simulates a semi-realistic corporate enterprise Active Directory with a DC and endpoints. Purple team goals include blue team detection capabilities and R&D for detection engineering new approaches. 

Cyb3rWard0g has [Microsoft-Sentinel2Go](https://github.com/OTRF/Microsoft-Sentinel2Go) which contains scripts in github for multiple configurations to build an entire lab in Azure

[MS Defender Evaluation lab](https://techcommunity.microsoft.com/t5/microsoft-defender-for-endpoint/evaluation-lab-expanded-os-support-amp-atomic-red-team/ba-p/2993927) which includes Red Canary's atomic red team.

## How to's and Building Home Lab references

The [UK National Cyber Security Center](https://github.com/ukncsc/lme) has a great project for small/home offices to help them get started with logging.  This can be used for home labs as well. Not a full SIEM solution, but a start.

Offensive Security has a [great blog](https://www.offensive-security.com/offsec/tjnulls-guide-to-building-a-home-lab/)  with lots of details and links with a couple of videos [here](https://youtu.be/X3TyFji-jEw) and [here](https://youtu.be/Ed1ujM3xWNg)

Building ELK SIEM in in two videos, [part 1](https://youtu.be/HI072Rkthoc) and [part 2](https://youtu.be/mIXf2k9BQ3k)

Building ELK SIEM in [blog format](https://www.hackingarticles.in/threat-hunting-log-monitoring-lab-setup-with-elk/)

Cyberrange options to deploy in Azure: https://levelup.gitconnected.com/building-azure-cyber-ranges-for-learning-and-fun-9df1debb2eae?gi=e662f36c25fb

Series of videos for [building a home lab](https://youtube.com/playlist?list=PLDqMNdDvMsRkmtiKcZwbhOz7MeLQE0r3G) by @DayCyberwox:

[Watch this talk](https://youtu.be/EtlI04dJWX4) with SANS Certified Instructor and course author Justin Henderson, as he shares what the steps are in building out a detection oriented blue team lab.

Great setup script for Windows PCs from https://twitter.com/ajpc500

## Tools and configurations to build your home lab

Filtering DNS and HTTPS Traffic on pfSense
https://docs.diladele.com/tutorials/filtering_https_traffic_squid_pfsense/index.html

BadBlood - BadBlood by @davidprowe, Secframe.com, fills a Microsoft Active Directory Domain with a structure and thousands of objects:  
https://github.com/davidprowe/BadBlood

Powershell script to create AD Domain Controller and Workstation     
https://browninfosecguy.com/Active-Directory-Lab-Setup-Tool






Here is a [video]( from Black Hat Trainings in 2020
https://www.youtube.com/watch?v=X3TyFji-jEw












Wrote a quick and dirty PowerShell script to install Sysmon (SwiftOnSecurity config), SilkService and Winlogbeat, and forward the logs on to HELK. Might be useful for those looking to quickly configure endpoint logs in a lab environment

https://gist.github.com/ajpc500/3a86ba1741d4868b69be5ce3a142d527

From https://twitter.com/HBRH_314:
In this first video of Malware Analysis Fundamentals, we create our analysis environment for safe inspection of malware utilizing Remnux and FLARE VM.
https://youtu.be/whApbC5OvOs

AWS Pen-Testing Laboratory - Pentesting Lab With A Kali Linux Instance Accessible Via Ssh And Wireguard VPN And With Vulnerable Instances In A Private Subnet 
https://www.kitploit.com/2021/06/aws-pen-testing-laboratory-pentesting.html

Podcast/Videos on various topics for building stuff for your lab:
https://thehomelab.show/
Videos: https://youtube.com/playlist?list=PLjGQNuuUzvmtAzqgH7PVvnF_v0X9ZKMeA

Justin Henderson from SANS SEC555 has a couple free labs:  https://t.co/pLipGouXDj
User: student Pass: sec555

And of course there is at least one homelab reddit
https://www.reddit.com/r/homelab/

Video from https://twitter.com/watsoninfosec on his home lab build:
https://youtu.be/-1kwszraub0



Whole thread on labs.  Including networking, not just security
https://twitter.com/JBizzle703/status/1433953668148219906?s=20
https://threadreaderapp.com/thread/1433953668148219906.html


Some great resources from Jeff McJunkin

https://bit.ly/kickasslab
https://www.youtube.com/watch?v=KogdkuEbfwc


## Free/demo software:

data router/parser/mover  Cribl:  https://cribl.io/download/

Rapid7 InsightIDR Free Trial (SIEM): https://www.rapid7.com/try/insightidr/

A Guide to log formats:
https://www.graylog.org/post/log-formats-a-complete-guide

Other resources for free/cheap software referenced in the SANS webcasts:   https://github.com/aboutsecurity/blueteam_homelabs

Direct link to download free Microsoft Hypber-V server    
https://www.microsoft.com/en-us/evalcenter/evaluate-hyper-v-server-2019

## Generating data for you lab

https://gist.github.com/braimee/edf91f87ee95b48c803895614a0ec57a

Cyb3rWard0g and Cyb3rPandaH have a great site with malicious data sets:
    https://securitydatasets.com/introduction.html
    
Generate suspicious activity
https://www.activecountermeasures.com/threat-simulation-overview-and-setup/

Generate fake user activity
https://github.com/ubeeri/Invoke-UserSimulator

A quick and dirty HTTP/S "organic" traffic generator.    https://github.com/philhagen/web-traffic-generator

This looks like a great way to generate a lot of different types of data:
https://github.com/swimlane/soc-faker

Some other ways to generate data to be collected by your SIEM

https://pypi.org/project/log-generator/

https://logs.to/

https://nxlog.co/documentation/nxlog-user-guide/generating-test-data.html

https://github.com/tdunning/log-synth


Attack Simulation tool:  Automating Red Canary's atomic-red team   https://www.atomic-operator.com/.6.0/

Create network traffic to stress test network devices:  https://www.candelatech.com/downloads.php

Attacking AD cheat sheet:  https://github.com/S1ckB0y1337/Active-Directory-Exploitation-Cheat-Sheet
