# Scenario D06: NEC Douglas D06 - Revised Activity Schedule after first programme submission

**Generated:** 2026-07-07 16:49

## Context
Two weeks after the starting date, the Contractor submits its first programme for acceptance showing a realistic sequencing of activities. The Contractor also submits a revised Activity Schedule that relates to the programme.

## MAS Query Topic
> Revised Activity Schedule after first programme submission.

Specific questions to address:
Describe the circumstances when the Contractor is able to submit a revised Activity Schedule, the process for doing this and how the Project Manager might reply in this particular case?

## Validation Results

### Overall — ✅ PASSED  (confidence: 1.0, iterations used: 1)

> Accepted: no per-metric dips; composite confidence 1.00 ≥ 0.8. (LLM semantic flagged 1 minor issue(s), but the verdict is gated on the composite-confidence rule and the LLM track does not block.)

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
 ✅ cl. 13.3 ✅ cl. 13.4 ✅ cl. 55.1 ✅ cl. 55.3 ✅ cl. 55.4 ✅ cl. 63.14

### LLM-based Semantic Validation

**Track verdict:** ❌ fail (overridden by high-confidence rule track)
**Severity:** minor

**Issues raised by LLM reviewer:**

1. **[E1 — Hallucinated clause — cited in synthesis but absent from raw evidence]** The synthesis cites DEVB Practice Notes Section A6.3.4.3 on the NEC side, but that numbered section does not appear anywhere in the raw NEC evidence.

**Gap queries proposed by LLM:**
- *GCC:* _(none)_
- *NEC:* Retrieve NEC-side evidence for DEVB Practice Notes Section A6.3.4.3 concerning revised Activity Schedules when the Contractor changes a planned method of working.

## Comparative Synthesis

> **Executive summary** — GCC gives no Activity Schedule right: it uses Engineer-approved programmes and BQ valuation. NEC4 expressly permits or requires revised Activity Schedules under cl. 55.3. The shift is from Engineer-led control to relational, time-limited alignment protecting payment and change assessment.

<details>
<summary><b>1. Spirit / Philosophy</b> — Engineer control vs aligned pricing governance.</summary>

GCC: The GCC corpus is silent on “Activity Schedule” and “Project Manager”. It governs planning through the “Programme” or “Works Programme” under Clause 16(1), administered by the Engineer, while financial valuation remains tied to Bills of Quantities rather than an activity schedule. In TCE terms, this is a more hierarchical, Engineer-led control model, with programme approval and payment certification operating as administrative safeguards.

NEC: NEC4 ECC uses the Activity Schedule as a commercial tracking document that must correspond with the Accepted Programme. Its philosophy is relational and process-based: cl. 10.2 mutual trust and co-operation is supported by submission, time-limited reply, stated reasons, and confined grounds for rejection. The Contractor retains freedom to alter planned methods, but must keep pricing, programme, and payment administration transparent.

</details>

<details>
<summary><b>2. GCC Position (Implementation)</b> — No Activity Schedule; revise the Works Programme.</summary>

**Implementation flow:**

1. Contractor changes sequence/methods and may submit amended Works Programme at any time (SCC Clause A1(6)(a)) →
2. Contractor revises programme whenever EOT granted or expedition instructed (Clause 50(4); Clause 51(1)) →
3. Contractor submits amended Works Programme within 21 days after EOT, expedition, variation, or significant deviation (SCC Clause A1(6)(b)) →
4. Engineer may instruct revised version within 14 days after identifying significant deviation (SCC Clause A1(7)) →
5. Engineer replies within 30 days: approve, reject with reasons, or require information; silence means deemed approval (SCC Clause A1(2)) →
6. If rejected, Contractor resubmits within 21 days; previous approved programme remains effective (SCC Clause A1(5); SCC Clause A1(8)(a)).

The GCC has no “Activity Schedule” or “Project Manager”. The contract administrator is the Engineer, financial valuation is by Bills of Quantities, and planning is by the “Programme” or “Works Programme” under Clause 16(1). Standard GCC revision duties arise whenever the Engineer grants an Extension of Time, when the Contractor must revise the programme accordingly under Clause 50(4), and when the Engineer considers progress too slow and instructs expedition, requiring programme revision under Clause 51(1).

For Mega Projects, SCC Clause A1(6)(b) requires the Contractor to review and submit an amended Works Programme within 21 days if an EOT is granted, expedition is instructed, a variation is ordered, or the Contractor foresees a “significant deviation between the actual or anticipated progress of the Works and the Works Programme”. SCC Clause A1(7) also entitles the Engineer, by written instruction, to require a revised version within 14 days if the Engineer identifies a significant deviation. Separately, if the Contractor wishes to change sequence or methods, it may at any time submit an amended Works Programme under SCC Clause A1(6)(a). Where construction methods have already received the Engineer’s consent, SCC Clause A9(2) provides that the Contractor “shall not change the methods of construction which have received the Engineer’s consent without the further consent in writing of the Engineer which shall not be unreasonably withheld.”

