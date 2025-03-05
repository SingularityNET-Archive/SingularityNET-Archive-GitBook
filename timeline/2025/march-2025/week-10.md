---
description: Mon 3rd Mar - Sun 9th Mar 2025
---

# Week 10

## Wednesday 5th March 2025

### Archives Workgroup

- **Type of meeting:** Monthly
- **Present:** Stephen [QADAO] [**facilitator**], CallyFromAuron [**documenter**], André, CallyFromAuron, Stephen [QADAO], PeterE, AshleyDawn, maxmilez, TheFreysDeFi, LordKizzy, Tevo, Zalfred, esewilliams, Alfred Itodele
- **Purpose:** Regular monthly meeting of the Archives WorkGroup in the SingularityNET Ambassador program
- **Meeting video:** [Link](https://www.youtube.com/playlist?list=PL4dGsCqdRj6ct6TwdrVKm_Bjg2ToCjzQh)
- **Working Docs:**
  - [Archives Dashboard ](https://archives-dashboard.netlify.app)
  - [Q1 2025 budget](https://docs.google.com/spreadsheets/d/14IYxBj-9MGCZRkYIupwvbHgPYZgohnyMSQ-EUFBgpYI/edit?usp=sharing)
  - [Archive names (a list of the name that people are most commonly known by in the Archives)](https://docs.google.com/spreadsheets/d/1r5LDA7yiERtWuu-HHYsBiG-RLyjDCtTZUB8H-xZHFsE/edit?usp=sharing)
  - [Q1 2025 DRAFT Quarterly report for Archives WG](https://docs.google.com/document/d/1JUyVzyjeGJkFkjtzkqk-glsqzdUqlIZ5LdOwWM5OGJY/edit?usp=sharing )
  - [q2 2025 budget draft](https://docs.google.com/spreadsheets/d/1BLCkYgyV0rnt-Ntlqp_DXGCm1t3KieAVMS_HaUamqQI/edit?usp=sharing)
  - [GitHub Issue for this meeting](https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/247)

#### Decision Items:
- Last meeting, we said that we would review, in this meeting, whether or not we can afford to implement the proposed initiative for this Quarter to create a skilled documentation team. 

Unfortunately token price is even lower than it was, so we definitely cannot do it - but we noted that the need for it might be obviated by our proposed experiment with not correcting summaries in Q2.

We agreed to close the Issue https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/235
  - [**rationale**] We had this in our Q1 budget: "If token price rises sufficiently above $0.55" (the exchange rate at which Q1 budgets were calculated). Price has dropped.
  - [**effect**] mayAffectOtherPeople
- Our Quarterly Report draft https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/231 and Q2 budget draft https://docs.google.com/spreadsheets/d/1BLCkYgyV0rnt-Ntlqp_DXGCm1t3KieAVMS_HaUamqQI/edit?usp=sharing were signed off
  - [**rationale**] Needs to be submitted on 10th March
  - [**effect**] affectsOnlyThisWorkgroup
- André, tool development: see https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/248
This month the Autosave feature has been completed, and bug fixes have been done

  - [**effect**] mayAffectOtherPeople
- We noted that whilst during this Quarter, André has done additional development work as well as the Summary Tool redesign, in Q2 his focus will shift purely to the tool redesign
  - [**effect**] affectsOnlyThisWorkgroup
- AI workflow, Q1 - see https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/233 

We noted that Stephen was planning to look this month at approaches to auditing graph data - but this turned out to be a much bigger chunk of work than would fit into this budget line, so it has become a proposal in the BGI Nexus funding round  https://deepfunding.ai/proposal/ethical-ai-auditing-a-practice-based-approach/ 

Instead, in this issue, he will be focusing on building infrastructure tools.
  - [**effect**] affectsOnlyThisWorkgroup
- LLM development (see https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/244 (Feb) and https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/252 (March)
Stephen has built a GitHub App Token Generator - basic proof-of-concept, which uses GraphQL to interface with GitHub data via GitHub API.  In March, he will be looking at other data tools that might be useful in our work in Q2.
  - [**effect**] affectsOnlyThisWorkgroup
- WG Sync call at the end of March - we decided to reiterate that meeting summaries will not be audited during Q2, and suggest a time limit to submit a summary, after which it will be recorded as "no summary given"

Suggestions ranged from a day to a Quarter - we settled on a month after the meeting took place.
  - [**rationale**] It shouldn't be turned into a competition; also, some WGs use meeting summary-writing as an onboarding task, so there needs to be time for support to be given and corrections to be made.
  - [**effect**] mayAffectOtherPeople
- Research on not correcting meeting summaries in Q2: 

We noted that our planned approach might influence what kind of data we get in a meeting summary, and in the resultant knowledge graph. 

Hypothesis: we will get well-defined edges (i.e. connections between entities), because this often depends on simple structured data (who was present in a meeting, which meetings a given topic was discussed in, etc); but we might have less information about what anyone *said* when they discussed a topic, since people in the Ambassador program have historically been less good at documenting this kind of information.

Analysis of what kind of data we are getting with uncorrected summaries might later feed in to the design of the new summary tool - perhaps by attempting to design it to help people collect the kind of data that is missing, if any.

#### Action Items:
- [**action**] Vani has approached DeepFunding, to ask if the Events Circle could take on documentation of DF Town Hall. Focus Group agreed this would be valid - waiting for a reply

Also some interest in Focus Group re: how the Archives tool could be used for further documentation within DF [**assignee**] CallyFromAuron [**due**] 2 April 2025 [**status**] in progress
- [**action**] André has fixed the  issue with tags where people are copy-pasting strings of comma-separated tags into the summary tool, but they are not rendering as separate tags, but as strings.  [**assignee**] André [**due**] 5 March 2025 [**status**] done
- [**action**] André and Vani to meet to wrap up the tag taxonomy issue by deciding on an initial controlled vocab for topic and emotion tags [**assignee**] André, CallyFromAuron [**due**] 2 April 2025 [**status**] todo
- [**action**] Andre to add "All", "Alfred Itodele" and "Maxmilez" as new Names in the names controlled vocab [**assignee**] André [**due**] 19 March 2025 [**status**] todo

#### Keywords/tags:
- **topics covered:** graph database, Neo4j, summary tool, autosave, decision tracking, Robert Stalnaker, AI ethics, Ai recordkeeping ethics, graph data modelling, Python, JSON, Decentralisation, Decentralization, representing our culture in summaries, tag taxonomy, names taxonomy, controlled vocabularies, comma-separated tags, semantic similarity, recordkeeping ethics, archives ethics
- **emotions:** interesting, wide-ranging, well-attended, slightly combative