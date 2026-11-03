# Scenario D04: NEC Douglas D04 - Compensation event assessment when the latest programme is not accepted

**Generated:** 2026-07-07 15:15

## Context
The latest revised programme submitted for acceptance has not been accepted, and the lack of acceptance is for a reason stated in the contract. The Project Manager must assess compensation events in that situation.

## MAS Query Topic
> Compensation event assessment when the latest programme is not accepted.

Specific questions to address:
In this situation, explain the process the Project Manager follows to assess compensation events?

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
 ✅ cl. 64.2 ✅ cl. 64.3 ✅ cl. 66.1

### LLM-based Semantic Validation

**Track verdict:** ✅ pass
**Severity:** minor

_No substantive issues raised._

## Comparative Synthesis

> **Executive summary** — GCC does not grant NEC-style compensation-event assessment: the Engineer falls back on the last approved programme, records, EOT, variation and disturbance machinery. NEC4 expressly shifts assessment to the Project Manager under cl. 64.1–64.2 when the latest programme is unaccepted. The behavioural shift is from retrospective claim proof to maintaining an accepted forecast.

<details>
<summary><b>1. Spirit / Philosophy</b> — Engineer control versus relational forecasting.</summary>

GCC: The GCC corpus does not use the terms "compensation events", "Project Manager", "Prices", or "quotations". It uses the "Engineer", "Variations" under Clauses 60 and 61, "Disturbance" under Clauses 63 and 64, and Bills of Quantities rather than Prices. Its governance philosophy is Engineer-led, claims-oriented and retrospective: in Transaction Cost Economics terms, it controls uncertainty through formal notice, records, approved baselines and ex post valuation.

NEC: NEC4 ECC manages change through a prospective compensation event regime operating heavily on an up-to-date Accepted Programme and a spirit of mutual trust and co-operation under cl. 10.2. The Accepted Programme is not merely evidence; it is the working forecast for assessing Prices, Completion Date and Key Dates. In TCE terms, NEC reduces transaction cost by relational governance, real-time information exchange and administratively disciplined forecasting.

</details>

<details>
<summary><b>2. GCC Position (Implementation)</b> — Last approved programme anchors assessment.</summary>

**Implementation flow:**

1. Contractor serves delay notice within 28 days of delay arising (Clause 50(1)(a)) →
2. Contractor serves additional-payment notice within 28 days of event (Clause 64(2)) →
3. Contractor keeps records and submits interim account with full particulars (Clause 64(3), Clause 64(4)) →
4. Engineer assesses using last approved Works Programme and available information (Clause 50(2), Clause 50(3), SCC Clause A1(8)(a)) →
5. Engineer values variations/disturbance and Contractor revises programme where required (Clause 61, Clause 63, Clause 64(6), Clause 50(4), SCC Clause A1(5), SCC Clause A1(6)(b)).

Under Clause 16(2), programme submission or approval does not relieve the Contractor of any duty or responsibility. If a newly submitted programme is not accepted, it has no contractual weight and the Engineer relies on the last approved baseline. For Mega Projects, SCC Clause A1(8)(a) states: "Unless and until an amended version of the Works Programme is approved by the Engineer... the programme previously approved by the Engineer shall remain as the Works Programme for all purposes of the Contract". SCC Clause A1(2) is cited in the GCC expert response, but no further operative detail was supplied for this topic.

If the Engineer rejects a submitted programme, the Engineer must give reasons. Under SCC Clause A1(5), the Contractor must submit a revised programme taking account of those reasons within 21 days. Until approval, the previously approved Works Programme applies. Whenever the Engineer grants an EOT, Clause 50(4) requires the Contractor to revise the programme. For Mega Project contracts, SCC Clause A1(6) and SCC Clause A1(6)(b) expand that duty: the Contractor must review and submit an amended Works Programme within 21 days if an EOT is granted, a variation is ordered, expedition is instructed, or the Contractor foresees a significant deviation between actual progress and the Works Programme.

Time is assessed retrospectively. The Engineer determines EOT by considering "all the circumstances known to him at that time" under Clause 50(2). If the programme is unreliable, or the Contractor fails to submit full and detailed particulars of the cause and extent of delay, Clause 50(3) permits the Engineer to consider EOT "only to the extent that the Engineer is able on the information available". Cost is also record-based. Variations are valued under Clause 61(1) using existing Contract rates or, failing agreement, a fair rate fixed by the Engineer under Clause 61(2); Clause 60(1) frames the variation route. For disturbance, the Engineer ascertains actual "Cost incurred" under Clause 63. Clause 64(2) requires notice of intention to claim additional payment within 28 days of the event; Clause 64(3) requires contemporary records; Clause 64(4) requires a first interim account giving full and detailed particulars. If those records or accounts are missing, Clause 64(6) restricts recovery to what the Engineer can assess "only to the extent that the Engineer is able on the information made available".

