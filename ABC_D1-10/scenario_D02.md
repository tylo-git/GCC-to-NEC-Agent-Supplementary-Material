# Scenario D02: NEC Douglas D02 - Submitted programme without time risk allowance

**Generated:** 2026-07-07 15:05

## Context
The Contractor submits a detailed programme for acceptance showing the order and timing of operations and details of resources and Equipment. The programme does not show any time risk allowance, and the Contractor says in discussions that it is based on best productivity throughout, resulting in planned Completion one month earlier than the Completion Date.

## MAS Query Topic
> Submitted programme without time risk allowance.

Specific questions to address:
How might the Project Manager reply to the submitted programme?

## Validation Results

### Overall — ✅ PASSED  (confidence: 1.0, iterations used: 1)

> All checks passed (composite confidence 1.00; no per-metric dips; LLM semantic also passed).

### Rule-based Validation (deterministic)

**Track verdict:** ✅ pass

| Metric | Value | Threshold | Status |
|---|---|---|---|
| Citation Accuracy Rate (GCC) | 1.00 | ≥ 0.85 | ✅ pass |
| Citation Accuracy Rate (NEC4) | 1.00 | ≥ 0.85 | ✅ pass |
| Coverage Rate (GCC) | 1.00 | ≥ 0.85 | ✅ pass |
| Coverage Rate (NEC4) | 1.00 | ≥ 0.85 | ✅ pass |
| Composite Confidence | 1.00 | ≥ 0.70 | ✅ pass |
| Clause format | 0 violation(s) | All match regex | ✅ pass |

**GCC anchor coverage:**
  _(no anchors defined for this scenario)_

**NEC4 anchor coverage:**
 ✅ cl. 31.2 ✅ cl. 31.3

### LLM-based Semantic Validation

**Track verdict:** ✅ pass
**Severity:** minor

_No substantive issues raised._

## Comparative Synthesis

> **Executive summary** — GCC does not expressly require time risk allowance but permits Engineer challenge to over-optimistic programmes; NEC expressly requires float and time risk allowances and supports rejection. GCC is ex post and Engineer-led; NEC is relational and prospective, so planning evidence must be produced earlier.

<details>
<summary><b>1. Spirit / Philosophy</b> — Engineer-led claims vs relational planning.</summary>

GCC: The GCC corpus does not use the terms "Project Manager", "time risk allowance", or "compensation events"; administration is by the Engineer, Architect or Surveyor, with time and cost change managed through Variations and Extension of Time claims. The programme is important evidence and a management aid, but approval does not transfer responsibility from the Contractor. In TCE terms, the regime relies more on ex post control, Engineer review, and claims evidence than on a fully relational planning system.

NEC: NEC4 ECC treats the programme as the primary tool for managing time and prospectively assessing compensation events, anchored in mutual trust and co-operation under cl. 10.2. It expressly requires transparent treatment of float and time risk allowances, and links acceptance status to future assessment consequences. In TCE terms, NEC reduces maladaptation and dispute costs by forcing early disclosure, collaborative correction, and prospective risk pricing.

</details>

<details>
<summary><b>2. GCC Position (Implementation)</b> — Programme realism checked, but approval limited.</summary>

**Implementation flow:**

1. Contractor submits initial programme within 14 days of acceptance of the Tender, showing "sequence, method and timing" (Clause 16(1)) →
2. Engineer checks conformity, sufficiency, and whether it is over-optimistic; if so, asks for written explanation (Contract Administration guidelines) →
3. If unconvinced, Engineer states dissatisfaction and requests a revised programme, without instructing how to revise it →
4. For Mega Projects, Engineer replies within 30 days by approval, request for further information, or rejection with reasons (SCC Clause A1(2)) →
5. For Mega Projects, Contractor resubmits within 21 days taking account of the Engineer’s reasons (SCC Clause A1(5)) →
6. Contractor revises whenever an EOT is granted, or on significant deviation in Mega Projects (Clause 50(4); SCC Clause A1(6)).

Under Clause 16(1), the Contractor must submit an initial programme within 14 days of the acceptance of the Tender showing the "sequence, method and timing" proposed to carry out the Works. It must include due allowance for Specialist Works and work by utility undertakings. The standard GCC does not expressly require a graphical "time risk allowance", but the Contractor is practically expected to allow adequate time for foreseeable constraints such as site investigations, temporary works, and utilities so that the programme is realistic.

The Engineer examines the programme against three criteria: conformity with the Contract requirements on sequence, method, and timing; whether it is "over-optimistic in respect of any critical activity or the Works as a whole"; and whether it contains sufficient information for management of the Contract. If realistic float, risk allowances, or foreseeable delays are omitted, the Engineer may treat it as failing the over-optimism criterion. The Engineer should ask the Contractor to explain in writing the basis of programming. If still dissatisfied, the Engineer informs the Contractor of dissatisfaction and requests a revised programme, but must not advise or instruct how it should be revised. Under the standard GCC there is no strict time limit for the Engineer’s reply.