SCC Clause A1(2) requires the Engineer, within 30 days of receiving the programme, to notify in writing that the programme is approved, rejected with reasons “including indication of those parts of the programme with which the Engineer is not satisfied”, or that further information is required. If the Engineer takes no action within 30 days, the programme is deemed approved. If rejected, SCC Clause A1(5) requires a revised programme within 21 days addressing the Engineer’s reasons. Under SCC Clause A1(8)(a), “Unless and until an amended version of the Works Programme is approved by the Engineer... the programme previously approved by the Engineer shall remain as the Works Programme for all purposes of the Contract”. Approval does not relieve the Contractor of duty or liability under Clause 16(2) and SCC Clause A1(8)(b).

Payment remains BQ-based: Clause 79(1) values work actually carried out, so programme acceptance does not alter fundamental valuation. However, SCC Clause A1(10) requires Monthly Progress Reports showing departures from the Works Programme, and amended Clause 78(3) makes that report a strict “condition precedent to consideration by the Engineer of any sums due to the Contractor”.

</details>

<details>
<summary><b>3. NEC4 Position (Implementation)</b> — Revised Activity Schedule by acceptance process.</summary>

**Implementation flow:**

1. Contractor changes planned method so Activity Schedule no longer relates to Accepted Programme, or correction is needed to relate activities to Scope (cl. 55.3) →
2. Contractor prepares revised Activity Schedule keeping total Prices unchanged and changed Prices reasonably distributed among incomplete activities (cl. 55.4) →
3. Contractor submits revised Activity Schedule with information showing activity-to-programme links (cl. 31.4; cl. 55.3) →
4. Project Manager replies within the period for reply stated in the Contract Data (cl. 13.3) →
5. Project Manager accepts or states reasons for non-acceptance, including cl. 55.4 grounds or need for more information (cl. 13.4; cl. 55.4) →
6. If not accepted, Contractor resubmits within the period for reply; payment uses most recently accepted Activity Schedule until acceptance (cl. 13.4; cl. 50.1).

NEC4 ECC manages commercial tracking through the Activity Schedule, which must align with the practical realities of the Accepted Programme to promote transparency and cl. 10.2 mutual trust and co-operation. The Activity Schedule is a pricing document only: under cl. 55.1, its information is not Scope or Site Information. This means it does not itself define the work, but it is central to payment and commercial assessment.

Cl. 55.3 gives the two primary circumstances for a revised Activity Schedule. First, the Contractor may or must submit one where it changes a planned method of working at its discretion so that the activities on the Activity Schedule no longer relate to the operations on the Accepted Programme. Secondly, the Contractor must correct the Activity Schedule so that activities relate to the Scope if they initially do not. To preserve correspondence between physical progress and payment, cl. 31.4 requires the Contractor to provide information showing how each activity on the Activity Schedule relates to the operations on each programme submitted for acceptance. The revised Activity Schedule is then submitted to the Project Manager for acceptance under cl. 55.3.

The Project Manager must reply within the period for reply stated in the Contract Data under cl. 13.3. If the Project Manager does not accept the submission, cl. 13.4 requires reasons to be stated; non-acceptance may also be justified where more information is needed to assess the submission fully. Cl. 55.4 confines withholding acceptance of a revised Activity Schedule to express grounds: it does not relate to the operations on the Accepted Programme; any changed Prices are not reasonably distributed between activities not completed; or the total of the Prices is changed.

Non-acceptance does not necessarily stop the Contractor working. Because the Activity Schedule is not Scope under cl. 55.1, the Contractor may proceed with its chosen method if it complies with the Scope, and Project Manager acceptance of a communication does not change the Contractor’s responsibility to Provide the Works under cl. 14.1. The commercial consequences are significant. Under Main Option A, Price for Work Done to Date is the total of Prices for completed activities under cl. 11.2(29); if resequenced work is not reflected in an accepted revised Activity Schedule, payment may wait until the original activities are entirely completed. Under Main Option C, interim payment is actual/forecast Defined Cost plus Fee under cl. 11.2(31), so cash flow is less affected, but cl. 63.14 makes “the changed Activity Schedule... used for the assessment for changed Prices”, affecting target cost and compensation events. Until acceptance, cl. 50.1 uses the most recently accepted Activity Schedule for the next amount due.

</details>

<details>
<summary><b>4. Behavioural Implications</b> — Retrospective control becomes proactive alignment.</summary>

