# Scenario D03: NEC Douglas D03 - Coordination with a separately engaged specialist contractor

**Generated:** 2026-07-07 16:02

## Context
The Client has a separate NEC contract with a specialist Contractor on the same project. The work of both Contractors needs careful coordination. The Contractor must have certain parts of the works ready so that the specialist Contractor can complete its works by a specific date before the Completion Date.

## MAS Query Topic
> Coordination with a separately engaged specialist contractor.

Specific questions to address:
Explain what provision in the contract could help the Client co-ordinate the two Contractors' works, whilst protecting against additional costs? Explain any limitations.

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
 ✅ cl. 25.1 ✅ cl. 31.2 ✅ cl. 60.1(5)

### LLM-based Semantic Validation

**Track verdict:** ✅ pass
**Severity:** minor

_No substantive issues raised._

## Comparative Synthesis

> **Executive summary** — Both contracts allow coordination of separate contractors while barring payment for ordinary, defined interface duties; relief arises only for excess instructions or failures by Others. GCC is Engineer-led and claims-based; NEC is relational and programme-led, requiring earlier Scope, programme and notice discipline.

<details>
<summary><b>1. Spirit / Philosophy</b> — Engineer-led claims vs relational planning.</summary>

GCC: The GCC approach is Engineer-led, specification/drawing-based and claims-oriented. It permits the Employer to engage Specialist Contractors for concurrent Specialist Works, but shifts ordinary, described coordination into the Contractor’s tendered risk through Clause 14, Clause 16(1), Clause 34 and SCC Clause A2. In TCE terms, it controls interface opportunism through ex ante pricing, notices, Engineer instructions and after-the-event EOT/cost claims.

NEC: NEC4 ECC treats separately engaged specialist contractors as “Others” under cl. 11.2(12) and manages them through Scope, Accepted Programme, compensation events and the duty to act in a spirit of mutual trust and co-operation under cl. 10.1 and cl. 10.2. Its governance is relational and process-based: the parties reduce transaction costs by making interfaces visible early, updating programmes and assessing change prospectively rather than relying mainly on retrospective claims.

</details>

<details>
<summary><b>2. GCC Position (Implementation)</b> — Tendered coordination with bounded relief.</summary>

**Implementation flow:**

1. Contractor submits initial programme within 14 days of Tender acceptance, allowing for described Specialist Works and utility works (Clause 16(1)) →
2. Engineer requires reasonable facilities, access and services for others; Contractor must not impede them (Clause 34(1); SCC Clause A2; SCC Clause A3/Clause 48(3)) →
3. Contractor consults, liaises, cooperates and prepares joint programmes, method statements, coordination drawings and specifications at no additional cost for baseline duties (Clause 34(2); Clause 34(3)(a); Clause 14) →
4. If instruction exceeds baseline facilities/access, Contractor gives written notice before taking action, stating estimated delay and Cost (Clause 34(3)(b)(i)) →
5. Engineer evaluates and, if necessary, gives explicit written instruction before EOT route arises (Clause 34(3)(b)(ii); SCC Clause A4/Clause 50(1)(b)(xi)) →
6. For actual delay/cost, Contractor gives probable-delay notice within 28 days of delay arising and cost-claim notice within 28 days of the event; Engineer assesses EOT and Disturbance Cost (Clause 50(1)(a); Clause 64(2); Clause 50(3); Clause 63(d)).

The GCC corpus does not use “Scope”, “Works Information”, or “compensation events”; technical requirements sit in the Specification and Drawings, while relief is through Variations, Claims and EOT. Clause 1(1) recognises that the Employer may engage “Specialist Contractors” to execute “Specialist Works” concurrently with the main Contractor, but baseline obligations must be identifiable in the contract documents. Clause 16(1) requires the Contractor’s programme, submitted within 14 days of Tender acceptance, to show “due allowance for the carrying out of Specialist Works and work by utility undertakings” where described in the Contract.

Clause 34 is the main interface provision and is expanded for complex or Mega Projects by SCC Clause A2. SCC Clause A3 amending Clause 48(3) states that the Contractor “shall not be entitled to exclusive possession of or uninterrupted access to the Site”. Amended Clause 34(1) requires the Contractor to “not impede and shall afford all reasonable facilities, access and/or services” to persons working on or adjacent to the Site. Clause 34(2) requires the Contractor to “take all reasonable steps to ensure that the Works are coordinated and integrated” with other works, including to “consult, liaise and cooperate... including where necessary in the preparation of joint programmes, method statements, coordination drawings and specifications”.

Cost exposure is limited by Clause 34(3)(a) and Clause 14: the Contractor “shall be deemed to have made adequate allowance in his Tender and in the Works Programme” for Clause 34(1) and Clause 34(2) obligations, so ordinary coordination is not extra payment. Clause 50(1)(b)(iv) was cited in the GCC response; the operative interface relief described was Clause 50(1)(b)(vii) and SCC Clause A4 amending Clause 50(1)(b)(xi).

Limits arise where the Engineer changes contractual sequence, method or timing: “changes to any sequence, method or timing of construction specified in the Contract” are Variations under Clause 60(1)(b). If facilities/access exceed Clause 34(1) baseline, Clause 34(3)(b) is a condition precedent: prior written notice with estimated delay and Cost, then explicit written Engineer instruction. Disruption by Specialist Contractors or Employer-engaged persons gives EOT under Clause 50(1)(b)(vii) and Disturbance Cost under Clause 63(d), subject to SCC A2 excluding cost relief to the extent caused or contributed to by the Contractor’s own failure to fulfil Clause 34 duties.