</details>

<details>
<summary><b>3. NEC4 Position (Implementation)</b> — PM assesses using own remaining-work programme.</summary>

**Implementation flow:**

1. Project Manager reviews programme and states reasons for non-acceptance within the period for reply (cl. 31.3, cl. 13.4) →
2. Contractor resubmits revised programme within the period for reply (cl. 13.4, cl. 32.2) →
3. On the compensation event, Project Manager assesses because latest programme is unaccepted for a stated reason (cl. 64.1) →
4. Project Manager states assumptions if effects are too uncertain to forecast reasonably (cl. 61.6) →
5. Project Manager uses own assessment of remaining-work programme, assesses Prices/time, notifies with details within quotation period, and implements (cl. 64.2, cl. 63.1, cl. 63.5, cl. 64.3, cl. 66.1).

The Accepted Programme is the programme identified in the Contract Data or the latest programme accepted by the Project Manager, which supersedes previous ones under cl. 11.2(1). When a compensation event occurs, the Contractor is typically instructed to submit a quotation under cl. 62.2. That quotation comprises proposed changes to the Prices, any delay to the Completion Date and Key Dates, details of the assessment, and alterations to the Accepted Programme.

If the Contractor submits a programme and the Project Manager rejects it for a contract reason, it does not become the Accepted Programme. Examples under cl. 31.3 include that the plans are not practicable, the programme does not represent the Contractor’s plans realistically, or it lacks required information. The Project Manager must state reasons for non-acceptance, and the Contractor must resubmit the revised programme within the period for reply, taking account of those reasons under cl. 13.4 and cl. 32.2.

Where the Project Manager has not accepted the Contractor’s latest programme for one of the stated contractual reasons, cl. 64.1 removes the Contractor’s right to assess the compensation event. The Project Manager is then mandated to assess it. Under cl. 64.2, because the latest programme is unaccepted and cannot be relied upon, the Project Manager must use their own assessment of the programme for the remaining work.

The assessment then follows the compensation-event valuation rules. Under cl. 63.1, the Project Manager evaluates changes to the Prices by reference to the effect of the compensation event on actual Defined Cost of work already done by the dividing date, forecast Defined Cost of work not yet done, and the resulting Fee. Under cl. 63.5, delay to the Completion Date is normally the length of time that planned Completion is later than that shown on the Accepted Programme current at the dividing date; where the latest programme is unaccepted, this relies on the Project Manager’s own remaining-work assessment. If effects are too uncertain to forecast reasonably, cl. 61.6 allows the Project Manager to state assumptions on which the assessment is based. Under cl. 64.3, the Project Manager notifies the Contractor of the assessment with details within the period allowed for the Contractor’s quotation submission. Under cl. 66.1, the Project Manager implements the compensation event upon notifying the assessment, altering the Prices and Completion Date accordingly.

</details>

<details>
<summary><b>4. Behavioural Implications</b> — Records remain, but timing moves earlier.</summary>

Under GCC, the Contractor protects position through notices, records and particulars, while the Engineer preserves administrative control by using the last approved Works Programme and valuing only what the record allows. The Contractor must notify delay within 28 days under Clause 50(1)(a), notify intention to claim additional payment within 28 days under Clause 64(2), keep contemporary records under Clause 64(3), and submit full and detailed particulars under Clause 64(4). If the current programme or claim evidence is weak, the Engineer’s incentive is to narrow the assessment to available information under Clause 50(3) and Clause 64(6).

Under NEC4, the immediate behavioural pressure is different. The Project Manager cannot allow programme non-acceptance to paralyse compensation-event assessment; cl. 64.1 requires the Project Manager to assess when the latest programme is unaccepted for a stated reason. The Project Manager must state reasons for non-acceptance, require resubmission within the period for reply, state assumptions where forecasting is uncertain under cl. 61.6, build an own assessment of the remaining-work programme under cl. 64.2, and notify a detailed assessment within the Contractor’s quotation period under cl. 64.3. The Contractor’s incentive is therefore to keep the Accepted Programme current, realistic and information-complete, because failure shifts assessment power from quotation-led collaboration to Project Manager assessment.

**Implementation comparison (GCC vs NEC4):**

| Aspect | GCC | NEC4 |
|---|---|---|
| Terminology | No CEs; uses Engineer, Variations, Disturbance. | Uses compensation events, PM, Prices, quotations. |
| Programme status | Last approved Works Programme remains operative: SCC A1(8)(a). | Accepted Programme defined by cl. 11.2(1). |
| Non-acceptance response | Reasons given; resubmit within 21 days: SCC A1(5). | Reasons; resubmit within period for reply: cl. 13.4, cl. 32.2. |
| Time assessment | Engineer considers known circumstances: Clause 50(2). | PM uses own remaining-work programme: cl. 64.2. |
| Cost assessment | Rates, fair rates, actual Cost incurred: Clauses 61, 63. | Actual/forecast Defined Cost plus Fee: cl. 63.1. |
| Evidence sanction | Assess only available information: Clauses 50(3), 64(6). | Contractor loses assessment right: cl. 64.1. |


