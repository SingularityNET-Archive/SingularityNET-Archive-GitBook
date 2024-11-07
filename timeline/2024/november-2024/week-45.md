---
description: Mon 4th Nov - Sun 10th Nov 2024
---

# Week 45

## Wednesday 6th November 2024

### Archives Workgroup

- **Type of meeting:** Biweekly
- **Present:** Stephen [QADAO] [**facilitator**], CallyFromAuron [**documenter**], André, CallyFromAuron, Stephen [QADAO], Onize, esewilliams, AshleyDawn, Slate, Effiom, lord kizzy, Sucre n Spice
- **Purpose:** Regular fortnightly meeting of the Archives WorkGroup in the SingularityNET Ambassador program
- **Meeting video:** [Link](https://www.youtube.com/playlist?list=PL4dGsCqdRj6ct6TwdrVKm_Bjg2ToCjzQh)
- **Working Docs:**
  - [SNET Archive AI features (draft of possible features an AI tool might have)](https://docs.google.com/document/d/1LROsgVAQ9fQbNgMRK5qMI8q8KYsN-rGI-Gq9lvXAN5w/edit?usp=sharing)
  - [Docs management tool](https://snet-doc-manager.netlify.app/#)
  - [New Summary Tool Features](https://docs.google.com/document/d/1wxziaDEdMdYeiqv0ecuuygHgfd9a9F18odje_2qaT7g/edit?usp=sharing)
  - [today's meeting issue ](https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/216)

#### Decision Items:
- RAG workflow documentation: see issue https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/175 - we noted how quickly RAG technology is changing; and noted the importance of an open source ethos in how we approach it.
  - [**effect**] affectsOnlyThisWorkgroup
- André's tool development this month has included adding a template for AI Sandbox/Think Tank. 
He has also been working on implementing a dropdown controlled vocab for the names of meeting participants. Some time ago, we agreed that we should use people's Discord names for this, ("Archive name = Discord name), and André has been looking at using a Discord bot to gather them. However, we notice that "Archive name = Discord name" has not been working that well - documenters don't apply it consistently, and particularly for new documenters, they might not know someone's Discord name if their Zoom name is different, so it causes confusion. So we have decided to use the name by which people have been most consistently recorded in the Archives, whether or not it matches their Discord name, to minimise the amount of changes that need to be made.

André proposed the same approach as we plan to use for tags: it will be possible to add a new name, but it will not appear immediately in the tool but will need to be approved. This means that if a documenter accidentally adds a name for someone who is already there in the controlled vocab, we can fix it.

  - [**rationale**] to resolve a barrier to good documentation, and ensure people are discoverable in the Archives.
  - [**opposing**] none
  - [**effect**] mayAffectOtherPeople
- We noted that in the Issue for our current (Q4 2024) budget https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/201, we said we would make some cuts to conform with budget fitting. 
This has been done, and as we've done in previous Quarters, we'll add something to the budget sheet on the right-hand side to show what changes were made.

We noted that the budget we submitted for Q4 was already severely cut, to try and address the low token price at the time - but we have still needed to make further cuts to conform to budget fitting. This has had an impact on the work we have been able to do. We noted that not all WGs did this in Q4 - some made little to no attempt to constrain the amount they asked for, and their high original budgets were perhaps intended to "give them something to cut". We note that the budget system we have at present basically incentivises workgroups to submit higher budgets than they need, in anticipation of budget fitting. 

This is obviously outside the scope of Archives WG to address, but we will raise it in Governance and/or Treasury; plus, we will mention it in our quarterly report.
  - [**rationale**] This issue has affected us strongly this Quarter, and is a shortcoming of the budget-fitting process, so we should mention our experience in Governance meetings.
  - [**effect**] mayAffectOtherPeople
- When looking at the monthly Archives issues, we noted that documenting DeepFunding Town Hall can slow down the process (sometimes timestamps are not great, and additional work needs to be done to document the sessions in a meaningful way).

We wondered if DF itself could make any further contribution to the work - e.g. by paying someone from the Town Hall team to add the documentation to the summary tool?

We might also need to discuss how the Archives dovetails with documentation that DF is doing itself, such as https://community.deepfunding.ai/


  - [**rationale**] We noted that it is good and important that the Archives isn't insular, and includes material from beyond just the Ambassador Program.
  - [**opposing**] We noted that it might not be easy for DF to fund this directly via the Ambassador Program treasury system - but possibly they could pay it directly themselves?
  - [**effect**] mayAffectOtherPeople
- In relation to the above, we recognised that we might need to include a budget line in Q1 2025 to support collaboration outside the Ambassador Program
  - [**rationale**] to enable us to capture material from other areas of the ecosystem, and have a more wide-ranging Archives that demonstrates the links and connections between the Ambassador Program and other areas of the ecosystem.
  - [**opposing**] None as such, although it might be difficult to do this comprehensively and still keep to a reasonable budget amount. It might be more about outreach to different parts of the ecosystem to see how we can support them with recordkeeping.
  - [**effect**] mayAffectOtherPeople
- Also while discussing the monthly Archives issues, we noted that the backlog for Governance WG is largely because documenting Governance meetings isn't an entry-level task, and requires quite a lot of understanding of the Program as a whole in order to understand what's being discussed.
We agreed to mention in our Q4 quarterly report that some meetings are harder/more complex to document than others. This could also be raised in the WG Sync call at the end of November, as it might be something that will influence how much different WGs budget for documentation.
  - [**effect**] mayAffectOtherPeople
- We began discussing our budget for Q1 2025. As token price is still moderate to low, it will still need to be quite limited, and to focus on core development work. We plan to include work to build a dashboard to enable people to query the Archives corpus; and build on Ubio's work in Q3 on using AI to apply human generated tags; and we will perhaps aim to take a comparative research approach to looking at the value of AI tooling in a recordkeeping context - what *can* it do successfully, and what is better and more ethically approached using e.g. a database-type search? 

We also want to progress policy-writing - an AI ethics in recordkeeping policy, and an open-source policy.

  - [**rationale**] We note that this *is* an ethics issue if a RAG retrieval process cannot easily say if it doesn't know; cannot easily show its sources for verification; or cannot be fully constrained to a specific corpus.
  - [**effect**] affectsOnlyThisWorkgroup

#### Action Items:
- [**action**] Video walkthru of how to use the GitHub Board - see https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/116  - not yet completed, but Onyeka will add the completed video to the Issue as soon as possible, and if needed, we'll review it in our November meeting. [**assignee**] lord kizzy [**due**] 6 November 2024 [**status**] done
- [**action**] Stephen to set a date, which will now be in November, for presenting the "Open-source paradigm" work at a TH, and let Peter know - this has been put back to November to give time to redesign the presentation in line with the Ambassador Program brand kit [**assignee**] Stephen [QADAO] [**due**] 29 November 2024 [**status**] in progress
- [**action**] Sucre to finish updating Ambassador gitbook to reflect changes to the Onboarding process, by the end of the Quarter - done except for discussing with Peter whether to add something on Moderators WG. [**assignee**] Sucre n Spice, CallyFromAuron [**due**] 29 November 2024 [**status**] done
- [**action**] Clement or Onyeka to announce the winners of the Good Meeting Summary prize some time in the coming week, and update the issue accordingly https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/191 [**assignee**] lord kizzy, Clement Umoh [**due**] 9 October 2024 [**status**] done
- [**action**] Vani to check through Budget issues from previous Quarters (such as https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/73 and https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/131), which we keep open until all issues that are costed in that quarter are closed, and ensure that they can be moved to "Done". [**assignee**] CallyFromAuron [**due**] 21 November 2024 [**status**] todo
- [**action**] Vani to start a draft Quarterly Report for this Quarter, and post it in the Issue here https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/214 for comments [**assignee**] CallyFromAuron [**due**] 14 November 2024 [**status**] todo
- [**action**] Vani to draft Q1 budget, and post in the Issue here https://github.com/SingularityNET-Archive/SingularityNET-Archive/issues/218 for comments and suggestions [**assignee**] CallyFromAuron [**due**] 14 November 2024 [**status**] todo

#### Keywords/tags:
- **topics covered:** Ethics, ai ethics in recordkeeping, AI ethics, Q1 2025 budget, q4 2024 report, DeepFunding, Deepfunding Town Hall, Governance, documentation skills, Budget fitting, fairness, barriers to good documentation, controlled vocabulary, dropdown, Discord names, open source, open source ethos, RAG retrieval process, markdown, JSON, dashboard, archives search, Collaboration, Governance documentation, Knowledge management across the singularityNET ecosystem
- **emotions:** short, Discursive, complex issues, wide ranging, joining the dots, retrospective