# Scenario B: Instructed Design Change Mid-Construction

**Generated:** 2026-07-07 15:51

## Context
During construction of a pumping station, the government client instructs the Engineer/PM to add a 500 m³ retention tank. The contractor seeks assessment of additional cost and extension of time.

## MAS Query Topic
> Engineer/PM instructs a scope change mid-construction: addition of a 500 m³ retention tank not in the original design. Compare how each contract treats variation valuation, time impact assessment, and the decision authority for the change.

Specific questions to address:
Variation valuation, time impact, and decision authority for the design change.

## Validation Results

### Overall — ✅ PASSED  (confidence: 0.95, iterations used: 1)

> Accepted under relaxed rule: 1 per-metric below threshold (within tolerance of 1); composite confidence 0.95 ≥ 0.8.

### Rule-based Validation (deterministic)

**Track verdict:** ❌ fail

| Metric | Value | Threshold | Status |
|---|---|---|---|
| Citation Accuracy Rate (GCC) | 1.00 | ≥ 0.85 | ✅ pass |
| Citation Accuracy Rate (NEC4) | 1.00 | ≥ 0.85 | ✅ pass |
| Coverage Rate (GCC) | 1.00 | ≥ 0.85 | ✅ pass |
| Coverage Rate (NEC4) | 0.80 | ≥ 0.85 | ❌ fail |
| Composite Confidence | 0.95 | ≥ 0.70 | ✅ pass |
| Clause format | 0 violation(s) | All match regex | ✅ pass |

**GCC anchor coverage:**
 ✅ Clause 60 ✅ Clause 61 ✅ Clause 50(1) ✅ Clause 64

**NEC4 anchor coverage:**
 ✅ cl. 60.1(1) ✅ cl. 61.1 ✅ cl. 63.1 ✅ cl. 63.5
 ❌ cl. 62.1

### LLM-based Semantic Validation

**Track verdict:** ✅ pass
**Severity:** minor

_No substantive issues raised._

## Comparative Synthesis

> **Executive summary** — Both contracts permit the instructed retention tank, but GCC values and extends time through Engineer-led retrospective variation/EOT machinery, while NEC treats it as a prospective compensation event. Practice shifts from defensive claim preservation to early quotation, programme forecasting, and PM-led implementation.

<details>
<summary><b>1. Spirit / Philosophy</b> — Engineer control vs relational process.</summary>

GCC: The GCC corpus does not use the terms “Scope” or “Works Information”; technical requirements are governed by the “Specification” and “Drawings”. A mid-construction addition is governed by an Engineer-led command-and-valuation model: the Engineer instructs, the Contractor complies, the Engineer values and assesses time, and disputes first return to the Engineer. In Transaction Cost Economics terms, it is closer to hierarchical/adversarial governance, using written instructions, notices, particulars, and binding interim decisions to manage opportunism.

NEC: NEC4 ECC manages the same change through a prospective compensation event process under a duty to act “in a spirit of mutual trust and co-operation” (cl. 10.2). The PM still has authority, but the commercial effect is surfaced through quotation, Defined Cost forecasting, Accepted Programme delay analysis, reply, assessment, and implementation. In TCE terms, it shifts toward relational governance by reducing uncertainty through early information exchange and collaborative risk pricing.

</details>

<details>
<summary><b>2. GCC Position (Implementation)</b> — Written variation, retrospective valuation.</summary>

**Implementation flow:**

1. Engineer issues written variation order adding the 500 m³ tank (Clause 60(1)(a), Clause 60(2)) →
2. Contractor complies and proceeds with due diligence despite dispute (Clause 15, Clause 86(1)) →
3. Contractor gives delay notice as soon as practicable and within 28 days (Clause 50(1)(a)) →
4. Contractor submits full and detailed delay particulars if required (Clause 50(3)) →
5. Engineer determines EOT on known circumstances and values the variation (Clause 50(2), Clause 61(1)) →
6. If no agreement, Engineer fixes rate; Contractor gives higher-rate claim notice within 28 days if dissatisfied (Clause 61(2), Clause 64(1)).

Under Clause 60(1)(a), the Engineer may order any variation necessary for completion of the Works or desirable to achieve satisfactory functioning, including “additions, omissions, substitutions, alterations, changes in quality, form, character, kind, position, dimension, level or line”. The additional 500 m³ retention tank is therefore a valid addition. Clause 60(2) provides that “No variation shall be made by the Contractor without an order in writing by the Engineer”, so authority depends on a written Engineer’s order. Clause 15 requires the Contractor to execute the Works to the Engineer’s satisfaction and comply with the Engineer’s instructions. Clause 86(1) reinforces continuity: even where the instruction is disputed, the Contractor “shall in every case continue to proceed with the Works with all due diligence”.

Valuation is retrospective by the Engineer under Clause 61(1). For same or similar work executed under similar conditions, the Contract rate applies under Clause 61(1)(b). For work not same or similar, Clause 61(1)(c) uses a rate based on Contract rates “so far as may be reasonable”. Failing agreement on that basis, Clause 61(1)(c) contemplates a rate “to be agreed between the Engineer and the Contractor”. If agreement fails, Clause 61(2) gives the Engineer unilateral power to “fix such rate as shall in his opinion be reasonable and notify the Contractor accordingly”. If the Contractor disputes that fixed rate, Clause 64(1) requires written notice of intention to claim a higher rate within 28 days.