</details>

<details>
<summary><b>5. GCC Lessons for NEC Adoption</b> — GCC claim routines become NEC controls.</summary>

Hong Kong practitioners already know the Clause 50(1)(a) workflow: notify the Engineer of the cause and probable extent of delay within 28 days of the delay arising. Under NEC4, that discipline should be transferred to the Accepted Programme and compensation-event process: the behavioural adjustment is to use delay awareness earlier, so the Project Manager can assess Completion Date impact against a reliable programme rather than reconstruct remaining work under cl. 64.2.

The Clause 64(2), Clause 64(3), and Clause 64(4) claims workflow also transfers directly. GCC practitioners are used to giving notice of intention to claim within 28 days of the event, keeping contemporary records, and submitting a first interim account with full and detailed particulars. Under NEC, those habits support cl. 62.2 quotations and cl. 63.1 Defined Cost assessment, but the adjustment is evidential and temporal: particulars must support proposed changes to Prices, Completion Date, Key Dates, assessment details, and Accepted Programme alterations, including forecast Defined Cost as well as actual cost.

GCC variation valuation under Clause 61(1), Clause 61(2), and Clause 61 remains useful, but NEC changes the purpose. Instead of waiting for retrospective Engineer valuation using Contract rates or fair rates, practitioners should use the same pricing discipline prospectively for compensation-event quotation and assessment, with the Project Manager stating assumptions under cl. 61.6 where the effects are too uncertain to forecast reasonably.

Finally, the Clause 50(4), SCC Clause A1(5), SCC Clause A1(6), SCC Clause A1(6)(b), and SCC Clause A1(8)(a) programme-revision mindset is the closest bridge to NEC. GCC practitioners know that the last approved programme remains operative until a compliant amended Works Programme is approved. NEC requires the same discipline but with sharper commercial consequences: prompt resubmission under cl. 13.4 and cl. 32.2 preserves a usable Accepted Programme and avoids loss of Contractor assessment rights under cl. 64.1. In practical terms, GCC claim, record, variation, and delay-analysis habits should be deployed earlier as NEC risk, forecast, quotation, and programme-management tools.

| GCC practice / experience | → How it transfers to NEC implementation |
|---|---|
| Clause 50(1)(a) 28-day delay notice. | Supports early CE timing evidence for cl. 63.5 assessment. |
| Clause 64(3) contemporary records. | Substantiate actual Defined Cost under cl. 63.1. |
| Clause 64(4) detailed interim account. | Convert particulars into cl. 62.2 quotation details. |
| Clause 61 variation valuation discipline. | Price CEs prospectively; use cl. 61.6 assumptions if uncertain. |
| Clause 50(4) and SCC A1 programme revision. | Resubmit promptly under cl. 13.4 and cl. 32.2. |

</details>

<details>
<summary><b>6. HK-Specific Notes</b> — PAH, DEVB and CEDD stress programme discipline.</summary>

The PAH Chapter 9 glossary table explicitly maps contract terminology to prevent confusion across frameworks. It confirms that, under GCC, time and cost effects are handled through "Extension of time, variations, claims" and payment through "Bills of Quantities / Schedule of Rates", contrasting this with NEC terms such as "Compensation events" and "Prices". This is important because the GCC expert response emphasises that GCC does not use "compensation events", "Project Manager", "Prices", or "quotations".

For Mega Project Contracts, PAH Chapter 5, Appendix 5.36, prescribes SCC Clause A1. The supplied expert response identifies SCC Clause A1(8)(a) as enforcing the rule that "Unless and until an amended version of the Works Programme is approved by the Engineer... the programme previously approved by the Engineer shall remain as the Works Programme for all purposes of the Contract". It also identifies SCC Clause A1(5), requiring a revised programme within 21 days after rejection taking account of the Engineer’s reasons, and SCC Clause A1(6) / SCC Clause A1(6)(b), requiring review and submission of an amended Works Programme within 21 days if an EOT is granted, a variation is ordered, expedition is instructed, or the Contractor foresees a significant deviation between actual progress and the Works Programme. SCC Clause A1(2) is cited in the GCC expert clause list, but no additional operative content was supplied for this topic. Works Bureau Technical Circular WB1900 does not address this aspect.