For Mega Projects, SCC Clause A1(2) tightens the process: within 30 days of receipt, the Engineer must approve, request further information, or reject. Rejection must give "reasons for such rejection... including indication of those parts of the programme with which the Engineer is not satisfied". SCC Clause A1(5) then requires the Contractor to submit a revised programme within 21 days taking account of the reasons.

Clause 16(2) provides that submission or approval does not relieve the Contractor of any duty or responsibility. SCC Clause A1(8)(b) similarly states that approval does not bind the Employer nor entitle the Contractor to an Extension of Time. For EOT assessment, the Engineer under Clause 50(2) must consider whether a delay event, such as inclement weather under Clause 50(1)(b), affected critical areas. The corpus states that "float values in a programme are an indication of the relative criticality of activities" and that an EOT should only be granted if delay "is predicted to reduce to below zero the total float on the critical path". Missing float therefore weakens proof that overall completion was affected. Clause 50(4) requires revision whenever an EOT is granted, and SCC Clause A1(6) adds revision where significant deviation from anticipated progress occurs in Mega Projects.

</details>

<details>
<summary><b>3. NEC4 Position (Implementation)</b> — Non-compliant programme may be rejected.</summary>

**Implementation flow:**

1. Contractor submits programme for acceptance, including required float and time risk allowances (cl. 31.1; cl. 31.2) →
2. Project Manager replies within two weeks by acceptance or reasons for non-acceptance (cl. 31.3; cl. 13.4) →
3. If no reply within two weeks, failure is a compensation event (cl. 60.1(6)) →
4. If rejected, Contractor resubmits within the period for reply, taking account of reasons (cl. 13.3; cl. 13.4) →
5. If a compensation event arises before acceptance for a stated reason, Project Manager assesses using own programme assessment (cl. 64.1; cl. 64.2) →
6. Accepted Programme then informs prospective delay and risk assessment (cl. 11.2(1); cl. 63.5; cl. 63.8).

NEC4 ECC requires proactive project management and transparent time control under mutual trust and co-operation (cl. 10.2). The programme is the main instrument for time management and prospective compensation-event assessment. Under cl. 31.1 and cl. 31.2, a submitted programme must show the information required by the contract, expressly including "provisions for float" and "time risk allowances". Time risk allowances are the Contractor’s contingencies for foreseeable risks and delays at the Contractor’s risk. A programme omitting them is fundamentally non-compliant.

Upon receipt, the Project Manager must reply within two weeks under cl. 31.3. Under cl. 13.4, the Project Manager must either accept or notify reasons for not accepting; acceptance may also be withheld if more information is needed to assess the submission fully. Failure to reply within this two-week period is a compensation event under cl. 60.1(6). The permitted cl. 31.3 reasons are that the Contractor’s plans shown are not practicable; the programme does not show the information the contract requires; it does not represent the Contractor’s plans realistically; or it does not comply with the Scope. Missing float and time risk allowances support non-acceptance because the programme "does not show the information which the contract requires" under cl. 31.2 and likely "does not represent the Contractor's plans realistically". Withholding acceptance for a reason stated in the contract is not a compensation event under cl. 13.8.

If mistakenly accepted, the defective programme becomes the Accepted Programme under cl. 11.2(1). Delay to the Completion Date is then assessed prospectively under cl. 63.5 as the length of time planned Completion is later than the planned Completion shown on the Accepted Programme current at the dividing date. Under cl. 63.8, compensation-event assessment must include risk allowances for cost and time for matters with a significant chance of occurring and at the Contractor’s risk. Without float or time risk allowances in the Accepted Programme, the Contractor has stripped out its buffer and complicated assessment of concurrent delays.

If rejected, the Contractor must resubmit within the period for reply under cl. 13.3, taking the Project Manager’s reasons into account under cl. 13.4. If a compensation event arises while the latest programme has not been accepted for a reason stated in the contract, the Contractor loses the right to assess it; the Project Manager assesses using their own assessment of the programme for the remaining work under cl. 64.1 and cl. 64.2. cl. 32.2 and cl. 60.1(9) are cited in the clause set, but no further operative detail was provided in the expert response.

</details>

<details>
<summary><b>4. Behavioural Implications</b> — Earlier planning discipline drives entitlement.</summary>

Under GCC, the Contractor’s immediate behavioural burden is to submit a plausible Clause 16(1) programme within 14 days, then defend its realism if the Engineer challenges it as over-optimistic. The Contractor should preserve the logic behind activity durations, float, utilities, Specialist Works, temporary works and foreseeable constraints, because omission of float later undermines proof under Clause 50(2) that a Clause 50(1)(b) or other delay affected critical areas. The Engineer’s behaviour is supervisory rather than co-planning: request a written explanation, state dissatisfaction, and request revision, but do not instruct the Contractor how to revise.