Time impact is addressed through Clause 50. A variation ordered under Clause 60 is an EOT ground under Clause 50(1)(b)(iv). Clause 50(1)(a) requires the Contractor to give written notice of the cause and probable extent of delay “as soon as practicable but in any event within 28 days” of the delay arising, or as soon as the Contractor can reasonably foresee that the instruction is likely to cause delay. Under Clause 50(3), the Engineer may require “full and detailed particulars of the cause and extent of the delay”. Under Clause 50(2), the Engineer determines the EOT by taking into account “all the circumstances known to him at that time”. Any unresolved dispute about the instruction, valuation, decision, or EOT is referred to and settled by the Engineer, who states his decision in writing under Clause 86(1); that decision is final and binding unless and until revised in mediation or arbitration.

</details>

<details>
<summary><b>3. NEC4 Position (Implementation)</b> — Scope change as compensation event.</summary>

**Implementation flow:**

1. PM instructs Scope change adding the 500 m³ tank (cl. 14.3) →
2. Contractor obeys the valid PM/Supervisor instruction (cl. 27.3) →
3. PM notifies compensation event and instructs quotation at the time of the instruction (cl. 60.1(1), cl. 61.1) →
4. Contractor submits quotation within three weeks; PM replies within two weeks of submission (cl. 62.2, cl. 62.3) →
5. Prices and delay are assessed using Defined Cost/Fee and Accepted Programme logic (cl. 63.1, cl. 63.2, cl. 63.5) →
6. PM assesses if needed, notifies assessment within the period allowed, and implements changes to Prices and Completion Date (cl. 64.1, cl. 64.3, cl. 66.1, cl. 66.2).

NEC4 ECC treats the retention tank as a Scope change and compensation event within a prospective management process. Under cl. 10.2, the parties act “in a spirit of mutual trust and co-operation”. The PM has express authority to instruct the Contractor in a way that changes the Scope under cl. 14.3. The Contractor has no option to refuse a compliant instruction: under cl. 27.3, the Contractor must obey an instruction which is in accordance with the contract and given by the Project Manager or the Supervisor.

An instruction changing the Scope, including the additional retention tank, is a compensation event under cl. 60.1(1). When issuing that instruction, the PM notifies the Contractor of the compensation event at the time of that communication and instructs the Contractor to submit quotations under cl. 61.1. The Contractor’s quotation comprises proposed changes to the Prices, any delay to the Completion Date and Key Dates, details of the assessment, and alterations to the Accepted Programme under cl. 62.2. The procedural implication stated for this scenario is that the Contractor submits the quotation within three weeks of being instructed, detailing forecast Defined Cost plus Fee, delay to planned Completion against the current Accepted Programme, and programme alterations (cl. 62.2, cl. 62.3). The PM replies to the quotation within two weeks of submission under cl. 62.3.

Valuation is prospective. Under cl. 63.1, the change to Prices is assessed as the effect of the compensation event on actual Defined Cost of work already done by the dividing date, forecast Defined Cost of work not yet done by the dividing date, and the resulting Fee. If PM and Contractor agree, rates or lump sums may instead be used under cl. 63.2. Time impact is assessed under cl. 63.5 as the length of time that, due to the compensation event, planned Completion is later than planned Completion shown on the Accepted Programme current at the dividing date.

If the PM decides the Contractor has not assessed the compensation event correctly, or the Contractor fails to submit within the time allowed, the PM makes their own assessment under cl. 64.1. The PM notifies the assessment under cl. 64.3, within the period allowed for the Contractor’s submission, which implements the compensation event under cl. 66.1 and changes the Prices and Completion Date under cl. 66.2. If dissatisfied, the Contractor may refer the dispute under Option W4, including cl. W4.1, cl. W4.2, cl. W4.3, cl. W4.4, and cl. W4.5.

</details>

<details>
<summary><b>4. Behavioural Implications</b> — Claims records become live forecasts.</summary>

GCC makes the Contractor’s immediate priorities compliance, notice, particulars, and record protection. The Engineer’s written order is the gatekeeper for the 500 m³ tank; the Contractor must not vary without it, must proceed even if disputed, and must protect time entitlement by notifying delay “as soon as practicable but in any event within 28 days”. The Contractor’s evidence is therefore directed to substantiating a later Engineer-led valuation and EOT: comparable rates, reasons why work is dissimilar, site records, delay cause, probable extent, and full particulars if required.

NEC changes the behavioural rhythm. The PM’s instruction is still authoritative, and the Contractor must obey it, but the commercial consequences are brought forward into the compensation event process. The Contractor must quickly convert the change into a quotation within three weeks, supported by forecast Defined Cost plus Fee, any delay to Completion Date and Key Dates, and alterations to the Accepted Programme. The PM must reply within two weeks or make an assessment where the quotation is wrong or missing.