For NEC4 Hong Kong practice, the DEVB Practice Notes and CEDD Playbook explicitly address the severe practical consequences of failing to maintain an Accepted Programme. The DEVB identifies the lack of an Accepted Programme as a "Common Pitfall", often caused by the Contractor’s lack of focus on planning, float, or time risk allowances. This forces the Project Manager to assess compensation events using their own assessment under cl. 64.2. The DEVB heavily discourages this outcome because it defeats the collaborative risk-sharing and prospective change-management ethos intended for Hong Kong projects.

The DEVB also advises a "pragmatic approach" to acceptance. For complex projects, instead of rejecting the entire programme, the Project Manager may conditionally accept a detailed sub-programme for the upcoming 3 to 12 months, while allowing minimal details for later activities. The stated purpose is to ensure an Accepted Programme remains in place for compensation-event assessments and to avoid breakdown of the quotation process.

The CEDD Playbook and DEVB strongly encourage Project Managers to use the power to state assumptions under cl. 61.6 when evaluating compensation events. This allows quotations to be provided in advance of the works taking place, limits uncertainty, prevents breakdown of the assessment process, and avoids retrospective valuation. No additional NEC4 Hong Kong Edition specifics such as a tender closing date baseline, W4, or Z-clauses were supplied in the expert material for this topic.

</details>

## Clause Map (extracted by CM-A)

Structured index of every clause cited by the expert agents, with its taxonomy category and a verbatim quote / paraphrase.

- **GCC · Clause 16(2)** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · condition: **submission or approval of a programme**
  > Under the GCC, the submission or approval of a programme does not relieve the Contractor of any duty or responsibility
- **GCC · Clause 50(1)(a)** — _early_warning_risk_ · obligation: **process** · party: **Contractor** · timeline: **28 days of the delay arising** · condition: **delay arising**
  > Contractor serves written notice to the Engineer of the cause and probable extent of a delay within 28 days of the delay arising (Clause 50(1)(a))
- **GCC · Clause 50(2)** — _extension_of_time_ · obligation: **process** · party: **Engineer**
  > The Engineer determines an Extension of Time (EOT) by taking into account "all the circumstances known to him at that time" (Clause 50(2))
- **GCC · Clause 50(3)** — _extension_of_time_ · obligation: **process** · party: **Engineer** · condition: **If the current programme is unreliable or the Contractor fails to submit full and detailed particulars of the cause and extent of a delay**
  > the Engineer is empowered to make their own assessment and consider the EOT "only to the extent that the Engineer is able on the information available" (Clause 50(3))
- **GCC · Clause 50(4)** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · condition: **Whenever the Engineer grants an EOT**
  > Whenever the Engineer grants an EOT, the Contractor must revise the programme accordingly (Clause 50(4))
- **GCC · Clause 60(1)** — _change_management_ · obligation: **process** · party: **n/a**
  > adjustments to time and cost are administered via "Variations" (Clauses 60 and 61)
- **GCC · Clause 61(1)** — _change_management_ · obligation: **process** · party: **n/a** · condition: **Variations**
  > Variations are valued under Clause 61(1) using existing Contract rates
- **GCC · Clause 61(2)** — _change_management_ · obligation: **process** · party: **Engineer** · condition: **failing agreement**
  > failing agreement, a fair rate fixed by the Engineer under Clause 61(2)
- **GCC · Clause 63** — _extension_of_time_ · obligation: **process** · party: **Engineer** · condition: **disturbance claims**
  > For disturbance claims, the Engineer ascertains the actual "Cost incurred" under Clause 63
- **GCC · Clause 64(2)** — _dispute_resolution_ · obligation: **process** · party: **Contractor** · timeline: **28 days of the event** · condition: **intention to claim additional payment**
  > notice of intention to claim additional payment within 28 days of the event (Clause 64(2))
- **GCC · Clause 64(3)** — _dispute_resolution_ · obligation: **duty** · party: **Contractor**
  > Contractor keeps contemporary records (Clause 64(3))
- **GCC · Clause 64(4)** — _dispute_resolution_ · obligation: **process** · party: **Contractor**
  > submits a first interim account giving full and detailed particulars (Clause 64(4))
- **GCC · Clause 64(6)** — _dispute_resolution_ · obligation: **process** · party: **Engineer** · condition: **If the Contractor fails to keep contemporary records or submit detailed accounts**
  > the Engineer assesses the financial claim "only to the extent that the Engineer is able on the information made available" (Clause 64(6))
- **GCC · Clause 61** — _change_management_ · obligation: **process** · party: **Engineer** · condition: **changes**
  > Engineer values changes using contract rates or fixes reasonable rates (Clause 61)
- **NEC4 · cl. 10.2** — _mutual_trust_ · obligation: **duty** · party: **both**
  > The NEC4 ECC manages change through a prospective compensation event regime, operating heavily on an up-to-date Accepted Programme and a spirit of mutual trust and co-operation (cl. 10.2).
