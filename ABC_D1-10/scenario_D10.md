# Scenario D10: NEC Douglas D10 - Security fencing omitted from the Activity Schedule and programme

**Generated:** 2026-07-07 15:40

## Context
A Client uses ECC Option A with secondary Option X15 for a new asset. The Contractor submitted the first programme for acceptance in accordance with the contract timescales but then realises that a 30 m length of security fencing has not been priced, is not shown on the Activity Schedule, and is not shown on the programme. The fencing is clearly identified in the Scope.

## MAS Query Topic
> Security fencing omitted from the Activity Schedule and programme.

Specific questions to address:
How would your answer to part a. differ if it was an Option C contract?

## Validation Results

### Overall — ✅ PASSED  (confidence: 1.0, iterations used: 1)

> Accepted: no per-metric dips; composite confidence 1.00 ≥ 0.8. (LLM semantic flagged 2 moderate issue(s), but the verdict is gated on the composite-confidence rule and the LLM track does not block.)

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
 ✅ cl. 55.1 ✅ cl. 55.3

### LLM-based Semantic Validation

**Track verdict:** ❌ fail (overridden by high-confidence rule track)
**Severity:** moderate

**Issues raised by LLM reviewer:**

1. **[E1 — Hallucinated clause — cited in synthesis but absent from raw evidence]** The synthesis cites NEC cl. 32.2 for revised programme requirements, but cl. 32.2 does not appear anywhere in the supplied NEC raw evidence.
2. **[E1 — Hallucinated clause — cited in synthesis but absent from raw evidence]** The synthesis cites NEC HK Edition cl. 11.2(34) for the amended PWDD definition, but cl. 11.2(34) does not appear anywhere in the supplied NEC raw evidence.

**Gap queries proposed by LLM:**
- *GCC:* _(none)_
- *NEC:* Retrieve NEC4 ECC/HK Edition evidence for cl. 32.2 and cl. 11.2(34), including any revised programme requirements and Option C PWDD definition amendments.

## Comparative Synthesis

> **Executive summary** — GCC keeps fencing required and usually within rates unless Clause 59(3) corrects a true BQ omission. Under NEC Option C, fencing is paid as Defined Cost plus Fee, but the target Prices stay unadjusted, shifting behaviour to prompt correction, cost evidence and share-risk management.

<details>
<summary><b>1. Spirit / Philosophy</b> — Engineer-led risk vs relational correction.</summary>

GCC: The GCC approach is Engineer-led and claims/valuation-oriented. The Contractor must execute the Works and necessary Temporary Works, while incomplete tender or programme documents are addressed through BQ valuation, Engineer correction, or Contractor risk under Clauses 10, 14, 16 and 59. In TCE terms, it emphasises ex ante risk pricing and later authoritative administration.

NEC: NEC4 ECC is process-based and relational, grounded in the spirit of mutual trust and co-operation under cl. 10.2. It separates Scope from the Activity Schedule and programme, so omissions are corrected through management processes rather than treated as relieving obligations. Under Option C, the commercial effect is managed through Defined Cost, Fee and the target/share mechanism rather than simple activity-price entitlement.

</details>

<details>
<summary><b>2. GCC Position (Implementation)</b> — Required work despite pricing/programme omission.</summary>

**Implementation flow:**

1. Contractor provides fencing/Temporary Works required for execution and site safety throughout progress (Clause 10; Clause 20(1)) →
2. Engineer may require written particulars or a revised programme whenever required for contract management (Clause 16(1)) →
3. Programme submission/approval gives no relief from contractual duties (Clause 16(2)) →
4. Engineer reviews whether omission is tender-rate risk or genuine BQ omission (Clause 14; Clause 59(1); Clause 59(3)) →
5. If genuine BQ omission, Engineer corrects it and ascertains value of work actually carried out (Clause 59(3)); otherwise Contractor bears cost.

The GCC contains no Option C target-contract machinery. The expert response states that the corpus is silent on an “Option C target contract”, “Activity Schedule”, “Prices”, “Defined Cost”, “Fee”, “target adjustment”, “disallowed cost”, “pain/gain share”, and “compensation events”. Payment is instead governed by the “Bills of Quantities” or “Schedule of Rates” under Clause 59(1), with time or cost effects administered through variations, claims and extensions of time.

The obligation to provide security fencing remains. Clause 10 requires the Contractor to execute the Works and provide all “Temporary Works... and everything whether of a temporary or permanent nature required in and for such execution”. Clause 20(1) requires the Contractor “throughout the progress of the Works” to “take full responsibility for the adequate stability and safety of all operations on the Site”. Therefore, required security fencing must be provided even if absent from the Contractor’s planning or pricing documents.