Under GCC, the Contractor’s behaviour is mainly defensive and administrative. It monitors progress against the approved Works Programme, revises it when Clause 50(4), Clause 51(1), SCC Clause A1(6)(b), or SCC Clause A1(7) is triggered, and seeks further written Engineer consent under SCC Clause A9(2) before changing previously consented construction methods. The evidence is programme-based: reasons for deviation, revised sequencing, and Monthly Progress Reports under SCC Clause A1(10). Payment behaviour remains tied to BQ measurement under Clause 79(1), but the amended Clause 78(3) progress-report condition precedent gives the Contractor a strong incentive to maintain reporting discipline.

Under NEC4, the Contractor’s conduct is more proactive because the commercial document must keep pace with actual planned working. A discretionary method change is not merely an internal planning matter: if the Activity Schedule no longer relates to the Accepted Programme, cl. 55.3 requires a revised Activity Schedule supported by cl. 31.4 linkage information. The Contractor must manage cash flow by ensuring changed Prices are reasonably distributed among incomplete activities and the total of Prices is unchanged under cl. 55.4. The Project Manager’s behaviour is also more constrained: reply within the Contract Data period under cl. 13.3, state reasons under cl. 13.4, and reject only on the listed cl. 55.4 grounds or for further information under cl. 13.4.

**Implementation comparison (GCC vs NEC4):**

| Aspect | GCC | NEC4 |
|---|---|---|
| Document type | Works Programme, not Activity Schedule (Clause 16(1)). | Activity Schedule is pricing information (cl. 55.1). |
| Contract administrator | Engineer approves, rejects, or requests information (SCC Clause A1(2)). | Project Manager replies within Contract Data period (cl. 13.3). |
| Revision trigger | EOT, expedition, variation, or significant deviation (SCC Clause A1(6)(b)). | Changed planned method breaks Activity Schedule/programme link (cl. 55.3). |
| Reply grounds | Reject with reasons and unsatisfactory parts (SCC Clause A1(2)). | Reject only listed grounds or information need (cl. 55.4; cl. 13.4). |
| Default document | Previous approved programme remains effective (SCC Clause A1(8)(a)). | Most recently accepted Activity Schedule used for payment (cl. 50.1). |
| Payment effect | BQ rates value work actually carried out (Clause 79(1)). | Option A pays completed activities only (cl. 11.2(29)). |


</details>

<details>
<summary><b>5. GCC Lessons for NEC Adoption</b> — GCC routines become NEC alignment tools.</summary>

HK practitioners already familiar with GCC programme control under Clause 50(4), Clause 51(1), SCC Clause A1(6)(b), and SCC Clause A1(7) can transfer that discipline directly into NEC4 alignment management. The adjustment is that a method change is not only a programme issue: under cl. 55.3 the Activity Schedule must also be revised where it no longer relates to operations on the Accepted Programme, and cl. 31.4 requires information showing that relationship.

The GCC habit of responding to Engineer comments also transfers. Under SCC Clause A1(2) the Engineer approves, rejects with reasons, or requires further information within 30 days; if rejected, SCC Clause A1(5) requires resubmission within 21 days. Under NEC, the Project Manager replies within the Contract Data period under cl. 13.3 and must state reasons under cl. 13.4, but the Contractor should aim to avoid rejection by addressing the cl. 55.4 tests at first submission: relation to the Accepted Programme, reasonable distribution of changed Prices among incomplete activities, and no change to total Prices.

GCC payment discipline must be repurposed. Clause 79(1) trains teams to evidence work actually carried out, while amended Clause 78(3) and SCC Clause A1(10) make Monthly Progress Reports commercially critical. Under NEC, the comparable discipline is earlier and more granular: Option A cash flow depends on completed activity Prices under cl. 11.2(29), the next amount due uses the most recently accepted Activity Schedule under cl. 50.1, and Option C target/compensation-event pricing uses Defined Cost under cl. 11.2(31) and the changed Activity Schedule under cl. 63.14.

The practical reframing is: use GCC claim, record, variation, programme-revision, and delay-analysis habits earlier under NEC to keep the Accepted Programme, Activity Schedule, payment application, and change assessment aligned before cash-flow disruption occurs.

| GCC practice / experience | → How it transfers to NEC implementation |
|---|---|
| Clause 50(4)/Clause 51(1) programme revision after EOT or expedition. | Use cl. 55.3 and cl. 31.4 to realign Activity Schedule and programme. |
| SCC Clause A1(6)(b) 21-day response to variation or significant deviation. | Submit revised Activity Schedule promptly when planned method changes under cl. 55.3. |
| SCC Clause A1(2) rejection reasons and SCC Clause A1(5) resubmission. | Pre-check cl. 55.4 grounds and respond to cl. 13.4 reasons. |
| SCC Clause A9(2) written consent for previously consented methods. | Treat method changes as requiring commercial alignment under cl. 55.3. |
| Clause 79(1) BQ records plus Clause 78(3)/SCC A1(10) reports. | Support cl. 50.1 payment and cl. 63.14 changed Prices with current evidence. |

