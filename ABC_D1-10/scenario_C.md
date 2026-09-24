# Scenario C: Programme Non-Compliance Without Early Warning

**Generated:** 2026-07-07 14:56

## Context
Contractor late on programme submission and execution. No early warning issued. Engineer/PM seeks to understand contractual consequences.

## MAS Query Topic
> The contractor submits the initial programme two weeks late and subsequently falls four weeks behind the accepted programme. No early warning notice has been issued. Compare the procedural consequences and remedies available to the Engineer/PM under each contract.

Specific questions to address:
Consequences and remedies for late programme submission without early warning.

## Validation Results

### Overall — ✅ PASSED  (confidence: 0.9, iterations used: 1)

> Accepted under relaxed rule: 1 per-metric below threshold (within tolerance of 1); composite confidence 0.90 ≥ 0.8.

### Rule-based Validation (deterministic)

**Track verdict:** ❌ fail

| Metric | Value | Threshold | Status |
|---|---|---|---|
| Citation Accuracy Rate (GCC) | 1.00 | ≥ 0.85 | ✅ pass |
| Citation Accuracy Rate (NEC4) | 1.00 | ≥ 0.85 | ✅ pass |
| Coverage Rate (GCC) | 1.00 | ≥ 0.85 | ✅ pass |
| Coverage Rate (NEC4) | 0.60 | ≥ 0.85 | ❌ fail |
| Composite Confidence | 0.90 | ≥ 0.70 | ✅ pass |
| Clause format | 0 violation(s) | All match regex | ✅ pass |

**GCC anchor coverage:**
 ✅ Clause 16 ✅ Clause 51 ✅ Clause 50(1)(a) ✅ Clause 81

**NEC4 anchor coverage:**
 ✅ cl. 15.1 ✅ cl. 31.1 ✅ cl. 32.1
 ❌ cl. 15.4 ❌ cl. 91.1

### LLM-based Semantic Validation

**Track verdict:** ❌ fail (overridden by high-confidence rule track)
**Severity:** significant

**Issues raised by LLM reviewer:**

1. **[E1 — Hallucinated clause — cited in synthesis but absent from raw evidence]** The synthesis cites SCC Clause A1(6)(b)(iv), but the GCC raw evidence only lists SCC Clause A1(6) and does not include that subclause number.
2. **[E1 — Hallucinated clause — cited in synthesis but absent from raw evidence]** The synthesis cites DEVB Practice Notes Section A6.1.1.20, but that numbered section does not appear anywhere in the NEC raw evidence.
3. **[E1 — Hallucinated clause — cited in synthesis but absent from raw evidence]** The synthesis cites NEC cl. 36.1 for acceleration, but cl. 36.1 does not appear anywhere in the NEC raw evidence.

**Gap queries proposed by LLM:**
- *GCC:* Retrieve the text/evidence for GCC SCC Clause A1(6)(b)(iv) addressing significant deviation from the Works Programme.
- *NEC:* Retrieve NEC/DEVB evidence for DEVB Practice Notes Section A6.1.1.20 on early warnings and NEC4 ECC cl. 36.1 on acceleration.

## Comparative Synthesis

> **Executive summary** — GCC gives the Engineer recovery, withholding and default levers but limits late claims; NEC imposes a direct 25% first-programme retention and adverse CE assessment. GCC is Engineer-led and retrospective, while NEC is relational and prospective, requiring earlier warnings, forecasts and evidence.

<details>
<summary><b>1. Spirit / Philosophy</b> — Engineer control versus proactive risk governance.</summary>

GCC: The GCC approach is Engineer-led, compliance-based and claims-oriented. Programme submission, delay notice, particulars and payment certification are administered through formal written steps; in Transaction Cost Economics terms, it controls uncertainty and opportunism through ex post verification, sanctions and certification powers.

NEC: NEC4 ECC treats time and risk management prospectively under the spirit of mutual trust and co-operation in cl. 10.2. The Accepted Programme, early warnings, revised programmes and compensation-event assessment form a relational governance system designed to reduce transaction costs by requiring transparent forecasting and early mitigation rather than retrospective blame allocation.

</details>

<details>
<summary><b>2. GCC Position (Implementation)</b> — Late programme becomes breach and recovery control.</summary>

**Implementation flow:**

1. Contractor submits initial programme within 14 days of acceptance of the Tender (Clause 16(1)) →
2. Contractor gives written delay notice within 28 days of cause arising, or forthwith when an Engineer order is foreseeably likely to delay (Clause 50(1)(a)) →
3. Contractor gives notice of intention to claim additional payment within 28 days after the event (Clause 64(2)) →
4. Engineer informs Contractor in writing if progress is too slow; Contractor immediately expedites and revises Clause 16 programme (Clause 51(1)) →
5. Engineer may instruct night work or extended hours (Clause 51(2)) and consider payment/default remedies (Clause 79(5), Clause 81(1)(e)).

Clause 16(1) requires the Contractor to submit the initial programme within 14 days of acceptance of the Tender; a submission two weeks late is a breach. Clause 16(2) preserves the Contractor’s duties: submission or approval of the programme does not relieve the Contractor of any duty or responsibility under the Contract.

The GCC has no general NEC-style early warning regime. Instead, Clause 50(1)(a) requires written notice of the cause and probable extent of delay within 28 days of the cause arising, and adds a foresight proviso: “as soon as the Contractor can reasonably foresee that any order or instruction issued by the Engineer is likely to cause a delay... the Contractor shall forthwith give notice in writing”. Clause 50(3) then limits EOT administration if full and detailed particulars are not submitted: the Engineer considers EOT “only to the extent that the Engineer is able on the information available”. Clause 50(4) is cited in the programme/delay framework, but no further operative detail was provided.

