# AI Use & Tool Evaluation Checklist

## For evaluating an AI-enabled use before the library authorizes it

Use this checklist whenever the library selects, configures, recommends, or materially relies on an AI or automated decision-support function—including when a vendor adds or modifies an AI feature inside a platform you already run. **Material reliance** means that an output meaningfully shapes staff action, public content, patron access, ranking, resource allocation, or another decision, regardless of the vendor's marketing label.

Beginning a review grants no permission to activate or use the feature. A completed checklist supplies the provenance and evidence for an entry in [`AI_Tool_Registry_Template.md`](AI_Tool_Registry_Template.md).

## 1. Scope, purpose, and assigned functions

- **AI-enabled use (authorized name & context):** _______
- **Also appears as / embedded location:** _______
- **Entry type:** [ ] Individual use record  [ ] Grouped record for comparable low-risk internal uses
- **Proposed service purpose:** _______
- **Non-AI or existing-service alternatives considered (e.g., improvements to existing search or staff support):** _______
- **Affected groups (patrons, staff, communities):** _______
- **Assigned authority functions** *(one person may hold several functions; identify the actual local, board, parent-agency, or consortial decision route)*:
  - **Service owner:** _______
  - **Reviewer(s):** _______
  - **Approving authority:** _______
  - **Registry maintainer & records custodian:** _______
  - **Authorized risk acceptor (if a time-limited exception is considered):** _______
- **Agreed workload allocation for this review (preparation, participation, testing, follow-up):** _______

## 2. Community and staff participation

Participation is integral to stewardship, with its form and depth proportionate to the consequences of the decision. Staff consultation and community participation provide complementary knowledge and do not substitute for one another.

- **Participation basis & proportionality:**
  - [ ] **Consequential or public-facing use:** Direct community and staff input informs problem definition, alternatives, and evaluation criteria before product or feature activation.
  - [ ] **Routine low-risk internal use:** Relies on documented prior engagement and standing policy (identify the policy and prior engagement: _______).
  - [ ] **Gap in prior community input:** No community input informed the applicable policy. *(Record this gap explicitly rather than treating participation as inherited: _______).*
- **Questions open to participant influence:** _______
- **Authority arrangement for evaluation criteria:**
  - **Criteria requiring joint agreement (changes require renewed agreement through the specified process):** _______
  - **Advisory input (departures require a recorded explanation):** _______
- **Accessibility, language, and outreach provisions (reaching beyond frequent borrowers and enthusiastic adopters):** _______
- **Recorded contributions & changes:** How did community and staff knowledge change the proposed purpose, alternatives, or success measures (for example, replacing raw usage/hold counts with task accuracy, preserved known-item access, and user correction)? _______
- **Disagreements and missing perspectives that limit the decision:** _______

## 3. Data handling and review depth

Check all data categories touched by this specific use:

- [ ] No patron data; nonconfidential internal staff use only
- [ ] De-identified or aggregate library data
- [ ] Patron search queries, conversational prompts, or reference interactions
- [ ] Personally identifiable patron or staff data (PII)
- [ ] Confidential patron records (borrowing history, reading records, account activity)
- [ ] Minors' data

**Review depth trigger:**
- [ ] **Core record only:** Nonconfidential internal use with no patron data, no public outputs, and no consequential effect on access or staff work.
- [ ] **Expanded impact review required:** Triggered if the use processes sensitive/patron data, produces public outputs, changes collection/catalog access or staff work, or shapes a consequential decision. Complete Sections 4–7 in full.

## 4. Vendor data terms and response deadline

- **Local deadline set for vendor clarification:** _______
- **Vendor response status at deadline:** [ ] Full response  [ ] Partial response  [ ] No response  [ ] Not applicable
  *(Note: Vendor silence or nonresponse remains unresolved evidence and never expands permission.)*
- **Model training & isolation:**
  - [ ] **Closed / isolated:** Contract or binding terms verify that inputs are not used to train models and are isolated from other customers (cite document and section: _______).
  - [ ] **Open / unverified:** Inputs may be used for training, subprocessors are undisclosed, or terms govern only test environments while live patron query terms remain unresolved. *(Do not authorize patron data or public activation.)*