</details>

<details>
<summary><b>6. HK-Specific Notes</b> — PAH and DEVB notes frame HK practice.</summary>

For GCC, PAH Chapter 9 (Section II.04) provides a glossary table contrasting GCC terminology with alternative contract frameworks. It confirms that the GCC uses “Bills of Quantities / Schedule of Rates” and an “Architect / Engineer / Surveyor”, distinguishing them from “Activity Schedule” and “Project Manager”, which belong to outside frameworks.

PAH Chapter 5 (Appendix 5.36) prescribes “Special Conditions of Contract for use in Mega Project Contracts”, specifically SCC A1 and SCC A9. These Hong Kong amendments provide the detailed programme-control machinery relevant to this topic: SCC Clause A1(2) gives the Engineer’s 30-day turnaround to approve, reject with reasons, or request further information, with deemed approval if no action is taken; SCC Clause A1(5) gives the Contractor 21 days to resubmit after rejection; SCC Clause A1(6)(a) permits an amended Works Programme at any time for changed sequence or methods; SCC Clause A1(6)(b) requires submission within 21 days after EOT, expedition, variation, or foreseen significant deviation; SCC Clause A1(7) allows the Engineer to require a revised version within 14 days after identifying significant deviation; SCC Clause A1(8)(a) keeps the previous approved Works Programme effective until amendment is approved; SCC Clause A1(8)(b) preserves the Contractor’s duties and liabilities; SCC Clause A1(10), together with amended Clause 78(3), links Monthly Progress Reports to payment consideration as a strict condition precedent. The GCC expert response states that the corpus does not address any scenario where an Activity Schedule replaces the BQ for payment assessment.

For NEC4 Hong Kong practice, DEVB Practice Notes Section A6.3.4.3 emphasises document alignment: if the Contractor changes a planned method of working so that Activity Schedule activities do not relate to operations on the Accepted Programme, revision is mandatory under NEC4 cl. 55.3 to maintain clarity in contract administration.

The DEVB Practice Notes also distinguish the commercial impact under Main Option A and Main Option C. For Option A, “the payment will follow the adjusted Activity Schedule”, so acceptance of the revised Activity Schedule is critical to interim payment for resequenced work. For Option C, although interim payment is based on Defined Cost, “the changed Activity Schedule... is used for the assessment for changed Prices” under cl. 63.14, so the revised Activity Schedule remains important for target cost tracking and compensation-event assessment.

No W4, Z-clause, or tender-closing-date baseline point was identified in the supplied expert responses for this specific Activity Schedule revision issue.

</details>

## Clause Map (extracted by CM-A)

Structured index of every clause cited by the expert agents, with its taxonomy category and a verbatim quote / paraphrase.

- **GCC · Clause 16(1)** — _programme_obligations_ · obligation: **definition** · party: **n/a**
  > planning is governed by the "Programme" (or "Works Programme").
- **GCC · Clause 16(2)** — _programme_obligations_ · obligation: **condition** · party: **Contractor** · condition: **approval**
  > approval does not relieve the Contractor of any duty or liability under the Contract (Clause 16(2) and SCC Clause A1(8)(b)).
- **GCC · Clause 50(4)** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **Whenever the Engineer grants an Extension of Time (EOT)** · condition: **the Engineer grants an Extension of Time (EOT)**
  > Whenever the Engineer grants an Extension of Time (EOT), the Contractor must revise the programme accordingly (Clause 50(4)).
- **GCC · Clause 51(1)** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · condition: **the Engineer considers progress too slow and instructs expedition**
  > if the Engineer considers progress too slow and instructs expedition, the Contractor must revise the programme (Clause 51(1)).
- **GCC · Clause 78(3)** — _payment_mechanism_ · obligation: **condition** · party: **Contractor** · condition: **submission of this report**
  > Under the amended Clause 78(3), the submission of this report is a strict "condition precedent to consideration by the Engineer of any sums due to the Contractor".
- **GCC · Clause 79(1)** — _payment_mechanism_ · obligation: **process** · party: **Engineer** · condition: **work actually carried out**
  > the GCC relies on BQ rates for valuing work actually carried out (Clause 79(1)),
- **NEC4 · cl. 10.2** — _mutual_trust_ · obligation: **duty** · party: **both**
  > The NEC4 ECC manages the commercial tracking of the project through the Activity Schedule, which must align with the practical realities of the Accepted Programme to ensure transparency and uphold the spirit of mutual trust and co-operation (cl. 10.2).