For money, Clause 64(2) requires a written notice of intention to claim additional payment within 28 days after the happening of the event. Clause 64(5) is an absolute time bar: if the 28-day Clause 64(2) notice is not given, “such claim shall not be considered”. Clause 64(6) similarly concerns cost particulars.

Where the Contractor is four weeks behind, Clause 51(1) applies if, in the Engineer’s opinion, the rate of progress is “too slow to ensure completion by the prescribed time”. The Engineer may inform the Contractor in writing; the Contractor must immediately take necessary steps to expedite completion and “revise the programme referred to in Clause 16 accordingly”. Under Clause 51(2), the Engineer may instruct night work or extended hours if necessary due to slow progress.

The standard GCC has no liquidated financial penalty specifically for late programme submission. However, Clause 79(5) allows the Engineer to “omit from any certificate the value of any work done, materials supplied or services rendered with which the Engineer may for the time being be dissatisfied... or for any other reason which to the Engineer may seem proper”. If delay and breach persist after warning, Clause 81(1)(e) allows expulsion: if the Engineer certifies that the Contractor, “despite previous warning by the Engineer in writing”, is failing to proceed with due diligence or is persistently in breach, the Employer may, after giving 7 days’ notice, expel the Contractor from the Site.

</details>

<details>
<summary><b>3. NEC4 Position (Implementation)</b> — First programme retention and CE consequences.</summary>

**Implementation flow:**

1. Contractor submits first programme within the period stated in Contract Data if none is identified (cl. 31.1) →
2. PM retains 25% of Price for Work Done to Date at assessment until a compliant first programme is submitted (cl. 50.1, cl. 50.5) →
3. PM replies within two weeks to accept or reject the submitted programme (cl. 31.3; cl. 13.4) →
4. Contractor gives early warning as soon as aware of matter delaying Completion or increasing Prices (cl. 15.1) →
5. PM instructs revised programme showing actual progress and delay response; PM replies within two weeks (cl. 32.1, cl. 32.2, cl. 31.3) →
6. If CE/early warning failures arise, PM applies cl. 61.5, cl. 63.7, cl. 61.3, cl. 64.1, cl. 64.2 and, for Options C/D/E, cl. 11.2(26).

Under NEC4 ECC, time and risk management are prospective and governed by mutual trust and co-operation (cl. 10.2). If no programme is identified in the Contract Data, the Contractor must submit a first programme to the Project Manager for acceptance within the period stated in the Contract Data (cl. 31.1). cl. 31.2 is cited as part of the programme framework, but no operative wording was provided in the source material.

If the Contractor misses the first-programme deadline, the Project Manager must retain 25% of the Price for Work Done to Date in assessing the amount due until the Contractor submits a first programme showing the required information (cl. 50.1, cl. 50.5). Once the first programme is submitted, even two weeks late, the Project Manager must reply within two weeks, accepting it or giving contractual reasons for non-acceptance (cl. 31.3). The source also states that the Project Manager releases the 25% retention in the next payment certificate following submission of a first programme containing all required information, and replies within two weeks to accept or reject it (cl. 13.4, cl. 31.3, cl. 50.5). The cl. 50.5 retention applies only to failure to submit the first programme; it cannot be used to penalise failure to submit later revised programmes or being behind schedule.

The Contractor must give early warning to the Project Manager as soon as it becomes aware of any matter which could delay Completion or increase the total of the Prices (cl. 15.1). Revised programmes must be submitted at the interval stated in the Contract Data or when instructed by the Project Manager (cl. 32.2), and must show actual progress and “how the Contractor plans to deal with any delays” (cl. 32.1). If the recovery plan is not achievable, the Project Manager may reject it because it “does not represent the Contractor’s plans realistically” or because “the Contractor’s plans which it shows are not practicable” (cl. 31.3).

If the four-week delay involves a compensation event, the Project Manager notifies the Contractor of failure to give an early warning when instructing the quotation (cl. 61.5). The event is then assessed as if the Contractor had given the early warning (cl. 63.7), excluding avoidable time and cost. Under Options C, D and E, cost incurred because the Contractor failed to give a required early warning is Disallowed Cost and deducted from payment (cl. 11.2(26)). If the Contractor failed to notify a compensation event within 8 weeks of becoming aware, it loses all entitlement to a change in the Prices or Completion Date (cl. 61.3). If an instructed revised programme is not submitted or is rejected for a contractual reason, the Project Manager assesses compensation events using their own assessment of the remaining-work programme (cl. 64.1, cl. 64.2).

</details>

<details>
<summary><b>4. Behavioural Implications</b> — Retrospective notices become live risk tools.</summary>

Under GCC, the Contractor’s immediate exposure is breach of Clause 16(1), then loss or restriction of entitlements if delay and cost notices are not preserved. The Engineer’s behaviour is formal and sequential: issue written slow-progress communication under Clause 51(1), require immediate expedition and a revised Clause 16 programme, consider night work or extended hours under Clause 51(2), administer EOT only on available information under Clause 50(3), reject unnotified money claims under Clause 64(5), and escalate to Clause 81(1)(e) if due diligence failures persist after warning.

