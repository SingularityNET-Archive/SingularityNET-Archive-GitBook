---
description: Mon 13th Oct - Sun 19th Oct 2025
---

# Week 42

## Wednesday 15th October 2025

### Archives Workgroup

- **Type of meeting:** Monthly
- **Present:** Stephen [QADAO] [**facilitator**], CallyFromAuron [**documenter**], CallyFromAuron, Stephen [QADAO], Alfred Itodele, omolola lawson, Tevo, AshleyDawn
- **Purpose:** Regular monthly meeting of the Archives WorkGroup in the SingularityNET Ambassador program
- **Meeting video:** [Link](https://www.youtube.com/playlist?list=PL4dGsCqdRj6ct6TwdrVKm_Bjg2ToCjzQh)
- **Working Docs:**
  - [Q3 2025 quarterly report](https://docs.google.com/document/d/1mXpk-Nx68M9Yfoqc3xpquXwA2Zy6zdIpGFSlCiWU7-k/edit?usp=sharing)
  - [Q4 2025 budget](https://docs.google.com/spreadsheets/d/14IYxBj-9MGCZRkYIupwvbHgPYZgohnyMSQ-EUFBgpYI/edit?usp=sharing#gid=1427269861)
  - [GitHub Issue for this meeting](https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/281)
  - [Ambassador Program example voluntary volunteer "Invisible work"](https://docs.google.com/spreadsheets/d/1MD6V9PbW-h7OwqEj3kdVgf27RaQfr4G6v4gH67Ya2io/edit?usp=sharing)

#### Decision Items:
- Token price remains very low, so we still won't submit any pending tasks for payment at the moment. if price has not risen to a reasonable level by the end of the Quarter, we will consider paying all those who are owed a percentage of the total reserves proportional to the amount they are owed.
  - [**effect**] affectsOnlyThisWorkgroup
- Monthly archives GitBook issues: summaries are still being submitted, although there are fewer coming in than there should be. We are not chasing them 

Summary quality remains problematic, and we note that despite our "experiment" with unaudited summaries, it will probably be difficult to trace / identify the source of a problem if we notice that our knowledge graph is returning information that is inaccurate because of inadequte summaries.

Core problem is vague summaries that waffle on with pointless, adjective-heavy  "story-like" detail, but fail to capture actual decisions (e.g. "A hugelky important and transformative decision was made about XYZ" without specifying what the decision was). This could perhaps be addressed in the summary tool redesign next year - removing "narrative" field and asking only for decisions, aqnd generally, much less unstructured data/free text?

We raised the possibility of closing the corpus rather than filling it with poor-quality material. We have not reached this stage yet, but it is a possibility.
  - [**rationale**] The poor quality is largely caused by documenters relying uncritically on unmediated AI-generated content, which is usually vague and unspecific because AI summary tools don't know our context; and documenters not applying sufficient "human-in-the-loop" critical insight to correct and expand AI summaries. As we do not have budget for quality control, and documenters do not seem to mind the ethical problems with uncritical use of AI-generated material, perhaps closing the corpus would be abetter approach than having an Archives full of nonsense. 
  - [**opposing**] Poor summary quality is being addressed, to some extent, outside of Archives WG (e.g. Vani checks and corrects summaries in WGs she is active in when they are presented for members' comments, and she also attempts to mentor and support documenters), but this is both time-consuming and limited in reach, and also unpaid. We noted that other measures might need to be implemented eventually (e.g proper training for documenters? Pushing the idea that it is unethical to use AI-generated material without having some oversight of it?)

  - [**effect**] mayAffectOtherPeople
- Knowledge graph development: see https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/282 and the repo here https://github.com/SingularityNET-Archive/Graph-Python-scripts 

Key focuses so far this month:
- 1) how we work with structured data, as opposed to unstructured
- 2) creating different sections in the repo for graph analysis (e.g. graph structures such as centrality, clustering, degree analysis, etc) and data analysis (what is the structure of the data?)
- 3) making the repo more user-friendly - e.g. a map of the repo and where data is coming from. Python users can create virtual environments and run scripts.
  - [**effect**] mayAffectOtherPeople
- We discussed the differences between data analysis (questions such as "where is the data coming from?") and graph analysis (use of graph structures such as centrality, clustering, degree analysis, path analysis)

Can create separate reports for each of these, and a unified report. Reports are linked to live data dumps, and will be automatically updated as more data is added.

Noted that some of the things that graph analysis will show us are purely the result of the design of the meeting summary template that is being used; but some is more substantive.
  - [**effect**] mayAffectOtherPeople
- We began to look at how we understand what graph data shows - what does it tell us? For example, co-attendance and degree: people are connected if they attend the same meeting, so how many people is a person connected with in that way? 

And - we know there can be a difference between simple meeting attendance and meaningful participation? (e.g. if someone is present but not participating) - but do co-attendance and degree give more subtle data on this?

We suggested that there should be an Archives meeting at some point to engage a group of people with analysing what this graph data is telling us, and saying what we think it means
  - [**rationale**] To compare the graph data with our lived experience of being in the Ambassador program; to start people thinking on what it means; and begin to develop some kind of community verification process for the graph analysis; also to ask the community what data is important, and start to develop some kind of weighting system
  - [**effect**] mayAffectOtherPeople
- We noted that what is shown in the graph data mostly parallels the info we can see in Treasury data and in calculations of who is a Core Contributor - the same people emerge as most engaged and active.

Could we use a combination of which person, which WG, number and type of action items assigned to someone, and their involvement in decision items to demonstrate participation or engagement?

  - [**rationale**] Possibly, could form part of a sentiment analysis

Also, might lead to some kind of weighting of what is important, which could eventually help in the design of reputation or conntribution weighting; 

or an ethical process/procedure for how to consult a community on weighting the info in a graph?
  - [**effect**] mayAffectOtherPeople
- We discussed other ways of analysing engagement, influence, participation, and/or contribution, either by individuals or by WGs. For instance:

- DOCUMENTS: How many docs does a WG link in their summaries? Who authored them - someone from that WG, or another WG? Are they open to edits? How many edits have been made? (tracking the spread of an idea across WGs, and how open to input the originators are)

- VOLUNTARY vs PAID WORK: (of course, requires ways of tracking volunteer work - Governance WG has been discussing this, e.g. logging it in a spreadsheet and then via Dework - see sample log here https://docs.google.com/spreadsheets/d/1MD6V9PbW-h7OwqEj3kdVgf27RaQfr4G6v4gH67Ya2io/edit?usp=sharing; logging who speaks in a meeting, audio or in Chat; weekly nominations process for who has contributed something you found useful that week; etc)

DECISIONS: how WGs and people are connected to decisions and decision-making. Who's contributing, whose thinking is being heard, are different WGs making decisions on similar topics and are they influenced by each other, etc

TAGS: looking at where similar topic tags are seen across different WGs

MEETING OUTCOMES: How do we track what comes out of meetings? Sometimes, it's actual decisions - but not always. And sometimes it's a decision that has little impact on the Program long term, or isn't really implemented
  - [**rationale**] how would all this kind of data - some of which is captured outside of meeting summaries - become part of a knowledge graph?
  - [**effect**] affectsOnlyThisWorkgroup
- We noted that Stephen delivered a successful session on Thurs 25 Sept at AI Sandbox/Think Tank to share the knowledge graph work so far.
See recording https://youtu.be/ByNe06ShpAw?si=OuuO3dMmm1rz4dVP 

- Archives WG's Q3 quarterly report and Q4 budget were approved with no objections

We note also that for Q1 2026, there will be no formal budget consent process, and just minimal reporting required on this Quarter's activities. So we will not need to write a Q1 2026 budget as such, but can decide in January how to spend budget cap, and will just need to report on our work at the end of Q1 (March 2026)
  - [**rationale**] This has been done due to low token price and to minimise the overhead associated with the consent process
  - [**effect**] affectsOnlyThisWorkgroup

#### Action Items:
- [**action**] Vani to publicise the information session at AI Sandbox/Think Tank next Thurs, 25th Sept [**assignee**] CallyFromAuron [**due**] 19 September 2025 [**status**] done
- [**action**] Vani to draft and submit minimal report for this Quarter's work [**assignee**] CallyFromAuron [**due**] 8 December 2025 [**status**] todo

#### Keywords/tags:
- **topics covered:** AI ethics, token price, open source tooling, Knowledge Graph, Knowledge management across the singularityNET ecosystem, Open source, meeting summary quality, structured vs unstructured data, semantic analysis, sentiment analysis, data analysis vs graph analysis, community data verification, Engagement and Reputation Systems, contribution, Participation, Graph RAG, AI Sandbox/Think Tank, documents in meeting summaries, topic tags, decision tracking, weighting, centrality, clustering, path analysis, degree analysis
- **emotions:** interesting, wide-ranging, Discursive, analytical, expansive


## Thursday 16th October 2025


### Governance Workgroup

- **Type of meeting:** Weekly
- **Present:** PeterE, CallyFromAuron [**facilitator**], CallyFromAuron [**documenter**], PeterE, CallyFromAuron, omolola lawson, Alfred Itodele, UKnowZork, AshleyDawn, Kateri, maxmilez, rems, ayomi shuga
- **Purpose:** Weekly Open Governance session
- **Working Docs:**
  - [GovWG governance workgroup facilitation and documentation rota](https://docs.google.com/spreadsheets/d/1iW2KbVOSbMurQo0zczWcb7Z8FIvVFc4zJLQH28reYgE/edit?usp=sharing)
  - [Governance calls, rolling agenda](https://docs.google.com/document/d/1t39dwlwLYYB_1z_5szq1rnOH7mVTHe8Tmwv0R6ELOyE/edit?usp=sharing)

#### Narrative:
The first of 2 sessions about holding WGs accountable beyond just the budget consent process.

WORK QUALITY
We noted that despite having discussed work quality several times, we still have not established an *ongoing* process for 
a) assessing it and
b) dealing with perceieved problems with it.

We do have the ad-hoc approach of running sentiment surveys to gather opinions about it; but as yet, the only action that has been taken on the basis of these is to adjust budget caps, which does not really address work quality.

We noted that there probably needs to be a public, Program-wide discussion on what is meant by "good / bad quality work". On this, 
- 1) we had some discussion on whether or not it is even quantifiable;
- 2) we agreed that it should be evidence-based as far as possible (i.e. we should ask people to back their opinions up with evidence)
- 3) perhaps requiring or recommending a Theory of Change from each WG would help them to define for themselves what "good quality work" means for them, and then the Program counld hold them accountable to that? 
- 4) Maybe this ("what is good-quality work?") would be a good Town Hall topic.
- 5) Whereas in the past there was a broad agreement that "work quality" discussions should be decoupled from budget decisions, the feeling of this meeting was that this is no longer the case, and that if a WG is producing bad quality work, it **should** affect their budget.