The risk position also changes. Under GCC, the Contractor carries more procedural risk if notice or higher-rate claim steps are missed, while the Engineer’s interim decision controls unless revised. Under NEC, the Contractor faces forecasting and programme-quality risk: a weak Accepted Programme or poorly supported quotation can allow the PM to impose an assessment that implements changes to Prices and Completion Date.

**Implementation comparison (GCC vs NEC4):**

| Aspect | GCC | NEC4 |
|---|---|---|
| Instruction authority | Engineer orders written variation (Clause 60(1)(a), Clause 60(2)). | PM instructs change to Scope (cl. 14.3). |
| Duty to comply | Contractor complies and proceeds despite dispute (Clause 15, Clause 86(1)). | Contractor obeys valid PM/Supervisor instruction (cl. 27.3). |
| Valuation basis | Retrospective rates under Clause 61(1)(b), Clause 61(1)(c). | Prospective Defined Cost plus Fee (cl. 63.1). |
| Alternative pricing | Engineer fixes reasonable rate if no agreement (Clause 61(2)). | Agreed rates or lump sums may be used (cl. 63.2). |
| Time assessment | EOT for Clause 60 variation after 28-day notice (Clause 50(1)(a), Clause 50(1)(b)(iv)). | Delay measured against Accepted Programme at dividing date (cl. 63.5). |
| Dispute route | Engineer written decision, binding unless revised (Clause 86(1)). | Option W4 dispute process, including cl. W4.2 to cl. W4.5. |


</details>

<details>
<summary><b>5. GCC Lessons for NEC Adoption</b> — GCC routines move earlier under NEC.</summary>

GCC practitioners already trained to insist on a written variation under Clause 60(2) can transfer that discipline directly to NEC cl. 14.3 and cl. 60.1(1). The behavioural adjustment is timing and classification: once the PM instructs the tank, the issue is not parked for later valuation; it immediately becomes a compensation event requiring PM notification under cl. 61.1 and a quotation process.

The GCC Clause 50(1)(a), Clause 50(3), and Clause 50(2) habit of identifying delay cause, probable extent, and detailed particulars transfers to NEC cl. 62.2 and cl. 63.5. The adjustment is evidential form: instead of only supporting an Engineer’s later EOT determination, the Contractor must express time impact as delay to planned Completion against the current Accepted Programme, including alterations to the programme.

GCC Clause 61(1)(b), Clause 61(1)(c), and Clause 61(2) valuation practice transfers partly to NEC cl. 63.1 and cl. 63.2. Quantity surveyors can still use rate reasoning where rates or lump sums are agreed, but the primary NEC discipline is forecasting actual and future Defined Cost plus Fee at the dividing date, not simply arguing a reasonable retrospective rate.

GCC Clause 64(1) and Clause 86(1) claim-preservation habits transfer to NEC cl. 64.1, cl. 64.3, cl. 66.1, cl. 66.2, and Option W4. The adjustment is to challenge through the live assessment and dispute route while recognising that the PM’s implemented assessment changes the Prices and Completion Date. In practical terms, GCC claim, record, variation, and delay-analysis habits should be used earlier under NEC as quotation, programme, and Defined Cost management tools.

| GCC practice / experience | → How it transfers to NEC implementation |
|---|---|
| Clause 60(2) written variation control. | Use cl. 14.3/cl. 60.1(1) instruction as CE trigger; open quotation immediately. |
| Clause 50(1)(a) 28-day delay notice discipline. | Convert delay warning into cl. 62.2 quotation and cl. 63.5 programme impact. |
| Clause 50(3) full and detailed particulars. | Support cl. 62.2 with cost build-up, delay analysis, and Accepted Programme alterations. |
| Clause 61(1)(b)/(c) variation rate analysis. | Inform cl. 63.2 rates/lump sums, but evidence cl. 63.1 Defined Cost plus Fee. |
| Clause 64(1)/Clause 86(1) dispute preservation. | Respond to cl. 64.1/cl. 64.3 PM assessment and escalate under Option W4. |

</details>

<details>
<summary><b>6. HK-Specific Notes</b> — HK approvals constrain change authority.</summary>

GCC Hong Kong context: The PAH Chapter 5, specifically the Appendix to the Form of Tender, and Works Bureau Technical Circular WB1900 Appendix A impose strict constraints on the contract administrator’s power. The Architect/Engineer must obtain confirmation of “no objection” from the Employer before ordering any variation committing the Employer to additional expenditure exceeding HK$300,000 under WB1900 for Building / E&M Works or HK$1,400,000 under PAH for Civil Works. This constraint does not apply where the variation is essential on grounds of safety or emergency and it is impracticable to refer the matter beforehand.

Under WB1900 Appendix B, the Architect/Engineer must refer the details of every variation and its estimated value to the Employer for information as soon as it is ordered. The Architect/Engineer must also report all claims and delays to the Employer, and must refer the principles underlying their assessment of EOT and claims so that the Employer can provide its view before the Architect/Engineer reaches a decision.