- **NEC4 · cl. 11.2(29)** — _uncategorised_ · obligation: **definition** · party: **n/a** · condition: **Under Main Option A**
  > Under Main Option A, the Price for Work Done to Date is strictly calculated as the total of the Prices for completed activities (cl. 11.2(29)).
- **NEC4 · cl. 11.2(31)** — _uncategorised_ · obligation: **definition** · party: **n/a** · condition: **Under Main Option C**
  > Under Main Option C, interim payment is based on actual/forecast Defined Cost plus Fee (cl. 11.2(31)), meaning interim cash flow is less affected
- **NEC4 · cl. 13.3** — _uncategorised_ · obligation: **process** · party: **PM** · timeline: **within the period for reply stated in the Contract Data** · condition: **Contractor's submission**
  > The Project Manager must reply to the Contractor's submission within the period for reply stated in the Contract Data (cl. 13.3).
- **NEC4 · cl. 13.4** — _mutual_trust_ · obligation: **process** · party: **PM** · condition: **If the Project Manager does not accept the submission**
  > If the Project Manager does not accept the submission, they must state their reasons (cl. 13.4).
- **NEC4 · cl. 14.1** — _change_management_ · obligation: **duty** · party: **Contractor** · condition: **The Project Manager's acceptance of a communication**
  > The Project Manager's acceptance of a communication also does not change the Contractor's responsibility to Provide the Works (cl. 14.1).
- **NEC4 · cl. 31.4** — _uncategorised_ · obligation: **process** · party: **Contractor** · condition: **each programme submitted for acceptance**
  > The Contractor must provide information which shows how each activity on the Activity Schedule relates to the operations on each programme submitted for acceptance (cl. 31.4).
- **NEC4 · cl. 50.1** — _payment_mechanism_ · obligation: **process** · party: **PM** · condition: **until the revised version is formally accepted**
  > Project Manager assesses the next amount due for payment using the most recently accepted Activity Schedule until the revised version is formally accepted (cl. 50.1).
- **NEC4 · cl. 55.1** — _uncategorised_ · obligation: **definition** · party: **n/a**
  > The information in the Activity Schedule is purely for pricing and is strictly not Scope or Site Information (cl. 55.1).
- **NEC4 · cl. 55.3** — _uncategorised_ · obligation: **process** · party: **Contractor** · condition: **The Contractor changes a planned method of working at its discretion so that the activities on the Activity Schedule no longer relate to the operations on the Accepted Programme; or the Contractor must correct the Activity Schedule so that the activities relate to the Scope**
  > The Contractor may or must submit a revised Activity Schedule to the Project Manager for acceptance under two primary circumstances (cl. 55.3):
- **NEC4 · cl. 55.4** — _uncategorised_ · obligation: **right** · party: **PM** · condition: **It does not relate to the operations on the Accepted Programme; Any changed Prices are not reasonably distributed between the activities which are not completed; or The total of the Prices is changed**
  > The Project Manager may only withhold acceptance of a revised Activity Schedule for the following express reasons (cl. 55.4):
- **NEC4 · cl. 63.14** — _uncategorised_ · obligation: **process** · party: **n/a** · condition: **For Option C**
  > For Option C, while interim payment is based on Defined Cost, "the changed Activity Schedule... is used for the assessment for changed Prices" (cl. 63.14).

## Raw Expert Evidence (NotebookLM responses)

The full unmodified responses from the GCC and NEC4 expert agents are reproduced below for traceability.

<details>
<summary>GCC expert response (1 iteration(s), 6,376 chars)</summary>