Under NEC, the behavioural incentives are sharper and earlier. The Contractor must submit a programme for acceptance under cl. 31.1 and cl. 31.2 that expressly shows float and time risk allowances; otherwise the Project Manager should reply within two weeks under cl. 31.3 and cl. 13.4 with contractual reasons for non-acceptance. Silence is risky for the Employer because no reply within two weeks is a compensation event under cl. 60.1(6). Rejection also carries consequences for the Contractor: if a compensation event arises before a compliant programme is accepted, cl. 64.1 and cl. 64.2 allow the Project Manager to assess using their own programme assessment. Thus NEC turns planning discipline from a later EOT evidential issue into a live condition for commercial self-assessment and collaborative administration.

**Implementation comparison (GCC vs NEC4):**

| Aspect | GCC | NEC4 |
|---|---|---|
| Programme submission | Within 14 days after Tender acceptance (Clause 16(1)). | Submitted for acceptance with required content (cl. 31.1; cl. 31.2). |
| Float or risk allowance | Not express; omission may be over-optimistic (Clause 16(1)). | Express "float" and "time risk allowances" required (cl. 31.2). |
| Administrator reply | No standard strict limit; Mega Projects 30 days (SCC A1(2)). | Project Manager replies within two weeks (cl. 31.3; cl. 13.4). |
| Reasons for rejection | Mega rejection gives reasons and unsatisfactory parts (SCC A1(2)). | Must state contractual non-acceptance reasons (cl. 31.3; cl. 13.4). |
| Resubmission | Mega revised programme within 21 days (SCC A1(5)). | Resubmit within period for reply (cl. 13.3). |
| Delay consequence | Float supports EOT criticality proof (Clause 50(1)(b); Clause 50(2)). | Accepted Programme drives cl. 63.5; rejection triggers cl. 64.1/64.2 risk. |


</details>

<details>
<summary><b>5. GCC Lessons for NEC Adoption</b> — GCC claim habits become NEC planning tools.</summary>

Start with the familiar Clause 16(1) discipline: Hong Kong GCC practitioners already know how to prepare a programme showing "sequence, method and timing" within 14 days of Tender acceptance. Under NEC, that skill transfers directly to cl. 31.1 and cl. 31.2, but the behavioural adjustment is precision: float and time risk allowances must be shown expressly, not left implicit in activity durations.

The GCC workflow for an over-optimistic programme also transfers. Under GCC practice the Engineer may ask for a written explanation, state dissatisfaction, and request revision; in Mega Projects SCC Clause A1(2) requires a 30-day reply and reasons, while SCC Clause A1(5) requires resubmission within 21 days. Under NEC, the same exchange becomes a stricter acceptance mechanism: the Project Manager replies within two weeks under cl. 31.3 and cl. 13.4, and the Contractor resubmits within the period for reply under cl. 13.3. The adjustment is timing and purpose: the response is not merely to satisfy review, but to protect the Accepted Programme platform.

GCC EOT practice under Clause 50(1)(b), Clause 50(2), and Clause 50(4) gives a useful foundation. Practitioners used to proving critical delay, total float impact, and revised programmes should apply that analysis prospectively under NEC cl. 63.5 and cl. 63.8. The adjustment is forecasting: use float and risk allowances to price and assess compensation events before delay crystallises.

Finally, the GCC understanding that Clause 16(2) and SCC Clause A1(8)(b) approval does not relieve responsibility should be retained, but reframed. Under NEC, mistaken acceptance creates an Accepted Programme under cl. 11.2(1), while non-acceptance may lead to Project Manager assessment under cl. 64.1 and cl. 64.2. GCC claim, record, variation, and delay-analysis habits should therefore be used earlier as NEC planning, acceptance, and compensation-event management tools.

| GCC practice / experience | → How it transfers to NEC implementation |
|---|---|
| Clause 16(1) sequence, method and timing programme. | cl. 31.1/cl. 31.2 programme; expressly show float and time risk allowances. |
| Engineer challenge to over-optimistic programme. | cl. 31.3/cl. 13.4 non-acceptance; answer stated reasons promptly. |
| SCC A1(2) rejection reasons workflow. | cl. 13.4 reasons; treat reply as contractual acceptance control. |
| Clause 50(2) criticality and total-float EOT proof. | cl. 63.5 assessment; forecast planned Completion impact prospectively. |
| Clause 50(4) and SCC A1(6) revised programmes. | Accepted Programme management; avoid cl. 64.1/cl. 64.2 PM assessment. |

</details>

<details>
<summary><b>6. HK-Specific Notes</b> — PAH and DEVB sharpen programme practice.</summary>