</details>

<details>
<summary><b>3. NEC4 Position (Implementation)</b> — Scope-defined cooperation and CE control.</summary>

**Implementation flow:**

1. Client defines Working Area sharing, interface constraints and expected work of Others in the Scope before tender / prior to the Contract Date (cl. 25.1; cl. 25.2; cl. 31.2) →
2. Contractor submits each programme showing order and timing of Client/Others’ work as agreed or as stated in the Scope (cl. 31.2) →
3. Contractor exchanges information, shares Working Areas as stated in the Scope, and provides access as notified by the Project Manager (cl. 25.1; cl. 27.1; cl. 27.2) →
4. Project Manager instructs any new coordination requirement or changed sequence by changing the Scope and notifies a compensation event (cl. 14.3; cl. 60.1(1); cl. 61.1) →
5. If Others depart from the Accepted Programme, Scope conditions, or do unstated Site work, Contractor notifies a compensation event within 8 weeks of becoming aware (cl. 60.1(5); cl. 61.3) →
6. Project Manager assesses delay and additional Defined Cost caused by the change or failure by Others and implements the compensation event.

NEC4 ECC manages separately engaged specialist contractors as “Others” under cl. 11.2(12), through transparent planning, prospective risk management and the obligation to act in a spirit of mutual trust and co-operation under cl. 10.1 and cl. 10.2. The Contractor’s obligations are strict but bounded. Under cl. 25.1, the Contractor must co-operate with Others in obtaining and providing information needed in connection with the works, but is only obliged to share the Working Areas with Others “as stated in the Scope”. Under cl. 25.2, the Contractor and Client provide services and other things to each other as stated in the Scope.

Access is also controlled. Under cl. 27.1 and cl. 27.2, the Contractor must provide access to work being done and to Plant and Materials to Others as notified by the Project Manager. Sequencing is programme-led: cl. 31.2 requires each programme submitted for acceptance to show the order and timing of the work of the Client and Others as last agreed with them or, if not agreed, as stated in the Scope.

The Client limits exposure by detailing the presence, sequencing, space-sharing and interface requirements in the Scope before tender / prior to the Contract Date, so the Contractor prices and programmes that defined level of cooperation. The Client cannot demand unforeseen cooperation, resequencing or special attendance beyond the contract documents without compensation.

If additional coordination, resequencing or access is required, the Project Manager gives an instruction changing the Scope under cl. 14.3; this is a compensation event under cl. 60.1(1), and cl. 61.1 addresses Project Manager notification. The Contractor is also protected where Others cause the interface failure. Under cl. 60.1(5), it is a compensation event if the Client or Others do not work within the times shown on the Accepted Programme, do not work within the conditions stated in the Scope, or carry out work on the Site not stated in the Scope. The Contractor must notify within eight weeks / 8 weeks of becoming aware under cl. 61.3. The Project Manager then assesses time and additional Defined Cost and implements the compensation event. cl. X12.1 was cited with Option X12 as an optional multiparty collaboration mechanism.

</details>

<details>
<summary><b>4. Behavioural Implications</b> — Retrospective claims become live controls.</summary>

Under GCC, the Client’s safest coordination behaviour is documentary precision at tender and disciplined Engineer administration during the works. Specialist Works, utilities, split drawings and Bills of Quantities must identify the interface so Clause 16(1), Clause 34(1), Clause 34(2), Clause 34(3)(a) and Clause 14 convert ordinary access, facilities, joint programming and coordination drawings into tendered obligations. The Contractor’s behaviour is protective: programme known Specialist Works within 14 days of Tender acceptance, cooperate without impeding others, but serve prior written notice under Clause 34(3)(b)(i) before carrying out allegedly excessive requirements, and then preserve EOT/cost by notices within 28 days under Clause 50(1)(a) and Clause 64(2).

Under NEC, the Client must manage interfaces proactively through Scope and the Accepted Programme. The Project Manager should ensure Others’ activities are realistically reflected in cl. 31.2 programmes before acceptance, because those dates and Scope conditions become the commercial baseline for cl. 60.1(5). The Contractor must exchange information, provide access, and share Working Areas only as stated/notified, while notifying compensation events within 8 weeks of becoming aware. The incentive shifts from arguing whether an Engineer’s direction exceeded a tendered duty to keeping Scope, programme, access notifications and compensation-event forecasts current.

**Implementation comparison (GCC vs NEC4):**

| Aspect | GCC | NEC4 |
|---|---|---|
| Baseline interface definition | Specialist Works described in Contract; Clause 1(1), Clause 16(1). | Others’ work stated in Scope/Accepted Programme; cl. 11.2(12), cl. 31.2. |
| Access and facilities | Reasonable facilities/access/services; Clause 34(1), SCC A3/Clause 48(3). | Share Working Areas as Scope states; cl. 25.1, cl. 27.1. |
| Coordination duty | Consult, liaise, joint programmes/drawings; Clause 34(2). | Co-operate and exchange information with Others; cl. 25.1. |
| Cost-protection mechanism | Tender deemed to include ordinary coordination; Clause 34(3)(a), Clause 14. | Defined Scope limits priced cooperation; cl. 25.1, cl. 31.2. |
| Changed requirement | Changed sequence/method/timing is Variation; Clause 60(1)(b). | Scope change is compensation event; cl. 14.3, cl. 60.1(1). |
| Notice for relief | 28-day delay/cost notices; Clause 50(1)(a), Clause 64(2). | CE notice within 8 weeks; cl. 61.3. |