[CLAUSE REFERENCES] Clause 16(1), Clause 16(2), Clause 50(4), Clause 51(1), Clause 78(3) (as amended by SCC), Clause 79(1), Special Conditions of Contract (SCC) Clause A1(2), SCC Clause A1(5), SCC Clause A1(6), SCC Clause A1(7), SCC Clause A1(8), SCC Clause A1(10), SCC Clause A9(2).
[GCC POSITION] Absence of Alternative Terminology in the GCC The GCC corpus is completely silent on the terms "Activity Schedule" and "Project Manager". Under the GCC framework, the contract administrator is the "Engineer" (or Architect/Surveyor), financial valuation is strictly governed by the "Bills of Quantities" (BQ) rather than an activity schedule, and planning is governed by the "Programme" (or "Works Programme").
Circumstances Requiring a Revised Programme The Contractor is required to submit a revised programme in specific circumstances:
Standard GCC: Whenever the Engineer grants an Extension of Time (EOT), the Contractor must revise the programme accordingly (Clause 50(4)). Additionally, if the Engineer considers progress too slow and instructs expedition, the Contractor must revise the programme (Clause 51(1)).
Mega Projects (SCC A1): Under SCC Clause A1(6)(b), the Contractor shall review and submit an amended Works Programme within 21 days if: (i) an EOT is granted; (ii) expedition is instructed; (iii) a variation is ordered; or (iv) the Contractor foresees a "significant deviation between the actual or anticipated progress of the Works and the Works Programme". Furthermore, the Engineer is entitled by written instruction to require the Contractor to produce a revised version within 14 days if the Engineer identifies a significant deviation (SCC Clause A1(7)).
Changes to the Planned Method of Working If the Contractor wishes to change their sequence or methods, they may at any time submit an amended Works Programme (SCC Clause A1(6)(a)). However, under SCC Clause A9(2), if the Contractor wishes to change methods of construction that have previously received the Engineer's consent, the Contractor "shall not change the methods of construction which have received the Engineer’s consent without the further consent in writing of the Engineer which shall not be unreasonably withheld."
Engineer’s Duties: Acceptance, Rejection, and Time Limits For complex contracts adopting the Mega Project provisions, SCC Clause A1(2) mandates that the Engineer shall, within 30 days of receiving the programme, notify the Contractor in writing that: (a) the programme is approved; or (b) the programme is rejected, "in which case reasons for such rejection shall be given, including indication of those parts of the programme with which the Engineer is not satisfied"; or (c) further information is required. If the Engineer takes no action within 30 days, the programme is deemed approved.
Consequences of Acceptance or Non-Acceptance
Programme Administration: If rejected, the Contractor must submit a revised programme within 21 days taking into account the Engineer's reasons (SCC Clause A1(5)). Under SCC Clause A1(8)(a), "Unless and until an amended version of the Works Programme is approved by the Engineer... the programme previously approved by the Engineer shall remain as the Works Programme for all purposes of the Contract". Furthermore, approval does not relieve the Contractor of any duty or liability under the Contract (Clause 16(2) and SCC Clause A1(8)(b)).
Payment: Because the GCC relies on BQ rates for valuing work actually carried out (Clause 79(1)), the acceptance or rejection of a programme (or the lack of an activity schedule) does not alter the fundamental valuation of physical work. However, under SCC Clause A1(10), the Contractor must submit a Monthly Progress Report highlighting departures from the Works Programme. Under the amended Clause 78(3), the submission of this report is a strict "condition precedent to consideration by the Engineer of any sums due to the Contractor".
[PROCEDURAL IMPLICATION]
Contractor foresees a significant deviation in actual progress or method from the baseline Works Programme (SCC A1(6)(b)(iv)).
Contractor submits requests to change any previously consented construction methods to the Engineer to obtain further written consent (SCC A9(2)).
Contractor submits an amended Works Programme to the Engineer within 21 days of the deviation or variation event (SCC A1(6)(b)).
Engineer reviews the revised programme and within 30 days notifies the Contractor in writing to approve it, reject it with detailed reasons, or request further information (SCC A1(2)).
If rejected, Contractor submits a further revised programme within 21 days addressing the Engineer's reasons for dissatisfaction (SCC A1(5)).
Until the new programme is approved, the Engineer and Contractor continue to rely on the last approved baseline programme for all contract administration purposes (SCC A1(8)(a)).
Contractor submits Monthly Progress Reports tracking progress against the active Works Programme; failure to do so blocks interim payment consideration (Clause 78(3) / SCC A1(10)).
Engineer assesses interim payment based on the BQ rates for work actually executed, independent of the programme's status (Clause 79(1)).
[HK CONTEXT] The Project Administration Handbook (PAH) Chapter 9 (Section II.04) provides a glossary table explicitly contrasting GCC terminology against alternative contract frameworks. It confirms that the GCC utilizes "Bills of Quantities / Schedule of Rates" and an "Architect / Engineer / Surveyor", explicitly distinguishing them from the terms "Activity Schedule" and "Project Manager" which belong to outside frameworks.
To address the specific programme control and submission mechanisms raised in the query, PAH Chapter 5 (Appendix 5.36) prescribes "Special Conditions of Contract for use in Mega Project Contracts" (specifically SCC A1 and SCC A9). These standard Hong Kong amendments explicitly define the strict 30-day turnaround for the Engineer's reply, the 21-day time limit for the Contractor's resubmission, and the condition precedent linking progress reporting to BQ payment evaluation. The corpus does not address any scenarios where an Activity Schedule replaces the BQ for payment assessment.
How does the Engineer assess BQ rates for variations?
What happens if interim payment falls below the minimum amount?
Are there specific rules for measuring materials stored on site?