Under NEC4, the PM’s response is more immediate and commercial. Missing the first programme triggers the cl. 50.5 25% retention against Price for Work Done to Date until a compliant first programme is submitted. Falling four weeks behind without early warning shifts the focus to updated forecasting: the PM instructs a revised programme under cl. 32.2, requires actual progress and delay-management proposals under cl. 32.1, and accepts or rejects the programme within two weeks under cl. 31.3.

The evidential incentive also differs. GCC evidence protects retrospective EOT and payment claims; NEC evidence supports live mitigation, quotations, Accepted Programme integrity and compensation-event assessment. No early warning under NEC can reduce CE recovery through cl. 61.5 and cl. 63.7, become Disallowed Cost under cl. 11.2(26) for Options C/D/E, and combine with the 8-week cl. 61.3 time bar to remove entitlement entirely.

**Implementation comparison (GCC vs NEC4):**

| Aspect | GCC | NEC4 |
|---|---|---|
| Initial programme deadline | Within 14 days of Tender acceptance (Clause 16(1)). | Within Contract Data period if none identified (cl. 31.1). |
| Late first programme sanction | Breach; no specific liquidated programme penalty (Clause 16(1)). | Retain 25% PWDD until compliant first programme (cl. 50.5). |
| Delay warning trigger | Delay notice within 28 days of cause (Clause 50(1)(a)). | Early warning as soon as aware (cl. 15.1). |
| Recovery programme power | Engineer requires expedition and revised Clause 16 programme (Clause 51(1)). | PM instructs revised programme showing delay response (cl. 32.1, cl. 32.2). |
| Unnotified money claim | Claim not considered if 28-day notice missed (Clause 64(5)). | CE entitlement barred if 8-week notice missed (cl. 61.3). |
| Administrator assessment power | EOT only on available information (Clause 50(3)). | PM assesses CE if programme missing/rejected (cl. 64.1, cl. 64.2). |


</details>

<details>
<summary><b>5. GCC Lessons for NEC Adoption</b> — GCC routines transfer, but must move earlier.</summary>

Hong Kong practitioners already know the discipline of Clause 16(1): a programme is a contractual submission, not a courtesy document. That habit transfers directly to NEC cl. 31.1, but the behavioural adjustment is sharper because cl. 50.5 attaches a 25% Price for Work Done to Date retention until a compliant first programme is submitted; the programme becomes a payment-critical control baseline.

GCC Clause 50(1)(a) and Clause 64(2) notice routines transfer to NEC cl. 15.1 early warnings and cl. 61.3 compensation-event notices. The adjustment is timing and purpose: GCC practitioners accustomed to 28-day delay and claim notices must warn the PM as soon as they become aware of matters that could delay Completion or increase Prices, and must preserve CE entitlement within 8 weeks of becoming aware where cl. 61.3 applies.

GCC slow-progress administration under Clause 51(1) and Clause 51(2) transfers to NEC revised-programme management under cl. 32.1 and cl. 32.2. The familiar recovery-programme skill remains useful, but NEC requires the Contractor to show actual progress and how it plans to deal with delays, while the PM tests whether the plan is realistic and practicable under cl. 31.3.

GCC particulars and record habits under Clause 50(3), Clause 64(6), Clause 78(3), Clause 79(5) and SCC Clause A1(10) transfer to NEC quotations, Accepted Programme assessment and cost consequences under cl. 61.5, cl. 63.7, cl. 11.2(26), cl. 64.1 and cl. 64.2. The practical reframing is simple: use GCC claim, record, variation and delay-analysis habits earlier under NEC as forecasting, mitigation and commercial-management tools.

| GCC practice / experience | → How it transfers to NEC implementation |
|---|---|
| Clause 16(1) initial programme submission discipline. | Use for cl. 31.1 compliance; avoid cl. 50.5 25% retention. |
| Clause 50(1)(a) 28-day delay notices. | Convert to cl. 15.1 early warnings as soon as aware. |
| Clause 64(2) claim notice and Clause 64(6) particulars. | Support cl. 61.3 CE notice and quotation evidence within 8 weeks. |
| Clause 51(1) recovery programme after slow-progress warning. | Prepare cl. 32.1 revised programme showing actual progress and delay response. |
| Clause 50(3) EOT analysis on available information. | Feed cl. 63.7 and cl. 64.1/cl. 64.2 PM assessment evidence. |

</details>

<details>
<summary><b>6. HK-Specific Notes</b> — PAH SCC controls and DEVB NEC guidance apply.</summary>

For GCC mega project contracts, the Project Administration Handbook (PAH) Chapter 5, Appendix 5.36 prescribes stricter mechanisms through SCC Clause A1 that directly address programme slippage and reporting. SCC A1(6)(b)(iv) requires the Contractor to review and submit an amended Works Programme if the Contractor foresees a “significant deviation between the actual or anticipated progress of the Works and the Works Programme”. Under SCC A1(7), if the Engineer notices a significant deviation, the Engineer may issue a written instruction requiring the Contractor to produce a revised version within 14 days.

SCC A1(10) requires the Contractor to submit a Monthly Progress Report highlighting departures from the Works Programme and proposing measures to make good the delays. An amendment to Clause 78(3) makes submission of this Monthly Progress Report a “condition precedent to consideration by the Engineer of any sums due to the Contractor”. The result is stronger than the standard GCC programme breach position: failure to provide the programme-based report can block the interim payment mechanism. The GCC expert response also states that Works Bureau Technical Circular WB1900 does not address this aspect.