</details>

<details>
<summary><b>5. GCC Lessons for NEC Adoption</b> — GCC routines shift earlier under NEC.</summary>

GCC Clause 16(1) programme discipline transfers directly to NEC cl. 31.2. Hong Kong practitioners already know to show “due allowance” for described Specialist Works and utility works within 14 days of Tender acceptance; under NEC, the adjustment is to use each programme as a live interface baseline showing the order and timing of Client/Others’ work as agreed or as stated in the Scope.

GCC Clause 34(1), Clause 34(2), Clause 34(3)(a), SCC Clause A2 and SCC Clause A3/Clause 48(3) train contractors to manage access, facilities, liaison, joint programmes, method statements, coordination drawings and specifications. Under NEC, those habits support cl. 25.1, cl. 25.2, cl. 27.1 and cl. 27.2, but the behavioural adjustment is to tie cooperation and Working Area sharing to what the Scope states or the Project Manager notifies, not merely to a broad Engineer-administered facilities duty.

GCC Clause 34(3)(b)(i)/(ii) prior-notice practice maps to NEC cl. 14.3, cl. 60.1(1), cl. 61.1 and cl. 61.3. The familiar protection step—notify before doing allegedly excessive coordination and require written instruction—becomes an earlier compensation-event discipline: identify the Scope change, notify or expect notification, and support prospective assessment before cost and delay accumulate.

GCC Clause 50(1)(a), Clause 64(2), Clause 50(3) and Clause 63(d) records remain useful for NEC assessment of time and Defined Cost, especially where Others do not follow the Accepted Programme or Scope under cl. 60.1(5). The practical reframing is simple: GCC claim, record, variation and delay-analysis habits should be used earlier under NEC as planning, notification, quotation and interface-management tools.

| GCC practice / experience | → How it transfers to NEC implementation |
|---|---|
| Clause 16(1) programme allowance for Specialist Works. | Use cl. 31.2 to show Others’ timing and agreed interface sequence. |
| Clause 34(2) liaison, joint programmes and coordination drawings. | Support cl. 25.1 cooperation with evidence of exchanged information. |
| Clause 34(3)(b)(i)/(ii) prior notice and written instruction. | Trigger cl. 14.3/cl. 60.1(1) Scope-change CE promptly. |
| Clause 50(1)(a) and Clause 64(2) delay/cost notices. | Notify cl. 60.1(5) CE within 8 weeks under cl. 61.3. |
| Clause 63(d) Disturbance Cost records and causation checks. | Substantiate Defined Cost and separate Contractor-caused coordination failures. |

</details>

<details>
<summary><b>6. HK-Specific Notes</b> — PAH and DEVB limit interface cost risk.</summary>

For GCC, the PAH Chapter 9 terminology mapping is important: it confirms that GCC contracts use “Bills of Quantities / Schedule of Rates” and “Extension of time, variations, claims”, not “Works Information”, “Scope”, or “Compensation events”. This matters because interface requirements must be embedded in the Specification, Drawings, Bills of Quantities / Schedule of Rates and GCC/SCC wording rather than assumed to operate through NEC terminology.

PAH Chapter 5, Section 9.1 gives specific Hong Kong project-office guidance for multi-contract arrangements. It requires careful checking of contract documents delineating the split of works, particularly drawings and BQ, to ensure consistency and avoid omissions or duplications at the interface. This supports the legal strategy under Clause 16(1), Clause 34 and Clause 14: if the Client wants ordinary coordination to be priced and non-compensable, the Specialist Works and interface boundaries must be described clearly at tender.

PAH Chapter 5, Appendix 5.36 prescribes SCC Clause A2, “Facilities for and coordination with others”, for “Mega Project Contracts”. Where Government can describe the “interfacing works” in sufficient detail at tender stage, those works may be expressly listed in Clause 34(1). The Employer may also include a specific pre-priced Bills of Quantities item for coordination with those responsible for the interfacing works. Under SCC A2 adding Clause 34(3), the Contractor is only entitled to this pre-priced sum if it has fulfilled its coordination obligations to the satisfaction of the Engineer. Works Bureau Technical Circular WB1900 does not address this aspect.

For NEC4 ECC Hong Kong use, the DEVB Practice Notes give explicit interface and compensation-event guidance. They warn Project Managers to assess reasonably whether the Contractor’s proposed programme for Others is achievable, because once accepted, delay by Others can trigger cl. 60.1(5). To limit Government exposure to cost uncertainty from delays by Others and utility interference, DEVB mandates that “the compensation events under NEC clause 60.1(5) should be provided with time compensation only”. The Library of Standard Amendments to NEC ECC must be adopted to exclude financial compensation for that event.

