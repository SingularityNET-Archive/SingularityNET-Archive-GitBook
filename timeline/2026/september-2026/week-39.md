---
description: 21st September 2026 to 27th September 2026
---

# Week 39

## Tuesday 22nd September 2026

### Governance Workgroup

- **Type of meeting:** Weekly
- **Present:** Tevo [**facilitator**], Tevo, kenichi [**documenter**], Duke, kenichi, Tevo
- **Purpose:** We spent the call ideating on what would we like to know in Q3 Retrospective

- **Working Docs:**

#### Narrative:
What information we would like to know from Retrospective? (bolded potential questions below)
This material could also help us to prepare async Retrospective if audience too small

At high level we would like few things based on our funded directions
These questions from each direction:
How difficult was to implement the proposal? (link to proposal)
Was reporting too difficult or burdensome relative to the value it provided? 
Did we find Reporting sufficient? (link to report)
What information was missing from the report?
Should this direction continue next quarter?
Knowing what we know now, would we design or fund this proposal differently?

Directions:
How Latam Went?
How African Went?
How ASI Project went?
How Coordination Manager Update went?
How Governance WG went?


What went well?

What didn't go well?

What was confusing?
There is no clear structure or expectations what needs to be reported on or how
African Guild uses past reports to define potential report outline
Assuming simple what was done list


What should we do next quarter? (potentially not use in Retrospective and fully focus on issues and insights)

What consumed significant effort without producing much value?  (we should not use that question because we have already stripped from Ambassador Program all that does not produce much value, potentially still usable question because it will lead to next largest bottleneck. This question might however continue to strip down layers of what makes a Ambassador program, because we are not properly architect our program nor get sustainable resource for this)

Were there responsibilities that nobody clearly owned?

What did we learn that should become a documented practice?
Our decisions are interpreted differently, this would help us have collective clarity 



#### Decision Items:
- We postpone Retrospective session to after Reporting sessions. Current Audience was too small

  - [**effect**] mayAffectOtherPeople
## Thursday 24th September 2026

### Governance Workgroup

- **Type of meeting:** Weekly
- **Present:** CallyFromAuron [**facilitator**], Tevo [**documenter**], CallyFromAuron, Tevo, kenichi, AshleyDawn, esewilliams, André
- **Purpose:** gv wg next quarter budget revisit (what should we recognise, how could we request action items, new docs, etc)
and workgroup/tooling updates

#### Discussion Points:
- What has been updated on Coordination Manager?
There were multiple performance, UX and UI updates elsewhere too but significant time and effort was spent on Mailbox Feature. The Mailbox is now ready for public use, but the code is not yet available. Estimating another 2 weeks before I get that far.
AI Computation cost for Q3 has been ~1100$
Most of the cost eats documentation cost and developer tooling to do establish proper testing workflows. However this is like investment to infrastructure that can be more or less reused
- What updates about Archival WG?
The archival activities are monitoring Gov WG activities so nothing much to report on, has no budget allocated either.
- Governance WG Updates.
https://docs.google.com/document/d/1C4oezfkEAI717zoJcUVtW0B5S3hwH7iVtOUEVHMrE4c/edit?usp=sharing
- How do we recognize work?
We find that operationally expecting people to write down invisible work will not work and feels unimpactful invisible work.
Rewarding all kinds of work is not feasible.
It remains difficult to log hidden work individuals produce.
Perhaps setting up a recurring sync call focused on every person describing or someones else perceived work to capture unique work
- Should we continue ASI Project?
The perceived attention is showing good numbers but very little async engagement from builders.
And from Foundation there is very little support or involvement of using the material. We get acknowledgement but collaboration is non existent.
- Kenichi proposed a GitBook-style Omega guide with setup, troubleshooting, and API documentation. Tevo said the Hypersprint was intended to provide similar material but had not been updated as expected, and he suggested submitting a public GitHub pull request to make the changes harder to overlook.
- The group evaluated GitBook as a dynamic documentation and analytics platform for onboarding and knowledge sharing. Vani raised concerns about continued GitBook use, while André described a repository-backed application that can display GitBooks and potentially evolve to support editing without a subscription.
- Vani raised questions about combining treasury, governance, meeting summaries, and historical archives, including scope, cost, migration, and delivery timing. André proposed incremental experiments and a possible full migration in Q1, while Tevo recommended prioritizing the archival data first.
- The group clarified that the intended governance and archive system would include consent processes, sentiment surveys, and other historical information in addition to documents. Vani emphasized community review of agent-generated insights, while Tevo highlighted outdated data and ethical questions around automated extraction and redaction.
- They agreed that the system preserves records but does not provide deeper labeling, classification, or knowledge-graph-style organization.
- The group discussed rebuilding the meeting-summary interface around APIs, choosing between shared and separate infrastructure, and the limitations of the existing closed-source governance dashboard.
- The group supported gradually bringing tools together rather than replacing them immediately. André planned to prioritize the treasury system and introduce additional features for testing, while the participants remained uncertain whether the ambassador knowledge base should be combined with archival systems.
- Vani identified consent outcomes and related governance information as important data that is currently buried in spreadsheets and documents. The discussion clarified that the key challenge is reconstructing the temporal and substantive relationship between objection reasons, proposal changes, consent rounds, meetings, and final outcomes
- Kenichi proposed a possible Discord bot limited to selected channels for identifying decisions and participants. Vani objected to retrospective use of Discord messages without consent, and the group clarified that objection rationales should come from the structured consent forms rather than unrelated discussions.
- Tevo suggested that the immediate need may be automated creation and editing of relationships between data objects rather than a new dashboard. Kenichi proposed first building a filtering system to classify governance records before connecting them to AI and a governance dashboard, with a possible historical view showing decision and meeting logs.
- Tevo clarified that a new archival platform could consolidate the knowledge base and governance data while replacing existing platforms, but the scope of migration was not settled. André suggested a central data node fed by other sources, while Vani proposed archival copies to protect distributed materials from deletion; the trade-offs and implementation approach remained open.
Tevo raised concerns about creating a third server and advocated for a single open-source platform. 
- The group considered the value of consolidating programme tools into one platform and questioned whether GovDash will continue receiving development support. Kenichi emphasized connecting historical data to the current toolset before pursuing additional GovDash features, while Vani noted that the status and future roadmap of GovDash remain unknown.
- Tevo described how the knowledge base uses embeddings, ingestion filters, analyzers, targeted queries, and AI models comparisons to produce answers.
Archival Integration with Knowledge Base would unlock AI Chat features
- André asked how the system organizes and stores information. Tevo explained that the current source is GitHub-derived Markdown files with embeddings and that link-only API data would require metadata creation, assessment, and normalization before it could be used reliably by an AI assistant.
- The discussion addressed whether archival files should be processed automatically or selected through an explicit governance process. Tevo proposed a review tool where users could approve, reject, or exclude data before it is incorporated into the knowledge base.
- Tevo identified Archival dashboard issues involving formatting, missing links, large text blocks, and limited queryability.

#### Decision Items:
- Continue rewarding Governance WG activities and tasks where possible, but did not decide what should they be and if we should continue with existing ones
- We wont use Discord discussion to enrich Archival Data with labels or timestamps or even additional info.
  - [**rationale**] Ethical Boundary

#### Action Items:
- [**action**] André agreed to investigate and potentially add API access to the Archival System to request archival data [**status**] todo
- [**action**] Identify meaningful recurring governance questions and desired answers to help determining the tooling  integrations paths [**status**] todo