For NEC4 ECC in Hong Kong, the DEVB Practice Notes provide guidance on enforcing the NEC mechanisms. On the 25% retention, DEVB reminds Project Managers that cl. 50.5 applies only to the first programme. Great care must be exercised: the Project Manager should not accept a substandard first programme merely to tick a box and avoid retaining funds, because the Accepted Programme is essential for project control.

For failure to provide early warning, DEVB Practice Notes Section A6.1.1.20 states that early warning is a strict contractual requirement. If the Contractor fails to provide it, the Project Manager must invoke cl. 61.5 and cl. 63.7 to assess the event as if the warning had been given. Under Options C and D, the Project Manager is instructed to use discretion to treat costs incurred due to the lack of early warning as Disallowed Cost.

On mitigation versus acceleration, the DEVB guidance states that the Contractor is strictly obliged to mitigate delays to optimise planned Completion at no cost or inefficiency to itself, for example by resequencing. If the Project Manager wants actively to bring the Completion Date forward using additional resources, the PM must instruct a quotation for acceleration under cl. 36.1. Acceleration cannot be unilaterally imposed on the Contractor; it requires mutual agreement.

</details>

## Clause Map (extracted by CM-A)

Structured index of every clause cited by the expert agents, with its taxonomy category and a verbatim quote / paraphrase.

- **GCC · Clause 16(1)** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **within 14 days of the acceptance of the Tender** · condition: **acceptance of the Tender**
  > Under Clause 16(1), the Contractor is contractually obligated to submit the initial programme within 14 days of the acceptance of the Tender
- **GCC · Clause 16(2)** — _programme_obligations_ · obligation: **condition** · party: **Contractor** · condition: **submission or approval of the programme**
  > under Clause 16(2), the submission or approval of the programme does not relieve the Contractor of any duty or responsibility under the Contract
- **GCC · Clause 50(1)(a)** — _early_warning_risk_ · obligation: **process** · party: **Contractor** · timeline: **within 28 days of the cause arising** · condition: **cause of delay arising**
  > Under Clause 50(1)(a), the Contractor must give written notice of the cause and probable extent of a delay within 28 days of the cause arising
- **GCC · Clause 50(3)** — _extension_of_time_ · obligation: **process** · party: **Engineer** · condition: **if the Contractor fails to submit full and detailed particulars of the delay**
  > Under Clause 50(3), if the Contractor fails to submit full and detailed particulars of the delay, the Engineer shall consider the EOT "only to the extent that the Engineer is able on the information available"
- **GCC · Clause 50(4)** — _programme_obligations_ · obligation: **process** · party: **n/a**
  > Clause 50(4)
- **GCC · Clause 51(1)** — _programme_obligations_ · obligation: **process** · party: **both** · timeline: **immediately** · condition: **if the rate of progress is, in the opinion of the Engineer, too slow to ensure completion by the prescribed time**
  > Clause 51(1) governs the recovery: if the rate of progress is, in the opinion of the Engineer, "too slow to ensure completion by the prescribed time", the Engineer may inform the Contractor in writing.
- **GCC · Clause 51(2)** — _programme_obligations_ · obligation: **right** · party: **Engineer** · condition: **if necessary due to the Contractor's slow progress**
  > The Engineer is also empowered under Clause 51(2) to instruct night work or extended hours if necessary due to the Contractor's slow progress
- **GCC · Clause 64(2)** — _dispute_resolution_ · obligation: **process** · party: **Contractor** · timeline: **within 28 days after the happening of the event** · condition: **happening of the event**
  > Under Clause 64(2), the Contractor must serve a written notice of intention to claim additional payment within 28 days after the happening of the event
- **GCC · Clause 64(5)** — _dispute_resolution_ · obligation: **condition** · party: **Contractor** · timeline: **28-day notice provision in Clause 64(2)** · condition: **if the Contractor fails to comply with the 28-day notice provision in Clause 64(2)**
  > Under Clause 64(5), if the Contractor fails to comply with the 28-day notice provision in Clause 64(2), "such claim shall not be considered"