The NEC4 HK guidance also addresses multiparty collaboration. NEC4 includes Option X12, cited as cl. X12.1 / Option X12, for formal multiparty collaboration across different contracts on the same project. DEVB advises, however, that because most public works projects mainly involve two Parties, the Client and the Contractor, this secondary Option is “normally not required”. Coordination is therefore normally managed through the NEC core clauses—cl. 25.1, cl. 25.2, cl. 27.1, cl. 27.2, cl. 31.2, cl. 60.1(1), cl. 60.1(5), cl. 61.1 and cl. 61.3—rather than through a formal X12 partnering structure.

</details>

## Clause Map (extracted by CM-A)

Structured index of every clause cited by the expert agents, with its taxonomy category and a verbatim quote / paraphrase.

- **GCC · Clause 1(1)** — _uncategorised_ · obligation: **definition** · party: **n/a**
  > The Employer frequently engages "Specialist Contractors" to execute "Specialist Works" concurrently with the main Contractor (Clause 1(1)).
- **GCC · Clause 14** — _physical_conditions_ · obligation: **condition** · party: **Contractor** · condition: **ordinary coordination does not trigger extra payment**
  > the general principles of Clause 14 (Sufficiency of Tender), the Contractor "shall be deemed to have made adequate allowance in his Tender and in the Works Programme"
- **GCC · Clause 16(1)** — _programme_obligations_ · obligation: **process** · party: **Contractor** · timeline: **within 14 days of Tender acceptance** · condition: **known Specialist Works described in the Contract**
  > Contractor submits the initial programme within 14 days of Tender acceptance, making due allowance for the known Specialist Works described in the Contract (Clause 16(1)).
- **GCC · Clause 34(1)** — _uncategorised_ · obligation: **duty** · party: **Contractor** · condition: **any person carrying out work on or adjacent to the Site**
  > Under the amended Clause 34(1), the Contractor "shall not impede and shall afford all reasonable facilities, access and/or services" to any person carrying out work on or adjacent to the Site.
- **GCC · Clause 50(1)(a)** — _early_warning_risk_ · obligation: **process** · party: **Contractor** · timeline: **within 28 days of the delay arising** · condition: **If Contractor suffers actual delay or disturbance due to the interfacing party's default, or due to the excessive instruction**
  > Contractor serves notice of probable delay within 28 days of the delay arising (Clause 50(1)(a)).
- **GCC · Clause 50(1)(b)** — _extension_of_time_ · obligation: **remedy** · party: **Contractor** · condition: **If a Specialist Contractor or Employer-engaged person defaults and disrupts the main Contractor**
  > If a Specialist Contractor or Employer-engaged person defaults and disrupts the main Contractor, this provides an EOT entitlement under Clause 50(1)(b)(vii)
- **GCC · Clause 60(1)(b)** — _change_management_ · obligation: **remedy** · party: **Contractor** · condition: **If the Engineer formally instructs changes to any sequence, method or timing of construction specified in the Contract**
  > If the Engineer formally instructs "changes to any sequence, method or timing of construction specified in the Contract", this constitutes a Variation under Clause 60(1)(b), entitling the Contractor to a valuation.
- **GCC · Clause 63(d)** — _extension_of_time_ · obligation: **remedy** · party: **Contractor** · condition: **If a Specialist Contractor or Employer-engaged person defaults and disrupts the main Contractor**
  > grounds for Disturbance Cost under Clause 63(d). However, SCC A2 amends Clause 63(d) to stipulate that the Contractor gets no cost relief to the extent the delay was caused or contributed to by their own failure
- **GCC · Clause 64(2)** — _dispute_resolution_ · obligation: **process** · party: **Contractor** · timeline: **within 28 days of the event** · condition: **intention to claim Cost**
  > Contractor serves notice of intention to claim Cost within 28 days of the event (Clause 64(2)).
- **GCC · Clause 34** — _uncategorised_ · obligation: **definition** · party: **n/a**
  > The primary provision governing interface management is Clause 34 (Facilities for other persons), which is substantially expanded for complex or Mega Projects via SCC Clause A2.
- **GCC · Clause 48(3)** — _engineer_powers_assignment_ · obligation: **duty** · party: **Contractor**
  > Under SCC Clause A3 (amending Clause 48(3)), the Contractor "shall not be entitled to exclusive possession of or uninterrupted access to the Site" and must coordinate activities with others.
- **GCC · Clause 34(2)** — _uncategorised_ · obligation: **duty** · party: **Contractor** · condition: **with the other works**
  > Under Clause 34(2), the Contractor is obligated to "take all reasonable steps to ensure that the Works are coordinated and integrated" with the other works.
- **GCC · Clause 34(3)(a)** — _uncategorised_ · obligation: **condition** · party: **Contractor** · condition: **in respect of his obligations under Clauses 34(1) and 34(2)**
  > Under the amended Clause 34(3)(a) and the general principles of Clause 14 (Sufficiency of Tender), the Contractor "shall be deemed to have made adequate allowance in his Tender and in the Works Programme"
- **GCC · Clause 34(3)(b)** — _uncategorised_ · obligation: **condition** · party: **both** · timeline: **prior to taking the action** · condition: **If the Engineer issues an instruction requiring attendance or facilities that the Contractor considers is in excess of their baseline obligations under Clause 34(1)**
  > Clause 34(3)(b) creates a strict limitation. The Contractor must notify the Engineer in writing prior to taking the action, detailing the estimated delay and Cost.