ACCOUNTABILITY
In the rolling agenda doc, there has been a suggestion of having a range of of possible processes to hold WGs accountable - e.g. 
- using sentiment analysis to decide if a WG should be stopped;
- probationary periods, and/or a process for giving a WG a warning and a time period in which to fix a particular expectation that needs to be met or it ceases to exist next quarter
- possible overall restructure of the whole Program to address issues raised

We agreed that the measures taken would need to be decided on a WG-by-WG basis, tailored to the specific issues that have been identified for that WG.
We discussed how this could be done, and concluded that using one of the WGs' own meetings for the discussion would wrk best, rather then trying to cover each WG in Givernance meetings in Q1 2026.

We agreed it would probably be unfair to end a WG on the basis of a sentiment survey alone, and that input from past consent processes should also be used

We suggested there could be a set of ground rules for minimum expectations for WGs, and any underperforming WGs should be given a chance to improve before being stopped.


SENTIMENT SURVEY v.3
Most of those in the meeting felt that we should implement a new sentiment survey this Quarter, but in a more focused way, looking at work quality, transparency, and perhaps impact / outcomes, as these have been raised several times in past GovWG sessions and in the budget consent process as important.

We'll use GoogleForms, because of the analytics it offers - and it will be anonymous.

We also want to include space for people to give rationales for their views, because in the last survey (which did not ask for reasons), the responses were sometimes puzzling

