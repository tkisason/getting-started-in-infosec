# Information security / Hacking for noobs 


A gentle introduction for beginners that want to start in information security. Though, the core concepts part will benefit anyone that wants to start in IT. Pull requests welcome. 

The background for this is that @twowreck said one day, hey @kisasondi let’s write a document that will help the beginners at our Faculty that want to learn more about information security, so we can streamline the process of “where to start” for 1st year students. We hope this document will be helpful for them, and everyone else that can find it interesting.  Well, we quit the Faculty, but we still want this to be public for benefit of others. 

This is not a in-depth document, but more as a “where to start” document that will give beginners a nice bootstrap (and keep you busy for at least 3-6 months)

For updates, just send a pull request or send me an e-mail. 

# Core concepts:
“I teached you so that one day you can teach other people...”
* A guy who teached @milobit a lot of things. :) 

**Note:** Expertise is important, and you should strive for expertise in one general field / speciality. Some people say that in average you need 7 years of dedicated work to become proficient and master a field. But with expertise, It’s important to learn concepts in other fields of study. You should strive to identify concepts, learn how things work from a broad outline and then be able to realize the limitations of your knowledge and learn something more about the topic you need.
* See: The T-Shaped individual


o, if you can’t find any article any more, use archive.org and find a archived version. 

Don’t mistake perceived expertise for actual expertise. Read about the Dunning-Kruger effect:
* https://en.wikipedia.org/wiki/Dunning%E2%80%93Kruger_effect


Example: You are facing a tough problem, that problem will be easy to solve if you know:
1. Why this problem is “hard”, i.e. What is your actual problem.
2. How we call the components in your problem? 
3. What is the technical name for your issue/problem?


After you know that, using Google is simple :) 


Read some philosophy:
* This document is old, but the old school adages still stand today: http://www.catb.org/esr/faqs/hacker-howto.html

Read your local misdemeanor and criminal laws!
* https://www.zakon.hr/z/98/Kazneni-zakon 
* Especially note computer crime acts:  (in Croatia: Kaznena djela protiv računalnih sustava, programa i podataka)
* https://www.zakon.hr/z/52/Prekr%C5%A1ajni-zakon 


**If you think about becoming an information security professional or a hacker in order to break into systems, DDoS etc, let’s get one thing straight, you will get caught, and put into jail (or worse). It’s inevitable (and why it is inevitable, you will know after you spend some time learning about forensics...).**

Understand this too: https://en.wikipedia.org/wiki/Locard%27s_exchange_principle 


Like doctors, information security is a honour based profession:
1. Always follow the law and don’t break the law.
2. Don’t be evil
3. Follow ethics and professional codes of conduct:
   1. http://www.issa.org/?page=CodeofEthics 
   2. https://www.ieee.org/about/corporate/governance/p7-8.html  
1. Don’t feed your ego. Even if you are 50 years old and you have 30 years experience in Infosec, you still have plenty to learn. Be humble and truthful. Some of the biggest experts i know are more humble than most noobs in the field.
2. Don’t say you are a hacker. If you keep saying that, trust me, you are not a hacker.
3. Don’t learn to hack. Get enough IT / Computer science knowledge, and hacking will happen by itself. You need to know how something works to be a expert or bend it to your will
4. Share knowledge and contribute to open source software.
   1. You should be a force of good and help people, not be a elitist (see under “ego” above)


Read about the following concepts, especially Dunning-Kruger:
* https://en.wikipedia.org/wiki/Dunning%E2%80%93Kruger_effect
* https://understandinginnovation.files.wordpress.com/2015/06/dunning-kruger-0011.jpg?w=640
* https://en.wikipedia.org/wiki/Impostor_syndrome 


Read this (yes, it’s important):
* http://hackingdistributed.com/2018/05/30/choose-your-own-security-disclosure-adventure/ 


Dedicate at least 1h a day to learning how X works (where X is anything IT / Computer related), it doesn’t matter if you learn how to code in Python, how BGP works or how FreeBSD works, as long as you are learning more, you are getting better and better. 


