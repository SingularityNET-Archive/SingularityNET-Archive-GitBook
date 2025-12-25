---
description: Mon 8th Dec - Sun 14th Dec 2025
---

# Week 50

## Wednesday 10th December 2025

### Archives Workgroup

- **Type of meeting:** Monthly
- **Present:** Stephen [QADAO] [**facilitator**], CallyFromAuron [**documenter**], CallyFromAuron, Stephen [QADAO], Tevo, PeterE, Alfred Itodele, Sharmila
- **Purpose:** Regular monthly meeting of the Archives WorkGroup in the SingularityNET Ambassador program
- **Meeting video:** [Link](https://www.youtube.com/playlist?list=PL4dGsCqdRj6ct6TwdrVKm_Bjg2ToCjzQh)
- **Working Docs:**
  - [GitHub Issue for this meeting](https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/289)
  - [Q4 2025 Archives WG report ](https://docs.google.com/document/d/1DjCL2NtDm2HvtEx-ki85YQV8pW966tZlUfq8EW3FXIQ/edit?usp=sharing)

#### Decision Items:
- Knowledge graph development: see 
- https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/285 (Nov 2025)  and 
- https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/287 (Dec 2025)

Key focus recently has been is prototyping a replacement Archives dashboard, and thereby  improving the data ingestion pipeline. Initial work on ingesting data from multiple sources into a Supabase schema has been completed, so we know it works; a prototype RAG system has been built using a minimal local LLM to parse data from a discrete source (sample JSON data from this year only); and a draft Discord bot capable of generating answers with verifiable citations.

  - [**effect**] mayAffectOtherPeople
- This work is now on hold while we protoype an actual redesigned Archives dashboard that puts summary submission, Archives corpus, a decision tracker, and graph RAG material all in one interface. This is based on forking André's original dashboard, and aiming to make it more generic, rather than specific to the needs of the Ambassador program; and improving its documentation (e.g. what terms mean, how authentication is set up, how our data is structured, etc).

  - [**effect**] mayAffectOtherPeople
- We noted, RE the setup of the RAG process - there is a lot of token overhead involved in just "throwing JSON at a generative model" - much more efficient to pre-query with SQL, creating a subsection of the data, and sending only that to the generative model.  Same approach will be used with graph queries - SQL first.

  - [**rationale**] Requires differentiating semantic queries (i.e. queries that are more suited to a RAG process) from queries that are better suited to SQL (e.g. arithmetic /counting type questions, etc). Some natural language processing could help identify what kind of query is being asked, and what process is best suited to answer it; i.e. by identifying different types of queries, and matching actual queries against these "types".
  - [**effect**] mayAffectOtherPeople
- We noted that a key element of our approach is that if the RAG cannot answer a question/iderntify a source, it will *say so*, rather than making something up

  - [**rationale**] so that answers are auditable/verifiable.
  - [**effect**] mayAffectOtherPeople
- We agreed that in early 2026, we will run a session as discussed in October to engage the wider Ambassador community with analyzing the graph data and verifying it/ analysing what it means, comparing its insights to their lived experience of being in the Ambassador program.

  - [**rationale**] Both as a way of developing a community verification process for graph outputs, and as a way of educating on basic graph analysis.
  - [**effect**] affectsOnlyThisWorkgroup
- We noted that one aim of the new dashboard is that it will be modular - and that it will be able to ingest *any* JSON or SQL data (i.e. not necessarily just meeting summaries); it will then be important for it to be able to understand how the different data sources are related to each other. 

However, ethically speaking, we don't necessarily want to assume what the connections are - it's important that a human in the loop should be *discovering* how things are connected, rather than allowing the graph RAG process to assume connections. 

- We notd that rational privacy (as for Cardano's Midnight chain) is important in an archival context - also the need to be clear about what info is public, and what consents are needed. 

  - [**rationale**] We discussed whether consent needs to be be retrospective: i.e. a person cannot know in advance how AI might use and process their data, or what insights it might come up with, so perhaps they can only give fully informed consent once they see and verify the outputs? (in a similar way to how an interview subject can only fully consent after the interview is finished and they know what they have said)
  - [**effect**] affectsOnlyThisWorkgroup
- We noted that for this Quarter, there is no budget consent process; but WGs are being asked for a simple, minimal report on their work; we have submitted Archives' report to the Governance Dashboard here https://singularitynet-governance-dashboard.vercel.app/dashboard/proposals/cmixenh0m0001jv0ao0ccwgl3

#### Action Items:
- [**action**] Vani to draft and submit minimal report for this Quarter's work [**assignee**] CallyFromAuron [**due**] 8 December 2025 [**status**] done

#### Keywords/tags:
- **topics covered:** AI ethics, Knowledge Graph, Knowledge management across the singularityNET ecosystem, Open source, structured vs unstructured data, semantic analysis, data analysis vs graph analysis, community data verification, contribution, Graph RAG, decision tracking, new Archives dashboard, SQL, generic tooling, Consent, retrospective consent, Q4 2025 quarterly report, Governance Dashboard, rational privacy, Midnight, data ingestion, multiple sources, JSON, JSON data into graph data, pre-query with SQL, human in the loop
- **emotions:** interesting, Discursive, didactic, ethics-led