For GCC, the Project Administration Handbook PAH Chapter 5, Appendix 5.36 prescribes SCC Clause A1 for "Mega Project Contracts". This significantly tightens the standard GCC programme process by introducing SCC Clause A1(2), which requires the Engineer to reply within 30 days of receipt by approving, requesting further information, or rejecting. If rejecting, the Engineer must give "reasons for such rejection... including indication of those parts of the programme with which the Engineer is not satisfied". SCC Clause A1(5) imposes a 21-day limit for the Contractor to submit a revised programme taking account of those reasons. SCC Clause A1(6) requires revision when significant deviation from anticipated progress occurs. SCC Clause A1(8)(b) confirms that approval does not bind the Employer nor entitle the Contractor to an EOT.

Hong Kong GCC training material in the corpus, including "Seminar reviewing Chapter 4 Time Extension Delays", emphasises the necessity of identifying total float for EOT claims. The corpus states that "float values in a programme are an indication of the relative criticality of activities" and that an EOT should only be granted if delay "is predicted to reduce to below zero the total float on the critical path". This makes realistic float a practical necessity for Hong Kong public works contractors even though standard GCC does not use the phrase "time risk allowance". Works Bureau Technical Circular WB1900 does not address this aspect.

For NEC4 ECC in Hong Kong, the DEVB Practice Notes of July 2023 and December 2024 specifically address substandard programmes missing float and time risk allowances. They identify as a "common pitfall" that the Contractor’s submitted programme is not up to the contract requirements because of a "lack of focus on planning and programming... which makes it difficult to understand what considerations have been taken into account in float, time risk allowances".

The DEVB Practice Notes advise that, where a programme is repeatedly substandard and cannot be accepted, the Project Manager should arrange a joint meeting or workshop among the key staff who prepare and assess the programme. In that workshop, "the definitions of terms namely 'float' and 'time risk allowances' and their provisions in the programme should also be elaborated to ensure mutual understanding of their importance".

The DEVB also advises a pragmatic approach to avoid the project operating without an Accepted Programme, because that would force the Project Manager to assess compensation events using their own assessment under cl. 64.2 and undermine NEC’s collaborative ethos. The Project Manager may conditionally accept a sub-programme showing detailed planning for the upcoming 3 to 12 months, with minimum required details for later activities, rather than rejecting the entire submission and derailing the compensation-event framework.

</details>

## Clause Map (extracted by CM-A)

Structured index of every clause cited by the expert agents, with its taxonomy category and a verbatim quote / paraphrase.

- **GCC · Clause 16(1)** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **within 14 days of the acceptance of the Tender** · condition: **acceptance of the Tender**
  > Under Clause 16(1), the Contractor is obligated to submit an initial programme within 14 days of the acceptance of the Tender showing the "sequence, method and timing" proposed to carry out the Works.
- **GCC · Clause 16(2)** — _programme_obligations_ · obligation: **condition** · party: **Contractor** · condition: **submission or approval of the programme**
  > Under Clause 16(2), the submission or approval of the programme does not relieve the Contractor of any duty or responsibility under the Contract.
- **GCC · Clause 50(1)(b)** — _extension_of_time_ · obligation: **condition** · party: **n/a** · condition: **a delay event (e.g., inclement weather under Clause 50(1)(b)) affected critical areas**
  > For the Engineer to evaluate an EOT under Clause 50(2), they must assess whether a delay event (e.g., inclement weather under Clause 50(1)(b)) affected critical areas.
- **GCC · Clause 50(2)** — _extension_of_time_ · obligation: **process** · party: **Engineer** · condition: **whether a delay event (e.g., inclement weather under Clause 50(1)(b)) affected critical areas**
  > For the Engineer to evaluate an EOT under Clause 50(2), they must assess whether a delay event (e.g., inclement weather under Clause 50(1)(b)) affected critical areas.
- **GCC · Clause 50(4)** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **whenever an EOT is granted** · condition: **an EOT is granted**
  > Revised Programmes: The Contractor has a continuing obligation to revise the programme whenever an EOT is granted (Clause 50(4)) or, in Mega Projects, when a significant deviation from anticipated progress occurs (SCC A1(6)).
- **NEC4 · cl. 10.2** — _mutual_trust_ · obligation: **duty** · party: **both**
  > The NEC4 ECC demands proactive project management and transparent time control, anchored in the spirit of mutual trust and co-operation (cl. 10.2).
- **NEC4 · cl. 11.2(1)** — _uncategorised_ · obligation: **definition** · party: **n/a** · condition: **If the Project Manager mistakenly accepts a programme without time risk allowances or float**
  > If the Project Manager mistakenly accepts a programme without time risk allowances or float, it becomes the Accepted Programme (cl. 11.2(1)).
- **NEC4 · cl. 13.3** — _uncategorised_ · obligation: **duty** · party: **Contractor** · timeline: **within the period for reply** · condition: **If Rejected**
  > The Contractor is obligated to resubmit a revised programme within the period for reply (cl. 13.3), taking the Project Manager's reasons into account (cl. 13.4).
