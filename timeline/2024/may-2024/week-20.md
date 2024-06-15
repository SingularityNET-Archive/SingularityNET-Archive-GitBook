# Week 20

## Wednesday 15th May 2024

### Archives Workgroup

- Type of meeting: Biweekly
- Present: Stephen [facilitator], Stephen, Vanessa [documenter], Vanessa, Stephen, André, 5oundwave5, Photogee, Ekemini Samuel, Clement Umoh, esewilliams, osmium
- Meeting video: [Link](https://www.youtube.com/playlist?list=PL4dGsCqdRj6ct6TwdrVKm_Bjg2ToCjzQh)
- Working Docs:
  - [Q2 budget](https://docs.google.com/spreadsheets/d/1d9j-IPA0wary0EdR8YIoKl1BF0mAtkV_dgTs0hSnzAs/edit?usp=sharing)
  - [Draft AI ethics doc](https://docs.google.com/document/d/1MIItGDkPIBMA6x-_rvIaWvpRE_sKkkz9TdEhao_MVwM/edit?usp=sharing)
  - [Meeting Issue](https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/156)
  - [LLM development - Data loading and preprocessing](https://github.com/SingularityNET-Archive/LLM-Development/blob/main/Colab/Data_Loading_and_Preprocessing.ipynb)
  - [LLM development - Vector store creation and similarity search](https://github.com/SingularityNET-Archive/LLM-Development/blob/main/Colab/Vector_Store_Creation.ipynb)
  - [SNET Archive AI features (draft of possible features an AI tool might have)](https://docs.google.com/document/d/1LROsgVAQ9fQbNgMRK5qMI8q8KYsN-rGI-Gq9lvXAN5w/edit?usp=sharing)

#### Decision Items:
- Stephen showed April and May work on colab development.  
  - [rationale] Straightforward semantic searches are returning correct results, though it needs some refinement to get it into more human language; next step will be prompt creation.
  - [effect] mayAffectOtherPeople
- Open Source Strategy issue (see https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/139) contains a lot of different work elements, and will eventually need breaking up - although we're not quite ready to separate it out yet.
  - [rationale] Needs breaking up so we can track the discrete tasks that it comprises (for example, RAG retrieval process; development of AI Ethics strategy doc; sharing our approach to open source licencing; etc)
  - [opposing] but the issues are all quite interconnected, so it is useful to keep them together for a little while longer
  - [effect] affectsOnlyThisWorkgroup
- On open-source document management, Andre has identified how to work with text changes to a google doc, and how to extract resolved comments and update text changes to the doc in the repo itself
  - [rationale] Next steps will be identifying headings; and automating turning the text into markdown; ultimately to use it as part of the source material for an LLM to search.
  - [effect] affectsOnlyThisWorkgroup
- We clarified the distiction between Stephen's LLM work and Ubio's this quarter
  - [rationale] Stephen focusing on extraction and interpretation of data using natural language; Ubio looking at categorisation, tagging, sentiment analysis; and comparing/assessing different models.
  - [effect] affectsOnlyThisWorkgroup
- Meeting Summary tool development this month - cancelled or "no summary given" meetings are now saving properly to the database; an automation has been created to dump all the summarires into the repo; and a summary template for the new AI Ethics WG has been added
  - [effect] mayAffectOtherPeople
- The data dump of meeting summaries only includes links to any linked docs. A next step is to create some kind of document manager tool that will extract the text and create a dump of that too
  - [effect] affectsOnlyThisWorkgroup

#### Action Items:
- [action] Stephen to check why SucrenSpice doesn't seem to have permissions to merge changes on Ambassador GitBook - still can't work out why [assignee] Stephen [due] 15 May 2024 [status] done
- [action] Duke to create a video walkthru of how to use the GitHub Board, based on Stephen's training session - see https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/116 - done, and to be shared by next meeting [assignee] duke peter [due] 29 May 2024 [status] in progress
- [action] Sucre to add the Q1 quarterly report to Ambassador GitBook when ready [assignee] SucrenSpice [due] 29 May 2024 [status] in progress
- [action] Ese to find out if Writers WG are currently doing meeting summaries: yes, they are. CJFrankie is now documenting their meetings [assignee] esewilliams [due] 15 May 2024 [status] done
- [action] All to add comments to AI ethics doc async [assignee] all [due] 29 May 2024 [status] in progress
- [action] Vanessa to start writing guide on how to make a doc community-owned - i.e. a process for how to work with a doc to avoid stuff like deleting it, deleting comments, etc [assignee] Vanessa [due] 29 May 2024 [status] in progress
- [action] Vanessa to add issues to the GitHub Board for the new tasks we agreed to do this Quarter https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/119 [assignee] Vanessa [due] 15 May 2024 [status] done
- [action] Sucre, Clement and Lord_Kizzy to agree criteria for "good meeting summaries" bounty, and pick one winner from May summaries which they will share at next meeting on 29th - see this issue https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/152 [assignee] SucrenSpice, lord kizzy, Clement Umoh [due] 29 May 2024 [status] in progress
- [action] Andre to discuss with Ubio re Town Hall presentation on Ubio's work - would Ubio like to do it, or can he provide guidance to those interested? (Ekemini and Ese) See this issue https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/150 [assignee] André [due] 29 May 2024 [status] in progress

#### Keywords/tags:
- topics covered: AI tooling, open source, document management, github board, AI ethics, Ethics, ethics of AGI, Writers WorkGroup, Town Hall presentation, Meeting Summaries, good meeting summaries, LLMs, LLM development, vector store, data preprocessing, similarity search, semantic query, JSON index filtering
- emotions: positive, Friendly, forward-looking, educational

### Research and Development Guild

- Type of meeting: Weekly
- Present: Guillermo [facilitator], Onyeka  [documenter], Curtis, William, WaKa, Ubiodee, malik, Ayodele, Peter, Mikasa, Vasu, Daniel, Franklynstein
- Purpose: R&D Updates and Discussions 
- Working Docs:
  - [Project Feedback Proposal:  COLLABORATION SKILLS DATABASE _ 150224](https://docs.google.com/document/d/1a_q2yq1jrLSUiPzIfADZSsOcV3za7PBPY_XXsCg8AS0/edit)
  - [Final Guilds requested Budget](https://docs.google.com/spreadsheets/d/1gPUEAjXOp2DA9B5UDiPizKwBdaQAMY4k/edit#gid=612486399)
  - [Final - Quarterly Workgroup Budget Calculator / Guilds Final Fitted Budget ](https://docs.google.com/spreadsheets/d/1BBogj9rAO52cpdGP3uvp8hAHNa4Qw66lz9JLjSC2yVs/edit#gid=1788547254)
  - [Typeform link](https://fqmtepho6kd.typeform.com/to/uHsVjdS5)
  - [R&D _ Q1 DELIVERABLES](https://drive.google.com/drive/folders/1qy4P7bWmzFDWbNe03Do5HSV3FLOGYMnT?usp=sharing)
  - [Research & Development Guild Budget Proposals Sheet](https://docs.google.com/spreadsheets/d/1Cu2snGCH-9H4rviHFwcMD_qV-qRLjwFbO4eNjrWX6Hs/edit?usp=drive_link)
  - [R&D _ Q1 Quarterly Report ](https://docs.google.com/document/d/1ZFZr_OxtuQd2x21ZQQtFiaMipuYdj8MvuYFljWsRRZ8/edit?usp=drive_link)
  - [Decision making tool](https://citizenos.com/)
  - [Research on Inclusivity for Individuals with Disabilities in SingularityNET Ecosystem](https://docs.google.com/document/d/1NFXUJ-yyXkXR4SBUzuG-KsQb3-5veaaiK1b4TWhTTHU/edit#heading=h.7160rr8iahel)
  - [Copy R&D Onboarding New Member introduction _ Skills Database Template](https://docs.google.com/document/d/129rRooKK12qYoxpyJGZ-9mK0X1oCQDU5Uor9v6dkJco/edit?usp=sharing)

#### Agenda Items:
- Welcoming New Members and Introduction
- Review of last meeting summary Action Items
- Q2 budget concern response
- Operations Update:  Operations Structure and Procedures
- Onboarding of new members

#### Discussion Points:
- Discussions on R&D Guild Budget and Duke's proposal ( Research on Inclusivity for Individuals with Disabilities in SingularityNET Ecosystem.): this wont be included in our Q2 budget, due to an increase in proposals from workgroups and intergration of new workgroups
- Discussions on an introductory task for new members, Lordkizzy came up with a suggestion on creating a Debugging task for new members but some members didnt like the idea of an introductory task and the feeling that an AI can assist in passing those tasks
- Discussions on budget for R&D Workshops
- Discussions on project management on Github, CURTIS & WAKA expressed interest in helping on Github management 

#### Decision Items:
- We decided to adopt a longevity reputation system for new members to be able to create a project proposal rather than an onboarding test
  - [rationale] new members can collaborate with existing members on projects but might have to stay awhile and attend meetings before they can actually create project proposals
  - [opposing] some members felt they needed to be an introductory task for new members to show commitments. so that this will build trust among guild members in terms of funds allocation 
  - [effect] affectsOnlyThisWorkgroup

#### Action Items:
- [action] Guillermo to have a call with Ubio on providing assistance to the multilingual project by conecting them with Celestes team. Audio to text AI DF awarded Project [assignee] Guilermo [due] 22 May 2024 [status] in progress
- [action] Ubio, WaKa, Rojo to add their contributions to the R&D _ Q1 Proposal Report _ Template. [assignee] WaKa, Rojo [due] 22 May 2024 [status] todo
- [action] Kenichi to share his evaluation doc for the Writer's WG with the R&D Guild [assignee] Kenichi [due] 22 May 2024 [status] todo
- [action] Kenichi to create a basic explanatory document on his initiatives for the ambassador program website and present it in the next meeting  [assignee] Kenichi [due] 22 May 2024 [status] todo
- [action] The Guild should give back our responses on the concerns on our Q2 budget. [assignee] Guild members [due] 8 May 2024 [status] done
- [action] Kizzy, Duke & Ubiodee to attend the next treasury meeting to have discussions on Duke's proposal [assignee] lord kizzy, Duke, Ubiodee [due] 22 May 2024 [status] done
- [action] Billy to create a report about this guild, its operation and also the ecosystem at large [assignee] Billy [due] 22 May 2024 [status] todo
- [action] Guillermo to try and see how Vasu can collaborate with guild members on projects. [assignee] Guilermo [due] 22 May 2024 [status] todo

#### Keywords/tags:
- topics covered: Guilds , Tool Development, Proposal, AI tooling, API, deliverables, Meeting Summaries, Budget Request, Q2 budget, Social media Dashboard, social media, agenda creation, GitHub, Workshop, Introductory task
- emotions: Collaborative, productive, Thoughtful , speedy , Welcoming, Session items reviewing moved slowly as we had disagreements in many items and required discussions

### Education Workgroup

- Type of meeting: Weekly
- Present: Slate [facilitator], Slate [documenter], Slate, Clement Umoh, Photogee, osmium, WaKa, Billy, esewilliams, malik, hogantuso, Kenichi, Mikasa
- Purpose: - ACP Implementation Discussion - ACP Blueprint discussion - What is ACP (Kenichi' Questions)  - Education Guild Blueprint 
- Working Docs:
  - [List of Ambassador Program DeepFunding proposals ](https://docs.google.com/spreadsheets/d/1jrOKJK2BrrS4Z5vLNyQqTxgJpt85ny0YsQ2kCuzPCog)

#### In this meeting we discussed:
- ACP Implementation discussion
- ACP Blueprint discussion 
- What is ACP (Kenichi's questions) 
- Education Guild Blueprint 
- WaKa's collective doc for Ambassador Program individuals proposals in deepfunding round 4

#### Discussion Points:
- Slate started the meeting welcoming everybody 
- Then he highlighted the agenda for today's meeting 
- Waka mentioned his doc in which he is collecting information regarding Deepfunding Round 4 proposals from people in the Ambassador Program 
- Osmium that he is iterating/ creating a blueprint regarding Education Guild and also working to rework the ACP old blueprint doc  
- Kenichi had multiple queries regarding ACP as he was not able to attend meetings for education guild for quite some time - those queries were answered by Slate and Osmium respectively 
- Slate mentioned that we will  be needing a process for implementing ACP on Google Classroom which will most probably be discussed next week 

#### Decision Items:
- ACP and Education Guild Blueprint 
  - [effect] affectsOnlyThisWorkgroup

#### Action Items:
- [action] Osmium for setting up ACP and Education Guild Blueprint for transparency and clarity  [assignee] osmium [due] 29 May 2024 [status] in progress
- [action] Google Classroom process implementation  [assignee] Slate [due] 29 May 2024 [status] in progress

#### Keywords/tags:
- topics covered: ACP, Google Classroom, processes, Blueprints 
- emotions: productive,  Collaborative, Businesslike., speedy

### Knowledge Base Workgroup

- Type of meeting: Biweekly
- Present: Tevo [facilitator], Tevo [documenter], Tevo, Olokoji, lord kizzy, André, Photogee, osmium, Ayo, esewilliams, Peter, Effiom
- Purpose: Aggregating Ambassador Program assets and relevant information under GitBook
- Miro board: [Link](https://miro.com/app/board/uXjVN-9yivE=/?share_link_id=819033103692)
- Other media: [Link](https://app.dework.xyz/singularitynet-ambas/process-guild)
- Working Docs:
  - [Knowledge Base WG](https://docs.google.com/document/d/1Lb9DwNSzmToyMhl5qZG9QEFipH9ZmlnDNaVU1jYeqFc/edit?usp=sharing)

#### Agenda item 1 - Onboarding Feedback Form - [resolved]

#### Discussion Points:
- How much reward should we provide to feedback givers?
- What are the requirements to get rewarded?
- How do we check requirements?

#### Decision Items:
- We reward 10$ in AGIX per person for filling out the feedback form and passing the group consensus
  - [effect] affectsOnlyThisWorkgroup
- We check Feedback forms monthly in a Workgroup Meeting
  - [effect] affectsOnlyThisWorkgroup

#### Action Items:
- [action] Reward the eligible people who for feedback [assignee] Tevo [status] todo

#### Agenda item 2 - Review Organized and Reviewed Items - [carry over]

#### Discussion Points:
- Reviewing: SingularityNET - Blog Website https://medium.com/@singularitynetambassadors
- Reviewing: SingularityNET Ambassadors - Medium Page https://medium.com/singularitynet
- It is easy to fall into the trap of using articles as content that we organize instead of the purpose of the platform
- Often times, these 2 items we reviewed overlapped with their reasons of relations to category questions

#### Decision Items:
- We removed the items from several organized positions and found categories where the item was missing
  - [effect] affectsOnlyThisWorkgroup

#### Action Items:
- [action] Re-review two items again with 2 additional person [status] todo
- [action] Review 1 new item added to the Organizing Resources Window Process Kanban board. [status] todo

#### Agenda item 3 - Retrospective on Async results - [carry over]

#### Discussion Points:
- Did we achieve a high Quality of Async work?

#### Decision Items:
- Change process to include 2 reviews per item, 1 review from a new or existing member and 1 review from a person whose organizing results have provided the best accuracy
  - [effect] affectsOnlyThisWorkgroup
- Create a veteran organizer role
  - [effect] affectsOnlyThisWorkgroup

#### Action Items:
- [action] In the next session we review the new method async results [due] 30 May 2024 [status] todo

#### Keywords/tags:
- topics covered: async, veteran organizer role, reviews, categorisation, Rewards, Onboarding, Feedback Form
## Thursday 16th May 2024


### Treasury Guild

- Type of meeting: Biweekly
- Present: Tevo [facilitator], Tevo [documenter], Tevo, Peter, kateri, vani, Duke, Photogee, lord kizzy, Effiom, Ayo, rob b, Sound Wave, Guillermo, Kenichi
- Purpose: Structuring Ambassador rules around payments, tasks and anything related to financial activities
- Miro board: [Link](https://miro.com/app/board/uXjVN8kUlbw=/?moveToWidget=3458764584775426018&cot=10)
- Other media: [Link](https://app.dework.xyz/singularitynet-ambas/treasury-guild-87240?taskId=83aeda8d-2434-42f9-9f48-be1345c9f8e6)
- Working Docs:
  - [Treasury Guild Dework Space](https://app.dework.xyz/singularitynet-ambas/treasury-guild-87240)
  - [Treasury Quaterly Budget Calculator](https://docs.google.com/spreadsheets/d/1BBogj9rAO52cpdGP3uvp8hAHNa4Qw66lz9JLjSC2yVs/edit?usp=sharing)
  - [Context-setting doc for Q2 budgets decision](https://docs.google.com/document/d/115c9r867HDV711v7cgu-thL6chfUHtK6Fhu6qVwA6es/edit?usp=sharing)
  - [Core Contributors list](https://docs.google.com/document/d/13uPKVnooFowpoxRBZJH71iIbHUyoOokdn_RCDvp_RHI/edit#heading=h.ij3cuj7d158h)
  - [Treasury Guild Proposal](https://docs.google.com/document/d/19k06OQEXJe0nYSrVVRLw1t_3BXSnUcXwsmLV9Tp07C4/edit?usp=sharing)

#### Agenda item 1 - Ambassador Program workgroups, budget plans and projects in Quarter 2 - [carry over]

#### Discussion Points:
- What are the next steps for proposals that did not get their budget request approved?
- New consent Forms
- Improvements for the consent process
- Consent form results

#### Decision Items:
- In the future, blockers after the deadline will not affect the results.
  - [effect] mayAffectOtherPeople
- We will no longer ask people to opt in.
  - [effect] mayAffectOtherPeople

#### Action Items:
- [action] Update the Consent Form to include space for amendments. [status] todo
- [action] Create a new Consent Form for the Marketing Guild. [status] todo
- [action] Create a new Consent Form for Writers WG. [status] todo
- [action] Update Core Contributor roles. [status] todo
- [action] Provide insight about opting out from the Core Contributor role every time Core contributors are called for consenting on the proposal. [status] todo

#### Agenda item 2 - Treasury Guild and its workgroups - [carry over]

#### Discussion Points:
- Shared general overview of Treasury Guild and its workgroups
- Who is interested in facilitating future Treasury Guild Sessions?
- How should the Treasury Guild continue facilitating?
- How have the sessions been facilitated so far?

#### Action Items:
- [action] Have an additional meeting about Treasury Guild facilitation. [status] todo
- [action] Update Treasury Guild Session time based on the new scheduling insight provided by when2Meet https://www.when2meet.com/?24905342-e8Hvc (same link for policy WG) [status] todo
- [action] Update Treasury Policy WG Session time based on the new scheduling insight provided by when2Meet [status] todo

#### Agenda item 3 - R&D Guild Proposal budget changes on the last minute - [carry over]

#### Discussion Points:
- The wrong budget may have been consented to on the consent forms. We cannot tell if people were looking at and consenting to the total given in the Budget Calculator google sheet, or the updated total in the Guild's actual budget, which included Duke Peter's proposal for a project looking at barriers due to disability.

#### Decision Items:
- It was mistakenly recorded in the meeting summary video that we had agreed not to update the budget to the new total that was submitted just before the deadline. But in fact, the meeting agreed to raise this issue for further discussion in a future meeting.
  - [rationale] R&D's budget was updated before the deadline, and the majority felt that the updated version is what people are likely to have been looking at, so the additional budget item should stand.
  - [opposing]  Some felt that people might have been consenting to the older total given in the Budget Calculator, which was lower
  - [effect] mayAffectOtherPeople

#### Action Items:
- [action] this issue will be discussed in a future meeting [assignee] all [due] 30 May 2024 [status] todo

#### Keywords/tags:
- topics covered: R&D guild, Q2 budget, Q2 budget decision process, Decision Making Process, consent decision making, Facilitation, scheduling, meeting time, deadlines, core contributors, Opt-in or opt-out
- emotions: muddled, interesting, unclear

### Onboarding Workgroup

- Type of meeting: Weekly
- Present: LadyTempestt [facilitator], lord kizzy [documenter], Clement Umoh, cjfrankie, SucrenSpice, Vanessa, Peter, lord kizzy, duke peter, daniel effiom, hogantuso, CollyPride, Gorga Siagian, LadyTempestt
- Purpose: Instead of the usual weekly workgroup meeting, this was an Onboarding Q&A session aimed at new people
- Working Docs:
  - [Onboarding session 16th May video](https://drive.google.com/file/d/17LMF1KmGhWYn77kBipzvor2HaVyMLhnN/view?usp=sharing)
  - [Onboarding slides video](https://youtu.be/ceOAl7ObJVU?si=KSWOnZRbH99aq_fr)
  - [Onboarding Sessions survey](https://docs.google.com/forms/d/e/1FAIpQLSdq9FMJ7-kmh2ElWglAjPHZko5Ra7DjixeW8yHjZSNFgJ0hoA/viewform)

#### In this meeting we discussed:
- Today's workgroup meeting was replaced by an Onboarding Session aimed at new people. We presented a video on how to join SingularityNET's ambassador program, and a walkthrough of the sNET Discord, follwed by a Q&A session.
- Q&A Session and suggestions: we noted that not many new people were in attendance and discussed how to rememdy it. Clement suggested that we ask leads of other WGs to advise new members to join one of these onboarding sessions to help them onboard.
- Tuso and Gorga suggested the creation of bots to welcome new members into program and guide them to e.g. the Getting Started channel
- LadyTempestt suggested that onboarding WG members could attend different Workgroups' meetings to  invite members to our onboarding sessions
- Vani suggested that we could post in the introductions channel to encourage people that are interested in the ambassador program
- We discussed whether we actually need onboarding sessions as such, if new people are not attending? We noted that perhaps the timing of this session was the problem, as it hasn't coincided with a big influx of new people.
- We discussed which Discord channels newcomers tend to use - Introductions? Ambassador-General? or just the channel for the WGs they are interested in?
- We discussed idea of colour-coding people's names on Discord to show their roles: but we noted that most people are part of many groups and have many roles , so it wouldn't really work, and our current WG tags already serve this function
- A hierarchy or system of levels in Discord was suggested, but several people questioned how this would be valid given our non-hierarchical ecosystem. Also questioned how someone's "level" would be determined (manually, and if so, by whom? or automated?) and on what basis (Time? Number of posts? A combination?) 
- We discussed how well we "spot" new people in Discord. We noted that there is a green leaf "I'm new" symbol next to people's names, but it seems not everyone can see it. There is also a welcome channel, but not everyone can see it - it might be best for it to remain restricted, but should any Onboarding members have access to it? 
- We also noted that if a new person posts to say hi, we welcome them - but if they don't - perhaps by being too shy - we can easily miss them
- LadyTempestt shared a link to our survey about these Onboarding sessions, and invited everyone to complete it by 31st May.

#### Decision Items:
- We decided to bring up the points from this discussion in our next Onboarding meeting on 23rd May
  - [rationale] because we didn't have time in this session to finish discussing them; plus, they need discussion in the context of the WG's overall work and planning
  - [effect] affectsOnlyThisWorkgroup

#### To carry over for next meeting:
- Getting Started discord channel
- Discussions on Outreach to new members

#### Keywords/tags:
- topics covered: survey , Onboarding sessions, Outreach, Onboarding, Discord walkthrough, Discord, Bots
- emotions: informative, interesting, Collaborative, Thoughtful 


## Friday 17th May 2024

### Video Workgroup

- Type of meeting: Weekly
- Present: Zalfred [facilitator], killy [documenter], lord kizzy, martinsoki, malik, osmium, Billy, DS9, Slate
- Purpose: Weekly updates
#### Discussion Points:
- More updates on the Zealy platform.
- Lord kizzy, as the task manager, provided weekly task updates.
- Slate as our social mdeia manager gave weekly updates on our socials.
- Discussion on new idea from DS9 on using models to promote our engagement.
- Discussion on lord kizzy's opinion on devising a means to allocate funds for these people.

#### Decision Items:
- the video workgroup decided that DS9 is to write a short proposal and present it to the Workgroup
  - [rationale] DS9's idea should be processed to avoid complication with other workgroups
  - [effect] mayAffectOtherPeople

#### Action Items:
- [action] Task Management/ tag the task payments, either it is a monthly or weekly payment [assignee] lord kizzy [due] 24 May 2024 [status] in progress
- [action] facilitator to give monthly updates [assignee] Zalfred [due] 24 May 2024 [status] todo
- [action] social manager, task manager and town hall editor to reach out to Peter to get admin access to the Zealy sprint [assignee] Slate, lord kizzy, malik [due] 10 June 2024 [status] done
- [action] DS9 is to tender a proposal concerning his idea and get back to us  [assignee] DS9 [due] 24 May 2024 [status] todo

#### Keywords/tags:
- topics covered: social media management, new people, videomaking, engagement, models, fund allocation
- emotions: Friendly, Casual, positive, speedy
## Saturday 18th May 2024

### Gamers Guild

- Type of meeting: Biweekly
- Present: Slate [facilitator], devon [documenter], malik, rebel, hufiumer69, lord kizzy, Gorga Siagian, 5oundwave5, flyn, Dr Strange, Tevo
- Purpose: Workgroup creation updates and progress 
- Working Docs:
  - [Quarterly Report ](https://docs.google.com/document/d/10E9GCj7RoHwRSQk8hT7bbxOD1trYh_EdIL-bAlPFXiQ/edit?usp=sharing)

#### Discussion Points:
- Slate outlined the meeting agenda
- Updates on the creation of workgroups was discussed.
- Discussion on video workgroup model  and how it should be improved?
- Discussion on APIs and the importance of integrating them into the model.
- Discussion on game passes and whether they should be added?
- What currency would be used to buy game passes?

#### Decision Items:
-  to adjust video display based on user preferences.

#### Action Items:
- [action] 5oundwaves to research on APIs [assignee] 5oundwave5 [status] todo

#### Game Rules:
Racing Game
The first to complete all 3 laps wins.


#### Leaderboard:
- 1st Rebel

#### Keywords/tags:
- topics covered: Rewards, Roblox, participation, metaverse
- emotions: Friendly, Collaborative, engaging new people, Thoughtful 
- games played: Racing Game