NEC4 Hong Kong context: The DEVB Practice Notes, the CEDD Playbook, and the NEC4 ECC HK Edition provide specific governance for this scenario. In Hong Kong public works, an instruction to change the Scope under cl. 60.1(1) is administratively categorized strictly as a “Variation”, whereas most other compensation events are categorized as “Claims” under the CEDD Playbook.

For internal financial authorities and approvals, because the retention tank is an instructed change to the Scope, the Project Manager must navigate internal government funding approvals. The CEDD Playbook flowcharts state that the PM may only give an instruction to increase the Prices without prior confirmation from the Client if the value is less than HK$1.4M. For cost estimates exceeding HK$1.4M, or limits specific to the PM’s delegate, the PM must obtain the Client’s confirmation of no objection or higher-tier approval, including D1, D2, or D6 levels, before issuing the instruction or accepting the quotation.

For dispute resolution, the NEC4 ECC HK Edition replaces the standard UK dispute clauses with Option W4. The cited Option W4 references are cl. W4.1, cl. W4.2, cl. W4.3, cl. W4.4, and cl. W4.5. A Party may first refer a Dispute to the Project Manager for a decision under cl. W4.2. If dissatisfied, a Payment Dispute may be referred to an adjudicator under cl. W4.3. Beyond this, disputes escalate to Mediation under cl. W4.4 and ultimately Arbitration under cl. W4.5 under the Arbitration Ordinance (Cap. 609).

</details>

## Clause Map (extracted by CM-A)

Structured index of every clause cited by the expert agents, with its taxonomy category and a verbatim quote / paraphrase.

- **GCC · Clause 15** — _change_management_ · obligation: **duty** · party: **Contractor** · condition: **Engineer's instructions**
  > Under Clause 15, the Contractor must execute the Works to the satisfaction of the Engineer and comply with the Engineer's instructions.
- **GCC · Clause 50(1)(a)** — _early_warning_risk_ · obligation: **process** · party: **Contractor** · timeline: **as soon as practicable but in any event within 28 days** · condition: **of the delay arising, or as soon as they can reasonably foresee the instruction is likely to cause delay**
  > The Contractor must give written notice of the cause and probable extent of the delay "as soon as practicable but in any event within 28 days" of the delay arising
- **GCC · Clause 50(1)(b)** — _extension_of_time_ · obligation: **condition** · party: **Contractor** · condition: **A variation ordered under Clause 60**
  > A variation ordered under Clause 60 is a specified ground for an Extension of Time (EOT) under Clause 50(1)(b)(iv).
- **GCC · Clause 50(2)** — _extension_of_time_ · obligation: **process** · party: **Engineer**
  > Assessment: The Engineer determines the EOT by taking into account "all the circumstances known to him at that time" (Clause 50(2)).
- **GCC · Clause 50(3)** — _extension_of_time_ · obligation: **right** · party: **Engineer**
  > Particulars: The Engineer may require the Contractor to submit "full and detailed particulars of the cause and extent of the delay" (Clause 50(3)).
- **GCC · Clause 60(1)(a)** — _change_management_ · obligation: **right** · party: **Engineer** · condition: **necessary for the completion of the Works or desirable to achieve satisfactory functioning**
  > Under Clause 60(1)(a), the Engineer has the power to order any variation that is necessary for the completion of the Works or desirable to achieve satisfactory functioning
- **GCC · Clause 60(2)** — _change_management_ · obligation: **condition** · party: **Contractor** · condition: **without an order in writing by the Engineer**
  > under Clause 60(2), "No variation shall be made by the Contractor without an order in writing by the Engineer."
- **GCC · Clause 61(1)(b)** — _change_management_ · obligation: **process** · party: **Engineer** · condition: **Work of the same/similar character executed under similar conditions**
  > Rule 1: Work of the same/similar character executed under similar conditions is valued at the rate set out in the Contract (Clause 61(1)(b)).
- **GCC · Clause 61(1)(c)** — _change_management_ · obligation: **process** · party: **Engineer** · condition: **Work not same/similar**
  > Rule 2: Work not same/similar is valued at a rate based on the Contract rates "so far as may be reasonable" (Clause 61(1)(c)).
- **GCC · Clause 61(2)** — _change_management_ · obligation: **right** · party: **Engineer** · condition: **If the Engineer and the Contractor fail to reach an agreement on the valuation rate**
  > If the Engineer and the Contractor fail to reach an agreement on the valuation rate, the Engineer has the unilateral power to "fix such rate as shall in his opinion be reasonable and notify the Contractor accordingly" (Clause 61(2)).
- **GCC · Clause 64(1)** — _dispute_resolution_ · obligation: **process** · party: **Contractor** · timeline: **within 28 days** · condition: **If the Contractor disagrees with this fixed rate**
  > If the Contractor disagrees with this fixed rate, they must give written notice of their intention to claim a higher rate within 28 days (Clause 64(1)).
- **GCC · Clause 86(1)** — _dispute_resolution_ · obligation: **process** · party: **both** · condition: **For any unresolved dispute regarding a decision, instruction, valuation, or EOT**
  > For any unresolved dispute regarding a decision, instruction, valuation, or EOT, the matter "shall be referred to and settled by the Engineer who shall state his decision in writing" under Clause 86(1).