- **GCC · Clause 50(3)** — _extension_of_time_ · obligation: **process** · party: **Engineer** · condition: **If Contractor suffers actual delay or disturbance due to the interfacing party's default, or due to the excessive instruction**
  > Engineer assesses the EOT based on critical path impact and ascertains the Disturbance Cost, verifying that the Contractor did not contribute to the delay through their own failure to coordinate (Clause 50(3) & Clause 63(d)).
- **GCC · Clause 34(3)** — _uncategorised_ · obligation: **condition** · party: **Contractor** · condition: **ordinary coordination**
  > Contractor consults, liaises, and prepares joint programmes and coordination drawings with the specialist contractor at no additional cost to the Employer (Clause 34(2) & 34(3)(a)).
- **NEC4 · cl. 10.1** — _mutual_trust_ · obligation: **process** · party: **both**
  > The NEC4 ECC manages interfaces between the Contractor and separately engaged specialist contractors—defined under the contract as "Others" (cl. 11.2(12))—through transparent planning, prospective risk management
- **NEC4 · cl. 10.2** — _mutual_trust_ · obligation: **duty** · party: **both**
  > the overriding requirement to act in a spirit of mutual trust and co-operation
- **NEC4 · cl. 11.2(12)** — _hk_specific_statutory_obligations_ · obligation: **definition** · party: **n/a**
  > separately engaged specialist contractors—defined under the contract as "Others" (cl. 11.2(12))
- **NEC4 · cl. 14.3** — _change_management_ · obligation: **process** · party: **PM** · condition: **If the Client requires additional coordination, resequencing, or access arrangements that were not originally detailed**
  > the Project Manager must give an instruction changing the Scope (cl. 14.3), which constitutes a compensation event under cl. 60.1(1)
- **NEC4 · cl. 25.1** — _mutual_trust_ · obligation: **duty** · party: **Contractor** · condition: **as stated in the Scope**
  > Under cl. 25.1, the Contractor must co-operate with Others in obtaining and providing information they need in connection with the works . Crucially, the Contractor is only obliged to share the Working Areas with Others "as stated in the Scope"
- **NEC4 · cl. 25.2** — _quality_management_ · obligation: **duty** · party: **both** · condition: **as stated in the Scope**
  > Similarly, the Contractor and the Client provide services and other things to each other as stated in the Scope
- **NEC4 · cl. 27.1** — _quality_management_ · obligation: **duty** · party: **Contractor** · condition: **as notified by the Project Manager**
  > Furthermore, the Contractor must provide access to work being done and to Plant and Materials to Others as notified by the Project Manager
- **NEC4 · cl. 27.2** — _quality_management_ · obligation: **duty** · party: **Contractor** · condition: **as notified by the Project Manager**
  > Contractor cooperates with Others by exchanging necessary information, shares the Working Areas as stated in the Scope, and provides access as notified by the Project Manager (cl. 25.1, cl. 27.2)
- **NEC4 · cl. 31.2** — _programme_obligations_ · obligation: **process** · party: **Contractor** · condition: **on each programme submitted for acceptance**
  > Under cl. 31.2, the Contractor must show on each programme submitted for acceptance the order and timing of the work of the Client and Others as last agreed with them or, if not so agreed, as stated in the Scope
- **NEC4 · cl. 60.1(1)** — _change_management_ · obligation: **remedy** · party: **Contractor** · condition: **If the Client requires additional coordination, resequencing, or access arrangements that were not originally detailed**
  > the Project Manager must give an instruction changing the Scope (cl. 14.3), which constitutes a compensation event under cl. 60.1(1)
- **NEC4 · cl. 60.1(5)** — _compensation_event_notification_quotation_assessment_ · obligation: **remedy** · party: **Contractor** · condition: **if the Client or Others do not work within the times shown on the Accepted Programme, do not work within the conditions stated in the Scope, or carry out work on the Site that is not stated in the Scope**
  > It is a compensation event under cl. 60.1(5) if the Client or Others: do not work within the times shown on the Accepted Programme, do not work within the conditions stated in the Scope, or carry out work on the Site that is not stated in the Scope
- **NEC4 · cl. 61.1** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **if a new coordination requirement or changed sequence arises**
  > Project Manager (if a new coordination requirement or changed sequence arises) issues an instruction changing the Scope (cl. 14.3) and notifies a compensation event (cl. 60.1(1))
- **NEC4 · cl. 61.3** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **Contractor** · timeline: **within 8 weeks of becoming aware** · condition: **if Others fail to work within the times on the Accepted Programme, breach conditions in the Scope, or carry out unstated work**
  > Contractor (if Others fail to work within the times on the Accepted Programme, breach conditions in the Scope, or carry out unstated work) notifies a compensation event within 8 weeks of becoming aware (cl. 61.3, cl. 60.1(5))

## Raw Expert Evidence (NotebookLM responses)

The full unmodified responses from the GCC and NEC4 expert agents are reproduced below for traceability.

<details>
<summary>GCC expert response (1 iteration(s), 7,165 chars)</summary>

