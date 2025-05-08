# All You Wanted to Know 

## One's life in one line
> - Fabio Massacci (MEng'92, PhD'98 Computer Engineering, MA'95 in International Relations), married with two children, has been in Rome, Cambridge, Toulouse, Trento, and 
> Amsterdam. He held visiting positions in Durham, Koblenz, Lueven, Marina del Rey, and Oslo. 

## Three standard deviations in three lines
> - He is one of the few professors who has presented in top hackers' venues (BlackHat USA, Asia), top computer security conferences (ACM CCS, IEEE S&P), 
> top empirical software engineering journals (ESEJ, IEEE TSE) and top risk analysis journals (Risk Analysis). For his work on security and trust in socio-technical systems he 
> has received the [*Ten years Most Influential Paper Award*](https://requirements-engineering.org/#awards) by the IEEE Requirements Engineering. He has coordinated several
> European > projects (including a multidisciplinary projects with economist, sociologists abd computer scientists on socio-economic aspects of security SECONOMICS). 
> He is the coordinator on the [Sec4AI4Sec Project](https://www.sec4ai4sec.eu/) on Cybersecurity for AI augmented systems.
> - While almost all professors are *sellers* of technologies (through their papers or their spin-offs) he was for 7 years deputy rectors for ICT procurements and services 
> supervising a 70+ workforce and several millions Euro in outsourcing contracts. This made him a *buyer* of computing technology and a *user* of risk analysis. His perspective
> of what is a useful security technology or a useful risk analysis is shaped by this experience and very diverse: prestigious corporations are not longer (only) the place to send your > students or funders of your research, they are sloppy suppliers selling overpriced products.
> - He actively participated to civil society. He worked as a volunteer with underprivilege people and in refugee camps. He held, among others, the post 
> of European Executive member and Treasurer of Service Civil International an international NGO with consultative status at UNESCO and the European Youth forum. For his MA he
> wrote a dissertation on the cooperation between democracies and social islamic movements (instead of funding Saudi princes). He qualified at the world-wide competition to become
> an U.N. Officer but eventually opted to be an Assistant Professor (ok, nobody is perfect). 

## News

Our observational study GDPR in the small on how privacy issues are managed in schools is at IEEE Security and Privacy Symposium (IEEE SS&P). We observed actions of over 100 teachers and staff at 1 kindergarten, 10 primary schools, 2 middle schools, and 2 secondary schools. [Read the findings here](https://fabiomassacci.github.io/docs/Privacy_in_the_Small-16.pdf)

Two papers at the International Conference on Software Engineeering (ICSE): in one paper we set a mathematical bounds on when using machine learning for automated vulnerability repair make sense (Hint: either it is very fast or recall is great, otherwise is not worth). [Read the paper here](https://arxiv.org/abs/2504.07027). In a second paper we used confident learning to understand when it is better to drop confusing samples from the data set (Hint: it does make sense, dropping 0.5% bad training points can improve recall from 60% to 77%). [Read the paper here](https://fabiomassacci.github.io/docs/Confidence_Learning_for_Vulnerabilities_icse.pdf)

The Lebanon pager attack is a subject of an editorial opinion I wrote for the IEEE Security and Privacy Magazine. Read the paper (open access) on [Israel and the Birth of State Cyberterrorism](https://doi.org/10.1109/MSEC.2024.3500114) This was actually a realization of a paper we wrote on legal principles for lethal cyber weapons (see below for further details).

## My Researcher IDs and where to find my papers.
- [Google Scholar](https://scholar.google.com/citations?hl=en&user=gC_ZVPgAAAAJ&sortby=pubdate),
- [Scopus](https://www.scopus.com/authid/detail.uri?authorId=55167501300)
- [ORCID](https://orcid.org/0000-0002-1091-8486))
- [DBLP](https://dblp.org/pid/59/6145.html)

You can also find quite a few on [Trento's web page](https://securitylab.disi.unitn.it/doku.php?id=publications) and in [Amsterdam's web page](https://research.vu.nl/en/persons/fabio-massacci). Few highlights can be also found below.

* * *

# Affiliations

## Current Affiliation
> - **Amsterdam** chair of Foundational Security at the [Vrije Universiteit](https://www.vu.vl), from 2020, part-time 
> - **Trento**, professor of cyber security at the [University of Trento](https://www.unitn.it), from 2001, now part-time

## Research Consultancies
- Durham, Fellow of the [Institute for Advanced Studies](https://www.dur.ac.uk/ias/)
- Paris, Wavestone, Research advisor
- Rome, Consorzio Italiano Nazionale per l'Informatica (CyberSeceurity Lab), local responsible for the OPTICS2 EU project

## Editorial Boards
- [IEEE Security and Privacy Magazine](https://www.computer.org/csdl/magazine/sp) - Associate Editor in Chief.

* * *

# Research Highlight

## Recent Selected Papers

#### If your users browse porn, does it increase the chances of malware encounters: a case control study

In this 20204 paper with TrendMicro we investigated (anonymized) users' behavior try to understand if some factors (whether you use the computer at night, browse porn, install a lot of software, etc.) increases the odds of malware encounter. This paper used the same techniques used for the famous British study used to determine whether smoking increases the odds of developing cancer of the lung: a case-control study.
The quick answer is... it depends. There is not one single bad things that you shouldn't do: browsing porn increases the chances of encountering malware, but if you are worried of bad guys trying to install coinminers you shouldn't allow gambling sites, and so on. Browing at night is generally harmless while getting a lot of software increases the chances of ransomware. 
You can read the full details of the methodology and the results
- on the full paper open access on [IEEE TIFS](https://doi.org/10.1109/TIFS.2024.3456960)

#### Building Principles for Lethal Cyber Weapons and State Cyberterrorism

I wrote in 2022 with my collaborator Silvia Vidor (a political scientist) a paper on building principles for lawful cybersecurity lethal weapons. The Israeli attack on Lebanon pagers is the first realization of what can happen. Looking at what we wrote we can conclude that Israel failed on all counts from the international law that we idenfied and mapped to cyberattack:
- (always distinguish between military targets (legitimate) and civilian targets (illegal),
- limit damage to civilian targets (“collateral damage”) to an amount that is proportional to the military advantage the attack can offer
- avoid superfluous injuries and unnecessary suffering (to military and civilian targets alike).
You can 
- read the 2022 paper [IEEE S&P Magazine](https://doi.org/10.1109/MSEC.2022.3143269)
- read the 2025 follow up as open access editorial [Israel and the Birth of State Cyber Terrorism](https://doi.org/10.1109/MSEC.2024.3500114)

#### Updates are useless - a comprehensive study of Advanced Persistent Threats

At TSE22 we have just published a comprehensive study of over 86 APTs and 350 campaigns from 2008 to 2020. It includes information about attack vectors, exploited vulnerabilities (e.g. 0-days vs public vulnerabilities), and affected software and versions. The paper has two important messages:  APTs are not as terrible as security experts depict them and updating is not *the* solution: either you do at lightspeed a gazillions of update or if do regresssion etc., then your risk likelihood is the same as those who only rush to update for disclosed vulnerabilities and before that did... nothing. 
- Read the paper [preprint](https://lnkd.in/eWDNQmGQ)
- Download the dataset [Dataset](https://lnkd.in/eXZYQbep)
If you still think attackers are more powerful than they are, you should read our paper below on the Work-Averse attacker model. 

#### Technical Leverage - _the_ software and security metric that CFOs can finally understand.

At ICSE21 we have just presented a new and simple metric borrowed from finance: the ratio in a project between other's people money (in this case code from imported dependencies) code and your own money (code you developed yourself). Our analysis on Java projects: shipping 4x times your own code base slows down releases by few paltry days. It's an _opportunity_. Beware, increase your leverage too much and you get +60% chances of shipping vulnerabilities. It's a _risk_. Make sure you don't end up as Lehman Brothers.
- Watch out the [video](https://www.youtube.com/watch?v=H9RwhR0DANQ)
- Check the [white paper on the IEEE S&P Magazine](https://assuremoss.eu/en/resources/Papers/2021-SPM)
- Read the [full paper at ICSE-21](https://assuremoss.eu/en/resources/Papers/2021-ICSE)
- Or just play with [demo](https://techleverage.eu).


#### Empirical Security and Software Engineering
  - *IEEE Transactions on Software Engineering* TSE-2020 (joint with SAP)  [Vuln4Real: A Methodology for Counting Actually Vulnerable Dependencies](to appear)
  - *ACM Computers and Communication Security* CCS-2020 [A Qualitative Study of Dependency Management and Its Security Implications](https://securitylab.disi.unitn.it/lib/exe/fetch.php?media=research_activities:experiments:ccs-2020-preprint.pdf)
  - *Empirical Software Engineering Journal* ESEJ-2020 (joint with TU/e and UMilano), [Measuring the accuracy of software vulnerability assessments: experiments with students and professionals](https://doi.org/10.1007/s10664-019-09797-4)

#### Risk Analysis and Policy
   - *Risk Analysis* RAJ-2021 (joint with Durham Business School andTU/e) [The Work-Averse Cyberattacker Model: Theory and Evidence from Two Million Attack Signatures]([https://doi.org/10.1111/risa.13454](https://onlinelibrary.wiley.com/doi/full/10.1111/risa.13732))
 - *Risk Analysis* RAJ-2020 (joint with Durham Business School and KIPA) [Who Should Pay for Interdependent Risk? Policy Implications for Security Interdependence Among Airports](https://doi.org/10.1111/risa.13454)
  - *Risk Analysis* RAJ-2018 (joint with TU/e) [Security Events and Vulnerability Data for Cyber Security Risk Estimation](http://www.win.tue.nl/~lallodi/allodi-risa-17.pdf)
  - *IEEE Security and Privacy Magazine* SPM-2020 (joint with TUDelft) [Governance Challenges for European Cybersecurity Policies: Stakeholder Views](https://securitylab.disi.unitn.it/lib/exe/fetch.php?media=research_activities:economics:ieee_governance_v28-cleaned.pdf)

#### Crypto and Fintech
  - *IEEE Security and Privacy Magazine* SPM-2020 on [Distributed Financial Exchanges: Security Challenges and Design Principles](https://securitylab.disi.unitn.it/doku.php?id=sp-2019-05-0134.r1_ngo.pdf)
  - *IEEE Symposiunm on Security and Privacy* SSP-2018 (joint with Durham Business School) on [FuturesMEX: secure, distributed futures market exchange](https://securitylab.disi.unitn.it/lib/exe/fetch.php?media=sp18proceedings.pdf). Also an [EU/US Patent Application](https://patentimages.storage.googleapis.com/33/02/e7/6deebeae0a1845/US20190244290A1.pdf)

## Less Active Research Topics 	
- Modelling Security Requirements Engineering (Now I do experiments on SRE). But you can still check my 
- [Logical Cryptanalysis or Crypto with SAT](https://disi.unitn.it/~massacci/CryptoSAT/) for representing crypto-problems as logical problems. This was an instrumental technology for the recent collision found on SHA-1. I have some old lover's interest in this so if you are interested drop me an email.

* * *
# Impact 	

## Scientific Awards
- 2015: [Ten Years Most Influential Paper Award at IEEE Requirements Engineering Conference](https://requirements-engineering.org/#awards) for our paper on Modeling security requirements through ownership, permission and delegation. You can read our pre-print copy or see our presentation at RE'15.
- 2001: AIxIA - Marco Somalvico Career Award for Young Researchers in AI by the Italian Association for Artificial Intelligence

## Industry Impact
- My research on risk reduction for vulnerability assessment made its way to the world standard Common Vulnerability Scoring System (CVSS) v3. You can see our Black Hat'13 presentation read the full paper on ACM TISSEC
- Our Work on Security-economics and risk was "owned" by National Grid UK/US who advocated it at high level meetings (UK Cabinet Meeting and EU presidency) and within E-ENTSOE.
- See the recent development of an intellectual child of mine: Logical Cryptanalysis was instrumental to break SHA-1

* * *
# Collaborators	

## Research Staff
- [Mengyuan Zhang](https://scholar.google.it/citations?hl=en&user=XebXoxIAAAAJ) - Tenure Track Assistant Professor at @VUAmsterdam
- [Johannes Hartel](https://johanneshaertel.github.io/) - Postdoctoral Researcher at @VUAmsterdam
  
## PhD Students
- [Winnie Mbaka](https://scholar.google.com/citations?user=S9jApi8AAAAJ&hl=en) on human factors in security (jointly with Katja Tuma)
- [Maria Camporese](https://www.linkedin.com/in/mariacamporese/) on automated vulnerability repair @UTrento
- [Yuan Feng]() on machine learning for vulnerability detection @UTrento
- [Emanuele Mezzi](https://www.linkedin.com/in/emanuele-mezzi/) on AI and ML for Threat Intelligence @VUAmsterdam and TNO (jointly with Katja Tuma) 
- [Francesco Minna](https://orcid.org/0000-0002-3018-044X) on run-time analysis for Cloud Security @VUAmsterdam (jointly with Katja Tuma)
- [Aurora Papotti](https://www.linkedin.com/in/aurora-papotti/) on the security of supply chains @VUAmsterdam
- [Ranindya (Nanin) Paramitha](https://www.linkedin.com/in/ranindya-paramitha-5766b513a/) on vulnerability mining @UTrento
- [Sarah van Gerwen](https://www.linkedin.com/in/sarah-van-gerwen-826331216/) on Human aspects on AI for threat intelligence @VUAmsterdam and Thales Research NL
- [Siqi Zhang](https://research.vu.nl/en/persons/siqi-zhang) on vulnerability prioritization and patching policies @VUAmsterdam (Jointly with Mengyuan Zhang)
  
## Former Collaborators
- Academia: Luca Allodi (TU/e), Nataliia Bielova (INRIA), Carlos Budde and Nicola Dragoni (DTU), Olga Gadyatskaya (ULeiden), Kate Labunets (TUDelft), Stephan Neuhaus (ZHAW), Federica Paci (UVerona), Katja Tuma (TU/e), Nicola Zannone (TU/e), Ganbayar Uuganbayar (UMongolia)
- industry: Stanislav Dashevsky (Forescout), Giorgio Di Tizio (Airbus), Duc Ly Vu (ChainGuard), Katsyarina Naliuka (Google), Viet Hung Nguyen (Bosch), Chan Nam Ngo (FinTech), Ivan Pashchenko (TomTom), Le Minh Sang Tran (RoboFi).
- Governement: Woohyun Shim (Korean Institute of Public Administration), Ayda Saidane (Revenue Quebec), Piera Sterlini (UTrento)

## NEW positions
- I am always interested in getting new candidates (either in Trento or in Amsterdam). Contact me with a specific proposal and make sure you have at least skipped some of my  papers. I receive gazillions of letters of the kind: 'I'm very keen to work on your supervision on... follow a list of things on which I have clearly no competences or skills.

* * *
# Projects 

## Active Projects
- HE Project [Sec4AI4Sec](https://www.sec4ai4sec-project.eu/)
- NWA Project [Theseus](https://project-theseus.nl)
- NWO-KIC Project [HEWSTI]()

## Past Projects
- EU H2020 [AssureMOSS](https://www.assuremoss.eu) - 12 partners - (EU Coordinator)
- EU H2020 [CyberSec4Europe](https://cybersec4europe.eu/) - 41 Partners - (Leader of Education and Skill WP)
- EU H2020 [OPTICS2](http://www.optics-project.eu) - 6 Partners
- FP7 [SECONOMICS](http://seconomicsproject.eu/)
- FP7 [SecureCHANGE](http://www.securechange.eu)
- FP6 MASTER
- FP6 S3MS
- FP5 SERENITY
- 

* * * 
# Civil Society Engagement
 
- 1995: International habilitation as United Nation Officer (Level P2)
- 1992-1997: European Executive Board Member and European Treasurer of Service Civil International.
- 1992-1993 Italian Treasurer for the Italian Consortium of Solidarity working on relief work in what at the time were the former republics of Yugoslavia
- Read an essay written for a professional Master in International Relations by the Italian Minister of Foreign Affairs and the Italian Defence Center. I advocated a different relationship between Western Democracies and Militant Islam, rather than funding conservative islamist leaders (like Saddam Hussein or Saudi princes) to bash communists. History proved me right. Download it in [Postscript](https://disi.unitn.it/~massacci/Publications/mass-95-SIOI.ps) 

 If you think that is strange, I have been also strongly involved in the sector of International Voluntary Service Organizations and Peace Movements. Now I'm more active in supporting Fair Trade Organization. I have a special relationship with the Philippines as I personally know quite a few activists of the human rights and fair trade movement there.
 
 I met my wife [Beatrice De Blasi](https://beatricedeblasi.photoshelter.com/index) while working in the NGO sector. 

# Lectures and Teaching

For the lectures, it is a lot better that you check the web pages of the University. Those ones are always updated (and anyhow they are the ones that I have to use).

For __Master Theses__, send me an email from your students' account. Try to read the bio to make sure that I'm sort of interested in the things you want to do. 

I also supervise Theses carried in industry and I actually encourage you to do so. A thesis in industry is not a bad thesis, there are just some caveat in terms to make sure that you can make an interesting work and report some interesting scientific findings. Several people continued into an industrial PhD.

I have several Research/Thesis projects for motivated students either in Amsterdam or Trento. The research project roughly correspond to 6 or 12 ECTS. They can also become thesis with either a broader or deeper scope.

# Contacts and Appointments

Jeez, you went till here. You deserve something. IF you are a former student of mine who wants a recommendation letter it is **mission critical** that you [read the instructions](https://disi.unitn.it/~massacci/instructions-for-references.html).

Otherwise, send me an email.... Ahahhaha that was a good joke... You can use 
> - my IEEE address "name.surname@ieee.org".
> - my Amsterdam address "initial.achternaam@vu.nl",
> - my Trento address "nome.cognome@unitn.it",

Alternatively you may contact me on [LinkedIn](https://www.linkedin.com/in/fabio-massacci-b3199225/). This is the only social network I use.

If you want to know where I am or talk to me, check my [IEEE Calendar](https://calendar.google.com/calendar/embed?src=fabio.massacci@ieee.org). Most likely on digital platform somewhere.

You might also directly call me at my office numbers
> - +31-20-5986098
> - +39-0461-282086

* * *

### Copyright
The text on this page is licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License [CC-BY-SA-3.0](https://creativecommons.org/licenses/by-sa/3.0/)

