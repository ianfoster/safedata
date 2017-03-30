# Introduction

Access to new types of data has revolutionized much of science. Yet that revolution has yet to fully make its way to the scientific study of human beings and their interactions, where progress has been hindered by the legal, technical, and operational obstacles to sharing and accessing sensitive data about individuals. New paradigms and platforms are required to enable sensitive data from different sources to be discovered, integrated, and analyzed in an appropriately controlled manner, while also allowing researchers to share analysis methods, results, and expertise in ways not easily possible today. Success in this endeavor may enable a fundamental change in how data on human beings from governments, statistical agencies, research institutions, and other organizations, are made available for research, and thus a flowering of new methods for studying human subjects.

Our goal in this class is to study the technical problems raised by sensitive data and the technical solutions that have been developed for working with this data. We will read and discuss scientific papers in the area and hear from distinguished invited speakers with experience in the development and application of those solutions. We’ll investigate not just the technologies but also the practical applications that make secure access to sensitive data so important: applications such as new scientific approaches to understanding human beings and human societies, and evidence-based policy for healthcare, poverty, and crime. Topics to be discussed include:

-	Opportunities for social science, evidence-based policy, program evaluation, and healthcare
-	Building and operating secure data enclaves 
-	Secure multi party computation
-	Statistical disclosure methods such as differential privacy
-	Privacy preserving data mining 
-	Search and discovery with sensitive data
-	Data de-identification, linkage, and re-identification
-	Deployment scenarios in cities, state governments, federal government
-	Regulatory challenges and regimes
-	Methods for sharing code and reproducible research
-	The Globus safe data platform

#  Class organization

The class is held Tue/Thu 9:00-10:20am in Ryerson 277. It runs from March 28 to June 1. The instructor is Ian Foster <foster@uchicago.edu>, whose office is in Searle 222. Please feel free to email anytime with questions or to set up a meeting.

Along with this website, we'll use [Piazza](https://piazza.com/uchicago/spring2017/cmsc33001/home) for course announcements, submitting paper reviews, posting lecture slides, and general discussion and questions about course material.

Grading
* Paper reviews — 25%
* Paper presentations — 20%
* Participation — 5%
* Course project — 50%

Separate pages provide guidance for [paper reviews and presentations](Content/reviews.md) and [class projects](Content/projects.md). 

# Schedule (subject to change)