Timeline for this:

- Lola will draft the survey; it will be sent out early Nov with a closing date of 17th Nov
- We will analyse results by the end of this Quarter
- Then early next Quarter (Q1 2026), we'll sit down with WGs who have had "poor sentiment" and talk thru what changes are being suggested - we'll also use past objections in the consent process as part of this
- And we will, by then, have in place a range of possible measures / actions that can be implemented, but we'll work it out with each WG on a case-by-case basis
- The WGs will be asked to implement whatever is agreed during the rest of Q1 2026, and reflect it in their reporting and budgeting for Q2 2026. 

FOR OUR NEXT MEETING, ON TUES 21ST OCT:
- 1) we need to discuss what these "measures and actions" could be
- 2) we need someone to draft a bit of text explaining the sentiment survey and how it is going to be used
- 3) Sign off Lola's survey draft
- 4) decide who's distributing it, and think a bit about how to best publicise it



#### Discussion Points:
- Processes for addressing work quality 
- Possible processes for holding WGs accountable
- New sentiment survey

#### Decision Items:
- We will implement another sentiment survey this Quarter, using GoogleForms, with a more targeted focus on work quality, transparency, and impact, and with space for people to give a rationale for their views. The survey will be anonymous.
  - [**rationale**] To gather data on the issues that have been identified in GovWG meetings and in the consent process as important (work quality, impact), and ensure we understand the reasons for people's views
  - [**opposing**] there was an opposing view from Vani that we shouldn't do a new  survey, but should instead work with the results of previous surveys and consent processes, to avoid "survey fatigue" - but this wasn't the majority view
  - [**effect**] mayAffectOtherPeople