Programme omission gives no waiver. Under Clause 16(1), the Engineer may instruct the Contractor to furnish written particulars or submit a revised programme showing the sequence and methods for installing the fencing whenever needed for contract management. Clause 16(2) states that submission to or approval by the Engineer of the programme “shall not relieve the Contractor of any duty or responsibility under the Contract”, so an accepted programme lacking fencing does not alter the duty.

Pricing turns on BQ risk allocation. Clause 14 deems the Contractor, before submitting his Tender, to have satisfied himself as to the “correctness and sufficiency of his Tender for the Works and of the rates stated in the priced Bills of Quantities”. If the fencing is a specific permanent works item omitted from the BQ but required by the Specification, Clause 59(3) applies: “Any error in description in the Bills of Quantities or item omitted therefrom shall not vitiate the Contract nor release the Contractor from the execution of the whole or any part of the Works...” and the Engineer “shall correct any such error or omission” and “ascertain the value of the work actually carried out”. If the fencing is a standard temporary safety measure, it is generally deemed included in existing rates.

</details>

<details>
<summary><b>3. NEC4 Position (Implementation)</b> — Option C pays cost but not target uplift.</summary>

**Implementation flow:**

1. Contractor provides fencing required by the Scope despite omission from Activity Schedule/programme (cl. 20.1; cl. 55.1) →
2. Project Manager notifies non-acceptance of non-compliant/unrealistic programme (cl. 31.3) →
3. Contractor revises Activity Schedule to relate to Scope without changing total Prices (cl. 55.3; cl. 55.4) →
4. Contractor submits revised programme with fencing operations, resources and planned Completion impact (cl. 31.2; cl. 32.1; cl. 32.2) →
5. Project Manager replies within the period for reply and assesses amount due; under Option C pays Defined Cost plus Fee and later assesses share (cl. 13.4; cl. 50.1; cl. 11.2(31); cl. 54.1).

NEC4 ECC manages the omission by separating Scope from Activity Schedule and programme, under mutual trust and co-operation in cl. 10.2. The Contractor must “Provide the Works in accordance with the Scope” under cl. 20.1. Because “Information in the Activity Schedule is not Scope or Site Information” under cl. 55.1, omission of security fencing from the Activity Schedule or programme does not relieve the Contractor from providing it. cl. 11.2(21) was cited in the expert reference set, but the supplied analysis attached no separate operative consequence to it for this issue.

Under Option A, the Prices are the lump-sum prices for activities on the Activity Schedule under cl. 11.2(32), and the Price for Work Done to Date is based strictly on completed activities under cl. 11.2(29). If fencing is omitted, there is no separate Price allocated to it; omitted activities do not attract a direct payment right and are deemed covered by other activity Prices. The Contractor must correct the Activity Schedule so activities relate to the Scope under cl. 55.1 and cl. 55.3, but the Project Manager rejects a revision if the “total of the Prices is changed” under cl. 55.4.

Under Option C, the answer differs fundamentally. The Activity Schedule establishes the target cost, being the total of the Prices, but is not used to calculate interim payments. The Contractor is paid PWDD as forecast/actual Defined Cost plus the Fee under cl. 11.2(31). The Defined Cost of erecting fencing is reimbursed under cl. 11.2(24) because the fencing is required to Provide the Works, and it is not Disallowed Cost under cl. 11.2(26) merely because it was missing from the Activity Schedule. However, cl. 55.4 prevents increasing the total Prices for the Contractor’s omission, so the Contractor receives cost reimbursement but likely suffers reduced gain share or increased pain share when the Project Manager assesses the Contractor’s share at Completion under cl. 54.1.

Programme correction is mandatory. A programme must show the order and timing of operations planned to Provide the Works under cl. 31.2. Omission of fencing means the programme may not comply with Scope or realistically show plans, giving grounds for non-acceptance under cl. 31.3. The Contractor submits a revised programme under cl. 32.1 and cl. 32.2, and the Project Manager replies within the period for reply under cl. 13.4.

</details>

<details>
<summary><b>4. Behavioural Implications</b> — Retrospective valuation shifts to live control.</summary>

Under GCC, the Contractor’s behavioural incentive is defensive completeness at tender and careful classification afterwards. The Contractor must provide and maintain fencing throughout the Works under Clause 10 and Clause 20(1), even if it failed to programme or price it. The Engineer may require written particulars or a revised programme under Clause 16(1), but approval of that programme does not protect the Contractor because Clause 16(2) preserves all duties. Commercial effort is therefore focused on showing whether the omission is a genuine BQ omission under Clause 59(3) or merely temporary protection included in rates under Clause 14 and Clause 59(1).

Under NEC, the omission must be actively cleaned up in live management documents. The Project Manager notifies non-acceptance of a programme that does not comply with the Scope or does not realistically show the Contractor’s plans under cl. 31.3. The Contractor corrects the Activity Schedule under cl. 55.3 without changing the total of the Prices under cl. 55.4, and submits a revised programme under cl. 32.1 and cl. 32.2 showing fencing operations, resources and impact on planned Completion.