- **NEC4 · cl. 13.4** — _mutual_trust_ · obligation: **process** · party: **PM** · timeline: **within two weeks** · condition: **Upon receiving a programme submission**
  > The Project Manager must either accept the programme or notify the Contractor of their reasons for not accepting it (cl. 13.4).
- **NEC4 · cl. 31.1** — _programme_obligations_ · obligation: **process** · party: **Contractor**
  > Contractor submits a programme for acceptance which fails to show required provisions for float and time risk allowances (cl. 31.1, cl. 31.2).
- **NEC4 · cl. 31.2** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · condition: **When the Contractor submits a programme for acceptance**
  > When the Contractor submits a programme for acceptance, it must satisfy the stringent content requirements of cl. 31.2. The contract expressly mandates that the Contractor shows "provisions for float" and "time risk allowances" on each submitted programme.
- **NEC4 · cl. 31.3** — _programme_obligations_ · obligation: **process** · party: **PM** · timeline: **within two weeks** · condition: **Upon receiving a programme submission**
  > Upon receiving a programme submission, the Project Manager has a duty to reply to the Contractor within two weeks (cl. 31.3).
- **NEC4 · cl. 32.2** — _programme_obligations_ · obligation: **process** · party: **n/a**
  > cl. 32.2
- **NEC4 · cl. 60.1(6)** — _compensation_event_notification_quotation_assessment_ · obligation: **remedy** · party: **PM** · timeline: **within this two-week period** · condition: **Failure by the Project Manager to reply**
  > Failure by the Project Manager to reply within this two-week period is a compensation event (cl. 60.1(6)).
- **NEC4 · cl. 60.1(9)** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **n/a**
  > cl. 60.1(9)
- **NEC4 · cl. 63.5** — _extension_of_time_ · obligation: **remedy** · party: **n/a** · timeline: **at the dividing date** · condition: **If Accepted**
  > Delay to the Completion Date (Extension of Time) is prospectively assessed as the length of time that planned Completion is later than the planned Completion shown on the Accepted Programme current at the dividing date (cl. 63.5).
- **NEC4 · cl. 63.8** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **n/a** · condition: **matters which have a significant chance of occurring and are at the Contractor's risk**
  > the assessment of a compensation event must include risk allowances for cost and time for matters which have a significant chance of occurring and are at the Contractor's risk (cl. 63.8).
- **NEC4 · cl. 64.1** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **if a compensation event arises and the Project Manager has not accepted the Contractor's latest programme for a reason stated in the contract**
  > the Contractor loses the right to assess the compensation event. Instead, the Project Manager makes their own assessment using their own assessment of the programme for the remaining work (cl. 64.1, cl. 64.2).
- **NEC4 · cl. 64.2** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **if a compensation event arises and the Project Manager has not accepted the Contractor's latest programme for a reason stated in the contract**
  > the Project Manager makes their own assessment using their own assessment of the programme for the remaining work (cl. 64.1, cl. 64.2).
- **NEC4 · cl. 13.8** — _change_management_ · obligation: **condition** · party: **PM** · condition: **Withholding acceptance for a reason stated in the contract**
  > Withholding acceptance for a reason stated in the contract is not a compensation event (cl. 13.8).

## Raw Expert Evidence (NotebookLM responses)

The full unmodified responses from the GCC and NEC4 expert agents are reproduced below for traceability.

<details>
<summary>GCC expert response (1 iteration(s), 6,022 chars)</summary>