[CLAUSE REFERENCES] Clause 1(1), Clause 14, Clause 16(1), Clause 34(1), Clause 50(1)(a), Clause 50(1)(b)(iv), Clause 50(1)(b)(vii), Clause 60(1)(b), Clause 63(d), Clause 64(2), Special Conditions of Contract (SCC) Clause A2, SCC Clause A3, SCC Clause A4.
[GCC POSITION] Note: The GCC corpus does not use the terms "Scope", "Works Information", or "compensation events". Technical requirements are stated in the "Specification" and "Drawings", and time/cost relief mechanisms are "Variations", "Claims", and "Extension of Time" (EOT).
Baseline Coordination Obligations The Employer frequently engages "Specialist Contractors" to execute "Specialist Works" concurrently with the main Contractor (Clause 1(1)). For these obligations to be binding at the baseline level, they must be identifiable in the contract documents. Under Clause 16(1), the Contractor’s submitted programme must explicitly show "due allowance for the carrying out of Specialist Works and work by utility undertakings" in so far as such work is described in the Contract.
Access, Sharing, and Cooperation The primary provision governing interface management is Clause 34 (Facilities for other persons), which is substantially expanded for complex or Mega Projects via SCC Clause A2.
Access & Sharing: Under SCC Clause A3 (amending Clause 48(3)), the Contractor "shall not be entitled to exclusive possession of or uninterrupted access to the Site" and must coordinate activities with others. Under the amended Clause 34(1), the Contractor "shall not impede and shall afford all reasonable facilities, access and/or services" to any person carrying out work on or adjacent to the Site.
Cooperation & Sequencing: Under Clause 34(2), the Contractor is obligated to "take all reasonable steps to ensure that the Works are coordinated and integrated" with the other works. This strictly includes the duty to "consult, liaise and cooperate... including where necessary in the preparation of joint programmes, method statements, coordination drawings and specifications".
Limiting Employer's Cost Exposure The Client limits its exposure to additional costs by legally shifting routine interface management into the Contractor's tendered risk. Under the amended Clause 34(3)(a) and the general principles of Clause 14 (Sufficiency of Tender), the Contractor "shall be deemed to have made adequate allowance in his Tender and in the Works Programme in respect of his obligations under Clauses 34(1) and 34(2)". Thus, ordinary coordination does not trigger extra payment.
Limitations on Transferring Interface Risk (Entitlement to Relief) The Client cannot use coordination clauses to transfer unlimited interface risk or enact fundamental changes without consequence. Relief is triggered when boundaries are exceeded:
Changed Sequence/Method: If the Engineer formally instructs "changes to any sequence, method or timing of construction specified in the Contract", this constitutes a Variation under Clause 60(1)(b), entitling the Contractor to a valuation.
Special Facilities/Excessive Coordination (Condition Precedent): If the Engineer issues an instruction requiring attendance or facilities that the Contractor considers is in excess of their baseline obligations under Clause 34(1), Clause 34(3)(b) creates a strict limitation. The Contractor must notify the Engineer in writing prior to taking the action, detailing the estimated delay and Cost. Following this notice, the Engineer must explicitly instruct the action in writing. Only then does it become a valid ground for EOT under SCC Clause A4 (amending Clause 50(1)(b)(xi)).
Disruption by Others: If a Specialist Contractor or Employer-engaged person defaults and disrupts the main Contractor, this provides an EOT entitlement under Clause 50(1)(b)(vii) and grounds for Disturbance Cost under Clause 63(d). However, SCC A2 amends Clause 63(d) to stipulate that the Contractor gets no cost relief to the extent the delay was caused or contributed to by their own failure to fulfill their coordination duties under Clause 34.
[PROCEDURAL IMPLICATION]
Contractor submits the initial programme within 14 days of Tender acceptance, making due allowance for the known Specialist Works described in the Contract (Clause 16(1)).
Engineer instructs Contractor to afford reasonable facilities, access, and services to the separately engaged specialist contractor (Clause 34(1)).
Contractor consults, liaises, and prepares joint programmes and coordination drawings with the specialist contractor at no additional cost to the Employer (Clause 34(2) & 34(3)(a)).
If Contractor believes an instruction for facilities or access goes beyond their contractual baseline, Contractor serves written notice prior to executing the instruction, detailing the estimated delay and Cost (Clause 34(3)(b)(i)).
Engineer evaluates the notice and, if the extra coordination is necessary, issues a formal written instruction to the Contractor to take the action (Clause 34(3)(b)(ii)).
If Contractor suffers actual delay or disturbance due to the interfacing party's default, or due to the excessive instruction, Contractor serves notice of probable delay within 28 days of the delay arising (Clause 50(1)(a)).
Contractor serves notice of intention to claim Cost within 28 days of the event (Clause 64(2)).
Engineer assesses the EOT based on critical path impact and ascertains the Disturbance Cost, verifying that the Contractor did not contribute to the delay through their own failure to coordinate (Clause 50(3) & Clause 63(d)).
[HK CONTEXT] The Project Administration Handbook (PAH) Chapter 9 explicitly maps contract terminologies to prevent confusion, affirming that GCC contracts utilize "Bills of Quantities / Schedule of Rates" and "Extension of time, variations, claims" rather than "Works Information", "Scope", or "Compensation events".
Regarding multi-contract arrangements, PAH Chapter 5, Section 9.1 dictates that the project office must carefully check the contract documents delineating the split of the works (particularly drawings and BQ) to ensure consistency and avoid omissions or duplications at the interface.
Furthermore, PAH Chapter 5 (Appendix 5.36) prescribes SCC Clause A2 ("Facilities for and coordination with others") for use in "Mega Project Contracts". Under this mechanism, if the Government can describe the "interfacing works" in sufficient detail at the tender stage, these works can be explicitly listed within the text of Clause 34(1). To provide a structured commercial mechanism for this interface, the Employer may include a specific pre-priced item in the Bills of Quantities concerning coordination with those responsible for the interfacing works. Under SCC A2 (adding Clause 34(3)), the Contractor is only entitled to be paid this pre-priced sum provided they have fulfilled their coordination obligations to the satisfaction of the Engineer.
Works Bureau Technical Circular WB1900 does not address this aspect.
How is the unit rate for variations determined using Rules 1 and 2?
What does the GCC say about a Contractor's liability for approved designs?
What steps should the Contractor take if the Engineer fails to respond?

