---
description: 23rd March 2026 to 29th March 2026
---

# Week 13

## Tuesday 24th March 2026

### Ambassador Town Hall

- **Type of meeting:** Weekly
- **Present:** PeterE [**facilitator**], NA [**documenter**], Alfred Itodele, Ayomi Shuga, kenichi, Peter, Tevo, CallyFromAuron
- **Purpose:** Regular weekly get-together for the Ambassador Program. Discussion of community-wide issues; sharing of updates and info; and in the last meeting of each month, an update from each Workgroup on what they have been doing
- **Town Hall Number:** 184
- **Working Docs:**


#### Timestamped video:
The Ambassador Town Hall is a recurring event happening live on the Ambassador Zoom channel https://www.youtube.com/@SNET_Ambassador each Tuesday at 18:00 UTC.

[00:00](undefined\&t=0s) Introductions & Administrative Updates
[01:25](undefined\&t=85s) Permissions & Escaping Lambs
[02:30](undefined\&t=150s) Meeting Recording And New Attendees
[05:37](undefined\&t=337s) Governance, Project Catalyst & Restructuring History
[12:00](undefined\&t=720s) Restructuring: Permanent Beta & Auditing
[16:15](undefined\&t=975s) Measuring Marketing Effectiveness & Metrics
[22:30](undefined\&t=1350s) Marketing Strategy & Project-driven Promotion
[35:00](undefined\&t=2100s) Audience Engagement & Local Outreach Vs. Online
[40:00](undefined\&t=2400s) Budget Constraints & Rewarding Contributions
[52:00](undefined\&t=3120s) Budget Distribution Models & Workgroup Structure
[01:06:45](undefined\&t=4005s) Oversight, Impact Measurement & "awareness Group" Proposal
[01:16:50](undefined\&t=4610s) Local Outreach: Project Vs. Awareness Group
[01:35:24](undefined\&t=5724s) Developer Focus & Awareness Group's Role
[02:16:30](undefined\&t=8190s) Next Steps: Proposal & Tools For Outreach

#### Town Hall Summary:
The meeting reviewed Ambassador Program logistics, quarterly reporting expectations, governance history, and marketing and analytics needs for outreach and developer recruitment. 

WGs should add their Q1 2026 mini reports to the Governance dashboard as soon as possible, but deadline will be after Easter.

Should the Ambassador program adopt a more action-research approach to assess the result of restructures and other changes?
 
Tracking tactics — include a question in Zoom registration, Zoom polls, UTM-style parameters, Bitly shortlinks, using the coordination manager page to measure clicks and conversions.

Marketing budget allocation: should projects produce and post their own publicity or should a central team do the posting, or even create the content? Should we consolidate Marketing, Writers, and Video WGs into a new WG. Kenichi arrived halfway through the meeting and argued for continued marketing activity; he will draft a concise proposal for this and add it to the GovWG restructure doc.  

Could include shifting funds from content production to local outreach and developer recruitment.

Different budget allocation models - project-style grants, retrospective funding tied to outcomes/impact, etc.

Tevo noted some issues with concurrency in the Coordination Manager, and bot work.


#### Keywords/tags:
- **topics covered:** Ambassador Program restructure, coordination manager, publicity, local outreach, developer onboarding
- **emotions:** long


## Wednesday 25th March 2026

### Archives Workgroup