Option C changes cash and risk behaviour. The Contractor must substantiate actual/forecast Defined Cost and Fee under cl. 11.2(31), showing that fencing cost is Defined Cost under cl. 11.2(24) and not Disallowed Cost under cl. 11.2(26). The Project Manager assesses the amount due under cl. 50.1 and later the Contractor’s share under cl. 54.1, so the omission becomes a target/share risk rather than a bar to interim reimbursement.

**Implementation comparison (GCC vs NEC4):**

| Aspect | GCC | NEC4 |
|---|---|---|
| Governing document | BQ/Schedule of Rates governs payment (Clause 59(1)). | Scope governs obligation, not Activity Schedule (cl. 20.1; 55.1). |
| Work obligation | Temporary Works and safety remain required (Clause 10; 20(1)). | Provide Works in accordance with Scope (cl. 20.1). |
| Programme omission | Approval gives no duty relief (Clause 16(2)). | PM may reject unrealistic/non-Scope programme (cl. 31.3). |
| Commercial correction | Engineer corrects genuine BQ omission (Clause 59(3)). | Revise Activity Schedule without total uplift (cl. 55.3; 55.4). |
| Option C payment | No Option C/Defined Cost machinery in corpus. | Paid Defined Cost plus Fee (cl. 11.2(31)). |
| Final risk | Temporary fencing generally within rates (Clause 14). | Unadjusted target affects share at Completion (cl. 54.1). |


</details>

<details>
<summary><b>5. GCC Lessons for NEC Adoption</b> — GCC routines become NEC management tools.</summary>

HK practitioners familiar with GCC Clause 10 and Clause 20(1) already know that temporary protection and site safety measures must be provided even when not separately priced or programmed. That habit transfers directly to NEC cl. 20.1: if security fencing is required by the Scope, it must be provided. The adjustment is purpose and timing: under NEC the omission should be treated immediately as a Scope/programme/Activity Schedule inconsistency to be corrected, not as a later debate about whether the duty exists.

The GCC Clause 16(1) workflow, where the Engineer may require written particulars or a revised programme, maps to NEC cl. 31.2, cl. 31.3, cl. 32.1 and cl. 32.2. The familiar skill is programme explanation; the NEC adjustment is that the Contractor must produce a realistic programme showing the fencing operations, resources and any effect on planned Completion, while the Project Manager has express grounds to withhold acceptance if the programme does not comply with Scope or represent plans realistically.

GCC Clause 59(3) experience with omitted BQ items helps practitioners understand document correction, but NEC changes the commercial consequence. Under NEC cl. 55.3 the Activity Schedule must be corrected so activities relate to the Scope, yet cl. 55.4 prevents changing the total of the Prices for the Contractor’s omission. Under Option C, the practitioner’s effort shifts from seeking an activity-price uplift to substantiating Defined Cost under cl. 11.2(24), showing the cost is not Disallowed Cost under cl. 11.2(26), obtaining assessment under cl. 50.1 and cl. 11.2(31), and managing the final share effect under cl. 54.1.

In practical terms, GCC claim, record, variation and delay-analysis habits are not discarded; under NEC they are used earlier to correct management documents, evidence Defined Cost, protect programme integrity and manage target/share exposure.

| GCC practice / experience | → How it transfers to NEC implementation |
|---|---|
| Clause 10/20(1) safety Temporary Works duty. | cl. 20.1: provide Scope fencing immediately; do not await pricing correction. |
| Clause 16(1) revised programme particulars. | cl. 31.2/32.1/32.2: show fencing sequence, resources and planned Completion impact. |
| Clause 16(2) no relief from approved programme. | cl. 31.3: expect non-acceptance if programme omits Scope operations. |
| Clause 59(3) BQ omission correction. | cl. 55.3/55.4: correct Activity Schedule, but keep total Prices unchanged. |
| GCC site/cost records for safety measures. | Option C cl. 11.2(24)/(26)/(31): evidence Defined Cost, avoid Disallowed Cost. |

</details>

<details>
<summary><b>6. HK-Specific Notes</b> — PAH, SMM and DEVB guide the HK handling.</summary>

For GCC, the Project Administration Handbook (PAH) Chapter 9, Section II.04 expressly maps terminology to avoid confusing GCC with NEC target-contract language. It confirms that GCC contracts use “Bills of Quantities / Schedule of Rates” for measurement and payment rather than an “Activity Schedule”, and “Contract Sum” rather than “Prices”. It also frames GCC administration through “Extension of time, variations, claims” rather than “Compensation events”. The GCC expert response also states that the corpus is silent on Option C target contracts, Defined Cost, Fee, target adjustment, Disallowed Cost and pain/gain share mechanisms.

