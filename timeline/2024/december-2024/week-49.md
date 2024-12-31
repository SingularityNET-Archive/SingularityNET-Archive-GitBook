---
description: Mon 2nd Dec - Sun 8th Dec 2024
---

# Week 49

## Wednesday 4th December 2024


### Archives Workgroup

- **Type of meeting:** Monthly
- **Present:** Stephen [QADAO] [**facilitator**], CallyFromAuron [**documenter**], André, CallyFromAuron, Stephen [QADAO], PeterE, AshleyDawn, Sucre n Spice, Onize
- **Purpose:** Regular monthly meeting of the Archives WorkGroup in the SingularityNET Ambassador program
- **Meeting video:** [Link](https://www.youtube.com/playlist?list=PL4dGsCqdRj6ct6TwdrVKm_Bjg2ToCjzQh)
- **Working Docs:**
  - [SNET Archive AI features (draft of possible features an AI tool might have)](https://docs.google.com/document/d/1LROsgVAQ9fQbNgMRK5qMI8q8KYsN-rGI-Gq9lvXAN5w/edit?usp=sharing)
  - [Docs management tool](https://snet-doc-manager.netlify.app/#)
  - [New Summary Tool Features](https://docs.google.com/document/d/1wxziaDEdMdYeiqv0ecuuygHgfd9a9F18odje_2qaT7g/edit?usp=sharing)
  - [Archives Dashboard ](https://archives-dashboard.netlify.app)
  - [Q1 2025 budget](https://docs.google.com/spreadsheets/d/14IYxBj-9MGCZRkYIupwvbHgPYZgohnyMSQ-EUFBgpYI/edit?usp=sharing)
  - [Q4 2024 quarterly report for Archives WG](https://docs.google.com/document/d/1XDezIhuovjDfsyAZ-kA97Ox_WOHphXDjS_nhlvoLkNo/edit?usp=sharing)
  - [Q1 budget consent results anonymized](https://docs.google.com/spreadsheets/d/1n83tAT9F9fO7sG3mbr3hcbJmTCrShhV024bXAa-aVA4/edit?usp=sharing)
  - [GitHub Issue for this meeting](https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/221)
  - [Archive names (a list of the name that people are most commonly known by in the Archives)](https://docs.google.com/spreadsheets/d/1r5LDA7yiERtWuu-HHYsBiG-RLyjDCtTZUB8H-xZHFsE/edit?usp=sharing)

#### Decision Items:
- André has implemented a controlled vocab for people's names in the Archives, based on Vani's "Archive Names" list https://docs.google.com/spreadsheets/d/1r5LDA7yiERtWuu-HHYsBiG-RLyjDCtTZUB8H-xZHFsE/edit?usp=sharing

He plans to write some code to enable us to go through old meeting summaries and corrrect any incorrect names (i.e. where someone has been recorded under a different name than the one that is usually used for them).

New names can be added when creating a meeting summary, but they will not be added to the controlled vocab until they have been approved in an Archives meeting. We will add a standing task on the Board for this, to ensure we check each meeting.

  - [**rationale**] To resolve a barrier to good documentation (documenters didn't always know what someone's Discord name was, so "Discord name = Archives name" was not working), and ensure people are discoverable in the Archives.
  - [**opposing**] none
  - [**effect**] mayAffectOtherPeople
- Q1 2025 Budget:
We noted that our Q1 2025 budget has been approved. We agreed that tasks that have been agreed for Q1 2025 will be added as Issues on our GutHub board.

We also noted that the new "budget cap" process has worked well - it seems to have speeded up the consent process, and also, by removing the need for budget fitting, it has removed the problems we noted in our last meeting (i.e. incentivising workgroups to submit higher budgets than they need, in anticipation of budget fitting).  

  - [**effect**] affectsOnlyThisWorkgroup
- We noted that in the end, we were unable to include in our Q1 2025 budget an item to support collaboration outside the Ambassador Program: it would have taken us over our budget cap, although we had identified a need for it. So we note that we should try to include it in Q2 2025.
  - [**rationale**] to enable us to capture material from other areas of the ecosystem, and have a more wide-ranging Archives that demonstrates the links and connections between the Ambassador Program and other areas of the ecosystem.
  - [**opposing**] None as such, although it might be difficult to do this comprehensively and still keep to a reasonable budget amount. It might be more about outreach to different parts of the ecosystem to see how we can support them with recordkeeping.
  - [**effect**] mayAffectOtherPeople
- We agreed that our first meeting in Jan will be Weds 8th Jan 2025
  - [**rationale**] Technically it should be the first Weds in Jan - but that's New Year's Day. Other meetings in Q1 *will* be the first Weds - so Weds 5th Feb and Weds 5th March.
  - [**opposing**] none
  - [**effect**] affectsOnlyThisWorkgroup
- There has been a shift in direction on our work on a RAG retrieval process, after Stephen reviewed Ubio's work (see https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/224 ). Stephen is aiming to structure the work as an autodidactic/self-learning approach, almost like a course. We have been questioning what we expect to use generative models *for*, and what we expect them to do; and looking at using (human) data analysis and data mining *before* we apply an LLM. Standard augmentation is usually about applying a **context** - so, what contextual constraints do we want to put on our use of a generative AI model in the context of the Archives? We need to be aware of where the data is structured and where it is unstructured (i.e. free text in meeting summaries), and look at how to structure data in a more constrained way (we note that JSON uses a "tree" structure, which has some parallels with the hierarchical structure of a traditional archival catalogue; and we can also see parallels with the approach of a knowledge graph database). Eventually we may use LLMs to help create semantic queries/prompts against an SQL database - so a hybrid of JSON/SQL rather than an actual knowledge graph.

This might also have implications for the redesign of the Summary Tool, in terms of how much of the data in a meeting summary is structured (and in what ways) and how much is free text. 

See also, updates in the relevant issues at https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/225 and https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/222 
  - [**rationale**] Stephen's work has shown that simply throwing large text corpora at a generative AI model tends to produce hallucinations and inaccuracies. 
  - [**effect**] affectsOnlyThisWorkgroup
- Summary tool redesign - in the light of Stephen's work above, we noted that in the new version of the Tool, rather than the current approach of several different summary templates, we might want all summaries to use the same template style as Treasury meetings, where actions and decisions are connected to each agenda item.

We discussed at length how to disambiguate summaries from summary detail, and constraining the "rambling" narratives which we see in some meeting summaries. 
  - [**rationale**] Aiming to minimise the amount of free text, and structure where free text is used.
  - [**effect**] mayAffectOtherPeople
- Summary tool redesign: possibility of linking/integrating summaries with GitHub pproject boards?
  - [**rationale**] because more and more WGs are starting to manage themselves via a GitHub Board, so the detail on an agenda item will be in the relevant Issue, and shouldn't need to be repeated in a summary - but how do we ensure that this is integrated and searchable in the Archives?
  - [**effect**] mayAffectOtherPeople
- André's tool development work for November https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/217 has included building the new Archives dashboard https://archives-dashboard.netlify.app

It is working, despite a couple of minor bugs.
  - [**rationale**] It enables searches, particularly of decisions - interesting in a governance context to see which WGs are making decisions that affect everyone, and where decisions across WGs might vary. Could help us keep abreast of when contradictory decisions are made in different meetings.
  - [**effect**] mayAffectOtherPeople
- We noted that Sucre has completed her update of the Ambassador GitBook for Q4 2024 - see https://snet-ambassadors.gitbook.io/home/welcome-and-how-to-join/our-workgroups 

She will update the relevant Issue https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/215, then it can be closed and paid.
  - [**effect**] affectsOnlyThisWorkgroup

#### Action Items:
- [**action**] Stephen presenting the "Open-source paradigm" work at a TH - this was done on 3rd December  https://youtu.be/iXsVeA5B7ao?si=_qW9xhC43TbapYxD [**assignee**] Stephen [QADAO] [**due**] 3 December 2024 [**status**] done
- [**action**] Vani to check through Budget issues from previous Quarters (such as https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/73 and https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/131), which we keep open until all issues that are costed in that quarter are closed, and ensure that they can be moved to "Done". [**assignee**] CallyFromAuron [**due**] 21 November 2024 [**status**] done
- [**action**] Vani to start a draft Quarterly Report for this Quarter, and post it in the Issue here https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/214 for comments [**assignee**] CallyFromAuron [**due**] 14 November 2024 [**status**] done
- [**action**] Vani to draft Q1 budget, and post in the Issue here https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/218 for comments and suggestions [**assignee**] CallyFromAuron [**due**] 14 November 2024 [**status**] done
- [**action**] Vani to approach DeepFunding, to ask about the issue raised in our November meeting about documentation of DF Town Hall: i.e. sometimes timestamps are not great, and additional work needs to be done to document the sessions in a meaningful way - could DF itself could make any further contribution to the work, e.g. by paying someone from the Town Hall team to add the documentation to the summary tool?

and discuss how the Archives dovetails with documentation that DF is doing itself, such as https://community.deepfunding.ai/ [**assignee**] CallyFromAuron [**due**] 8 January 2025 [**status**] todo
- [**action**] Vani to add the tasks in the Q1 2025 budget to the GitHub Board [**assignee**] CallyFromAuron [**due**] 8 January 2025 [**status**] todo
- [**action**] André or Sucre to update the Ambassador Calendar to add the correct dates of Archives WG meetings in Q1 2024 (8th Jan, 5th Feb, 5th March) [**assignee**] André, Sucre n Spice [**due**] 18 December 2024 [**status**] todo

#### Keywords/tags:
- **topics covered:** LLMs, LLM development, Q1 2025 budget, budget caps, meeting summary tool, RAG retrieval process, archive names, controlled vocabularies, Budget fitting, Collaboration, spin-offs, Knowledge management across the singularityNET ecosystem, archives dashboard, narratives, concise summaries, good meeting summaries, Governance, Decision Making Process, decision tracking, autodidact, self-learning, data mining, data analysis, generative AI models, data structure, archives cataloguing, JSON, SQL, structured and unstructured data, hallucination, fabrication, education, learning, open source, open source ethos, knowledge graph, summary template, github board, DeepFunding
- **emotions:** small, in-depth, Discursive, exploratory



### Research and Development Guild

- **Type of meeting:** Weekly
- **Present:** advanceameyaw [**facilitator**], LordKizzy [**documenter**], LordKizzy, AshleyDawn, advanceameyaw, CollyPride, guillermolucero, Slate, parthiv, PeterE
- **Purpose:** R&D Updates and Discussions 
- **Working Docs:**
  - [Research on Inclusivity for Individuals with Disabilities in SingularityNET Ecosystem](https://docs.google.com/document/d/1NFXUJ-yyXkXR4SBUzuG-KsQb3-5veaaiK1b4TWhTTHU/edit#heading=h.7160rr8iahel)
  - [Kenichi's proposal: LEGACY v0.1](https://docs.google.com/document/d/1Wt4bBpX8fFO19SnccoZUMC5EUhCThtg03G8CMR4BsYk/edit#heading=h.mh210wtijphs)
  - [Reputation System using SoulBound Tokens (SBTs) ](https://docs.google.com/document/d/1l0A8BFSe_RDvqDLHyJaIa1A92ggXwBBNUG2RtM8BIgo/edit#heading=h.gm1rgrhw4mb)
  - [Q3 Research & Development Guild Budget](https://docs.google.com/spreadsheets/d/1UojjDUZ8oG2X11gq7aBiEAwWuCfsnehDU1oVfviBnik/edit?usp=sharing)
  - [UPDATE R&D Guild Q2 Quarterly Report Response of Community Concerns ](https://docs.google.com/spreadsheets/d/1s73947FVd4qQ2PLrJySpITzQvDO4py2757pqoMeHBDI/edit?usp=sharing)
  - [Q2 Quarterly Report Update: R&D Guild   Response to Community Concerns ](https://docs.google.com/document/d/12PaXH1LhU0LW0p_T87G5KmmSEwgNTSEn6-Ei-sHxtkw/edit#heading=h.oc2atqqh7mud)
  - [LEGACY vs Web3 Contributor Dashboard](https://docs.google.com/document/d/10v3sUgdtRGkIU_a8K5roGA21-6xNzDLKEkImEiFdZdk/edit?usp=sharing)
  - [R&D Guild Q3 Operations Update ](https://docs.google.com/document/d/1AzG3_q3vOS0LoFXOjUrwyXu1OSv3qExPjiGYEYsaK44/edit?usp=sharing)
  - [R&D Guild Proposal Template](https://docs.google.com/document/d/14cl-X09nWY2RIDKcPWZv14-JbQqohovggJ0HOp6DKXk/edit)
  - [New Collaboration Skills Database Proposal](https://docs.google.com/document/d/130e1LR8zCaeIJrpO-12eAoHze19VUkJUZK6mYyyHOSs/edit)
  - [NON-DISCLOSURE AGREEMENT](https://docs.google.com/document/d/1RaCoXN3fhPwDxqhTTuefbOQLegAvQbCbUNE9GTg_NgM/edit)
  - [Retrospective and Learnings from Q4 R&D New Operations Systems](https://docs.google.com/document/d/1UzCa_pVjdCQ2WJkPXfNDa-4ic-YGjJQ-sH45gx4P_xg/edit?usp=sharing)
  - [Slides on the voting results ](https://docs.google.com/presentation/d/1M3o8dlh1pSB0PDaWM3sjlN2LQMaTjp8A_5DoXXXXIQE/edit?usp=sharing)

#### Agenda Items:
- Welcoming new members and Introduction
- Review of last meeting summary Action Items
- UPDATE STATUS ON DEVELOPMENT: EC-Entity-Connections, W3CD-Web3-Contributors-Dashboard, CSDB-Collaboration-Skills-Database, Social-Media-Dashboard, Reputation-System-using-SoulBound-Tokens-SBTs
- R&D New Metta Coder lab 

- Q1 Budget and Tier system
- Facilitation in Q1
- Open discussion
How to implement the potential outcome of AI SandBox & AI Think Tank in the R&D Guild in the next quarters.

#### Discussion Points:
- Review of last meeting summary Action Items: Advance went through the action items for the previous meeting and we had a brief introduction for new members
- UPDATE STATUS ON DEVELOPMENT: Teams are currently working async on their projects and will give an update at the end of the month
- R&D Guild Metta Coder Lab Initiative: The initiative is set to start in Q1 2025 and communications are still ongoing with the representatives from the Foundation.
- Follow up on the CSDB: AJ gave a presentation update on the Users' Data Consent  
- UPDATE STATUS ON DEVELOPMENT: Governance Dashboard, lordkizzy couldn't have a call with Guillermo due to his busy schedule but promised to host one in the coming week
- How to implement the potential outcome of AI SandBox & AI Think Tank in the R&D Guild in the next quarters: Lordkizzy shared his views on the the open discussion, he felt that there is a possibility for a collaboration between the R&D Guild, Education Guild, AI Sandbox/Think-tank and Marketing Guild, and he gave a scenario where tools being developed by the R&D Guild could be presented as a project showcase for AI Sandbox, then educational materials could be created on the tool by Education Guild and then these tools could be marketed by Marketing Guild.

#### Action Items:
- [**action**] CSDB team to finish and get ready for redeployment by 25th of NOV [**assignee**] AJ, Advanceameyaw [**due**] 11 December 2024 [**status**] todo
- [**action**] Lordkizzy and guillermo to have a call to discuss on the governance dashboard project [**assignee**] LordKizzy, guillermolucero [**due**] 11 December 2024 [**status**] todo
- [**action**] AJ to give a presentation on his updates to the CSDB project (Data privacy) in the next call [**assignee**] AJ [**due**] 11 December 2024 [**status**] todo
- [**action**] Members to express interest in the sheet for facilitation  [**assignee**] All members [**due**] 18 December 2024 [**status**] todo
- [**action**] Lordkizzy and Guillermo to schedule a call with the team to discuss the automation of core Contributors by Treasury guild [**assignee**] LordKizzy, guillermolucero [**due**] 11 December 2024 [**status**] todo

#### Keywords/tags:
- **topics covered:** Tool Development, AI tooling, Presentation, Operations, Workshop, Facilitation, CSDB, collaboration skills database, data privacy, privacy, Marketing Guild, Education Guild, AI Sandbox/Think Tank, collaboration
- **emotions:** Casual, speedy, Welcoming, Thoughtful, Friendly, Collaborative


## Thursday 5th December 2024

### Governance Workgroup

- **Type of meeting:** Weekly
- **Present:** PeterE [**facilitator**], CallyFromAuron [**documenter**], PeterE, CallyFromAuron, LadyTempestt, Duke, LordKizzy, Sucre n Spice, AshleyDawn, CollyPride
- **Purpose:** Weekly Open Governance session
- **Working Docs:**
  - [Governance calls, rolling agenda](https://docs.google.com/document/d/1t39dwlwLYYB_1z_5szq1rnOH7mVTHe8Tmwv0R6ELOyE/edit?usp=sharing)
  - [Ambassador Program Budget Planner](https://docs.google.com/spreadsheets/d/1BBogj9rAO52cpdGP3uvp8hAHNa4Qw66lz9JLjSC2yVs/edit?usp=sharing)
  - [A.I Sandbox/Think-tank Q4 Report](https://docs.google.com/document/d/1LEGDMIj7fmLvTsCy0rbvop5TMC-kZt-AYCZIlU4Cavw/edit?usp=sharing)
  - [Q1 Budget Consent Process - objections](https://docs.google.com/document/d/1RsIiorAun9Hkn9Dq26TMq1J5M7vkIPHHCuRnjVrqTk0/edit?usp=sharing)

#### Narrative:
AI Sandbox/Think-Tank is the only remaining Workgroup with unresolved objections to their budget.

We discussed the objections, and the responses that the workgroup has made in this doc https://docs.google.com/document/d/1RsIiorAun9Hkn9Dq26TMq1J5M7vkIPHHCuRnjVrqTk0/edit?usp=sharing.

The objectors were not present in the meeting, so the objections were discussed based on the information given in the consent forms. We noted that if those who object are not present, this means they must accept that the decision will be made by those who do attend.

Key points raised:
 - the comment (not an objection) about the group's GitHub Board not being under the Ambassador Program github organisation: accepted as a valid question, and the group will consider moving it; but as it's not an objection as such, it doesn't affect the budget decision.
 - the meeting could not see any similarity between what AI Sandbox does, and what R&D does, so could not understand the objection that the two groups are doing the same thing.
 - AI Sandbox's work *is* a form of community engagement and community contribution, so the objection that there is a lack of these things is inaccurate.
 - several of the objections seem to be based on a misunderstanding of what the group is trying to do - for example, it doesn't aim to focus on assessing tools built by the community, but on tools (often commercial tools) that might be used by the community.
- To the objection that AI developers and specialists should be invited to be involved in Sandbox sessions, LordKizzy (speaking on behalf of the workgroup) noted that although this would be good, it could incur costs beyond the group's budget. However, Peter offered to ask around at the Foundation to see if there are people who would be prepared to get involved for no cost.

The meeting also noted that several of the comments are not really objections, but suggestions. Since no specific harm was identified, and no solid reason not to approve the budget was given, these points are not valid as objections. The person suggesting these things should progress them, if they want to do so, by joining the workgroup and working on the issues they have raised.

Overall, the meeting agreed that the points raised have been sufficiently answered, so the group's budget has passed.




#### Discussion Points:
- Reaching agreement on AI Sandbox/Think Tank's Q1 2025 budget.

#### Decision Items:
- AI Sandbox/Think Tank's budget has passed
  - [**rationale**] Because the objections raised in the consent form are either not valid as objections, or have been adequately answered by the workgroup.
  - [**opposing**] None
  - [**effect**] mayAffectOtherPeople

#### Action Items:
- [**action**] Peter to ask around at the Foundation for specialists and developers who might be able to join Sandbox sessions, to fulfil the suggestion that "Absence of AI specialists, AGI developers, or credible panelists reduces the sandbox’s value". [**assignee**] PeterE [**due**] 14 January 2025 [**status**] todo
- [**action**] LordKizzy to look into the possibility of moving the group’s GitHub Board to the Ambassador Program github organisation [**assignee**] LordKizzy [**due**] 14 January 2025 [**status**] todo

#### Keywords/tags:
- **topics covered:** Decision Making Process, consent decision making, Q1 2025 budget, Q4 2024 quarterly report, AI Sandbox/Think Tank, validity of objections, experts, AI developers, SingularityNET Foundation, R&D guild, github board
- **emotions:** decisive, focused, thorough, calm
## Friday 6th December 2024

### Video Workgroup

- **Type of meeting:** Weekly
- **Present:** Malik [**facilitator**], Zalfred [**documenter**], SubZero, Zalfred, Rojo, hogantuso, AndrewBen, malik, LordKizzy, killy, devon, osmium, Slate
- **Purpose:** Weekly meeting of the Video WorkGroup. The meeting focused on weekly updates and tasks distribution.
#### Discussion Points:
- UPDATE FROM THE TASK MANAGER
A quick update from Tuso on various tasks assigned within the week.

- UPDATE FROM THE SOCIAL MEDIA MANAGER adding that he will be off for a few weeks. Offering a special training for qualified and interested persons who'd like to take up the task. 

#### Decision Items:
- Concerning the need for a temporary social media manager, Andrew Ben emerged as one who'd take up the task. 
  - [**opposing**] No oppositions as Andrew Ben is a senior member and qualified to take up the task.

#### Action Items:
- [**action**] SOCIAL MEDIA MANAGER [**assignee**] AndrewBen [**status**] todo
- [**action**] TASK MANAGER [**assignee**] Malik [**status**] todo
- [**action**] MEETING FACILITATION [**assignee**] Zalfred [**status**] todo
- [**action**] MEETING DOCUMENTATION [**assignee**] LordKizzy [**status**] todo
- [**action**] TOWN HALL VIDEO EDIT [**assignee**] devon [**status**] todo
- [**action**] TOWN HALL SUMMARY EDIT [**assignee**] hogantuso [**status**] todo
- [**action**] REVIEW TEAM [**assignee**] killy, SubZero [**status**] todo