- **NEC4 · cl. 11.2(1)** — _uncategorised_ · obligation: **definition** · party: **n/a**
  > The Accepted Programme is defined as the programme identified in the Contract Data or the latest programme accepted by the Project Manager, which supersedes previous ones (cl. 11.2(1)).
- **NEC4 · cl. 13.4** — _mutual_trust_ · obligation: **process** · party: **both** · timeline: **within the period for reply** · condition: **non-acceptance**
  > The Project Manager must state their reasons for non-acceptance, and the Contractor must resubmit the revised programme within the period for reply, taking account of those reasons (cl. 13.4, cl. 32.2).
- **NEC4 · cl. 31.3** — _programme_obligations_ · obligation: **condition** · party: **Contractor** · condition: **plans are not practicable, it does not represent plans realistically, or lacks required information**
  > If the Contractor submits a programme but the Project Manager rejects it for a reason stated in the contract (e.g., plans are not practicable, it does not represent plans realistically, or lacks required information under cl. 31.3), it does not become the Accepted Programme.
- **NEC4 · cl. 32.2** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **within the period for reply** · condition: **non-acceptance**
  > The Project Manager must state their reasons for non-acceptance, and the Contractor must resubmit the revised programme within the period for reply, taking account of those reasons (cl. 13.4, cl. 32.2).
- **NEC4 · cl. 61.6** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **If the effects of the compensation event are too uncertain to be forecast reasonably**
  > If the effects of the compensation event are too uncertain to be forecast reasonably, the Project Manager states assumptions about the event on which the assessment is based (cl. 61.6).
- **NEC4 · cl. 62.2** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **Contractor** · condition: **When a compensation event occurs**
  > When a compensation event occurs, the Contractor is typically instructed to submit a quotation, which comprises proposed changes to the Prices, any delay to the Completion Date and Key Dates, details of the assessment, and alterations to the Accepted Programme (cl. 62.2).
- **NEC4 · cl. 63.1** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **compensation event**
  > the Project Manager evaluates the changes to the Prices based on the effect of the compensation event upon the actual Defined Cost of work already done by the dividing date, the forecast Defined Cost of work not yet done, and the resulting Fee (cl. 63.1).
- **NEC4 · cl. 63.5** — _extension_of_time_ · obligation: **process** · party: **PM**
  > Any delay to the Completion Date is normally assessed as the length of time that planned Completion is later than that shown on the Accepted Programme current at the dividing date (cl. 63.5);
- **NEC4 · cl. 64.1** — _compensation_event_notification_quotation_assessment_ · obligation: **duty** · party: **PM** · condition: **If the Project Manager has not accepted the Contractor's latest programme for one of the reasons stated in the contract**
  > If the Project Manager has not accepted the Contractor's latest programme for one of the reasons stated in the contract, the Contractor loses the right to assess the compensation event. Instead, the Project Manager is mandated to assess the compensation event themselves (cl. 64.1).
- **NEC4 · cl. 64.2** — _compensation_event_notification_quotation_assessment_ · obligation: **duty** · party: **PM** · condition: **Because the latest programme is unaccepted**
  > The Project Manager must assess the compensation event using their own assessment of the programme for the remaining work (cl. 64.2).
- **NEC4 · cl. 64.3** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · timeline: **within the period allowed for the Contractor's quotation submission**
  > Project Manager notifies the Contractor of their assessment with details within the period allowed for the Contractor's quotation submission (cl. 64.3).
- **NEC4 · cl. 66.1** — _compensation_event_notification_quotation_assessment_ · obligation: **remedy** · party: **PM** · timeline: **upon notifying their assessment**
  > Project Manager implements the compensation event upon notifying their assessment, altering the Prices and Completion Date accordingly (cl. 66.1).

## Raw Expert Evidence (NotebookLM responses)

The full unmodified responses from the GCC and NEC4 expert agents are reproduced below for traceability.

<details>
<summary>GCC expert response (1 iteration(s), 5,574 chars)</summary>