- We decided that contrary to past discussions in GovWG, a WG's work quality SHOULD affect its budget, and discussions on work quality should perhaps no longer be viewed as "decoupled" from discussions about budget allocations
  - [**rationale**] a general sense that, particularly in these times of low token price, we do not want to be paying for work that is widely perceived as low quality
  - [**effect**] mayAffectOtherPeople
- We agreed it would probably be unfair to end a WG on the basis of a sentiment survey alone, and that input from past consent processes should also be used

  - [**rationale**] because sentiment surveys are widely perceived as unsupported opinion, more so than issues raised in the consent process
  - [**effect**] mayAffectOtherPeople
- We agreed that regardless of the exact process, underperforming WGs should be given a chance to improve before being stopped
  - [**effect**] mayAffectOtherPeople
- We agreed that there should be a range of possible processes and measures that could be used with "underperforming" WGs, and that actions should be decided on a WG-by-WG basis according to what the issues are for that WG, and based on discussions with the WG itself. These discussions should happen in the WG's own meetings, rather than in GovWG meetings.
  - [**rationale**] Because it's hard to think of all eventualities in advance, and it's important to decide on actions in collaboration with the WG concerned
  - [**effect**] mayAffectOtherPeople

#### Action Items:
- [**action**] Lola will draft a survey [**assignee**] omolola lawson [**due**] 21 October 2025 [**status**] todo
- [**action**] All to discuss, in a future meeting, possible "measures and actions" that could be taken to address problems identified by the sentiment survey [**assignee**] all [**due**] 21 October 2025 [**status**] todo

#### Keywords/tags:
- **topics covered:** sentiment survey, sentiment analysis, work quality, Theory of Change, impact, outcomes, WG accountability, Budget caps, token price
- **emotions:** Focused,  Collaborative, thoughtful, analytic,  forward-looking, lots in Chat, Only a few of those present spoke

### AI Sandbox/Think-tank