- **Local configuration controls:** Can technology staff isolate the feature for staff-only testing with invented queries, disable personalization/account linking, and turn off unapproved vendor updates? _______

## 5. Impact review (the four managerial questions)

Answer each question with the evidence examined, unanswered questions, and **the specific activity prevented by any material uncertainty**. Good Accuracy cannot compensate for unacceptable Enforceability.

- **Accuracy.** How does the feature perform on agreed library tasks compared with existing tools? Which holdings, languages, or interpretations does it miss?
  - *Evidence & limits:* _______
  - *Activity prevented by current uncertainty:* _______
- **Autonomy.** What judgment is delegated to the system (query interpretation, ranking, summarizing, filtering), what human control remains, and are unreviewed functions (such as personalized ordering or automated weeding) excluded?
  - *Evidence & limits:* _______
  - *Activity prevented by current uncertainty:* _______
- **Recourse.** When the system misinterprets a request or produces an error, how can a patron or staff member redirect it, report the concern without exposing unnecessary reading history, and obtain service through a non-AI alternative?
  - *Correction & alternative service route:* _______
  - *Stop / pause trigger:* _______
- **Enforceability.** Are data terms, change notices, and configuration controls contractually enforceable, and does the library have a feasible stop or exit route?
  - *Evidence & limits:* _______
  - *If an essential or imposed platform cannot be withdrawn immediately, specify any time-limited exception controls, named risk acceptor, expiration, and exit route:* _______

## 6. Intellectual freedom and stewardship costs

- **Intellectual freedom check:**
  - [ ] Does not filter, rank, recommend, or flag collection content for patrons.
  - [ ] Shapes what patrons encounter. Explain how alternative catalog/collection access and human mediation are preserved, and confirm that majority preference cannot restrict lawful access: _______
- **Environmental footprint:** Has the vendor disclosed energy, water, or carbon metrics, or would a simpler non-AI / task-specific tool suffice? _______
- **Internal labor & workload:** Whose workflow changes, how were staff consulted, and how does actual review/support effort compare with the agreed workload allocation? *(Efficiency gains support service quality and working conditions, never staff reduction.)* _______
- **Supply-chain labor:** Has the vendor documented labor standards for data labeling and moderation? _______
- **Accessibility & language support:** Does the interface meet accessibility standards and support users across languages and literacy levels? _______

## 7. Authorized disposition and review state

Keep **authorized disposition** (what is permitted now) separate from **review state** (what evaluation work is happening).

**Authorized disposition:**
- [ ] **Authorized within defined scope and conditions:** _______
- [ ] **Limited internal exercise authorized; public activation deferred:** *(Specify isolated test configuration, invented queries, and session/workload cap: _______)*
- [ ] **Time-limited exception with controls (essential/imposed platform):** *(Requires named risk acceptor, compensating controls, expiration date, and escalation/exit route: _______)*
- [ ] **Deferred** (essential evidence or safe test configuration unavailable; specify what is blocked: _______)
- [ ] **Refused / Declined**
- [ ] **Retired / Discontinued**

**Separate review state:**
- [ ] `Review required`
- [ ] `Underway` *(Grants no permission beyond the explicit disposition above; specify pending evidence: _______)*
- [ ] `Complete` *(Note: A completed internal test does not authorize a public pilot without a new decision.)*

**Conditions, stop rules, and next review point:**
- **Permitted scope & explicit exclusions:** _______
- **Immediate stop / escalation triggers (e.g., vendor update outside scope, unapproved data processing):** _______
- **Actual staff effort vs. agreed workload allocation:** _______
- **Next review date or decision meeting & operational consequence at that point:** _______

**Service owner:** _______  
**Reviewer(s):** _______  
**Approving authority:** _______  
**Date:** _______  
**Registry entry created / updated:** [ ] Yes

*Created by Jose Ruiz-Vazquez; Version 0.3.0 prepared with Witt Salley. Licensed under CC BY 4.0: adapt freely for your library with attribution. Version 0.3.0, 2026.*

*Consistent with the American Library Association's Guidance on the Use of Artificial Intelligence in Libraries (2026). An independent resource for public libraries; not an official publication of the American Library Association, Core, or any library system.*