</details>

<details>
<summary>NEC4 expert response (1 iteration(s), 5,848 chars)</summary>

[CLAUSE REFERENCES] cl. 10.2, cl. 11.2(29), cl. 11.2(31), cl. 13.3, cl. 13.4, cl. 14.1, cl. 31.4, cl. 50.1, cl. 55.1, cl. 55.3, cl. 55.4, cl. 63.14
[NEC POSITION] The NEC4 ECC manages the commercial tracking of the project through the Activity Schedule, which must align with the practical realities of the Accepted Programme to ensure transparency and uphold the spirit of mutual trust and co-operation (cl. 10.2).
Contractual Circumstances for Submission: The information in the Activity Schedule is purely for pricing and is strictly not Scope or Site Information (cl. 55.1). The Contractor may or must submit a revised Activity Schedule to the Project Manager for acceptance under two primary circumstances (cl. 55.3):
The Contractor changes a planned method of working at its discretion so that the activities on the Activity Schedule no longer relate to the operations on the Accepted Programme.
The Contractor must correct the Activity Schedule so that the activities relate to the Scope (if they initially do not).
Process for Submission and Programme Correspondence: To maintain alignment between physical progress and payment, the contract requires strict correspondence between the commercial and planning documents. The Contractor must provide information which shows how each activity on the Activity Schedule relates to the operations on each programme submitted for acceptance (cl. 31.4). When revising the Activity Schedule, the Contractor submits it to the Project Manager for acceptance (cl. 55.3).
Project Manager’s Duties, Reasons for Rejection, and Time Limits: The Project Manager must reply to the Contractor's submission within the period for reply stated in the Contract Data (cl. 13.3). If the Project Manager does not accept the submission, they must state their reasons (cl. 13.4). The Project Manager may only withhold acceptance of a revised Activity Schedule for the following express reasons (cl. 55.4):
It does not relate to the operations on the Accepted Programme;
Any changed Prices are not reasonably distributed between the activities which are not completed; or
The total of the Prices is changed. Additionally, acceptance can be withheld if more information is needed to assess the submission fully (cl. 13.4).
Consequences of Acceptance or Non-Acceptance:
Ability to Proceed: Because the Activity Schedule is not Scope (cl. 55.1), a lack of an accepted revised Activity Schedule does not technically prevent the Contractor from proceeding with their chosen method of working, provided that method complies with the Scope. The Project Manager's acceptance of a communication also does not change the Contractor's responsibility to Provide the Works (cl. 14.1).
Payment and Administration: Under Main Option A, the Price for Work Done to Date is strictly calculated as the total of the Prices for completed activities (cl. 11.2(29)). If the Contractor proceeds with a new method of working but the revised Activity Schedule is not accepted, payment cannot be made for the newly resequenced work until the original activities are entirely completed. This can severely disrupt the Contractor's cash flow. Under Main Option C, interim payment is based on actual/forecast Defined Cost plus Fee (cl. 11.2(31)), meaning interim cash flow is less affected, but an unaccepted Activity Schedule disrupts the assessment of the target cost and the valuation of compensation events.
[PROCEDURAL IMPLICATION]
Contractor changes a planned method of working at their discretion, causing the existing Activity Schedule to no longer relate to the operations on the Accepted Programme (cl. 55.3).
Contractor prepares a revised Activity Schedule, ensuring the total of the Prices is unchanged and Prices are reasonably distributed among incomplete activities (cl. 55.3, cl. 55.4).
Contractor submits the revised Activity Schedule to the Project Manager for acceptance, along with information showing how the new activities relate to the operations on the programme (cl. 31.4, cl. 55.3).
Project Manager reviews the submission and replies within the period for reply (cl. 13.3).
Project Manager either accepts the revised Activity Schedule or notifies non-acceptance, explicitly stating the contractual reasons under cl. 55.4 or cl. 13.4.
Contractor (if the submission is not accepted) resubmits the revised Activity Schedule within the period for reply, taking account of the Project Manager's reasons for non-acceptance (cl. 13.4).
Project Manager assesses the next amount due for payment using the most recently accepted Activity Schedule until the revised version is formally accepted (cl. 50.1).
[HK CONTEXT] The DEVB Practice Notes provide specific guidance on the administrative and commercial consequences of revising the Activity Schedule:
Alignment of Documents: DEVB PN Section A6.3.4.3 emphasizes that if the Contractor changes a planned method of working so that the activities on the Activity Schedule do not relate to the operations on the Accepted Programme, the revision is mandatory under NEC4 cl. 55.3 to maintain clarity in contract administration.
Impact on Option A vs. Option C: The Practice Notes highlight the differing consequences of the accepted revision. For Option A, "the payment will follow the adjusted Activity Schedule." Therefore, obtaining acceptance is critical for the Contractor to secure interim payments for the resequenced works. For Option C, while interim payment is based on Defined Cost, "the changed Activity Schedule... is used for the assessment for changed Prices" (cl. 63.14). Thus, the revised Activity Schedule is essential for properly tracking the target cost and assessing compensation events.
What are the sanctions for not working collaboratively?
When can a Project Manager reject a revised Activity Schedule?
How does Option A handle payment for incomplete activities?