So, for starts, let’s talk about behaviour and some information, read this:
* https://www.belfercenter.org/CyberPlaybook
* https://theintercept.com/2017/11/19/how-to-protect-yourself-against-spearphishing-a-comic-explanation/
* https://medium.com/@thegrugq/campaign-information-security-ff6ac49966e1
* https://techsolidarity.org/resources/congressional_howto.html 
* When you don’t know what to read, read something from this list:
   * https://scrty.io/ 


Learn how to play with systems /  devices without breaking stuff and making that playing simple and easy. Use virtual machines (and later on, build your own playground/lab). First off, read on what a Virtual Machine is...
Download and install Virtualbox:
* https://www.virtualbox.org/wiki/Downloads
* Learn what’s NAT, Bridged and Host-Only networking does, and why is it important:
* Learn what’s the VirtualBox Extension Pack (and why you want it)
* Learn what guest additions are (hint: open a terminal and enter: apt update && apt install virtualbox-guest-utils in a VM to enable dynamic screen resizing, shared folders/clipboard etc)
* Learn how shared folders work (and why that’s dangerous if you run malware in a VM)
* Learn what are snapshots! They enable experimenting and reverting to where things were not broken. 
* Learn what’s an ova file (appliance export/import)


Install Ubuntu desktop and ubuntu server in a VM. If you are wondering if you should go with the “latest and greatest” or LTS (Long term support) - Go with Long Term Support (LTS).
* https://www.ubuntu.com/desktop
* https://www.ubuntu.com/download/server
* Take snapshots, so you can easily revert. 


Pass the entire LinuxJourney tutorial: https://linuxjourney.com/
* If you like it or not, you need to know the basics: How a modern operating system works. You don’t have to know how the CFS scheduler works in the kernel (and how it is implemented), but you should know what a scheduler is, what is a kernel etc, and be comfortable in using a modern Linux based operating system (in the shell, ie. command line, not in the GUI :) ). 
* The man command will give you the manual for any command. Learn how to use man. Read the manpages (and do some examples) for the following commands: ls, grep, find, which, curl, wget, ssh, systemctl 


As you get better and better, your curiosity will guide you to explore the systems in depth. Someone might download the entire Linux kernel source and read it through (or you won’t care about operating systems that much, and you will see how your favourite web programming framework works under the hood, or how that nice pair of bluetooth headphones communicate with your PC. It’s irrelevant what, curiosity and getting better and better in knowledge is what’s important)


Learn at least one high level language (Python, Ruby, Go… ):
* This is a nice tutorial:
   * https://www.codecademy.com/catalog/language/python
   * One additional might be the official python tutorial. 
   * 2.x or 3.x? Learn Python3. 
   * Check out : https://ipython.org/ 
* I repeat, you don’t have to be an expert, but pass some problems so you get to at least to the mid of the intermediate list here:
   * https://adriann.github.io/programming_problems.html
* This is also a great list:
   * https://www.interviewbit.com/ 


Get a solid intro to computer systems:
* https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-11
* https://www.edx.org/course/cs50s-introduction-computer-science-harvardx-cs50x
* https://www.amazon.com/Computer-Science-Distilled-Computational-Problems/dp/0997316020
* https://en.wikiversity.org/wiki/Introduction_to_Computer_Science
* Some people like a book called “Computer Science Distilled: Learn the Art of Solving Computational Problems by W. Filho”
* This is an awesome materiel in Computer Architecture: https://www.youtube.com/playlist?list=PL5Q2soXY2Zi9OhoVQBXYFIZywZXCPl4M_ 

Get some background on operating systems:
* http://greenteapress.com/thinkos/thinkos.pdf
* http://www.shubhro.com/2018/01/20/brushing-up-os-c/ 
* https://web.stanford.edu/class/cs140e/syllabus/#schedule 