For GCC temporary site safety measures, the Standard Method of Measurement (SMM) for Civil Engineering Works in the corpus states that unit rates in the BQ are comprehensively inclusive. The SMM requires unit rates to include “(ix) temporary protection and its subsequent removal”, “(x) Temporary Works”, and “(xxi) liabilities, obligations and risks involved in the execution of the Works set forth or reasonably implied in the Contract”. On that basis, temporary site security fencing is contractually treated as covered by existing BQ rates even if the Contractor did not separately itemise or price it, unless the case is a genuine omitted specific item addressed by Clause 59(3).

For NEC4 in Hong Kong, DEVB Practice Note Section A6.3.4.3 aligns with the Activity Schedule correction mechanism. It confirms that if the Activity Schedule does not relate to the operations on the Accepted Programme or the Scope, it must be revised under cl. 55.3. For Option A, interim payment follows the newly adjusted Activity Schedule once accepted. For Option C, the Activity Schedule is used only for tracking the target cost and assessing changed Prices for compensation events, not for calculating interim payment.

For Option C cash flow in the NEC4 Hong Kong Edition, the HK Edition amends the PWDD definition at cl. 11.2(34). The assessment is based on the actual payment made by the Contractor at the assessment date, plus an estimated amount for cost components to be paid up to one week after the next assessment date. The Contractor is therefore paid for the fencing through this mechanism, subject to risk-based payment checking by the Project Manager to ensure the costs are not Disallowed Cost. This HK-specific amendment is central to the answer to the Option C question: omission from the Activity Schedule does not create a target uplift, but it also does not by itself prevent reimbursement of properly evidenced Defined Cost.

</details>

## Clause Map (extracted by CM-A)

Structured index of every clause cited by the expert agents, with its taxonomy category and a verbatim quote / paraphrase.

- **GCC · Clause 10** — _uncategorised_ · obligation: **duty** · party: **Contractor**
  > Under Clause 10, the Contractor is obligated to execute the Works and provide all "Temporary Works... and everything whether of a temporary or permanent nature required in and for such execution".
- **GCC · Clause 14** — _physical_conditions_ · obligation: **condition** · party: **Contractor** · timeline: **before submitting his Tender**
  > Under Clause 14, the Contractor is "deemed to have satisfied himself before submitting his Tender as to the correctness and sufficiency of his Tender for the Works and of the rates stated in the priced Bills of Quantities".
- **GCC · Clause 16(1)** — _programme_obligations_ · obligation: **right** · party: **Engineer** · condition: **whenever required for contract management**
  > Engineer may instruct the Contractor to furnish particulars in writing or submit a revised programme showing the sequence and methods for installing the fencing, whenever required for contract management (Clause 16(1)).
- **GCC · Clause 16(2)** — _programme_obligations_ · obligation: **condition** · party: **Contractor** · condition: **submission to or approval by the Engineer of the programme**
  > Clause 16(2) expressly states that the submission to or approval by the Engineer of the programme "shall not relieve the Contractor of any duty or responsibility under the Contract."
- **GCC · Clause 20(1)** — _early_warning_risk_ · obligation: **duty** · party: **Contractor** · timeline: **throughout the progress of the Works**
  > Clause 20(1) dictates that the Contractor shall "throughout the progress of the Works take full responsibility for the adequate stability and safety of all operations on the Site".
- **GCC · Clause 59(1)** — _payment_mechanism_ · obligation: **process** · party: **n/a**
  > Under the GCC, financial valuation is strictly governed by the "Bills of Quantities" (BQ) or "Schedule of Rates" (Clause 59(1)), and time or cost effects are administered via variations, claims, and extensions of time.
- **GCC · Clause 59(3)** — _payment_mechanism_ · obligation: **process** · party: **Engineer** · condition: **Any error in description in the Bills of Quantities or item omitted therefrom**
  > Clause 59(3) applies: "Any error in description in the Bills of Quantities or item omitted therefrom shall not vitiate the Contract nor release the Contractor from the execution of the whole or any part of the Works... The Engineer shall correct any such error or omission, shall ascertain the value of the work actually carried out".
- **NEC4 · cl. 10.2** — _mutual_trust_ · obligation: **duty** · party: **both**
  > upholding the spirit of mutual trust and co-operation (cl. 10.2) by requiring prompt correction of discrepancies.
- **NEC4 · cl. 11.2(21)** — _uncategorised_ · obligation: **definition** · party: **n/a**
  > [CLAUSE REFERENCES] cl. 10.2, cl. 11.2(21), cl. 11.2(24), cl. 11.2(26), cl. 11.2(29), cl. 11.2(31), cl. 11.2(32), cl. 13.4, cl. 20.1, cl. 31.2, cl. 31.3, cl. 32.1, cl. 50.1, cl. 54.1, cl. 55.1, cl. 55.3, cl. 55.4