- **Type of meeting:** Monthly
- **Present:** Stephen [QADAO] [**facilitator**], CallyFromAuron [**documenter**], CallyFromAuron, Stephen [QADAO], PeterE, Tevo
- **Purpose:** Regular meeting of the Archives WorkGroup in the SingularityNET Ambassador program
- **Meeting video:** [Link](https://www.youtube.com/playlist?list=PL4dGsCqdRj6ct6TwdrVKm_Bjg2ToCjzQh)
- **Working Docs:**
  - [GitHub Issue for this meeting](https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/292)

#### Decision Items:
- Knowledge graph development and prototyping a replacement Archives dashboard:

As discussed with the temporary "external fundraising" WG during Q4 2025, we were very hopeful of getting Catalyst Fund15 funding to take some of our graph drevelopment work further using Midnight (Cardano's rational privacy chain), with what we think was a very strong propoisal - see https://youtu.be/QM9_OR3pPew?si=K1DORI6bT4PtebmU .for an outline.  This would have supported what we wanted to do in the WG this Quarter, and would have meant that despite the Ambassador Program being unable to offer meaningful levels of funding for this kind of devlopment work, we still could have continued to progress. But, unexpectedly and very unfortunately, Project Catalyst announced in February that it was ceasing operations, right in the middle of Fund 15.

This has meant that we had to abandon the actual graph development work that we'd started in this Quarter, as there simply wasn't the funding to do anyhing meaningful. We have  instead focused on essential fixes to the existing summary tool, maintaining the Archive, forking the original dashboard and making some improvemenst to its documentation in readiness for further development if and when funding is ever available, and non-tech planning of the features a new meeting summary plaform would need, based on our experience of the last 2 years of the Archives.
  - [**effect**] affectsOnlyThisWorkgroup
- RE our RAG process development, we reiterated the point we discussed last meeting - that our overall technical approach to the setup of a RAG is in contrast to how people are approaching it elsewhere in sNET, and therefore might be a useful counterpoint, especially in relation to the appropriateness of the data-sampling. 

Elsewhere, the approach often used is to give entire corpora of data to a general, uncontextualised generative model; which will then probably make unwarranted assumptions about that data. Whereas our approach refines things so that we pre-query with SQL, creating a subsection of the data, and send only that to the generative model. This is more efficiant; and means not only do you understand the sources for an answer given by a RAG, but also the structure of the question itself. 

This approach could have been a useful lesson learnt on using RAG, but we simply haven't had the resources to develop the approach fully. We will still be looking for funding to pursue it at some point in the future, though it's probably out of scope for the Ambassador program.

  - [**effect**] mayAffectOtherPeople
- We re-emphasised the importance of sources - being able to identify where a RAG process is deriving its answers from - in terms of auditability and explainability. 

We had hoped to build a generative model that could be constrained by a query to a specific subset of data; and a user would be able to verify that the correct subset was used, which would make the results of a query much more auditable. 
  - [**effect**] mayAffectOtherPeople
- We noted that the structure of the existing Archives dashboard reflects how tech solutions tend to be developed in communities - quite ad-hoc, with iterative fixes and patches in response to user needs. This has its strengths, but can end up with a somewhat  convoluted back-end. We recognise that the summary tool needs some rationalising and tidying. 

The ideal in the long-term would be a modular tool, where different features can be put together to suit the community using it. After 2 years, we now have a good understanding of the requirement process for the different elements, and how they can be made modulat and composeable, so we could build recordkeeping tooling that could be usable across sNET, not just the Ambassador Program.

- In relation to our "rug-pulled" Catalyst Midnight proposal, we noted that writing it made us very conscious of the importance of data consent and privacy in a recordkeeping context where AI is being used. Not only informed consent about how data is used, and processed but also who has control of the submission of data, and who can access and conrol responses e.g. from a RAG query.
In traditional, commercial generative models (Claude, ChatGPT) a user is essentially giving the model all their data - and also, to an extent, it's possiblke to hack these ools so that your source data  may be accessible to other users.

So possibly, it is inappropriate ethically for a communiy organisation (such as the Ambassador program) to be using its data wih a commercial, general model such as ChatGPT.

A more appropriate and a more informed approach would be to use ZKP (zero-knowledge proof) to protect the community's data sources. Our Midnight proposal in Catalyst's Fund 15 was a proof-of-concept to show that it's possible to do this with a RAG process.

  - [**effect**] mayAffectOtherPeople
- As a side note, we mentioned how damaging the closure of Project Catalyst right in the middle of a Fund was.

Not only did it damage trust and confidence to completely suspend Project Catalyst just before the vote, when proposals had already been submitted and reviews conducted, it also meant that all the considerable resources that proposers had committed to developing proposals were effectively wasted.
  - [**effect**] mayAffectOtherPeople
- We noted the deleterious impact on the WG of the severe drops in token price over the past 15 months.

For over a year, core members of Archives WG have elected to wait and not submit tasks for payment, in the hope that price would rise eventually. We have not taken any payment for over a year, i.e. since Jan 2025. We believed for quite a long time that this was the right and responsible course of action.

However, we realised this Quarter that it was no longer tenable, as there was litle likelihood in the forseeable future of price rising even to the $0.20-ish levels of mid-2025. So we took the decision to use WG reserves to pay our outstanding tasks on the basis of a percentage of what we are each owed. See Issue here: https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/293.  This meant we received only around 25% overall of the agreed value of our work. This, coupled with the demise of Project Catalyst (a likely alternative source of funding to support our work) means we now cannot sustain our involvement, beyond a minimal "maintenance" approach to the Archive's tools and processes.

So, with sadness, this meeting marks the closure of Archives WG in its current incarnation. In Q2 and beyond, we hope to be able, as always, to maintain the Archives and ensure transparent documentaion of whatever initiatives the Ambvassador Program undertakes.

  - [**rationale**] Repeated drops in token price over the last 15 months.
  - [**effect**] mayAffectOtherPeople

#### Keywords/tags:
- **topics covered:** Knowledge Graph, Knowledge management across the singularityNET ecosystem, community data verification, Graph RAG, new Archives dashboard, SQL, generic tooling, rational privacy, Midnight, pre-query with SQL, Project Catalyst, Catalyst Fund 15, Catalyst Fund 15 rug-pull, token price, WG reserves, payments, underfunding, closure of Archives WG, budget sustainability, ZKP, zero-knowledge proof, ethics of sharing community data, ChatGPT
- **emotions:** sad, depressing, realistic