[CLAUSE REFERENCES] Clause 16(2), Clause 50(1)(a), Clause 50(2), Clause 50(3), Clause 50(4), Clause 60(1), Clause 61(1), Clause 61(2), Clause 63, Clause 64(2), Clause 64(3), Clause 64(4), Clause 64(6), Special Conditions of Contract (SCC) Clause A1(2), SCC Clause A1(5), SCC Clause A1(6), SCC Clause A1(8)(a).
[GCC POSITION] Note: The GCC corpus does not use the terms "compensation events", "Project Manager", "Prices", or "quotations"
. Contract administration is managed by the "Engineer", adjustments to time and cost are administered via "Variations" (Clauses 60 and 61) and claims for "Disturbance" (Clauses 63 and 64), and the financial value is governed by the Bills of Quantities rather than Prices.
Status of the Accepted Programme Under the GCC, the submission or approval of a programme does not relieve the Contractor of any duty or responsibility
. If a newly submitted programme has not been accepted, the Engineer relies on the last approved baseline. For Mega Projects, SCC Clause A1(8)(a) explicitly dictates that "Unless and until an amended version of the Works Programme is approved by the Engineer... the programme previously approved by the Engineer shall remain as the Works Programme for all purposes of the Contract"
Effect of a Rejected or Unaccepted Programme If a submitted programme is rejected by the Engineer, it holds no contractual weight. The Engineer must give reasons for rejection
. Under SCC Clause A1(5), the Contractor is obligated to submit a revised programme taking into account the reasons given for the rejection within 21 days
. Until it is successfully approved, the previously approved baseline applies
Assessment of Cost, Delay, and Use of Own Assessment/Assumptions The GCC does not utilize prospective "quotations" to assess time and cost. Assessment is strictly retrospective and based on contemporary records:
Time Impact: The Engineer determines an Extension of Time (EOT) by taking into account "all the circumstances known to him at that time" (Clause 50(2))
. If the current programme is unreliable or the Contractor fails to submit full and detailed particulars of the cause and extent of a delay, the Engineer is empowered to make their own assessment and consider the EOT "only to the extent that the Engineer is able on the information available" (Clause 50(3))
Cost Assessment: Variations are valued under Clause 61(1) using existing Contract rates, or failing agreement, a fair rate fixed by the Engineer under Clause 61(2)
more_horiz
. For disturbance claims, the Engineer ascertains the actual "Cost incurred" under Clause 63
. If the Contractor fails to keep contemporary records or submit detailed accounts, the Engineer assesses the financial claim "only to the extent that the Engineer is able on the information made available" (Clause 64(6))
Duties on the Contractor to Submit or Revise Programmes Whenever the Engineer grants an EOT, the Contractor must revise the programme accordingly (Clause 50(4))
. Under Mega Project contracts, SCC Clause A1(6)(b) explicitly expands this duty, requiring the Contractor to review and submit an amended Works Programme within 21 days if an EOT is granted, a variation is ordered, expedition is instructed, or the Contractor foresees a significant deviation between actual progress and the Works Programme
more_horiz
[PROCEDURAL IMPLICATION]
Contractor serves written notice to the Engineer of the cause and probable extent of a delay within 28 days of the delay arising (Clause 50(1)(a)) and notice of intention to claim additional payment within 28 days of the event (Clause 64(2)).
Contractor keeps contemporary records (Clause 64(3)) and submits a first interim account giving full and detailed particulars (Clause 64(4)).
Engineer assesses the delay and EOT utilizing the last previously approved Works Programme as the baseline, as unaccepted revised programmes do not supersede the baseline (SCC A1(8)(a)).
Engineer evaluates time and cost based on all circumstances known at the time (Clause 50(2)). If the programme is unreliable or the Contractor fails to provide detailed particulars, the Engineer makes their own assessment based strictly on the information available (Clause 50(3) and Clause 64(6)).
Engineer values changes using contract rates or fixes reasonable rates (Clause 61) and ascertains actual Cost incurred for disturbance (Clause 63).
If a submitted programme is rejected, Contractor submits a revised programme within 21 days addressing the Engineer's reasons for rejection (SCC A1(5)).
Contractor submits a further revised programme whenever an EOT is granted or a significant deviation occurs (Clause 50(4), SCC A1(6)).
[HK CONTEXT] The Project Administration Handbook (PAH) Chapter 9 contains a glossary table that explicitly maps contract terminology to prevent confusion across different frameworks. It confirms that under the GCC, time and cost effects are handled through "Extension of time, variations, claims" and payment through "Bills of Quantities / Schedule of Rates", expressly contrasting this with terms like "Compensation events" and "Prices"
more_horiz
For Mega Project Contracts, PAH Chapter 5 (Appendix 5.36) prescribes SCC Clause A1, which enforces the rule that the last approved programme remains the Works Programme until a new one is approved
. Works Bureau Technical Circular WB1900 does not address this aspect.
What is the effect of ambiguities or discrepancies in contract documents?
How does the Engineer verify if a programme is over-optimistic?
What are the three rules for valuing varied work in Rule 61?

</details>

<details>
<summary>NEC4 expert response (1 iteration(s), 5,977 chars)</summary>