- **NEC4 · cl. 11.2(24)** — _uncategorised_ · obligation: **remedy** · party: **Contractor** · condition: **because it is required to Provide the Works**
  > The Contractor is reimbursed the Defined Cost (cl. 11.2(24)) of erecting the fencing because it is required to Provide the Works.
- **NEC4 · cl. 11.2(26)** — _uncategorised_ · obligation: **condition** · party: **Contractor** · condition: **simply because it was missing from the Activity Schedule**
  > The cost of the fencing is not a Disallowed Cost (cl. 11.2(26)) simply because it was missing from the Activity Schedule.
- **NEC4 · cl. 11.2(29)** — _uncategorised_ · obligation: **definition** · party: **n/a** · condition: **completed activities**
  > The Price for Work Done to Date (PWDD) is based strictly on completed activities (cl. 11.2(29)).
- **NEC4 · cl. 11.2(31)** — _uncategorised_ · obligation: **remedy** · party: **Contractor** · condition: **Under Option C**
  > the Contractor is paid the PWDD, which is the forecast/actual Defined Cost plus the Fee (cl. 11.2(31)).
- **NEC4 · cl. 11.2(32)** — _uncategorised_ · obligation: **definition** · party: **n/a** · condition: **Under Option A**
  > Under Option A, the Prices are the lump sum prices for the activities on the Activity Schedule (cl. 11.2(32)).