- **Type of meeting:** Think-Tank
- **Present:** LordKizzy [**facilitator**], Kateri [**documenter**], Jeffrey Ndarake, Maxmilez, UKnowZork, martinsoki, osmium, LordKizzy, Kateri
- **Purpose:** Regular biweekly meeting
- **Working Docs:**
  - [Presentation Template](https://www.canva.com/design/DAGTr2f8gW8/YWrjpheKKdAoifI9pjrbsQ/view?utm_content=DAGTr2f8gW8&utm_campaign=designshare&utm_medium=link&utm_source=editor)
  - [Agenda ](https://discord.com/channels/909843832491896832/1098295570898104340/1428347765469085777)

#### In this meeting we discussed:
- Today session is an open discussion: The topic: "At what point does Artificial Intelligence stop being a tool and start being a collaborator?"
- The discussion focused on the evolution of Artificial Intelligence, highlighting the distinctions between Narrow AI, Artificial General Intelligence (AGI), and Artificial Superintelligence (ASI).

Narrow AI: Artificial Intelligence that is limited to a single domain. It cannot perform complex, multi-domain reasoning but is designed to handle specific tasks effectively.
Examples include chatbots (like ChatGPT), large language models (LLMs), image recognition systems, video generating platform (imvideo) and voice assistants (such as Siri and Alexa).

Artificial General Intelligence (AGI): A human-level form of AI that can understand, learn, reason, and make decisions across multiple domains, not just a single task. Unlike Narrow AI, AGI would be capable of performing a wide range of tasks and adapting to new challenges, much like a human mind.
Example: a single AI system that can carry out all required tasks at once from problem-solving to communication to creative work.

Artificial Superintelligence (ASI): A stage of AI where machine intelligence surpasses human intelligence in reasoning, creativity, problem-solving, and even emotional understanding. At this point, AI would not only think faster and more accurately than humans but also demonstrate capabilities far beyond our comprehension.
It represents an “out-of-this-world” level of advancement, where AI becomes more intelligent than the best human minds in virtually every field.
- Back to today’s discussion: When should we see AI as not just a tool, but start recognizing it as a collaborator?
Collaboration between humans and AI emerged as a key theme, with participants debating the nature of such partnerships given AI’s lack of consciousness. Jeffreystressed the importance of verifying AI-generated outputs to ensure reliability. Kateri highlighted that collaboration with AI is already used into daily tasks, making it less of a future concept and more of a present reality. Max Milez added depth by noting the complexities of defining collaboration, especially since AI’s backend processes make it difficult to clearly separate tool use from true partnership (He discussed his struggles with AI tools, specifically mentioning a day spent trying to use chat GPT for a video project. He noted that the AI often provided names without links, necessitating further searches on platforms like inVideo. Milez expressed that once AGI is achieved, it should function like Google, providing comprehensive access to information from a single application.


- Addressing Over-Reliance on AI in Education: Lord Kizzy expressed concerns about the growing reliance on AI in education, noting that students often generate answers through AI tools without first engaging their own reasoning. He compared current practices to earlier stages of education, where learning advanced more gradually and students-built knowledge step by step. 
UknowZork added to this concern by highlighting the negative impact of excessive technology use in schools, arguing that it undermines the development of foundational learning skills. She recalled her own educational experience, where calculators and other technological aids were rarely used, and students had to build problem-solving abilities independently. UknowZork suggested that schools establish clear boundaries for the use of AI, encouraging students to first seek answers from traditional resources such as textbooks and libraries before turning to AI tools. Lord Kizzy emphasized the need to strike a balance between collaboration with AI and over-dependence on it.
- AI tool Exhibition Overview and Template Introduction: Lord Kizzy outlined the purpose of the AI tools Exhibition, which serves as a platform for members to showcase AI tools that can enhance the Ambassador Program. He highlighted the use of a standardized template for presentations and encouraged participants to review previous exhibitions for guidance. 

It was noted that, due to budget restrictions, the AI tool exhibition had been paused for a period. However, despite the limited resources, the initiative is being revived and relaunched, signaling a renewed focus on integrating AI tools into the program. 

The meeting ended with Lord Kizzy further asking if anyone was interested in taking up the presentation slot, but no one responded at the time. He mentioned that he would reach out to Advance or Gorga to invite them to present at the next meeting. If they are unavailable, he committed to delivering the presentation himself.

#### Action Items:
- [**action**] Lord Kizzy will share the template for the AI tool exhibition and provide the link of the channel [**assignee**] LordKizzy [**due**] 16 October 2025 [**status**] in progress
- [**action**] Lord Kizzy to reach out to Advance and Gorga to see it that are available to present next meeting [**assignee**] advanceameyaw, Gorga Siagian, LordKizzy [**due**] 16 October 2025 [**status**] todo
- [**action**] Advance to document next meeting [**assignee**] advanceameyaw [**due**] 30 October 2025 [**status**] todo

#### Keywords/tags:
- **topics covered:** Narrow AI, AGI, ASI, AI TOOLSET EXHIBITION, AI is just a tool, AI Emotion
- **emotions:** Educational,  Collaborative, Interactive