[CLAUSE REFERENCES] cl. 10.2, cl. 11.2(1), cl. 13.4, cl. 31.3, cl. 32.2, cl. 61.6, cl. 62.2, cl. 63.1, cl. 63.5, cl. 64.1, cl. 64.2, cl. 64.3, cl. 66.1
[NEC POSITION] The NEC4 ECC manages change through a prospective compensation event regime, operating heavily on an up-to-date Accepted Programme and a spirit of mutual trust and co-operation (cl. 10.2).
Status of the Accepted Programme and Quotation Requirements: The Accepted Programme is defined as the programme identified in the Contract Data or the latest programme accepted by the Project Manager, which supersedes previous ones (cl. 11.2(1)). When a compensation event occurs, the Contractor is typically instructed to submit a quotation, which comprises proposed changes to the Prices, any delay to the Completion Date and Key Dates, details of the assessment, and alterations to the Accepted Programme (cl. 62.2).
Effect of a Rejected or Unaccepted Programme: If the Contractor submits a programme but the Project Manager rejects it for a reason stated in the contract (e.g., plans are not practicable, it does not represent plans realistically, or lacks required information under cl. 31.3), it does not become the Accepted Programme. If the Project Manager has not accepted the Contractor's latest programme for one of the reasons stated in the contract, the Contractor loses the right to assess the compensation event. Instead, the Project Manager is mandated to assess the compensation event themselves (cl. 64.1).
Project Manager's Own Assessment and Assumptions: Because the latest programme is unaccepted, it cannot be relied upon. The Project Manager must assess the compensation event using their own assessment of the programme for the remaining work (cl. 64.2). In this assessment, the Project Manager evaluates the changes to the Prices based on the effect of the compensation event upon the actual Defined Cost of work already done by the dividing date, the forecast Defined Cost of work not yet done, and the resulting Fee (cl. 63.1). Any delay to the Completion Date is normally assessed as the length of time that planned Completion is later than that shown on the Accepted Programme current at the dividing date (cl. 63.5); however, without a valid current programme, this evaluation relies on the Project Manager's own assessment of the remaining work. If the effects of the compensation event are too uncertain to be forecast reasonably, the Project Manager states assumptions about the event on which the assessment is based (cl. 61.6).
Contractor's Duties to Revise: Despite the Project Manager making their own assessment of the compensation event, the Contractor still has a strict duty to resubmit the unaccepted programme. The Project Manager must state their reasons for non-acceptance, and the Contractor must resubmit the revised programme within the period for reply, taking account of those reasons (cl. 13.4, cl. 32.2).
[PROCEDURAL IMPLICATION]
Project Manager assesses the Contractor's submitted programme and notifies non-acceptance, stating the contractual reasons (e.g., plans are not practicable) within the required time (cl. 31.3, cl. 13.4).
Contractor resubmits a revised programme taking account of the Project Manager's reasons within the period for reply (cl. 13.4, cl. 32.2).
Project Manager (when a compensation event occurs and requires assessment) notifies the Contractor that they will assess the compensation event themselves because the latest programme was not accepted for a stated reason (cl. 64.1).
Project Manager states assumptions about the compensation event if the effects are too uncertain to be forecast reasonably (cl. 61.6).
Project Manager prepares their own assessment of the programme for the remaining work to replace the unaccepted programme (cl. 64.2).
Project Manager assesses the change to the Prices (actual/forecast Defined Cost plus Fee) and the delay to the Completion Date and Key Dates based on their own assessment of the remaining work (cl. 63.1, cl. 63.5, cl. 64.2).
Project Manager notifies the Contractor of their assessment with details within the period allowed for the Contractor's quotation submission (cl. 64.3).
Project Manager implements the compensation event upon notifying their assessment, altering the Prices and Completion Date accordingly (cl. 66.1).
[HK CONTEXT] The DEVB Practice Notes and CEDD Playbook explicitly address the severe practical consequences of failing to maintain an Accepted Programme in Hong Kong public works:
The "Common Pitfall": DEVB identifies the lack of an Accepted Programme as a common pitfall, often caused by the Contractor's lack of focus on planning, float, or time risk allowances
. This forces the Project Manager to assess compensation events using their own assessment under cl. 64.2
. The DEVB heavily discourages this outcome because it defeats the collaborative risk-sharing and prospective change management ethos intended for Hong Kong projects.
Pragmatic Approach to Acceptance: To avoid the breakdown of the quotation process and prevent the Project Manager from being forced to make their own assessments, DEVB advises a "pragmatic approach"
. For complex projects, instead of rejecting the entire programme, the Project Manager may conditionally accept a detailed sub-programme for the upcoming 3 to 12 months (allowing minimal details for later activities)
. This ensures an Accepted Programme remains in place for compensation event assessments.
Using Assumptions: The CEDD Playbook and DEVB strongly encourage Project Managers to use the power to state assumptions under cl. 61.6 when evaluating CEs
. This allows quotations to be provided in advance of the works taking place and limits uncertainty, preventing the breakdown of the assessment process and avoiding retrospective valuation
How does Option A's payment differ if activities are incomplete?
What are the sanctions if the first programme is late?
How is the Contractor's share calculated in a target contract?