Get a feel on how the web looks/works:
* https://www.codecademy.com/catalog/language/html-css (Learn HTML/CSS)
* https://www.codecademy.com/learn/introduction-to-javascript (Get some basic intro to JS)


Important note: If you want to be an expert, let’s say in web application security, you should know how the web works and how web applications work in order to be successful. I.e. put in the work so you know how the underlying system works, and after that it will be easy to understand why something is broken (or to find if something is broken). For example, this is best seen in good developers, when you show them where they introduced a vulnerability, they instantly “get it” and know why this happened. They know the underlying concepts well enough to easily grasp the security concepts needed. This can be applied to any field: reverse engineering, hardware hacking, social engineering… 

One of the key concepts for technical and organizational parts of security is threat modelling. Read the book by A. Shostack: “Threat Modeling: Designing for Security”
* https://www.amazon.com/Threat-Modeling-Designing-Adam-Shostack/dp/1118809998 
Second book you need to read is “Security Engineering” by Ross Anderson:
* The whole book is available for free here: https://www.cl.cam.ac.uk/~rja14/book.html 
* Or the print version of the book is available here: https://www.amazon.com/Security-Engineering-Building-Dependable-Distributed/dp/0470068523


# Specializations


## Reverse engineering / malware analysis:

You won’t be able to properly understand reverse engineering / binary exploitation if you don’t know a Low level language, start with C and ASM
* Here are some cool resources to help you get started in C:
* https://viewsourcecode.org/snaptoken/
* http://goalkicker.com/CBook/ 
* http://www.shubhro.com/2018/01/20/brushing-up-os-c/


Check this out:
* Malwareunicorn’s RE 101 / 102 workshops: https://securedorg.github.io/ 
* Malwaretech’s  RE challenges: https://www.malwaretech.com/beginner-malware-reversing-challenges
Specialities:


## Appsec / WebAppSec:

* First: Write a couple of simple applications (a small blog engine, a twitter clone, a RESTfull API for a bookstore...)
   * Preferably in PHP, Java, Python :) 
   * Try to do it manually. Now use the most popular framework for that language.
   * Be a semi competent junior web-dev before you 
* This is a good tutorial for beginners:
   * https://www.hacker101.com/ 
* Read the entire Web Application Hackers Handbook (2ed or newer):
   * https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470
* Read the entire Web Application Defenders Cookbook:
   * https://www.amazon.com/Web-Application-Defenders-Cookbook-Protecting/dp/B01B9A4AYQ 
* Read the Tangled web:
   * https://www.amazon.com/Tangled-Web-Securing-Modern-Applications/dp/1593273886
* Load OWASP broken web apps VM:
   * https://www.owasp.org/index.php/OWASP_Broken_Web_Applications_Project 
* This is an interesting cheat sheet:
   * https://jdow.io/blog/2018/03/18/web-application-penetration-testing-methodology/ 
* Check out the following applications:
* OWASP ZAP
* Burp Suite
* sqlmap
* Dirb / gobuster / dirsearch
* This is an interesting exercise to pass: https://www.obeythetestinggoat.com/pages/book.html#toc 
* Run this: https://www.owasp.org/index.php/OWASP_Juice_Shop_Project , find all vulns :) 
* This is a nice set of writeups on bug bounties:
   * https://pentester.land/list-of-bug-bounty-writeups.html 


## Forensics / Reverse engineering

* Contributions required :) 

## Cryptography:

* Read the book: Serious Cryptography by JP Aumasson
   * If you don’t understand anything from that book, research, google, etc. Make sure you understand the basic concepts and building blocks (primitives)
* How do you use Elliptic curves for cryptography? Why do you have to use ECDH and ECDSA. 
* Research on how GnuPG works, explore why the web of trust works and what are the pros and cons of web of trust
* Figure out how TLS works, can you in detail explain the following terms and how they work:
   * PKI, TLS handshake, SNI, Ciphersuite, Ephemeral ciphers and Perfect forward secrecy, how ECDHE is used in the handshake, how does the entire TLS process work?