[CLAUSE REFERENCES] Clause 16(1), Clause 16(2), Clause 50(1)(b), Clause 50(2), Clause 50(4), Special Conditions of Contract (SCC) Clause A1(2), SCC Clause A1(5), SCC Clause A1(6), SCC Clause A1(8)(b).
[GCC POSITION] Note: The GCC corpus does not use the terms "Project Manager", "time risk allowance", or "compensation events". Contract administration is managed by the "Engineer" (or Architect/Surveyor), and cost/time changes are administered via "Variations" and "Extension of Time" claims.
Contractual Requirements for Programme Content and Submission Under Clause 16(1), the Contractor is obligated to submit an initial programme within 14 days of the acceptance of the Tender showing the "sequence, method and timing" proposed to carry out the Works. The programme must include due allowance for the carrying out of Specialist Works and work by utility undertakings. While the standard GCC does not explicitly dictate the graphical display of a "time risk allowance", the Contractor is practically required to allocate adequate time for foreseeable constraints (e.g., site investigations, temporary works, utilities) to ensure the programme is realistic.
Grounds for Reply: Assessing "Over-optimistic" Programmes The Engineer examines the submitted programme against three specific criteria: (a) Conformity with the requirements of the Contract regarding sequence, method, and timing; (b) Whether the programme is "over-optimistic in respect of any critical activity or the Works as a whole"; and (c) Sufficiency of information for the management of the Contract. If the programme omits realistic float, risk allowances, or foreseeable delays, the Engineer will assess it as failing criterion (b) (i.e., being "over-optimistic").
The Reply Process, Reasons, and Timing If the programme is deemed over-optimistic, the Engineer must ask the Contractor to explain in writing the basis of their programming. If the Engineer remains unconvinced, they must inform the Contractor of their dissatisfaction and request a revised programme. Crucially, the Engineer must not advise or instruct the Contractor on how the programme should be revised. Under the standard GCC, there is no strict time limit for the Engineer's reply. However, for Mega Projects, SCC Clause A1(2) mandates that the Engineer must respond within 30 days of receipt by either approving it, requesting further information, or rejecting it. If rejecting, the Engineer must provide "reasons for such rejection... including indication of those parts of the programme with which the Engineer is not satisfied".
Consequences of Acceptance and Practical Effects
Status of Acceptance: Under Clause 16(2), the submission or approval of the programme does not relieve the Contractor of any duty or responsibility under the Contract. For Mega Projects, SCC A1(8)(b) reiterates that approval does not bind the Employer nor entitle the Contractor to an Extension of Time (EOT).
Delay Assessment and Float: The omission of float severely compromises future delay management. The corpus states that "float values in a programme are an indication of the relative criticality of activities". For the Engineer to evaluate an EOT under Clause 50(2), they must assess whether a delay event (e.g., inclement weather under Clause 50(1)(b)) affected critical areas. An EOT should only be granted if the delay "is predicted to reduce to below zero the total float on the critical path". A programme lacking float makes it nearly impossible for the Contractor to prove that a delay event truly impacted the overall completion date.
Revised Programmes: The Contractor has a continuing obligation to revise the programme whenever an EOT is granted (Clause 50(4)) or, in Mega Projects, when a significant deviation from anticipated progress occurs (SCC A1(6)).
[PROCEDURAL IMPLICATION]
Contractor submits the initial programme showing sequence, method, and timing within 14 days of Tender acceptance (Clause 16(1)).
Engineer analyzes the programme for conformity, sufficiency of information, and realism to ensure it is not over-optimistic (Contract Administration guidelines).
If the programme is deemed over-optimistic due to the omission of reasonable float or risk allowances, the Engineer requests the Contractor to explain the basis of their programming in writing.
If dissatisfied with the explanation, the Engineer informs the Contractor of dissatisfaction and requests a revised programme, without instructing the Contractor on how to revise it.
(For Mega Projects) Engineer formally notifies the Contractor within 30 days of receipt whether the programme is approved, rejected with reasons, or if further information is required (SCC A1(2)).
(For Mega Projects) If rejected, Contractor submits a revised programme taking into account the Engineer's reasons within 21 days (SCC A1(5)).
Contractor executes the works; if an EOT is granted later, Contractor revises the programme accordingly (Clause 50(4)).
[HK CONTEXT] The Project Administration Handbook (PAH) Chapter 5 (Appendix 5.36) prescribes SCC Clause A1 for "Mega Project Contracts", which significantly tightens the programme submission and review process compared to the standard GCC. It introduces a strict 30-day limit for the Engineer to reply, mandates that reasons be given for rejection, and imposes a 21-day limit for the Contractor to resubmit.
Furthermore, engineering training guidelines within the corpus (e.g., "Seminar reviewing Chapter 4 Time Extension Delays") emphasize the absolute necessity of identifying total float for EOT claims, making the inclusion of realistic float a practical necessity for Hong Kong public works contractors, even if the term "time risk allowance" is not explicitly utilized in the GCC text. Works Bureau Technical Circular WB1900 does not address this aspect.
How does the Engineer verify measurement for interim payment certificates?
What happens if a Contractor disagrees with the Engineer's valuation?
Explain the rules for valuing variations when no rates apply.

</details>

<details>
<summary>NEC4 expert response (1 iteration(s), 6,568 chars)</summary>