</details>

## SYN-A Chain-of-Thought Reasoning

<details>
<summary>Three-level reasoning trace (L1 → L2 → L3)</summary>

[L1 — Spirit/Philosophy] GCC treats the issue as Engineer-led programme administration, not commercial re-pricing through an Activity Schedule. The Contractor’s freedom to alter sequence or methods exists mainly through amended Works Programme procedures and, for previously consented construction methods, further written Engineer consent; this reflects a more hierarchical, claims/administration model with higher ex post control costs in Transaction Cost Economics terms. NEC4 ECC instead makes the Activity Schedule a pricing instrument that must stay aligned with the Accepted Programme, using acceptance/rejection rules, reasons, and time-limited replies to support relational governance under cl. 10.2 mutual trust and co-operation.

[L2 — Clause-level Comparison] GCC has no “Activity Schedule” or “Project Manager”; Clause 16(1) concerns the Programme/Works Programme and Clause 79(1) values work by BQ rates. Revised programme duties arise under Clause 50(4) when an EOT is granted, Clause 51(1) when expedition is instructed, SCC Clause A1(6)(b) within 21 days after specified events or significant deviation, SCC Clause A1(7) within 14 days after Engineer instruction, and SCC Clause A1(6)(a) at any time for changed sequence or methods; SCC Clause A9(2) requires further written consent for previously consented methods. NEC4 directly answers the Activity Schedule question: cl. 55.3 permits/requires a revised Activity Schedule when planned working methods change so activities no longer relate to the Accepted Programme, or where correction is needed so activities relate to the Scope; cl. 31.4 requires information linking activities to programme operations; cl. 13.3 requires the Project Manager’s reply within the Contract Data period; cl. 13.4 requires reasons for non-acceptance; cl. 55.4 limits rejection to non-alignment, unreasonable redistribution of changed Prices among incomplete activities, or changed total Prices.

[L3 — Practice/Behavioural Implications + GCC-to-NEC Transfer] In GCC practice, the Contractor notifies and revises programme documents for Engineer approval, tracks departures through Monthly Progress Reports under SCC Clause A1(10), and is paid for work actually carried out under Clause 79(1), with amended Clause 78(3) making the report a condition precedent to payment consideration. In NEC practice, the Contractor must act earlier: if its planned method changes, it submits a revised Activity Schedule with programme-linking information under cl. 31.4 and cl. 55.3, protects Option A cash flow under cl. 11.2(29), and preserves Option C target/compensation-event assessment under cl. 11.2(31) and cl. 63.14. The transferable GCC lesson is not generic “good administration”: GCC programme-revision habits under Clause 50(4), Clause 51(1), SCC Clause A1(6), SCC Clause A1(7), and SCC Clause A1(5) transfer to NEC programme/Activity Schedule alignment; GCC method-consent discipline under SCC Clause A9(2) transfers to NEC cl. 55.3 submissions; GCC BQ/progress-report discipline under Clause 79(1), amended Clause 78(3), and SCC Clause A1(10) transfers into NEC evidence for payment and pricing, but the behavioural adjustment is timing and purpose—use the records prospectively to maintain Accepted Programme/payment alignment, not merely retrospectively to justify Engineer certification.

</details>

---

### Query Plan (QP-A)
- **L1 (spirit):**     How does the contract’s governance philosophy balance administrative control over pricing or scheduling documents with the Contractor’s freedom to alter its planned method of working after the first programme submission?
- **L2 (clauses):**    What clauses state when the Contractor may or must submit a revised Activity Schedule, what information or linkage to the accepted programme is required, and what grounds and time limits govern the Project Manager’s reply?
- **L3 (practice):**   In practice, how does submitting a revised Activity Schedule after the first programme affect payment, programme acceptance, change control, and the parties’ behaviour in managing planned methods and cash flow?
- **canonical_topic:** `programme_obligations`

### Anchor Clauses (scenario ground-truth, used for CR)
- **GCC anchors:**  (none)
- **NEC4 anchors:** cl. 13.3, cl. 13.4, cl. 55.1, cl. 55.3, cl. 55.4, cl. 63.14

*Generated by MAS v2.2 — LangGraph orchestrator (6 agents + 3 rule modules).*