</details>

<details>
<summary>NEC4 expert response (1 iteration(s), 5,469 chars)</summary>

[CLAUSE REFERENCES] cl. 10.1, cl. 10.2, cl. 11.2(12), cl. 14.3, cl. 25.1, cl. 25.2, cl. 27.1, cl. 27.2, cl. 31.2, cl. 60.1(1), cl. 60.1(5), cl. 61.1, cl. 61.3, cl. X12.1
[NEC POSITION] The NEC4 ECC manages interfaces between the Contractor and separately engaged specialist contractors—defined under the contract as "Others" (cl. 11.2(12))—through transparent planning, prospective risk management, and the overriding requirement to act in a spirit of mutual trust and co-operation
Obligations to Cooperate, Share, and Provide Access: The Contractor has strict, yet specifically bounded, obligations regarding Others. Under cl. 25.1, the Contractor must co-operate with Others in obtaining and providing information they need in connection with the works
. Crucially, the Contractor is only obliged to share the Working Areas with Others "as stated in the Scope"
. Similarly, the Contractor and the Client provide services and other things to each other as stated in the Scope
. Furthermore, the Contractor must provide access to work being done and to Plant and Materials to Others as notified by the Project Manager
Sequencing and Programme Requirements: Coordination is heavily reliant on the Accepted Programme. Under cl. 31.2, the Contractor must show on each programme submitted for acceptance the order and timing of the work of the Client and Others as last agreed with them or, if not so agreed, as stated in the Scope
Limiting Client Exposure and Transferring Risk: The Client can rely on these provisions to coordinate works and limit exposure to additional costs by comprehensively detailing the presence, sequencing, space-sharing, and interface requirements in the Scope prior to the Contract Date
. Because the Contractor's obligation to accommodate Others is limited to what is stated in the Scope and the Accepted Programme, the Contractor prices and programmes for this defined level of coordination at tender stage
. The Client cannot demand cooperation, impose unforeseen sequencing, or require special attendance that exceeds what is stated in the contract documents without compensation
Triggers for Change, Variations, and Compensation Events: If the Client requires additional coordination, resequencing, or access arrangements that were not originally detailed, the Project Manager must give an instruction changing the Scope (cl. 14.3), which constitutes a compensation event under cl. 60.1(1)
. Furthermore, the Contractor is protected if the interface breaks down due to the fault of the separate specialists. It is a compensation event under cl. 60.1(5) if the Client or Others:
do not work within the times shown on the Accepted Programme,
do not work within the conditions stated in the Scope, or
carry out work on the Site that is not stated in the Scope
. If such an event occurs, the Contractor is entitled to an assessment for time and cost impact, provided they notify the compensation event within eight weeks of becoming aware
[PROCEDURAL IMPLICATION]
Client defines the requirements for sharing Working Areas, interface constraints, and the expected work of Others comprehensively within the Scope prior to tender
Contractor submits a programme showing the planned order and timing of the work of the Client and Others, based on agreements made or the constraints stated in the Scope (cl. 31.2)
Contractor cooperates with Others by exchanging necessary information, shares the Working Areas as stated in the Scope, and provides access as notified by the Project Manager (cl. 25.1, cl. 27.2)
Project Manager (if a new coordination requirement or changed sequence arises) issues an instruction changing the Scope (cl. 14.3) and notifies a compensation event (cl. 60.1(1))
Contractor (if Others fail to work within the times on the Accepted Programme, breach conditions in the Scope, or carry out unstated work) notifies a compensation event within 8 weeks of becoming aware (cl. 61.3, cl. 60.1(5))
Project Manager assesses any delay and additional Defined Cost caused by the change or failure by Others and implements the compensation event
[HK CONTEXT] The DEVB Practice Notes provide explicit Hong Kong-specific guidance on managing interfaces and the related compensation events:
Time-Only Compensation for cl. 60.1(5): DEVB Practice Notes explicitly warn Project Managers to reasonably assess if the Contractor's proposed programme for Others is achievable, because once accepted, any delay by Others triggers a compensation event under cl. 60.1(5)
. However, to limit the Government's exposure to cost uncertainties associated with delays by Others and utility interference, DEVB mandates that "the compensation events under NEC clause 60.1(5) should be provided with time compensation only"
. The Library of Standard Amendments to NEC ECC must be adopted to exclude financial compensation for this specific event
Multiparty Collaboration (Option X12): While NEC4 includes Option X12 for formal multiparty collaboration across different contracts on the same project, DEVB advises that because the majority of public works projects mainly involve two Parties (the Client and the Contractor), this secondary Option is "normally not required"
. Coordination is typically managed via the core clauses rather than formal X12 partnering agreements
How do core clauses differ from secondary Option X clauses?
What happens if an activity is omitted from the Activity Schedule?
Explain the Contractor's share in a target cost contract.