</details>

## SYN-A Chain-of-Thought Reasoning

<details>
<summary>Three-level reasoning trace (L1 → L2 → L3)</summary>

[L1 — Spirit/Philosophy] GCC treats the accepted/approved programme as an Engineer-administered control document rather than the engine of prospective change pricing. If a newer programme is unaccepted, governance falls back to the last approved baseline, retrospective records, Engineer valuation, and claim safeguards; in Transaction Cost Economics terms, it relies on formal control, evidential discipline, and ex post verification. NEC4 ECC instead makes the Accepted Programme central to relational, prospective governance under cl. 10.2: the parties are expected to maintain a reliable shared forecast so compensation events can be assessed promptly, transparently, and without retrospective reconstruction.

[L2 — Clause-level Comparison] Under GCC, the corpus does not use “compensation events”, “Project Manager”, “Prices”, or “quotations”; it uses the “Engineer”, “Variations” under Clauses 60 and 61, “Disturbance” under Clauses 63 and 64, and Bills of Quantities / Schedule of Rates. Clause 16(2) preserves the Contractor’s responsibility despite programme submission or approval. Clause 50(1)(a) requires delay notice within 28 days of the delay arising; Clause 50(2) requires the Engineer to consider “all the circumstances known to him at that time”; Clause 50(3) permits assessment “only to the extent that the Engineer is able on the information available”; Clause 50(4) requires programme revision after EOT. Cost follows Clause 61(1), Clause 61(2), Clause 63, and Clause 64(2)–64(6). Mega Project SCC Clause A1(5), SCC Clause A1(6), SCC Clause A1(6)(b), and SCC Clause A1(8)(a) make the last approved Works Programme remain operative and require resubmission within 21 days. Under NEC4, cl. 11.2(1) defines the Accepted Programme; cl. 31.3 governs reasons for non-acceptance; cl. 13.4 and cl. 32.2 require reasons and resubmission within the period for reply; cl. 64.1 shifts assessment to the Project Manager where the latest programme is not accepted for a stated reason; cl. 64.2 requires the Project Manager’s own programme assessment; cl. 63.1, cl. 63.5, cl. 61.6, cl. 64.3, and cl. 66.1 then govern Defined Cost, delay, assumptions, notification, and implementation.

[L3 — Practice/Behavioural Implications + GCC-to-NEC Transfer] The practical change for Hong Kong practitioners is not that programme, record, delay, and variation skills disappear; they move earlier and become management tools. GCC Clause 50(1)(a) delay notice discipline transfers to NEC early identification of programme risk and CE assessment support, but the behavioural adjustment is timing and purpose: not merely protecting EOT entitlement after delay arises, but keeping an Accepted Programme reliable enough for cl. 63.5 and cl. 64.2 assessment. GCC Clause 64(3) contemporary record habits transfer to NEC cl. 63.1 Defined Cost support, but records must support forecast as well as actual cost. GCC Clause 64(4) full and detailed particulars transfer to cl. 62.2 quotations, but particulars must include proposed Prices, Completion Date, Key Dates, assessment details, and Accepted Programme alterations. GCC Clause 61 variation valuation transfers to NEC CE pricing, but NEC requires prospective assessment and stated assumptions under cl. 61.6 where uncertainty would otherwise distort the assessment. GCC Clause 50(4) and SCC Clause A1(6)(b) programme-revision workflows transfer directly to NEC cl. 13.4 and cl. 32.2 resubmission duties, with the behavioural adjustment that prompt correction avoids loss of Contractor assessment rights under cl. 64.1 and prevents Project Manager-only reconstruction under cl. 64.2.

</details>

---

### Query Plan (QP-A)
- **L1 (spirit):**     How does the contract’s governance philosophy allocate responsibility for keeping an accepted and reliable programme so that compensation event assessment remains fair, timely, and administratively workable?
- **L2 (clauses):**    What clauses govern the Project Manager’s assessment of a compensation event where the latest submitted programme has not been accepted, including which programme or assumptions are used and what duties arise for quotation and assessment?
- **L3 (practice):**   What practical behaviours should the Project Manager and Contractor adopt when the current programme is unaccepted to avoid distorted time and cost assessments, procedural deadlock, or disputes?
- **canonical_topic:** `compensation_event_notification_quotation_assessment`

### Anchor Clauses (scenario ground-truth, used for CR)
- **GCC anchors:**  (none)
- **NEC4 anchors:** cl. 64.2, cl. 64.3, cl. 66.1

*Generated by MAS v2.2 — LangGraph orchestrator (6 agents + 3 rule modules).*