- **GCC · Clause 61(1)** — _change_management_ · obligation: **process** · party: **Engineer** · condition: **The addition**
  > The addition is valued retrospectively by the Engineer under Clause 61(1) using a three-tier rule system:
- **GCC · Clause 60** — _change_management_ · obligation: **condition** · party: **Contractor** · condition: **A variation ordered under Clause 60**
  > A variation ordered under Clause 60 is a specified ground for an Extension of Time (EOT) under Clause 50(1)(b)(iv).
- **NEC4 · cl. 10.2** — _mutual_trust_ · obligation: **duty** · party: **both**
  > requiring the parties to act in a spirit of mutual trust and co-operation (cl. 10.2)
- **NEC4 · cl. 14.3** — _change_management_ · obligation: **right** · party: **PM**
  > The Project Manager has the express authority to give an instruction to the Contractor which changes the Scope (cl. 14.3)
- **NEC4 · cl. 27.3** — _change_management_ · obligation: **duty** · party: **Contractor** · condition: **instruction which is in accordance with the contract and is given by the Project Manager or the Supervisor**
  > The Contractor does not have the option to refuse; the Contractor must obey an instruction which is in accordance with the contract and is given by the Project Manager or the Supervisor (cl. 27.3)
- **NEC4 · cl. 60.1(1)** — _change_management_ · obligation: **condition** · party: **n/a** · condition: **An instruction changing the Scope**
  > An instruction changing the Scope (such as adding a new retention tank) constitutes a compensation event under cl. 60.1(1)
- **NEC4 · cl. 61.1** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · timeline: **at the time of that communication** · condition: **When issuing this instruction**
  > When issuing this instruction, the Project Manager notifies the Contractor of the compensation event at the time of that communication and instructs the Contractor to submit quotations (cl. 61.1)
- **NEC4 · cl. 62.2** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **Contractor** · timeline: **within three weeks of being instructed** · condition: **being instructed**
  > Contractor submits a quotation within three weeks of being instructed, detailing the forecast Defined Cost plus Fee, the delay to planned Completion against the current Accepted Programme, and any alterations to the programme (cl. 62.2, cl. 62.3).
- **NEC4 · cl. 62.3** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · timeline: **within two weeks of submission** · condition: **submission**
  > Project Manager replies to the quotation within two weeks of submission (cl. 62.3).
- **NEC4 · cl. 63.1** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **n/a** · condition: **the effect of the compensation event**
  > The change to the Prices is assessed prospectively as the effect of the compensation event upon the actual Defined Cost of work already done by the dividing date, the forecast Defined Cost of work not yet done by the dividing date, and the resulting Fee (cl. 63.1)
- **NEC4 · cl. 63.5** — _extension_of_time_ · obligation: **process** · party: **n/a** · timeline: **the length of time that, due to the compensation event, planned Completion is later than planned Completion as shown on the Accepted Programme current at the dividing date** · condition: **due to the compensation event**
  > A delay to the Completion Date is formally assessed as the length of time that, due to the compensation event, planned Completion is later than planned Completion as shown on the Accepted Programme current at the dividing date (cl. 63.5)
- **NEC4 · cl. 64.1** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **If the Project Manager decides that the Contractor has not assessed the compensation event correctly in their quotation, or if the Contractor fails to submit the quotation within the time allowed**
  > If the Project Manager decides that the Contractor has not assessed the compensation event correctly in their quotation, or if the Contractor fails to submit the quotation within the time allowed, the Project Manager makes their own assessment of the compensation event (cl. 64.1)
- **NEC4 · cl. 64.3** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · timeline: **within the period allowed for the Contractor's submission**
  > Project Manager notifies the Contractor of their assessment within the period allowed for the Contractor's submission (cl. 64.3), thereby implementing the compensation event and changing the Prices and Completion Date (cl. 66.1, cl. 66.2).
- **NEC4 · cl. 66.1** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **The Project Manager notifies the Contractor of this assessment**
  > The Project Manager notifies the Contractor of this assessment, which formally implements the compensation event (cl. 64.3, cl. 66.1)
- **NEC4 · cl. 66.2** — _compensation_event_notification_quotation_assessment_ · obligation: **remedy** · party: **n/a**
  > changes the Prices and Completion Date accordingly (cl. 66.2)
- **NEC4 · cl. 63.2** — _compensation_event_notification_quotation_assessment_ · obligation: **right** · party: **both** · condition: **if the Project Manager and the Contractor agree**
  > Alternatively, if the Project Manager and the Contractor agree, rates or lump sums may be used to assess the change to the Prices (cl. 63.2)

## Raw Expert Evidence (NotebookLM responses)

The full unmodified responses from the GCC and NEC4 expert agents are reproduced below for traceability.

<details>
<summary>GCC expert response (1 iteration(s), 5,914 chars)</summary>

