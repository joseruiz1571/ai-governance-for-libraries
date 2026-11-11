# AI Tool & Use Registry

## A working decision-record template for public libraries

A registry is not a spreadsheet. A spreadsheet is a list that no one owns and no one maintains, and it fails the moment two branches disagree about what counts as the same tool or whether an internal test authorizes public use. A registry is an authority record: it names a maintaining authority, it records where each entry came from, and it keeps the history of what changed and why. Libraries already do this work. You do it every time you maintain an authority file for subject headings or local history ([Program for Cooperative Cataloging NACO Manual](https://www.loc.gov/aba/pcc/naco/documents/NACOParticipantsManual.pdf)). Bibliographic authority and managerial authority remain distinct, but the transferable practice is maintaining enough context to understand and revise a decision record.

The goal is the smallest amount of structure that still lets an uninvolved colleague, a board member, or a patron reconstruct the decision: what use is permitted, under which conditions, on what evidence, shaped by whose knowledge, and who has authority to revise it. Existing procurement, privacy, accessibility, or collection records can supply supporting details through links; stewardship need not create a parallel record system.

## What the registry is for

The unit of review is an **AI-enabled use**: a particular feature, workflow, service, program, or decision context where the library selects, configures, recommends, or materially relies on an AI or automated decision-support function. Material reliance means that an output meaningfully shapes staff action, public content, access, ranking, resource allocation, or another decision. Different uses of the same vendor product may require different permissions.

The registry records AI-enabled uses across your library before scattered practice hardens into de facto policy. It separates **authorized disposition** (what may occur and under which conditions) from **review state** (whether evaluation is required, underway, or complete). Starting a review grants no permission, and an authorized internal staff exercise does not authorize a public pilot.

Three library-specific stakes ride on this:

- **Intellectual freedom.** A feature that interprets queries, filters, ranks, or flags content is making collection and access decisions. The registry is where delegated judgment gets named rather than absorbed silently.
- **Patron privacy.** Any use that touches circulation data, search queries, reference interactions, or patron records sits under your state's library-records confidentiality law. The registry is where vendor defaults and unresolved data terms get checked.
- **Public accountability and participation.** The registry connects community knowledge and staff experience with institutional choices, preserving how contributions shaped the service purpose or evaluation criteria and how concerns return to review.

## How a use enters the registry

An AI-enabled use enters through any of these triggers. Comparable low-risk internal uses (such as nonconfidential drafting or proofreading tools) may share a **grouped record** when their purpose, data, owner, conditions, and review arrangements are the same. Consequential, patron-facing, or sensitive-data uses receive an individual expanded record.

- Procurement of a new platform or service
- Renewal of an existing contract
- A vendor adding or modifying an AI feature in a platform you already run (such as personalized catalog ranking)
- A staff request or proposal to use a tool in a workflow
- A limited internal exercise, pilot, or trial
- A patron-facing deployment
- A recurring patron or staff concern that reopens review

The vendor-update trigger is the one libraries miss most often. A changed feature outside the approved scope requires a new decision.

## The decision record fields

Complete one record for each selected use or group of comparable low-risk internal uses. Separate initial and final dispositions when tracking a review cycle.

| Field | What it records |
| :--- | :--- |
| **Authorized name & use scope** | The controlled name for the use (feature, workflow, service, program, or decision context), purpose, non-AI or existing-service alternatives considered, audience, and affected groups. Note whether this is an individual entry or a grouped low-risk entry. |
| **Also appears as** | Vendor names, marketing labels, and where the feature is embedded inside other platforms (ILS, discovery layer, database, office suite). |
| **Data involved** | What data the use processes. Explicitly flag patron queries, PII, minors' data, or confidential borrowing/search/reference records. |
| **Assigned functions** | **Service owner** (oversees the use), **Reviewer** (evaluates evidence), **Approver** (determines disposition within delegated powers), **Registry maintainer** (updates the record), **Records custodian** (manages access and retention), and **Authorized risk acceptor** (for any permitted time-limited exception). One person may hold several functions; identify where local, board, parent-agency, or consortial authority actually resides. |
| **Authorized disposition** | What activity is currently permitted, restricted, deferred, refused, retired, or covered by a time-limited exception with controls. Identify approved scope, conditions, the authorizing actor, and expiration. State explicitly when no permission exists or when an internal exercise is authorized while public activation remains deferred. |
| **Review state** | `Review required`, `Underway`, or `Complete` (including any unresolved work). This field describes evaluation activity only and grants no permission. |
| **Review depth & linked records** | `Core record` (for routine low-risk internal uses) or `Expanded impact review` (triggered by sensitive data, public outputs, changed access/staff work, or consequential decisions), with links to existing procurement, privacy, accessibility, collection, or legal reviews. |
| **Participation basis** | Affected groups; questions open to community and staff influence; criteria requiring joint agreement vs. advisory input and the process for changing them; outreach, accessibility, and language provisions; or relevant prior engagement/standing policy. If no community input informed the applicable policy, record the gap explicitly rather than describing participation as inherited. |
| **Participation & influence** | Contributions from community members and staff (distinguished by source); how they changed the problem definition, alternatives, evaluation criteria, or conditions; disagreements and missing perspectives that limit the decision; reasoned responses to advice not adopted; and the route for reconsideration. |
| **Evidence & uncertainty** | Sources and local configuration examined; supported conclusions across Accuracy, Autonomy, Recourse, and Enforceability; unanswered questions; and **the specific activity prevented by each material uncertainty**. |
| **Vendor response** | Local response deadline and whether vendor response was `Full`, `Partial`, `Absent`, or `Inapplicable`. Vendor nonresponse remains unresolved evidence and never expands permission. |
| **Workload** | Estimated and actual staff effort (preparation, review, participation, accessibility, communication, and follow-up) compared against the agreed workload allocation. |
| **Communication, stop & recourse** | Staff instructions; accessible public explanation; who receives a concern; what events (such as unapproved vendor processing or configuration drift) immediately stop or pause the use; who can correct or escalate; and the alternative non-AI service route for patrons. |
| **Next work & review point** | Responsible actor, pending tasks, review date or trigger event, and the operational consequence of reaching that point (whether operation pauses or continues under a separately authorized temporary arrangement). |
| **Provenance, change log & superseded by** | How the use entered review, dated history of changes between initial and final entries (with reasons recorded), access/retention rules, and pointers to any replacement or retirement record. |

## Illustrative example: Conversational catalog discovery

The example below illustrates how a library records a bounded internal exercise when live-query vendor terms remain unresolved. Every entry is hypothetical and reports no actual product test or vendor commitment.

| Field | Illustrative entry |
| :--- | :--- |
| **Authorized name & use scope** | Optional conversational catalog discovery (individual expanded review). Purpose: examine conversational retrieval from invented descriptions while preserving known-title access and user correction. Alternatives retained: existing catalog search improvements and desk reference support. |
| **Assigned functions** | Public-services manager owns the use and maintains the record; collection and technology staff review; library director approves; established records custodian manages retention. |
| **Authorized disposition** | A limited internal staff exercise using invented queries and public catalog metadata is authorized for one scheduled staff-development session. **Public activation is deferred.** Personalization and automated collection decisions are outside scope. |
| **Review state** | `Underway` — review of live patron use awaits retrieval findings, vendor live-query terms, and a separate decision. |
| **Participation & influence** | Community advisers and staff considered alternatives and replaced increased holds as the sole success measure with exploratory discovery tasks, preserved known-title access, and user correction of misunderstood requests. The director accepted these jointly developed criteria as test conditions; material departures require renewed agreement. Disagreements and limits of representation are recorded. |
| **Evidence, uncertainty & vendor response** | Technology staff verified an isolated test configuration; retrieval results do not yet exist. Unresolved live-query data retention and subprocessor terms prevent any live patron pilot. Vendor silence at the next decision meeting leaves public activation deferred. |
| **Communication, stop & recourse** | Ordinary catalog service continues unchanged. Any configuration change or unapproved data processing stops the internal exercise immediately and triggers technology/director review. |

## Impact review (the four managerial questions)

When a use triggers expanded review, organize the assessment around four questions. These are managerial prompts rather than a composite score—good retrieval Accuracy cannot compensate for unacceptable data Enforceability.

- **Accuracy.** How does the feature perform on the intended library task compared with existing options, what relevant holdings or interpretations does it miss, and what claims must be restricted?
- **Autonomy.** What judgment is delegated (query interpretation, ranking, personalization), what human control remains, and how are unreviewed functions excluded?
- **Recourse.** How can a patron or staff member correct a misunderstood request, report an error, and obtain service through a reliable alternative route?
- **Enforceability.** Can the library secure and act upon data terms, local configuration controls, change notices, and a feasible stop or exit route? Where an essential or imposed platform cannot be withdrawn immediately, any **time-limited exception** must name an authorized risk acceptor, specific compensating controls, an expiration date, and an escalation or exit route.

## Record reconstructability check

To verify that a completed record works as an authority record rather than an unused log, ask a colleague who did not participate in the review to answer eight questions using the written record alone:

1. Can the reader identify the use, its current **authorized disposition**, and its separate **review state**?
2. Can the reader identify the evidence, uncertainties, and reasons supporting the decision?
3. Can the reader identify permitted scope, conditions, deferred or prohibited activities, and any expiration?
4. Can the reader identify responsible functions and the authority able to change the decision?
5. Can the reader trace whose knowledge (community and staff) shaped the purpose or criteria and how the decision responded?
6. Can the reader identify disagreements, missing perspectives, and the route for further participation?
7. Can the reader identify correction, escalation, alternative-service, and exit routes?
8. Can the reader identify the next review point, its operational consequence, and relevant change history?

*Created by Jose Ruiz-Vazquez; Version 0.3.0 prepared with Witt Salley. Licensed under CC BY 4.0: adapt freely for your library with attribution. Version 0.3.0, 2026.*

*An independent resource for public libraries. Not an official publication of the American Library Association, Core, or any library system.*