* Read the wireguard spec: https://www.wireguard.com/papers/wireguard.pdf 
* Read the Double Rachet spec: https://signal.org/docs/specifications/doubleratchet/ 
* Read the Bitcoin paper: https://bitcoin.org/bitcoin.pdf 
* All of the above show nice cryptographic systems. If you understand the above 3 papers, you will know how to research further. 


# Interesting assignment lists:


## Assignment list from @viss (Dan Tentler):

Pick a company and tell me:
- who is their head of security
- everyone on their team all the way down
- are these recognizable names or people?
- are they randoms or are they part of the community
- every social media profile available with every person found
- an assessment of "are they just a cissp douche who doesnt care" or "are they legit, do they take shit seriously"
- an assessment of "should I try to reach out this company for security services" based on their appetite for "actual security" not "checking boxes"

Start up wordpress from scratch:
- linux, apache, php, mysql.
- don't harden it, just make it live
- once it's up, install wpscan on another host and scan the blog
- install several vulnerable plugins, and set the blogs password to something easily guessable
- modify htaccess to deny permissions to anybody not you
- install the sucuri security plugin and configure it. 
- run wpscan again, observe differences
- using htaccess, block the wpscan user agent, and try wpscan again, observe results
- attempt to shell the blog and gain access
- setup a webshell
- use the webshell against the target

## Assignment list from @da_667:
* The original resource is available here: https://twitter.com/da_667/status/1041867361765269505 
* cybrary.it  is a free resource that provides access to a bunch of different information security and/or general IT training courses. Alot of these courses are built around certifications. and if you don't know my stance on certifications Its true that they are NOT a requirement to get a job, but its also true that they won't hurt you. and even if you don't like them, or don't plan on getting the certification for the material you're watching, you still probably learned something valuable.
* Codecademy and/or Khanacademy are "freemium training resources. That is, for the most part a lot of the stuff is free, some of the stuff may also be behind paywalls. Just to give you forewarning.
* If you're more of a bookworm packt publishing gives out new, free books on a regular schedule. Additionally most of their book choices are fairly affordable as well.
* http://leanpub.com  is another website full of cheap books that, depending on the author and/or the material, the book might be in various stages of being done, and allow you to define what you pay for the book.
* Keep a look out for when humble bundle is doing partnerships with nostarch press. NSP books are good and humblebundle makes them REALLY cheap.
* another good, free resource for training would be http://opensecuritytraining.info/Training.html  take a look at what they have to provide, there is a ton of valuable knowledge to pick up, and at no charge.
* If you're looking for materials on reverse engineering, Mr. Yurichev's reverse engineering for beginners has been recommended repeatedly. https://yurichev.com/ 
* do you wanna learn how to fuckin' annihilate malware? @malwareunicorn 's RE101 and RE102 courses are extremely well put together, high quality and free: https://sites.google.com/secured.org/malwareunicorn/reverse-engineering 
* Want to learn about web applications and how to attack them? Samurai WTF. Comes with course documentation and a self-contained VM for practicing on.  (please note that it is a little bit long in the tooth, but still serves the purpose): https://sourceforge.net/projects/samurai/
* Don’t forget the slides: https://sourceforge.net/projects/samurai/files/SamuraiWTF%20Course/
* While we're talking exploitation resources, its pretty basic, but metasploit unleashed is a GREAT resources for getting familiar with the metasploit framework and/or using as a cross-reference for remember command syntax.While we're talking about metasploit unleashed, lets talk about metasploitable. Metasploitable is an intentionally vulnerable VM that is older than dirt, and so full of holes it looks like an XCOM mission site after I've been done with it.
* Before we move on to talking about wargames, CTFs and challenges, I almost forgot to mention that SANS cyberaces is a thing. http://www.cyberaces.org/courses/   while its a little bit old, its still a valuable free resource for learning some of the foundations out there.
* Okay so now we talk about CTFs and other exercises. Before I even get started here. Shout out to @blackroomsec This huge catalog of challenges is amazing. https://www.blackroomsec.com/updated-hacking-challenge-site-links/
* his is a massive list of challenges and must have been a mother to put together. There is just so much to choose from there, you can't really go wrong. But let me tell you about some of my favorites.
* first and foremost, I love the "overthewire" challenges. They have a learning curve that starts off super soft and easy to pick up, especially if you have some systems administration experience, but quickly get HARD once you think you have your shit together.
* best part about it is that, if you get stuck, there are write-ups all over the net and how others managed to solve it. There is NO SHAME in looking up others write-ups if only to see if you can replicate their work. this isn't a competition. Its for your training and benefit.
* along those lines, http://vulnhub.com  is a website that hosts a huge variety of vulnerable virtual machines that are a unique challenge all their own. Most of them are called "boot2root" vms in that you are supposed to boot them up and through a trail of breadcrumbs get root