[CLAUSE REFERENCES] cl. 10.2, cl. 11.2(1), cl. 13.3, cl. 13.4, cl. 31.1, cl. 31.2, cl. 31.3, cl. 32.2, cl. 60.1(6), cl. 60.1(9), cl. 63.5, cl. 63.8, cl. 64.1, cl. 64.2
[NEC POSITION] The NEC4 ECC demands proactive project management and transparent time control, anchored in the spirit of mutual trust and co-operation (cl. 10.2). The programme is the primary tool for managing time and prospectively assessing compensation events.
Programme Content Requirements and Non-Compliance: When the Contractor submits a programme for acceptance, it must satisfy the stringent content requirements of cl. 31.2. The contract expressly mandates that the Contractor shows "provisions for float" and "time risk allowances" on each submitted programme. Time risk allowances are the Contractor's contingencies for foreseeable risks and delays that are at their own risk. A programme omitting these provisions is fundamentally non-compliant with the contract.
Project Manager’s Powers, Duties, and Time Limits for Reply: Upon receiving a programme submission, the Project Manager has a duty to reply to the Contractor within two weeks (cl. 31.3). The Project Manager must either accept the programme or notify the Contractor of their reasons for not accepting it (cl. 13.4). Failure by the Project Manager to reply within this two-week period is a compensation event (cl. 60.1(6)).
Express Grounds for Non-Acceptance: The Project Manager may only withhold acceptance for the four permitted reasons listed in cl. 31.3:
The Contractor's plans which it shows are not practicable;
It does not show the information which this contract requires;
It does not represent the Contractor's plans realistically; or
It does not comply with the Scope. Additionally, cl. 13.4 provides that acceptance may be withheld if more information is needed to assess the submission fully. If a programme omits time risk allowances and float, the Project Manager has strict contractual grounds to reject it because "it does not show the information which the contract requires" (violating cl. 31.2) and likely "does not represent the Contractor's plans realistically" (as foreseeable delays are inevitable). Withholding acceptance for a reason stated in the contract is not a compensation event (cl. 13.8).
Consequences for Delay Assessment, EoT, and Future Risk:
If Accepted: If the Project Manager mistakenly accepts a programme without time risk allowances or float, it becomes the Accepted Programme (cl. 11.2(1)). Delay to the Completion Date (Extension of Time) is prospectively assessed as the length of time that planned Completion is later than the planned Completion shown on the Accepted Programme current at the dividing date (cl. 63.5). Furthermore, the assessment of a compensation event must include risk allowances for cost and time for matters which have a significant chance of occurring and are at the Contractor's risk (cl. 63.8). Without float or time risk allowances established in the Accepted Programme, the Contractor has stripped themselves of their own buffer, making them highly vulnerable to their own risk events and severely complicating the assessment of concurrent delays.
If Rejected: The Contractor is obligated to resubmit a revised programme within the period for reply (cl. 13.3), taking the Project Manager's reasons into account (cl. 13.4). Crucially, if a compensation event arises and the Project Manager has not accepted the Contractor's latest programme for a reason stated in the contract (such as missing cl. 31.2 information), the Contractor loses the right to assess the compensation event. Instead, the Project Manager makes their own assessment using their own assessment of the programme for the remaining work (cl. 64.1, cl. 64.2).
[PROCEDURAL IMPLICATION]
Contractor submits a programme for acceptance which fails to show required provisions for float and time risk allowances (cl. 31.1, cl. 31.2).
Project Manager assesses the submitted programme and replies to the Contractor within two weeks, notifying non-acceptance (cl. 31.3).
Project Manager explicitly states the contractual reasons for non-acceptance in the reply, citing that the programme "does not show the information which the contract requires" (as cl. 31.2 requires float and time risk allowances) and "does not represent the Contractor's plans realistically" (cl. 13.4, cl. 31.3).
Contractor resubmits the programme within the period for reply, correcting the deficiencies by incorporating float and time risk allowances to take account of the Project Manager's reasons (cl. 13.4).
Project Manager (if a compensation event occurs before a compliant programme is accepted) assesses the compensation event using their own assessment of the programme for the remaining work because the latest programme was not accepted for a stated reason (cl. 64.1, cl. 64.2).
[HK CONTEXT] The DEVB Practice Notes (July 2023 / December 2024) specifically address the practical problem of substandard programmes missing float and time risk allowances in Hong Kong projects:
A Common Pitfall: DEVB explicitly identifies it as a "common pitfall" that the Contractor’s submitted programme is not up to the requirements of the contract specifically because of a "lack of focus on planning and programming... which makes it difficult to understand what considerations have been taken into account in float, time risk allowances".
Joint Workshops: If a programme is repeatedly substandard and cannot be accepted, the DEVB advises the Project Manager to arrange a joint meeting or workshop among the key staff who prepare and assess the programme. During this workshop, "the definitions of terms namely 'float' and 'time risk allowances' and their provisions in the programme should also be elaborated to ensure mutual understanding of their importance".
Pragmatic Acceptance: To prevent the project from operating without an Accepted Programme—which forces the Project Manager to assess compensation events using their own assessment (cl. 64.2) and undermines the collaborative ethos—the DEVB advises taking a "pragmatic approach". The Project Manager may conditionally accept a sub-programme showing detailed planning for the upcoming 3 to 12 months, with minimum required details for later activities, rather than rejecting the entire submission and derailing the compensation event framework.
What are the common pitfalls in Hong Kong regarding Time Risk Allowances?
How does the Project Manager assess an event when no programme is accepted?
Can a Project Manager accept a programme missing float in Hong Kong?

</details>