[CLAUSE REFERENCES] Clause 15, Clause 50(1)(a), Clause 50(1)(b)(iv), Clause 50(2), Clause 50(3), Clause 60(1)(a), Clause 60(2), Clause 61(1)(b), Clause 61(1)(c), Clause 61(2), Clause 64(1), Clause 86(1).
[GCC POSITION] Note: The GCC corpus does not use the terms "Scope" or "Works Information". The technical requirements of the contract are governed by the "Specification" and "Drawings".
Authority to Issue the Instruction and Duty to Comply Under Clause 60(1)(a), the Engineer has the power to order any variation that is necessary for the completion of the Works or desirable to achieve satisfactory functioning, which explicitly includes "additions, omissions, substitutions, alterations, changes in quality, form, character, kind, position, dimension, level or line". Instructing an additional 500 m³ retention tank is a valid addition. However, under Clause 60(2), "No variation shall be made by the Contractor without an order in writing by the Engineer." The Contractor is strictly obligated to comply. Under Clause 15, the Contractor must execute the Works to the satisfaction of the Engineer and comply with the Engineer's instructions. Furthermore, under Clause 86(1), even if there is a dispute regarding the instruction, the Contractor "shall in every case continue to proceed with the Works with all due diligence".
Valuation and Assessment for Payment The addition is valued retrospectively by the Engineer under Clause 61(1) using a three-tier rule system:
Rule 1: Work of the same/similar character executed under similar conditions is valued at the rate set out in the Contract (Clause 61(1)(b)).
Rule 2: Work not same/similar is valued at a rate based on the Contract rates "so far as may be reasonable" (Clause 61(1)(c)).
Rule 3: Failing agreement on Rule 2, the work shall be valued "at a rate to be agreed between the Engineer and the Contractor" (Clause 61(1)(c)).
Notification and Assessment of Time Impact
A variation ordered under Clause 60 is a specified ground for an Extension of Time (EOT) under Clause 50(1)(b)(iv).
Notice: The Contractor must give written notice of the cause and probable extent of the delay "as soon as practicable but in any event within 28 days" of the delay arising, or as soon as they can reasonably foresee the instruction is likely to cause delay (Clause 50(1)(a)).
Particulars: The Engineer may require the Contractor to submit "full and detailed particulars of the cause and extent of the delay" (Clause 50(3)).
Assessment: The Engineer determines the EOT by taking into account "all the circumstances known to him at that time" (Clause 50(2)).
Decision-Making in Event of Disagreement If the Engineer and the Contractor fail to reach an agreement on the valuation rate, the Engineer has the unilateral power to "fix such rate as shall in his opinion be reasonable and notify the Contractor accordingly" (Clause 61(2)). If the Contractor disagrees with this fixed rate, they must give written notice of their intention to claim a higher rate within 28 days (Clause 64(1)). For any unresolved dispute regarding a decision, instruction, valuation, or EOT, the matter "shall be referred to and settled by the Engineer who shall state his decision in writing" under Clause 86(1). The Engineer's decision is final and binding unless and until revised in mediation or arbitration.
[PROCEDURAL IMPLICATION]
Engineer issues a formal order in writing to the Contractor instructing the addition of the 500 m³ retention tank (Clause 60(1)(a) & 60(2)).
Contractor complies with the instruction and proceeds with the varied work with all due diligence (Clause 15, Clause 86(1)).
Contractor serves written notice to the Engineer of the probable effect and extent of the delay within 28 days of the variation order or the delay arising (Clause 50(1)(a)).
Contractor submits full and detailed particulars of the delay to the Engineer (Clause 50(3)).
Engineer determines and grants an Extension of Time based on all known circumstances (Clause 50(2)).
Engineer and Contractor attempt to agree on the value of the variation using existing Contract rates as a basis (Clause 61(1)).
If agreement fails, Engineer fixes a reasonable rate and formally notifies the Contractor (Clause 61(2)).
If the Contractor intends to claim a higher rate than the one fixed, Contractor serves written notice to the Engineer within 28 days of the notification (Clause 64(1)).
If disagreement persists over the time or cost consequences, either party refers the dispute to the Engineer for a formal written decision, which remains binding until mediation or arbitration (Clause 86(1)).
[HK CONTEXT] According to the Project Administration Handbook (PAH) Chapter 5 (Appendix to the Form of Tender) and Works Bureau Technical Circular WB1900 (Appendix A), the Employer imposes strict constraints on the contract administrator's power. The Architect/Engineer is required to obtain confirmation of "no objection" from the Employer before ordering any variation committing the Employer to additional expenditure exceeding HK$300,000 (under WB1900 for Building / E&M Works) or HK$1,400,000 (under PAH for Civil Works). This constraint does not apply if the variation is essential on grounds of safety or emergency where it is impracticable to refer the matter beforehand.
Furthermore, under WB1900 Appendix B, the Architect/Engineer must refer the details of every variation and its estimated value to the Employer for information as soon as it is ordered. The Architect/Engineer must also report all claims and delays to the Employer, and must refer the principles underlying their assessment of EOT and claims to enable the Employer to provide their view before the Architect/Engineer reaches a decision.
Who decides if the Engineer's fixed rate is reasonable?
What happens if a design change commits the Employer to extra expenditure?
What are the rules for valuing work of a dissimilar character?

</details>

<details>
<summary>NEC4 expert response (1 iteration(s), 5,844 chars)</summary>