# Misc interesting resources

ARBCTF resources:
* https://github.com/ARBCTF/resources/blob/master/README.md

Misc but interesting stuff:
* https://www.informationsecurity.ws/2015/12/the-cybersecurity-consultants-toolkit/
* http://www.pse-journal.hr/upload/files/pse/2017/4/vukovic.pdf 

Youtube - Infosec Educational Playlist:
* https://www.youtube.com/playlist?list=PL091tVBWhjdRwEx2alle3d-qkGO5Rh05i

# Youtube channels worth looking:

**Really good stuff:**
* https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w 
* https://www.youtube.com/channel/UCVFXrUwuWxNlm6UNZtBLJ-A

**Good stuff:**
* https://www.youtube.com/channel/UCgKtZlTRV1ruNPO_QOhCpVw
* https://www.youtube.com/channel/UChjC1q6Ami7W0E71TzPZELA
* https://www.youtube.com/channel/UCaEgw3321ct_PE4PJvdhXEQ
* https://www.youtube.com/channel/UCoFU24KMXmCi4Sl3KIFPSVg
* https://www.youtube.com/channel/UCIwQ8uOeRFgOEvBLYc3kc3g
* https://www.youtube.com/channel/UCtThfJl65L04ukWp0XZi3yg
* https://www.youtube.com/channel/UCMACXuWd2w6_IEGog744UaA
* https://www.youtube.com/channel/UC4m2G6T18_JcjwxwtwKJijw
* https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA
* https://www.youtube.com/channel/UCz2aqRQWMhJ4wcJq3XneqRg
* https://www.youtube.com/channel/UC9Qa_gXarSmObPX3ooIQZrg
* https://www.youtube.com/channel/UCio4BvuxdzRGWR9aXg7ztfQ
* https://www.youtube.com/channel/UC0bkqrWNBKxGZi-4gIfaCpg
* https://www.youtube.com/channel/UCUB9vOGEUpw7IKJRoR4PK-A
* https://www.youtube.com/channel/UCF0HwgCMJ3ZXSktymhtIIqA


## Etgar’s list:


Liveoverflow
* https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w
Murmus CTF
* https://www.youtube.com/channel/UCUB9vOGEUpw7IKJRoR4PK-A
Gynvael
* https://www.youtube.com/user/GynvaelEN
MalwareAnalysisHedgehog
* https://www.youtube.com/channel/UCVFXrUwuWxNlm6UNZtBLJ-A
DefconConference
* https://www.youtube.com/channel/UC6Om9kAkl32dWlDSNlDS9Iw
TheExploiteers
* https://www.youtube.com/channel/UC3yU54eqJZeAXMcJCErj_DQ
CryptoCat
* https://www.youtube.com/channel/UCEeuul0q7C8Zs5C8rc4REFQ
TheSecurityTube
* https://www.youtube.com/channel/UCBRNlyf9lURksAEnM-pyQdA
S1GM4
* https://www.youtube.com/channel/UCLzsoLvkQI7XXQfPG5XM47w
Derek Rook
* https://www.youtube.com/channel/UCMACXuWd2w6_IEGog744UaA
Army cyber institute
* https://www.youtube.com/user/ArmyCyberInstituteWP
HackHappy
* https://www.youtube.com/channel/UCVakgfsqxUDo2uTmv9MV_cA
JackkTutorials
* https://www.youtube.com/user/JackkTutorials
Seytonic
* https://www.youtube.com/channel/UCW6xlqxSY3gGur4PkGPEUeA
HackerSploit
* https://www.youtube.com/channel/UC0ZTPkdxlAKf-V33tqXwi3Q
Abdelkader Belcaid
* https://www.youtube.com/channel/UCCKCh5N2MLGhtqEqIZYjP1Q
Cyber Security IPB
* https://www.youtube.com/channel/UCH6CPf10u9uQu3w1DRhOliw
Black Hat
* https://www.youtube.com/watch?v=bfH_Ah5X9v8
Tony Gambacorta
* https://www.youtube.com/channel/UCGbeTQOPHwFikUlme8Txzvw
GalaxyNinja Top-Hat-Sec
* https://www.youtube.com/channel/UCI9pfCytpEy89dJmMAl6p1Q
MalwareAnalysisForHedgehogs
* https://www.youtube.com/channel/UCVFXrUwuWxNlm6UNZtBLJ-A
Candan BÖLÜKBAŞ
* https://www.youtube.com/channel/UC7NmOUOJn0Vr5BrfzjgBD2A
L!NK
* https://www.youtube.com/channel/UCv6i6WVf-KeUeXFmp9oy29w
HackersOnBoard
* https://www.youtube.com/channel/UChGDEluRG9r5kCecRAQTx_Q
NetSecProf
* https://www.youtube.com/channel/UCyoaOIKSqZTiM9-QcoIbNSg
howCode (general programming)
* https://www.youtube.com/channel/UCovR8D97-8qmQ8hWQW0d3ew
betaCoding
* https://www.youtube.com/user/betacoding
DrapsTV
* https://www.youtube.com/user/DrapsTV
Coding Tech
* https://www.youtube.com/channel/UCtxCXg-UvSnTKPOzLH4wJaQ
Fun fun functions
* https://www.youtube.com/channel/UCO1cgjhGzsSYb1rsB4bFe4Q
Siraj Raval
* https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A
Free Training
* https://www.youtube.com/channel/UC3RYdKzMQmdz8I8IU2iQDZA
OWASP
* https://www.youtube.com/user/OWASPGLOBAL
Elias Osif
* https://www.youtube.com/channel/UCcxmD7gdooV5Qkb-6b8RU6w
Deep Web Academy
* https://www.youtube.com/channel/UCJ31aJo8U-ZaRnZ4Y27so_Q
The PC Security Channel (TPSC)
* https://www.youtube.com/channel/UCKGe7fZ_S788Jaspxg-_5Sg
David Hoelzer
* https://www.youtube.com/channel/UCpi0MkJ23w83bHpxA4ZvGFg
CryptoCat
* https://www.youtube.com/channel/UCEeuul0q7C8Zs5C8rc4REFQ
Binary adventure
* https://www.youtube.com/channel/UCSLlgiYtOXZnYPba_W4bHqQ
OALabs
* https://www.youtube.com/channel/UC--DwaiMV-jtO-6EvmKOnqg
Da532
* https://www.youtube.com/user/iewan64
HazardEdit
* https://www.youtube.com/channel/UCG0LukbgMa6vJkA_JJ4Jepg

## Legal playgrounds

* HackTheBox (Make sure to use seperate environment not the one that's used on daily bases. Connecting to those challenges trough a VM for example a kali VM will be enough, since everyone is hacking on those platforms, so you don't become collateral damage.
https://www.hackthebox.eu/
* Vulnhub
https://www.vulnhub.com/
* Overthewire
http://overthewire.org/wargames/


## Misc interesting articles

* Fergus Henderson - Software Engineering at Google: https://arxiv.org/pdf/1702.01715.pdf