## SYN-A Chain-of-Thought Reasoning

<details>
<summary>Three-level reasoning trace (L1 → L2 → L3)</summary>

PART 1 — Chain-of-thought reasoning

[L1 — Spirit/Philosophy]  
GCC treats the programme as an Engineer-reviewed planning submission but not as the central commercial engine of the contract. Its philosophy is more administratively hierarchical and claims-oriented: the Contractor plans and bears responsibility, the Engineer reviews for realism, and later delay relief is tested through EOT analysis under Clause 50. In Transaction Cost Economics terms, GCC relies more on ex post control, evidential discipline, and Engineer certification than on a relational, continuously updated planning platform. NEC4 ECC instead makes the programme a live management instrument within mutual trust and co-operation under cl. 10.2. Its governance is relational and process-based: acceptance, non-acceptance, compensation-event assessment, risk allowances, and future delay forecasting are integrated so that time risk is managed prospectively rather than reconstructed retrospectively.

[L2 — Clause-level Comparison]  
Under GCC Clause 16(1), the Contractor submits the initial programme within 14 days of acceptance of the Tender, showing the “sequence, method and timing” and allowing for Specialist Works and utility undertakings. Clause 16(2) prevents submission or approval from relieving the Contractor of contractual responsibility. The Engineer may treat a programme with omitted float or risk allowance as over-optimistic, ask for a written explanation, and request revision, but under the standard GCC there is no strict reply period. For Mega Projects, SCC Clause A1(2) requires a reply within 30 days by approval, request for further information, or rejection with reasons, including indication of unsatisfactory parts; SCC Clause A1(5) requires resubmission within 21 days; SCC Clause A1(6) requires revision on significant deviation; SCC Clause A1(8)(b) confirms approval does not bind the Employer or entitle EOT. Delay consequences are then tested under Clause 50(1)(b), Clause 50(2), and Clause 50(4). NEC4 is more explicit: cl. 31.1 and cl. 31.2 require a programme for acceptance showing “provisions for float” and “time risk allowances”; cl. 31.3 requires the Project Manager’s reply within two weeks and limits non-acceptance to stated grounds; cl. 13.4 requires acceptance or reasons, while cl. 13.3 drives resubmission within the period for reply. No reply is a compensation event under cl. 60.1(6); proper withholding is not a compensation event under cl. 13.8. If accepted, the programme becomes the Accepted Programme under cl. 11.2(1) and informs cl. 63.5 and cl. 63.8 assessments. If not accepted for a stated reason, cl. 64.1 and cl. 64.2 shift assessment to the Project Manager. cl. 32.2 and cl. 60.1(9) are cited in the NEC clause set but no further operative detail is provided in the expert response.

[L3 — Practice/Behavioural Implications + GCC-to-NEC Transfer]  
In practice, a Hong Kong GCC-trained team is used to submitting an initial Clause 16(1) programme, defending its realism if challenged, maintaining records, and later proving under Clause 50(2) that a delay affected critical activities and reduced float. That workflow transfers to NEC, but timing and purpose change. The GCC habit of showing sequence, method and timing maps to cl. 31.1 and cl. 31.2, where the submitted programme must expressly show float and time risk allowances before it can become commercially useful. The GCC practice of answering the Engineer’s concerns about an over-optimistic programme maps to NEC non-acceptance under cl. 31.3 and cl. 13.4, but NEC requires the Project Manager to state contractual reasons within two weeks and expects the Contractor to resubmit within the period for reply under cl. 13.3. The GCC EOT discipline under Clause 50(1)(b), Clause 50(2), and Clause 50(4)—criticality, total float, revised programmes—maps to the NEC Accepted Programme and prospective assessment under cl. 63.5 and cl. 63.8. The behavioural adjustment is to move float, risk allowance, and causation evidence upstream: not merely as later claim proof, but as the baseline for acceptance, compensation-event pricing, and avoiding Project Manager assessment under cl. 64.1 and cl. 64.2.

</details>

---

### Query Plan (QP-A)
- **L1 (spirit):**     How does the contract’s programme regime reflect its governance philosophy on proactive time management, risk allocation, and collaborative administration of the works?
- **L2 (clauses):**    What clauses govern the required contents of a submitted programme, including any requirement for time risk allowance or float, and what rights or duties does the Project Manager or contract administrator have when replying to a non-compliant submission?
- **L3 (practice):**   In practice, how might rejection, acceptance, qualified acceptance, or silence affect the contractor’s planning discipline, entitlement to extensions of time, and administration of future delay events?
- **canonical_topic:** `programme_obligations`

### Anchor Clauses (scenario ground-truth, used for CR)
- **GCC anchors:**  (none)
- **NEC4 anchors:** cl. 31.2, cl. 31.3

*Generated by MAS v2.2 — LangGraph orchestrator (6 agents + 3 rule modules).*