Date | Content
------- | -------------
3/28 | Introduction. Defining the space. [Slides](Slides/Intro.pdf).
3/30 | **Technological challenges and opportunities**. Required: [Privacy and security with big data](Papers/garfinkel_gates_draft1.pdf), Simson Garfinkel, 2017; [Privacy protecting research: Challenges and opportunities](Papers/goroffpreliminary_privacy_draft_for_gates.pdf), Daniel Goroff and Jules Polonetsky, 2017.
4/4 | No lecture.
4/6 | **Guest lecture: Charlie Catlett**, Argonne National Laboratory. The Array of Things and opportunities and challenges in urban data.
4/11 | **Safe data enclaves and related topics**. Required: [Five safes: designing data access for research](http://www2.uwe.ac.uk/faculties/BBS/Documents/1601.pdf), Tanvi Desai, Felix Ritchie, Richard Welpton, 2016. (_[Notes](Content/fivesafes.md)_); Recommended: [NORC Data Enclave:Providing Secure Remote Access to Sensitive Microdata](http://ec.europa.eu/eurostat/documents/1001617/4398365/S02P1-NORC-DATA-ENCLAVE-SCHEUREN.ppt), Julia Lane et al., 2009; [Data Access in a Cyber World: Making Use of Cyberinfrastructure](https://pdfs.semanticscholar.org/ce88/76858c14560afd6d8bd3e8bcae8425d33cab.pdf), Julia Lane et al., 2008.
4/13 | TBD
4/18 | **Guest lecture (remote): Julia Lane**, New York University. Big data for public policy: The quadruple helix. Background reading: [P1](Papers/point-pam.21921.pdf), [P2](Papers/counterpoint-pam.21922.pdf), [P3](Papers/Jarmin_OHara_JPAM_CounterPoint_2016.pdf), [P4](Papers/Jarmin_OHara_JPAM_Point_2016.pdf), [P5](https://www.nap.edu/catalog/18614/proposed-revisions-to-the-common-rule-for-the-protection-of-human-subjects-in-the-behavioral-and-social-sciences).  
4/20 | TBD
4/25 | TBD
4/27 | TBD
5/2 | TBD
5/4 | **Guest lecturer: Simson Garfinkel**, NIST. Technical challenges in disclosure control.
5/9 | TBD
5/11 | TBD
5/16 | TBD
5/18 | **Guess lecture: Brett Goldstein**, University of Chicago. Responsible data mining.
5/23 | TBD
5/25 | TBD
5/30 | **Project presentations** for those graduating this quarter
6/1  | Reading period
6/6  | **Project presentations**
6/8  | **Project presentations**

To be scheduled: Bob Grossman, Matt Gee.

# Papers to be discussed (a work in progress)

## Overview 
- [New approaches to confidentiality protection](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.85.3083&rep=rep1&type=pdf), John Abowd, Julia Lane, 2004.
- [Privacy and confidentiality in the use of administrative and survey data](https://obamawhitehouse.archives.gov/sites/default/files/omb/mgmt-gpra/privacy_and_confidentiality_in_the_use_of_administrative_and_survey_data_0.pdf), 2016. (Report by OMB.)

## Safe data enclaves
- [NORC Data Enclave:Providing Secure Remote Access to Sensitive Microdata](http://ec.europa.eu/eurostat/documents/1001617/4398365/S02P1-NORC-DATA-ENCLAVE-SCHEUREN.ppt), Julia Lane et al., 2009. (Slides)
- [Data Access in a Cyber World: Making Use of Cyberinfrastructure](https://pdfs.semanticscholar.org/ce88/76858c14560afd6d8bd3e8bcae8425d33cab.pdf), Julia Lane et al., 2008.

## Anonymization and de-identification
- [How To Break Anonymity of the Netflix Prize Dataset](https://arxiv.org/abs/cs/0610105), Arvind Narayanan and Vitaly Shmatikov, 2006.
- [A systematic review of re-identification attacks on health data](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0028071), Emam et al., 2011.
- [Unique in the Crowd: The privacy bounds of human mobility](http://www.nature.com/articles/srep01376), Yves-Alexandre de Montjoye et al., 2013.
- [Unique in the shopping mall: On the reidentifiability of credit card metadata](https://dspace.mit.edu/openaccess-disseminate/1721.1/96321), Yves-Alexandre de Montjoye et al., 2014.
- [Not So Unique in the Crowd: a Simple and Effective Algorithm for Anonymizing Location Data](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.663.4441&rep=rep1&type=pdf), Yi Song et al., 2014. 

## Reidentification risks
- [The "Re-identification" of Governor William Weld's Medical Information: A Critical Re-examination of Health Data Identification Risks and Privacy Protections, Then and Now](https://fpf.org/wp-content/uploads/The-Re-identification-of-Governor-Welds-Medical-Information-Daniel-Barth-Jones.pdf), Daniel Barth-Jones, 2012. (_[Notes](Content/weld.md)_) 

## Statistical disclosure control ([Notes](Content/statistical_disclosure_control.md))
- [Statistical Disclosure Control for Survey Data](http://personal.lse.ac.uk/skinnecj/SDC%20for%20survey%20data%20S3RI.pdf), Chris Skinner, 2009.

## Secure multi-party computation
- [Multiparty Computation Goes Live](http://eprint.iacr.org/2008/068/20081028:111447), Peter Bogetoft et al., 2008.

## Computing on masked data
- [Computing on Masked Data: a High Performance Method for Improving Big Data Veracity](https://arxiv.org/pdf/1406.5751.pdf), Jeremy Kepner et al., 2014.
- [Computing on Masked Data to improve the Security of Big Data](https://arxiv.org/abs/1504.01287), Vijay Gadepally et al., 2015.

## Differential privacy
- [Privacy by the Numbers: A New Approach to Safeguarding Data](https://www.scientificamerican.com/article/privacy-by-the-numbers-a-new-approach-to-safeguarding-data/), Erica Klarreich, 2012.
- [A firm foundation for private data analysis](https://www.microsoft.com/en-us/research/publication/a-firm-foundation-for-private-data-analysis), Cynthia Dwork, 2011.
- [Privacy-Preserving Data Analysis for the Federal Statistical Agencies](https://arxiv.org/pdf/1701.00752.pdf), John Abowd et al., 2017.
- [The algorithmic foundations of differential privacy](http://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf), Cynthia Dwork and Aaron Roth, 2014.

## (Fully) homomorphic encryption
- [Technical Perspective: A First Glimpse of Cryptography's Holy Grail](http://cacm.acm.org/magazines/2010/3/76275-technical-perspective-a-first-glimpse-of-cryptographys-holy-grail/abstract), Daniele Micciancio, 2010.
- [Computing Arbitrary Functions of Encrypted Data](https://crypto.stanford.edu/craig/easy-fhe.pdf), Craig Gentry, 2010.
- [What is Homomorphic Encryption, and Why Should I Care?](https://community.embarcadero.com/blogs/entry/what-is-homomorphic-encryption-and-why-should-i-care-38566), Craig Stuntz, 2010.

## Residual information in documents
- [Leaking sensitive information in complex document files—and how to prevent it](https://simson.net/clips/academic/2014.IEEE.leaking_pdfs.pdf), Simson Garfinkel, 2014.

## Secure databases
- [CryptDB: Protecting Confidentiality with Encrypted Query Processing](http://web.cs.ucdavis.edu/~franklin/ecs228/2013/popa_etal_sosp_2011.pdf), Raluca Ada Popa et al., 2011.

## Responsible data
- [Data,  Responsibly:  Fairness,  Neutrality  and Transparency  in  Data  Analysis](https://hal.inria.fr/hal-01290695/document), Julia Stoyanovich et al., 2016. (3 pages)

## Other
- [Privacy: Theory meets Practice on the Map](https://lehd.ces.census.gov/doc/help/ICDE08_conference_0768.pdf), Ashwin Machanavajjhala et al., 2008.
- [Verifiable  Differential  Privacy](https://arifeldman.com/pub/VerDP-EuroSys15.pdf), Arjun Narayan et al., 2015.
- [Multiple imputation for statistical disclosure limitation](http://www2.stat.duke.edu/~jerry/Papers/jos03.pdf), TE Raghunathan et al., 2003.

# Class project

TBD.