- **GCC · Clause 64(6)** — _dispute_resolution_ · obligation: **process** · party: **Contractor** · condition: **failure to provide cost particulars**
  > (Similarly for cost particulars under Clause 64(6)
- **GCC · Clause 78(3)** — _payment_mechanism_ · obligation: **condition** · party: **Contractor** · condition: **submitting this Monthly Progress Report**
  > an amendment to Clause 78(3) dictates that submitting this Monthly Progress Report is a "condition precedent to consideration by the Engineer of any sums due to the Contractor"
- **GCC · Clause 79(5)** — _payment_mechanism_ · obligation: **right** · party: **Engineer** · condition: **work done, materials supplied or services rendered with which the Engineer may for the time being be dissatisfied, or any other reason which to the Engineer may seem proper**
  > under Clause 79(5), the Engineer has the broad discretionary power to "omit from any certificate the value of any work done, materials supplied or services rendered with which the Engineer may for the time being be dissatisfied... or for any other reason which to the Engineer may seem proper"
- **GCC · Clause 81(1)(e)** — _termination_rights_ · obligation: **remedy** · party: **Employer** · timeline: **after giving 7 days' notice** · condition: **if the Engineer certifies that the Contractor despite previous warning by the Engineer in writing is failing to proceed with the Works with due diligence or is persistently in breach of any of his obligations**
  > Clause 81(1)(e) applies. If the Engineer certifies that the Contractor "despite previous warning by the Engineer in writing is failing to proceed with the Works with due diligence or is persistently in breach of any of his obligations", the Employer may, after giving 7 days' notice, expel the Contractor from the Site
- **GCC · Clause 16** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **immediately** · condition: **if the rate of progress is too slow to ensure completion by the prescribed time**
  > The Contractor must then immediately take necessary steps to expedite completion and "revise the programme referred to in Clause 16 accordingly"
- **NEC4 · cl. 10.2** — _mutual_trust_ · obligation: **duty** · party: **both**
  > time and risk management are handled prospectively, relying heavily on the spirit of mutual trust and co-operation (cl. 10.2).
- **NEC4 · cl. 11.2(26)** — _uncategorised_ · obligation: **remedy** · party: **Contractor** · timeline: **next payment assessment** · condition: **If the contract uses a target or reimbursable Option**
  > any cost incurred because the Contractor failed to give an early warning required by the contract is treated as Disallowed Cost and deducted from the Contractor's payment (cl. 11.2(26))
- **NEC4 · cl. 13.4** — _mutual_trust_ · obligation: **process** · party: **PM** · timeline: **within two weeks; next payment certificate following submission** · condition: **following the submission of a first programme containing all required information**
  > Project Manager releases the 25% retention in the next payment certificate following the submission of a first programme containing all required information, and replies within two weeks to accept or reject the programme (cl. 13.4, cl. 31.3, cl. 50.5).
- **NEC4 · cl. 15.1** — _early_warning_risk_ · obligation: **duty** · party: **Contractor** · timeline: **as soon as they become aware** · condition: **any matter which could delay Completion or increase the total of the Prices**
  > The Contractor has an express duty to give an early warning to the Project Manager as soon as they become aware of any matter which could delay Completion or increase the total of the Prices (cl. 15.1)
- **NEC4 · cl. 31.1** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **within the period stated in the Contract Data** · condition: **If no programme is identified in the Contract Data**
  > If no programme is identified in the Contract Data, the Contractor must submit a first programme to the Project Manager for acceptance within the period stated in the Contract Data (cl. 31.1)
- **NEC4 · cl. 31.2** — _programme_obligations_ · obligation: **process** · party: **n/a**
- **NEC4 · cl. 31.3** — _programme_obligations_ · obligation: **process** · party: **PM** · timeline: **within two weeks** · condition: **Once submitted**
  > Once submitted (even if two weeks late), the Project Manager must reply within two weeks, either accepting it or giving contractual reasons for non-acceptance (cl. 31.3)
- **NEC4 · cl. 32.1** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · condition: **A revised programme**
  > A revised programme must show the actual progress achieved and, crucially, "how the Contractor plans to deal with any delays" (cl. 32.1)
- **NEC4 · cl. 32.2** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **at the interval stated in the Contract Data or when instructed by the Project Manager** · condition: **when instructed by the Project Manager**
  > the Contractor is required to submit revised programmes at the interval stated in the Contract Data or when instructed by the Project Manager (cl. 32.2)
- **NEC4 · cl. 50.1** — _payment_mechanism_ · obligation: **process** · party: **PM** · timeline: **at the first assessment date** · condition: **if the initial programme has not yet been submitted**
  > Project Manager assesses the amount due at the first assessment date and retains 25% of the Price for Work Done to Date if the initial programme has not yet been submitted (cl. 50.1, cl. 50.5).
- **NEC4 · cl. 50.5** — _payment_mechanism_ · obligation: **remedy** · party: **PM** · timeline: **until the Contractor submits a first programme showing the information which the contract requires** · condition: **if the Contractor misses this deadline**
  > if the Contractor misses this deadline, the Project Manager is required to retain 25% of the Price for Work Done to Date in the assessment of the amount due until the Contractor submits a first programme showing the information which the contract requires (cl. 50.5)
- **NEC4 · cl. 61.3** — _compensation_event_notification_quotation_assessment_ · obligation: **remedy** · party: **Contractor** · timeline: **within 8 weeks of becoming aware** · condition: **If the delay stems from a compensation event that the Contractor failed to notify**
  > If the delay stems from a compensation event that the Contractor failed to notify within 8 weeks of becoming aware, the Contractor loses all entitlement to a change in the Prices or the Completion Date (cl. 61.3)
- **NEC4 · cl. 61.5** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · timeline: **when instructing the quotation** · condition: **If the delay is due to a compensation event**
  > If the delay is due to a compensation event, the Project Manager notifies the Contractor of the failure to give an early warning when instructing the quotation (cl. 61.5)
- **NEC4 · cl. 63.7** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **as if the Contractor had given the early warning**
  > The event is then assessed as if the Contractor had given the early warning (cl. 63.7)
- **NEC4 · cl. 64.1** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **If the Contractor fails to submit the instructed revised programme, or if it is rejected for a contractual reason**
  > If the Contractor fails to submit the instructed revised programme, or if it is rejected for a contractual reason, the Contractor loses the right to assess compensation events. The Project Manager will instead assess them using their own assessment of the programme for the remaining work (cl. 64.1, cl. 64.2)
- **NEC4 · cl. 64.2** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **If the Contractor fails to submit the instructed revised programme, or if it is rejected for a contractual reason**
  > If the Contractor fails to submit the instructed revised programme, or if it is rejected for a contractual reason, the Contractor loses the right to assess compensation events. The Project Manager will instead assess them using their own assessment of the programme for the remaining work (cl. 64.1, cl. 64.2)
- **NEC4 · cl. 36.1** — _extension_of_time_ · obligation: **process** · party: **n/a**

## Raw Expert Evidence (NotebookLM responses)

The full unmodified responses from the GCC and NEC4 expert agents are reproduced below for traceability.

<details>
<summary>GCC expert response (1 iteration(s), 6,268 chars)</summary>

[CLAUSE REFERENCES] Clause 16(1), Clause 16(2), Clause 50(1)(a), Clause 50(3), Clause 50(4), Clause 51(1), Clause 51(2), Clause 64(2), Clause 64(5), Clause 64(6), Clause 78(3) (as amended by SCC), Clause 79(5), Clause 81(1)(e), Special Conditions of Contract (SCC) Clause A1(6), SCC Clause A1(7), SCC Clause A1(10).
[GCC POSITION] Submission, Revisions, and Acceptance of Programme Under Clause 16(1), the Contractor is contractually obligated to submit the initial programme within 14 days of the acceptance of the Tender
. Submitting it two weeks past this deadline is a breach of this obligation. Furthermore, under Clause 16(2), the submission or approval of the programme does not relieve the Contractor of any duty or responsibility under the Contract
. If the Contractor falls behind, Clause 51(1) governs the recovery: if the rate of progress is, in the opinion of the Engineer, "too slow to ensure completion by the prescribed time", the Engineer may inform the Contractor in writing. The Contractor must then immediately take necessary steps to expedite completion and "revise the programme referred to in Clause 16 accordingly"
. The Engineer is also empowered under Clause 51(2) to instruct night work or extended hours if necessary due to the Contractor's slow progress
Duty to Notify Delay Risks / Early Warning The standard GCC relies on strict retrospective and foreseeable notification mechanisms rather than a general "early warning" system.
Time: Under Clause 50(1)(a), the Contractor must give written notice of the cause and probable extent of a delay within 28 days of the cause arising
. It includes a foresight proviso: "as soon as the Contractor can reasonably foresee that any order or instruction issued by the Engineer is likely to cause a delay... the Contractor shall forthwith give notice in writing"
Cost: Under Clause 64(2), the Contractor must serve a written notice of intention to claim additional payment within 28 days after the happening of the event
Consequences of Failing to Notify The failure to provide timely notices severely limits the Contractor's entitlements:
Additional Cost: The time-bar is absolute. Under Clause 64(5), if the Contractor fails to comply with the 28-day notice provision in Clause 64(2), "such claim shall not be considered"
Extension of Time (EOT): Under Clause 50(3), if the Contractor fails to submit full and detailed particulars of the delay, the Engineer shall consider the EOT "only to the extent that the Engineer is able on the information available"
. (Similarly for cost particulars under Clause 64(6)
Powers and Remedies of the Contract Administrator
Withholding/Reducing Payment: The standard GCC does not specify a liquidated financial penalty specifically for late programme submission. However, under Clause 79(5), the Engineer has the broad discretionary power to "omit from any certificate the value of any work done, materials supplied or services rendered with which the Engineer may for the time being be dissatisfied... or for any other reason which to the Engineer may seem proper"
Breach/Default and Expulsion: If the Contractor continues to fall behind and ignores the Engineer's instructions, Clause 81(1)(e) applies. If the Engineer certifies that the Contractor "despite previous warning by the Engineer in writing is failing to proceed with the Works with due diligence or is persistently in breach of any of his obligations", the Employer may, after giving 7 days' notice, expel the Contractor from the Site
[PROCEDURAL IMPLICATION]
Engineer issues a formal warning in writing to the Contractor regarding the persistent breaches (late programme submission) and the failure to proceed with due diligence (falling four weeks behind) (Clause 81(1)(e)).
Engineer formally informs the Contractor in writing that the rate of progress is too slow to ensure completion (Clause 51(1)).
Contractor immediately takes steps to expedite completion and submits a revised/recovery programme (Clause 51(1)).
Engineer may exercise the power to omit from the Contractor's interim payment certificate the value of any work or services with which they are dissatisfied due to the unmitigated delays or missing administrative submissions (Clause 79(5)).
Engineer rejects any claims for additional payment arising from the delay events because the Contractor failed to serve the mandatory 28-day notice of intention to claim (Clause 64(2), Clause 64(5)).
Engineer considers any EOT based strictly only on the limited information available to them, as the Contractor failed to provide timely delay notices and particulars (Clause 50(1)(a), Clause 50(3)).
If the Contractor fails to expedite the works or continues to breach obligations after the written warning, Engineer certifies this to the Employer, and the Employer may give 7 days' notice to expel the Contractor (Clause 81(1)(e)).
[HK CONTEXT] For Mega Project Contracts, the Project Administration Handbook (PAH) Chapter 5 (Appendix 5.36) prescribes stricter mechanisms via SCC Clause A1 that directly address this scenario:
Requirement for Revised Programme: SCC A1(6)(b)(iv) explicitly requires the Contractor to review and submit an amended Works Programme if the Contractor foresees a "significant deviation between the actual or anticipated progress of the Works and the Works Programme"
. Furthermore, under SCC A1(7), if the Engineer notices a significant deviation, the Engineer is entitled by written instruction to require the Contractor to produce a revised version within 14 days
Payment Withholding: SCC A1(10) requires the Contractor to submit a Monthly Progress Report highlighting departures from the Works Programme and proposing measures to make good the delays
. Crucially, an amendment to Clause 78(3) dictates that submitting this Monthly Progress Report is a "condition precedent to consideration by the Engineer of any sums due to the Contractor"
. Thus, failure to provide these programme-based reports completely blocks the interim payment mechanism. Works Bureau Technical Circular WB1900 does not address this aspect.
How should the Engineer respond if the initial programme is late?
Can payment be withheld if the Monthly Progress Report is missing?
What are the Engineer's powers when progress is too slow?

</details>

<details>
<summary>NEC4 expert response (1 iteration(s), 6,906 chars)</summary>

[CLAUSE REFERENCES] cl. 10.2, cl. 11.2(26), cl. 13.4, cl. 15.1, cl. 31.1, cl. 31.2, cl. 31.3, cl. 32.1, cl. 32.2, cl. 50.1, cl. 50.5, cl. 61.3, cl. 61.5, cl. 63.7, cl. 64.1, cl. 64.2
[NEC POSITION] Under the NEC4 ECC, time and risk management are handled prospectively, relying heavily on the spirit of mutual trust and co-operation (cl. 10.2).
Initial Programme Submission and Payment Sanctions: If no programme is identified in the Contract Data, the Contractor must submit a first programme to the Project Manager for acceptance within the period stated in the Contract Data (cl. 31.1)
. To enforce this, if the Contractor misses this deadline, the Project Manager is required to retain 25% of the Price for Work Done to Date in the assessment of the amount due until the Contractor submits a first programme showing the information which the contract requires (cl. 50.5)
more_horiz
. Once submitted (even if two weeks late), the Project Manager must reply within two weeks, either accepting it or giving contractual reasons for non-acceptance (cl. 31.3)
Duty to Notify Delay Risks (Early Warning) and Revisions: The Contractor has an express duty to give an early warning to the Project Manager as soon as they become aware of any matter which could delay Completion or increase the total of the Prices (cl. 15.1)
. Furthermore, the Contractor is required to submit revised programmes at the interval stated in the Contract Data or when instructed by the Project Manager (cl. 32.2)
. A revised programme must show the actual progress achieved and, crucially, "how the Contractor plans to deal with any delays" (cl. 32.1)
Consequences, Powers, and Remedies for Failure to Notify: Because the Contractor fell 4 weeks behind without giving an early warning or delay notice, the Project Manager has several powers and remedies:
Limiting Entitlement (Assessment): If the delay is due to a compensation event, the Project Manager notifies the Contractor of the failure to give an early warning when instructing the quotation (cl. 61.5)
. The event is then assessed as if the Contractor had given the early warning (cl. 63.7)
. This means any time or cost that could have been avoided by competent and prompt mitigation had the warning been given is excluded from the Contractor's extension of time and financial entitlement
Disallowed Cost (Options C, D, E): If the contract uses a target or reimbursable Option, any cost incurred because the Contractor failed to give an early warning required by the contract is treated as Disallowed Cost and deducted from the Contractor's payment (cl. 11.2(26))
Time-Bar for Compensation Events: If the delay stems from a compensation event that the Contractor failed to notify within 8 weeks of becoming aware, the Contractor loses all entitlement to a change in the Prices or the Completion Date (cl. 61.3)
Rejection of the Revised Programme: The Project Manager can instruct the Contractor to submit a revised programme to show how they will recover the 4-week delay (cl. 32.2)
. If the Contractor's submitted plan is not achievable, the Project Manager can reject it on the grounds that it "does not represent the Contractor's plans realistically" or that "the Contractor's plans which it shows are not practicable" (cl. 31.3)
Project Manager's Own Assessment: If the Contractor fails to submit the instructed revised programme, or if it is rejected for a contractual reason, the Contractor loses the right to assess compensation events. The Project Manager will instead assess them using their own assessment of the programme for the remaining work (cl. 64.1, cl. 64.2)
Note that the 25% payment withholding under cl. 50.5 applies only to the failure to submit the first programme; it cannot be used to penalise the Contractor for failing to submit subsequent revised programmes or for falling behind schedule
[PROCEDURAL IMPLICATION]
Project Manager assesses the amount due at the first assessment date and retains 25% of the Price for Work Done to Date if the initial programme has not yet been submitted (cl. 50.1, cl. 50.5).
Contractor submits the first programme 2 weeks late (cl. 31.1).
Project Manager releases the 25% retention in the next payment certificate following the submission of a first programme containing all required information, and replies within two weeks to accept or reject the programme (cl. 13.4, cl. 31.3, cl. 50.5).
Project Manager (upon discovering the 4-week delay) instructs the Contractor to submit a revised programme showing actual progress and how they plan to deal with the delay (cl. 32.1, cl. 32.2).
Contractor submits the revised programme within the period for reply (cl. 32.2).
Project Manager replies within two weeks, accepting the revised programme or rejecting it if the recovery plan is not realistic or practicable (cl. 31.3).
Project Manager (if the delay involves a compensation event) notifies the Contractor of their failure to give an early warning when instructing a quotation (cl. 61.5).
Project Manager assesses the compensation event (or reviews the Contractor's quotation) as if the early warning had been given, stripping out avoidable delays and costs (cl. 63.7).
Project Manager (for Options C/D/E) deducts any costs incurred due to the lack of early warning as Disallowed Cost in the next payment assessment (cl. 11.2(26), cl. 50.1).
[HK CONTEXT] The DEVB Practice Notes provide robust guidance on enforcing these mechanisms in Hong Kong:
The 25% Retention: DEVB reminds Project Managers that the cl. 50.5 25% retention applies only to the first programme. Great care must be exercised; the Project Manager should not accept a substandard first programme simply to tick a box and avoid retaining the funds, as the Accepted Programme is essential for project control
Failure to Provide Early Warning: Section A6.1.1.20 explicitly dictates that an early warning is a strict contractual requirement. If the Contractor fails to provide it, the Project Manager must invoke cl. 61.5 and 63.7 to assess the event as if the warning had been given. Furthermore, under Options C and D, the Project Manager is instructed to use their discretion to treat costs incurred due to the lack of an early warning as Disallowed Cost
Mitigation vs Acceleration: In dealing with the 4-week delay, DEVB guidelines clarify that the Contractor is strictly obliged to mitigate delays to optimise planned Completion at no cost or inefficiency to themselves (e.g., resequencing). If the Project Manager wishes to actively bring the Completion Date forward using additional resources, they must instruct a quotation for acceleration under cl. 36.1. Acceleration cannot be unilaterally imposed on the Contractor; it requires mutual agreement
How does Option B handle remeasurement for compensation events?
Explain the 25% payment sanction for missing the first programme.
What costs are typically included in the Fee vs Defined Cost?

</details>

## SYN-A Chain-of-Thought Reasoning

<details>
<summary>Three-level reasoning trace (L1 → L2 → L3)</summary>

[L1 — Spirit/Philosophy]
GCC treats programme control as an Engineer-led compliance and claims-administration regime: the Contractor must submit the programme, notify delay and claims within strict periods, and recover only if it preserves evidential rights. In Transaction Cost Economics terms, it relies more on ex post verification, certification, withholding and default remedies to control opportunism. NEC4 ECC instead makes programme and risk information part of prospective joint management under cl. 10.2: the Contractor must warn, update and forecast early so the Project Manager can manage Completion, Prices and mitigation before the risk crystallises.

[L2 — Clause-level Comparison]
Under GCC, Clause 16(1) requires the initial programme within 14 days of acceptance of the Tender; Clause 16(2) prevents submission or approval from relieving the Contractor of responsibility. Delay governance then moves through Clause 50(1)(a) written notice within 28 days of the cause arising, Clause 50(3) limited EOT consideration where particulars are missing, Clause 50(4) as cited, and Clause 51(1)–(2) written notice of slow progress, immediate expedition, programme revision and possible night work or extended hours. Additional payment is controlled by Clause 64(2), Clause 64(5) and Clause 64(6), while payment/default pressure may arise through Clause 79(5), Clause 78(3) as amended by SCC Clause A1(10), and Clause 81(1)(e). Under NEC4, cl. 31.1, cl. 31.2, cl. 31.3, cl. 32.1 and cl. 32.2 structure first and revised programmes; cl. 50.1 and cl. 50.5 impose the 25% Price for Work Done to Date retention for missing the first programme; cl. 15.1, cl. 61.5, cl. 63.7, cl. 11.2(26), cl. 61.3, cl. 64.1 and cl. 64.2 control the consequences of no early warning, late compensation-event notice and inadequate programme information.

[L3 — Practice/Behavioural Implications + GCC-to-NEC Transfer]
For Hong Kong practitioners trained under GCC, the transferable skill is not simply “claiming”; it is disciplined time, notice and record management. GCC Clause 16(1) programme submission discipline maps to NEC cl. 31.1 and cl. 50.5, but NEC changes the purpose: the programme is not just an administrative submission but the commercial baseline for prospective assessment and payment release. GCC Clause 50(1)(a) delay notices and Clause 64(2) claim notices map to NEC cl. 15.1 early warnings and cl. 61.3 compensation-event notices; the adjustment is timing and purpose, from preserving retrospective entitlement within 28 days to warning “as soon as” aware and, for Contractor-notified compensation events, within 8 weeks of becoming aware. GCC Clause 51(1) recovery workflow maps to NEC cl. 32.1 and cl. 32.2 revised programmes: the Contractor must show actual progress and “how the Contractor plans to deal with any delays”, while the PM may reject unrealistic or impracticable plans under cl. 31.3. GCC particulars and site records supporting Clause 50(3), Clause 64(6) and payment certification map to NEC quotations, Defined Cost/Disallowed Cost consequences and PM assessment under cl. 63.7, cl. 11.2(26), cl. 64.1 and cl. 64.2; the behavioural change is to use evidence earlier for forecasting, mitigation and collaborative risk control rather than only later for claims defence.

</details>

---

### Query Plan (QP-A)
- **L1 (spirit):**     How does the contract’s governance philosophy allocate responsibility for timely and transparent programme management when the contractor fails to submit or maintain an acceptable programme?
- **L2 (clauses):**    What clauses define the contractor’s obligations to submit the initial programme, update or comply with the accepted programme, give early warning or notice of delay, and what powers, sanctions, or remedies are available to the contract administrator when those obligations are breached?
- **L3 (practice):**   In practice, how does late programme submission combined with subsequent delay and absence of early warning affect administration of progress, assessment of delay relief, payment or withholding mechanisms, instructions to recover, and the contractor’s exposure to adverse consequences?
- **canonical_topic:** `programme_obligations`

### Anchor Clauses (scenario ground-truth, used for CR)
- **GCC anchors:**  Clause 16, Clause 51, Clause 50(1)(a), Clause 81
- **NEC4 anchors:** cl. 15.1, cl. 15.4, cl. 31.1, cl. 32.1, cl. 91.1

*Generated by MAS v2.2 — LangGraph orchestrator (6 agents + 3 rule modules).*