</details>

## SYN-A Chain-of-Thought Reasoning

<details>
<summary>Three-level reasoning trace (L1 → L2 → L3)</summary>

[L1 — Spirit/Philosophy] GCC treats coordination as an Engineer-administered, tender-risk allocation problem: if Specialist Works are described, the Contractor must price/programme ordinary interface management and claim only when defined contractual boundaries are exceeded. NEC4 ECC treats the same interface as a transparent planning and prospective risk-management process: Others are identified, their work is embedded in Scope and the Accepted Programme, and compensation events manage departures. In Transaction Cost Economics terms, GCC reduces opportunism through ex ante risk pricing, Engineer control, notices and claims; NEC reduces coordination transaction costs through relational governance, mutual trust and co-operation, programme transparency, and prospective assessment.

[L2 — Clause-level Comparison] Under GCC, Clause 1(1) recognises Specialist Contractors/Specialist Works; Clause 16(1) requires the Contractor’s programme within 14 days of Tender acceptance to allow for described Specialist Works and utility works; Clause 34, as expanded by SCC Clause A2, imposes facilities, access, services, consultation, liaison, cooperation, joint programmes, method statements, coordination drawings and specifications. SCC Clause A3 amending Clause 48(3) denies exclusive possession or uninterrupted access. Clause 34(3)(a) and Clause 14 deem the Contractor to have allowed in tender/programme for Clause 34(1) and Clause 34(2) duties, but Clause 34(3)(b)(i) and Clause 34(3)(b)(ii) require prior written notice of estimated delay and Cost, followed by written Engineer instruction, if the Contractor says the requirement exceeds baseline obligations. Relief then runs through SCC Clause A4 amending Clause 50(1)(b)(xi), Clause 50(1)(a), Clause 50(1)(b)(iv), Clause 50(1)(b)(vii), Clause 50(3), Clause 60(1)(b), Clause 63(d), and Clause 64(2). Under NEC4, cl. 11.2(12) defines separately engaged contractors as Others; cl. 10.1 and cl. 10.2 supply mutual trust/co-operation; cl. 25.1, cl. 25.2, cl. 27.1 and cl. 27.2 impose cooperation, Working Area sharing, services and access only as stated/notified; cl. 31.2 requires each programme to show the order and timing of Client/Others’ work; cl. 14.3 and cl. 60.1(1) make changed Scope a compensation event; cl. 60.1(5), cl. 61.1 and cl. 61.3 protect the Contractor where Others depart from the Accepted Programme, Scope conditions, or carry out unstated Site work.

[L3 — Practice/Behavioural Implications + GCC-to-NEC Transfer] A Hong Kong practitioner moving from GCC to NEC should not abandon GCC discipline; they should redeploy it earlier. GCC Clause 16(1) programming of Specialist Works transfers to NEC cl. 31.2 programming of Others, but the behavioural adjustment is that interface timing must be actively agreed or stated in the Scope and then used as a live compensation-event baseline. GCC Clause 34(1), Clause 34(2), Clause 34(3)(a), SCC Clause A2 and SCC Clause A3 routines for access, facilities, liaison, joint programmes and coordination drawings transfer to NEC cl. 25.1, cl. 25.2, cl. 27.1 and cl. 27.2, but the purpose shifts from showing compliance with a tendered duty to managing Scope-defined access and evidence. GCC Clause 34(3)(b)(i)/(ii) prior notice and written-instruction discipline transfers to NEC cl. 14.3, cl. 60.1(1), cl. 61.1 and cl. 61.3, but the timing changes from “protect the claim before acting” to “notify/assess prospectively before the commercial effect hardens.” GCC Clause 50(1)(a), Clause 64(2), Clause 50(3) and Clause 63(d) delay/cost records transfer to NEC compensation-event assessment of time and Defined Cost, but practitioners must forecast effect and separate their own coordination failures from failures by Others.

</details>

---

### Query Plan (QP-A)
- **L1 (spirit):**     How does the contract allocate responsibility for coordination with separately engaged contractors while preserving the intended risk balance between the Client and the Contractor?
- **L2 (clauses):**    Which provisions require the Contractor to cooperate with, give access to, or coordinate with other contractors, and when do instructions or requirements concerning such coordination entitle the Contractor to additional time or cost?
- **L3 (practice):**   In practice, how can the Client use programme, access, sequencing, and coordination requirements to manage interfaces between contractors without inadvertently creating compensable changes or delay claims?
- **canonical_topic:** `programme_obligations`

### Anchor Clauses (scenario ground-truth, used for CR)
- **GCC anchors:**  (none)
- **NEC4 anchors:** cl. 25.1, cl. 31.2, cl. 60.1(5)

*Generated by MAS v2.2 — LangGraph orchestrator (6 agents + 3 rule modules).*