[CLAUSE REFERENCES] cl. 10.2, cl. 14.3, cl. 27.3, cl. 60.1(1), cl. 61.1, cl. 62.2, cl. 62.3, cl. 63.1, cl. 63.5, cl. 64.1, cl. 64.3, cl. 66.1, cl. 66.2, cl. W4.1, cl. W4.2, cl. W4.3, cl. W4.4, cl. W4.5
[NEC POSITION] The NEC4 ECC manages mid-construction design or scope changes through its prospective compensation event regime, requiring the parties to act in a spirit of mutual trust and co-operation (cl. 10.2)
Authority to Issue and Obligation to Comply: The Project Manager has the express authority to give an instruction to the Contractor which changes the Scope (cl. 14.3)
. The Contractor does not have the option to refuse; the Contractor must obey an instruction which is in accordance with the contract and is given by the Project Manager or the Supervisor (cl. 27.3)
Notification and Assessment Rules: An instruction changing the Scope (such as adding a new retention tank) constitutes a compensation event under cl. 60.1(1)
. When issuing this instruction, the Project Manager notifies the Contractor of the compensation event at the time of that communication and instructs the Contractor to submit quotations (cl. 61.1)
The Contractor submits a quotation comprising proposed changes to the Prices, any delay to the Completion Date and Key Dates, details of their assessment, and alterations to the Accepted Programme (cl. 62.2)
Valuation of Payment: The change to the Prices is assessed prospectively as the effect of the compensation event upon the actual Defined Cost of work already done by the dividing date, the forecast Defined Cost of work not yet done by the dividing date, and the resulting Fee (cl. 63.1)
. Alternatively, if the Project Manager and the Contractor agree, rates or lump sums may be used to assess the change to the Prices (cl. 63.2)
Assessment of Time: A delay to the Completion Date is formally assessed as the length of time that, due to the compensation event, planned Completion is later than planned Completion as shown on the Accepted Programme current at the dividing date (cl. 63.5)
Disagreement and Decision: If the Project Manager decides that the Contractor has not assessed the compensation event correctly in their quotation, or if the Contractor fails to submit the quotation within the time allowed, the Project Manager makes their own assessment of the compensation event (cl. 64.1)
. The Project Manager notifies the Contractor of this assessment, which formally implements the compensation event (cl. 64.3, cl. 66.1) and changes the Prices and Completion Date accordingly (cl. 66.2)
. If the Contractor disagrees with the Project Manager's assessment, this disagreement crystallizes into a dispute, which is decided by the dispute resolution mechanisms designated in the contract
[PROCEDURAL IMPLICATION]
Project Manager gives an instruction to the Contractor changing the Scope to add the 500 m³ retention tank (cl. 14.3).
Project Manager notifies the Contractor of the compensation event at the time of giving the instruction and instructs the Contractor to submit a quotation (cl. 61.1).
Contractor obeys the instruction and begins providing the works for the retention tank as required by the changed Scope (cl. 27.3).
Contractor submits a quotation within three weeks of being instructed, detailing the forecast Defined Cost plus Fee, the delay to planned Completion against the current Accepted Programme, and any alterations to the programme (cl. 62.2, cl. 62.3).
Project Manager replies to the quotation within two weeks of submission (cl. 62.3).
Project Manager makes their own assessment of the compensation event if they decide the Contractor's assessment is incorrect, or if they cannot agree on the valuation/time consequences (cl. 64.1).
Project Manager notifies the Contractor of their assessment within the period allowed for the Contractor's submission (cl. 64.3), thereby implementing the compensation event and changing the Prices and Completion Date (cl. 66.1, cl. 66.2).
Contractor (if dissatisfied with the Project Manager's assessment) refers the dispute to the appropriate dispute resolution tier (e.g., cl. W4.2) for a formal decision.
[HK CONTEXT] The DEVB Practice Notes, the CEDD Playbook, and the NEC4 ECC HK Edition provide highly specific governance for this scenario:
Variation vs. Claim Categorization: In Hong Kong public works, an instruction to change the Scope under cl. 60.1(1) is administratively categorized strictly as a "Variation", whereas most other compensation events are categorized as "Claims" (CEDD Playbook)
Internal Financial Authorities (Approvals): Because the retention tank is an instructed change to the Scope, the Project Manager must navigate internal government funding approvals. The CEDD Playbook flowcharts stipulate that the Project Manager may only give an instruction to increase the Prices without prior confirmation from the Client if the value is less than HK$1.4M. For cost estimates exceeding HK$1.4M (or limits specific to the PM's delegate), the PM must obtain the Client's confirmation of no objection or higher-tier approval (e.g., D1, D2, or D6 levels) before issuing the instruction or accepting the quotation
more_horiz
Dispute Resolution (Option W4): If the Contractor disagrees with the Project Manager's assessment, the NEC4 ECC HK Edition replaces standard UK dispute clauses with Option W4. A Party may refer a Dispute to the Project Manager for a decision first (cl. W4.2). If dissatisfied, a Payment Dispute can be referred to an adjudicator (cl. W4.3). Beyond this, disputes are escalated to Mediation (cl. W4.4) and ultimately Arbitration (cl. W4.5) under the Arbitration Ordinance (Cap. 609)
What if the Project Manager fails to respond to my design proposal?
How is payment calculated if an activity is only partially complete?
Does accepting a design change shift responsibility for its quality?

</details>

## SYN-A Chain-of-Thought Reasoning

<details>
<summary>Three-level reasoning trace (L1 → L2 → L3)</summary>

[L1 — Spirit/Philosophy] GCC treats the additional 500 m³ retention tank through an Engineer-led variation and claims architecture: the Engineer controls instruction, valuation, EOT assessment, and first-instance dispute decision, while the Contractor preserves entitlement through notices, particulars, records, and continued progress. In Transaction Cost Economics terms, GCC relies on hierarchical/adversarial governance to control opportunism after the event. NEC4 ECC instead treats the same change as a compensation event managed prospectively through Scope instruction, quotation, programme-based time assessment, PM reply/assessment, and implementation; cl. 10.2 frames this as relational governance based on mutual trust, cooperation, transparency, and early commercial forecasting.

[L2 — Clause-level Comparison] Under GCC, Clause 60(1)(a) authorises the Engineer to order additions and other variations; Clause 60(2) bars the Contractor from making a variation without the Engineer’s written order; Clause 15 requires compliance with Engineer’s instructions; and Clause 86(1) requires continued due diligence despite dispute. Valuation is retrospective under Clause 61(1), using Clause 61(1)(b) for same/similar work, Clause 61(1)(c) for dissimilar work based on Contract rates “so far as may be reasonable”, and agreement where possible; failing agreement, Clause 61(2) lets the Engineer “fix such rate as shall in his opinion be reasonable and notify the Contractor accordingly”. Time relief arises because a Clause 60 variation is an EOT ground under Clause 50(1)(b)(iv), subject to Clause 50(1)(a) notice “as soon as practicable but in any event within 28 days”, Clause 50(3) particulars, and Clause 50(2) Engineer determination. Under NEC4, cl. 14.3 gives the PM authority to instruct a Scope change; cl. 27.3 requires obedience; cl. 60.1(1) makes the Scope change a compensation event; cl. 61.1 requires PM notification and quotation instruction at the same time; cl. 62.2 and cl. 62.3 govern quotation and reply; cl. 63.1 values by actual/forecast Defined Cost plus Fee at the dividing date, with cl. 63.2 allowing agreed rates or lump sums; cl. 63.5 assesses delay against planned Completion on the Accepted Programme; cl. 64.1 and cl. 64.3 allow PM assessment; cl. 66.1 and cl. 66.2 implement changes to Prices and Completion Date; disputes proceed through W4, including cl. W4.1, cl. W4.2, cl. W4.3, cl. W4.4, and cl. W4.5.

[L3 — Practice/Behavioural Implications + GCC-to-NEC Transfer] GCC-trained Hong Kong practitioners already know the core disciplines needed for NEC: written instruction control, prompt delay notices, full particulars, valuation substantiation, records, and continued progress under dispute. The transfer is not abandonment but retiming. GCC Clause 60(2) written-order discipline maps to NEC cl. 14.3/cl. 60.1(1): practitioners should still insist on a clear administrator instruction, but must immediately treat it as a compensation event process rather than waiting for retrospective valuation. GCC Clause 50(1)(a), Clause 50(3), and Clause 50(2) delay-notice and EOT workflows map to NEC cl. 62.2 and cl. 63.5: the behavioural adjustment is to convert delay narratives and particulars into Accepted Programme-based forecasts of planned Completion. GCC Clause 61(1)(b), Clause 61(1)(c), and Clause 61(2) rate-valuation skills map to NEC cl. 63.1 and cl. 63.2: practitioners should retain rate logic where agreed but must support forecast Defined Cost plus Fee rather than merely argue a reasonable retrospective rate. GCC Clause 64(1) and Clause 86(1) claim/dispute preservation maps to NEC cl. 64.1, cl. 64.3, cl. 66.1, cl. 66.2, and Option W4: the adjustment is to engage earlier with the PM’s assessment, preserve disagreement through W4 if needed, and continue collaboratively while commercial consequences are implemented.

</details>

---

### Query Plan (QP-A)
- **L1 (spirit):**     How does the contract’s governance philosophy allocate control and responsibility when the contract administrator directs a significant mid-construction design or scope change?
- **L2 (clauses):**    Which clauses govern the authority to instruct the additional retention tank, the valuation of the resulting change, and the assessment of any extension of time or delay impact?
- **L3 (practice):**   In practice, how do the instruction, quotation or valuation process, programme analysis, and administrator’s decision-making role shape the contractor’s behaviour and risk position?
- **canonical_topic:** `change_management`

### Anchor Clauses (scenario ground-truth, used for CR)
- **GCC anchors:**  Clause 60, Clause 61, Clause 50(1), Clause 64
- **NEC4 anchors:** cl. 60.1(1), cl. 61.1, cl. 62.1, cl. 63.1, cl. 63.5

*Generated by MAS v2.2 — LangGraph orchestrator (6 agents + 3 rule modules).*