- **NEC4 · cl. 13.4** — _mutual_trust_ · obligation: **process** · party: **PM** · timeline: **within the period for reply** · condition: **provided the total Prices haven't changed and the distribution is reasonable**
  > Project Manager replies within the period for reply, accepting the revised Activity Schedule (provided the total Prices haven't changed and the distribution is reasonable) and the revised programme (cl. 13.4, cl. 31.3, cl. 55.4).
- **NEC4 · cl. 20.1** — _quality_management_ · obligation: **duty** · party: **Contractor**
  > The Contractor's primary obligation is to "Provide the Works in accordance with the Scope" (cl. 20.1).
- **NEC4 · cl. 31.2** — _programme_obligations_ · obligation: **duty** · party: **Contractor**
  > A programme must show the order and timing of the operations which the Contractor plans to do to Provide the Works (cl. 31.2).
- **NEC4 · cl. 31.3** — _programme_obligations_ · obligation: **process** · party: **PM** · condition: **the submitted programme is not accepted because it does not comply with the Scope or represent plans realistically**
  > Project Manager notifies the Contractor that the submitted programme is not accepted because it does not comply with the Scope or represent plans realistically (cl. 31.3).
- **NEC4 · cl. 32.1** — _programme_obligations_ · obligation: **duty** · party: **Contractor**
  > The Contractor is obligated to submit a revised programme showing the actual progress and corrected operations (cl. 32.1).
- **NEC4 · cl. 50.1** — _payment_mechanism_ · obligation: **process** · party: **PM**
  > Project Manager assesses the amount due (cl. 50.1).
- **NEC4 · cl. 54.1** — _uncategorised_ · obligation: **process** · party: **PM** · timeline: **at Completion** · condition: **under Option C**
  > Project Manager (under Option C) assesses the Contractor's share at Completion by comparing the final PWDD (which includes the fencing costs) against the final total of the Prices (which remains unadjusted for the omission) (cl. 54.1).
- **NEC4 · cl. 55.1** — _uncategorised_ · obligation: **definition** · party: **n/a**
  > The contract explicitly states that "Information in the Activity Schedule is not Scope or Site Information" (cl. 55.1).
- **NEC4 · cl. 55.3** — _uncategorised_ · obligation: **duty** · party: **Contractor** · condition: **so that the activities relate to the Scope**
  > The Contractor must correct the Activity Schedule so that the activities relate to the Scope (cl. 55.1, cl. 55.3).
- **NEC4 · cl. 55.4** — _uncategorised_ · obligation: **duty** · party: **PM** · condition: **if the "total of the Prices is changed"**
  > However, the Project Manager will reject any revision if the "total of the Prices is changed" (cl. 55.4).
- **NEC4 · cl. 32.2** — _programme_obligations_ · obligation: **process** · party: **Contractor**
  > Contractor submits a revised programme incorporating the fencing operations, its resources, and any impact on planned Completion to the Project Manager for acceptance (cl. 32.1, cl. 32.2).
- **NEC4 · cl. 11.2(34)** — _uncategorised_ · obligation: **definition** · party: **n/a** · timeline: **at the assessment date** · condition: **in the HK Edition**
  > the HK Edition amends the PWDD definition (cl. 11.2(34) in the HK Edition). The assessment is based on the actual payment made by the Contractor at the assessment date, plus

## Raw Expert Evidence (NotebookLM responses)

The full unmodified responses from the GCC and NEC4 expert agents are reproduced below for traceability.

<details>
<summary>GCC expert response (1 iteration(s), 5,067 chars)</summary>

[CLAUSE REFERENCES] Clause 10, Clause 14, Clause 16(1), Clause 16(2), Clause 20(1), Clause 59(1), Clause 59(3).
[GCC POSITION] Absence of Target Contract Terminology The corpus is explicitly silent on the concepts of an "Option C target contract", "Activity Schedule", "Prices", "Defined Cost", "Fee", "target adjustment", "disallowed cost", "pain/gain share", and "compensation events". Under the GCC, financial valuation is strictly governed by the "Bills of Quantities" (BQ) or "Schedule of Rates" (Clause 59(1)), and time or cost effects are administered via variations, claims, and extensions of time.
Obligation to Provide Fencing Under Clause 10, the Contractor is obligated to execute the Works and provide all "Temporary Works... and everything whether of a temporary or permanent nature required in and for such execution". Furthermore, Clause 20(1) dictates that the Contractor shall "throughout the progress of the Works take full responsibility for the adequate stability and safety of all operations on the Site". Therefore, the Contractor is strictly obliged to provide the required security fencing, regardless of its omission from their planning or pricing documents.
Effect of Omission from the Accepted Programme The omission of the fencing from the accepted programme does not waive the Contractor's obligation, nor does it automatically affect planned Completion or key dates. Clause 16(2) expressly states that the submission to or approval by the Engineer of the programme "shall not relieve the Contractor of any duty or responsibility under the Contract."
Omission from Pricing Documents (Bills of Quantities) and Entitlement Because the GCC does not use an Activity Schedule, payment entitlement is assessed against the BQ. Under Clause 14, the Contractor is "deemed to have satisfied himself before submitting his Tender as to the correctness and sufficiency of his Tender for the Works and of the rates stated in the priced Bills of Quantities". These rates contractually cover all his risks, liabilities, and implied obligations. If the fencing was a specific permanent works item omitted from the BQ but required by the Specification, Clause 59(3) applies: "Any error in description in the Bills of Quantities or item omitted therefrom shall not vitiate the Contract nor release the Contractor from the execution of the whole or any part of the Works... The Engineer shall correct any such error or omission, shall ascertain the value of the work actually carried out". However, if the fencing is a standard temporary safety measure, it is generally deemed included in the Contractor's existing rates.
[PROCEDURAL IMPLICATION]
Contractor provides and maintains all necessary Temporary Works, including security fencing, throughout the progress of the Works to ensure site safety (Clause 10, Clause 20(1)).
Engineer may instruct the Contractor to furnish particulars in writing or submit a revised programme showing the sequence and methods for installing the fencing, whenever required for contract management (Clause 16(1)).
Engineer reviews the Contract to determine if the fencing was a specifically itemized omitted item or a general temporary work deemed covered by the Tender (Clause 14, Clause 59(3)).
If it is a genuine BQ omission of a specific item, Engineer corrects the omission and ascertains the value of the work actually carried out (Clause 59(3)).
If the fencing is deemed a temporary work included in the Contract rates, Contractor bears the cost without additional payment, as prior approval of a programme lacking the fencing provides no relief from contractual duties (Clause 14, Clause 16(2)).
[HK CONTEXT] The Project Administration Handbook (PAH) Chapter 9, Section II.04 explicitly maps contract terminologies to prevent confusion. It affirms that GCC contracts utilize "Bills of Quantities / Schedule of Rates" for measurement and payment rather than an "Activity Schedule", and use "Contract Sum" rather than "Prices". It also uses "Extension of time, variations, claims" rather than "Compensation events".
Regarding payment for temporary site safety measures, the Standard Method of Measurement (SMM) for Civil Engineering Works detailed in the corpus stipulates that unit rates in the BQ are comprehensively inclusive. The SMM mandates that the unit rates shall include "(ix) temporary protection and its subsequent removal", "(x) Temporary Works", and "(xxi) liabilities, obligations and risks involved in the execution of the Works set forth or reasonably implied in the Contract". Therefore, the cost of temporary site security fencing is contractually deemed to be fully covered by the existing BQ rates, even if the Contractor failed to separately itemise or price it.
The corpus is silent on Option C target contracts, Defined Cost, Fee, target adjustment, disallowed cost, and pain/gain share mechanisms.
What is the procedure if a Bill of Quantities item is missing?
How are variations valued when contract rates are not applicable?
What are the rules for measuring irregular volumes using end areas?

</details>

<details>
<summary>NEC4 expert response (1 iteration(s), 6,439 chars)</summary>

[CLAUSE REFERENCES] cl. 10.2, cl. 11.2(21), cl. 11.2(24), cl. 11.2(26), cl. 11.2(29), cl. 11.2(31), cl. 11.2(32), cl. 13.4, cl. 20.1, cl. 31.2, cl. 31.3, cl. 32.1, cl. 50.1, cl. 54.1, cl. 55.1, cl. 55.3, cl. 55.4
[NEC POSITION] The NEC4 ECC manages omissions through strict separation of the Scope (the technical requirements) and the Activity Schedule/Programme (the commercial and management tools), upholding the spirit of mutual trust and co-operation (cl. 10.2) by requiring prompt correction of discrepancies.
Obligation to Provide the Fencing: The Contractor's primary obligation is to "Provide the Works in accordance with the Scope" (cl. 20.1). The contract explicitly states that "Information in the Activity Schedule is not Scope or Site Information" (cl. 55.1). Therefore, the omission of the security fencing from the Activity Schedule and the programme does not relieve the Contractor of the obligation to provide it.
Consequences under Option A (Priced Contract with Activity Schedule): Under Option A, the Prices are the lump sum prices for the activities on the Activity Schedule (cl. 11.2(32)). The Price for Work Done to Date (PWDD) is based strictly on completed activities (cl. 11.2(29)). Because the fencing was omitted, there is no "Price" allocated to it. Omitted activities never attract a direct right to payment and are deemed to be covered by the Prices for the other listed activities
. The Contractor must correct the Activity Schedule so that the activities relate to the Scope (cl. 55.1, cl. 55.3). However, the Project Manager will reject any revision if the "total of the Prices is changed" (cl. 55.4). Thus, the Contractor must absorb the cost of the fencing by redistributing the existing total of the Prices among the uncompleted activities; the Contractor is not entitled to an increase in the Prices for their own pricing omission.
Consequences under Option C (Target Contract with Activity Schedule): Under Option C, the financial impact differs fundamentally. The Activity Schedule establishes the target cost (the total of the Prices) but is not used to calculate interim payments. Instead, the Contractor is paid the PWDD, which is the forecast/actual Defined Cost plus the Fee (cl. 11.2(31)).
Defined Cost: The Contractor is reimbursed the Defined Cost (cl. 11.2(24)) of erecting the fencing because it is required to Provide the Works.
Disallowed Cost: The cost of the fencing is not a Disallowed Cost (cl. 11.2(26)) simply because it was missing from the Activity Schedule.
Target Adjustment & Pain/Gain Share: The total of the Prices (the target) cannot be adjusted upwards for the Contractor's error (cl. 55.4). Consequently, the Contractor will be reimbursed the actual cost of the fencing, but because the target cost does not include an allowance for it, the Contractor will likely suffer a reduced gain share or an increased pain share during the Project Manager's assessment of the Contractor's share at Completion (cl. 54.1).
Consequences for the Programme: A programme must show the order and timing of the operations which the Contractor plans to do to Provide the Works (cl. 31.2). Omitting the fencing means the programme does not comply with the Scope and does not represent the Contractor's plans realistically. The Project Manager has express grounds to not accept the programme (cl. 31.3). Furthermore, missing operations distort the baseline for assessing compensation events, as the Accepted Programme must reliably show planned Completion and Key Dates. The Contractor is obligated to submit a revised programme showing the actual progress and corrected operations (cl. 32.1).
[PROCEDURAL IMPLICATION]
Contractor provides the security fencing as required by the Scope, despite its omission from the commercial and programming documents (cl. 20.1).
Project Manager notifies the Contractor that the submitted programme is not accepted because it does not comply with the Scope or represent plans realistically (cl. 31.3).
Contractor corrects the Activity Schedule so that the activities relate to the Scope, redistributing the existing total of the Prices without changing the total amount, and submits it to the Project Manager for acceptance (cl. 55.1, cl. 55.3).
Contractor submits a revised programme incorporating the fencing operations, its resources, and any impact on planned Completion to the Project Manager for acceptance (cl. 32.1, cl. 32.2).
Project Manager replies within the period for reply, accepting the revised Activity Schedule (provided the total Prices haven't changed and the distribution is reasonable) and the revised programme (cl. 13.4, cl. 31.3, cl. 55.4).
Project Manager assesses the amount due (cl. 50.1). Under Option A, payment is made against completed activities on the newly accepted Activity Schedule (cl. 11.2(29)). Under Option C, payment is made for the actual/forecast Defined Cost of the fencing (cl. 11.2(31)).
Project Manager (under Option C) assesses the Contractor's share at Completion by comparing the final PWDD (which includes the fencing costs) against the final total of the Prices (which remains unadjusted for the omission) (cl. 54.1).
[HK CONTEXT] The DEVB Practice Notes provide practical alignment for these mechanisms in Hong Kong:
Activity Schedule Revisions: DEVB PN Section A6.3.4.3 confirms that if the Activity Schedule does not relate to the operations on the Accepted Programme (or the Scope), it must be revised under cl. 55.3. For Option A, interim payment will strictly follow the newly adjusted Activity Schedule once accepted. For Option C, the Activity Schedule is only used for tracking the target cost and assessing changed Prices for compensation events.
Target Contract Cash Flow (Option C): To prevent Contractors from suffering negative cash flow when incurring costs for omitted items, the HK Edition amends the PWDD definition (cl. 11.2(34) in the HK Edition). The assessment is based on the actual payment made by the Contractor at the assessment date, plus an estimated amount for cost components to be paid up to one week after the next assessment date. The Contractor will be paid for the fencing under this mechanism, subject to risk-based payment checking by the Project Manager to ensure the costs are not Disallowed Cost.
How is a compensation event assessed under Option A?
What happens if an activity is omitted from the schedule?
How do Activity Schedules differ between Option A and C?

</details>

## SYN-A Chain-of-Thought Reasoning

<details>
<summary>Three-level reasoning trace (L1 → L2 → L3)</summary>

[L1 — Spirit/Philosophy] GCC treats incomplete pricing or programming documents through an Engineer-led, risk-allocation model: the Contractor must execute the Works and necessary Temporary Works, with omissions resolved through BQ correction or absorbed within tendered rates. In Transaction Cost Economics terms, GCC relies more on ex ante risk pricing, certification, and later valuation. NEC4 separates Scope from Activity Schedule/programme and uses relational governance under cl. 10.2: discrepancies are surfaced, corrected, and commercially managed through defined processes rather than treated as waivers of required work.

[L2 — Clause-level Comparison] On the GCC side, Clause 10 and Clause 20(1) keep the fencing obligation alive; Clause 16(2) prevents an approved programme from relieving contractual responsibility; Clause 14 places tender sufficiency risk on the Contractor; Clause 59(1) locates payment in the BQ/Schedule of Rates; and Clause 59(3) allows the Engineer to correct a genuine BQ omission and ascertain the value of work actually carried out. On the NEC4 side, cl. 20.1 and cl. 55.1 make clear that required Scope work remains required even if omitted from the Activity Schedule or programme; cl. 31.2, cl. 31.3, cl. 32.1 and cl. 32.2 require programme correction; cl. 55.3 and cl. 55.4 require Activity Schedule correction without changing the total of the Prices; cl. 50.1 governs assessment; and under Option C cl. 11.2(24), cl. 11.2(26), cl. 11.2(31), cl. 11.2(34) in the HK Edition, and cl. 54.1 mean the Contractor is paid Defined Cost plus Fee for fencing, but the target remains unadjusted and the pain/gain outcome absorbs the omission.

[L3 — Practice/Behavioural Implications + GCC-to-NEC Transfer] GCC practitioners should recognise continuity in the basic duty: Clause 10 and Clause 20(1) habits of providing temporary protection and site safety transfer directly to NEC cl. 20.1, but the behavioural adjustment is to treat the omission as a live management discrepancy, not merely a later claim/payment issue. The familiar GCC Clause 16(1) workflow—Engineer requiring particulars or a revised programme—transfers to NEC cl. 31.2, cl. 31.3, cl. 32.1 and cl. 32.2, but timing and purpose shift from Engineer control to prompt correction of the Accepted Programme baseline. GCC Clause 59(3) experience with missing BQ items transfers only partly: under NEC cl. 55.3 and cl. 55.4 the Activity Schedule is corrected to relate to Scope, but the total Prices are not increased for the Contractor’s omission; under Option C the practical focus moves to substantiating Defined Cost, avoiding Disallowed Cost under cl. 11.2(26), securing interim payment under cl. 50.1 and cl. 11.2(31)/HK cl. 11.2(34), and accepting that cl. 54.1 will reflect the unadjusted target in the final share calculation.

</details>

---

### Query Plan (QP-A)
- **L1 (spirit):**     How does the contract’s governance philosophy allocate responsibility for delivering required security fencing where pricing and programming documents are incomplete?
- **L2 (clauses):**    Which clauses determine whether security fencing omitted from the Activity Schedule and programme remains required work, affects the Prices or Defined Cost, or gives rise to a change, compensation event, payment adjustment, or programme revision, especially under Option C?
- **L3 (practice):**   In practice, how should the contractor and project manager administer the omission, including notification, programme correction, quotation or assessment, cost substantiation, and the effect on interim payment and final commercial risk?
- **canonical_topic:** `payment_mechanism`

### Anchor Clauses (scenario ground-truth, used for CR)
- **GCC anchors:**  (none)
- **NEC4 anchors:** cl. 55.1, cl. 55.3

*Generated by MAS v2.2 — LangGraph orchestrator (6 agents + 3 rule modules).*