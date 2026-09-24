# Scenario D08: NEC Douglas D08 - No response to design submission after Client changes floor requirement

**Generated:** 2026-07-07 16:59

## Context
An ECC Option C design and build contract is awarded for a pedestrian bridge, with a two-week period of reply. The Contractor submits a steel-floor design for acceptance. The Scope provided by the Client is not specific on floor type. The Client later definitely requires a marble floor. Three weeks after the Contractor submitted its steel-floor design, it still has no response from the Project Manager. The Accepted Programme shows the design acceptance is needed the next day; otherwise the Contractor starts to incur additional costs and may miss a materials supply window.

## MAS Query Topic
> No response to design submission after Client changes floor requirement.

Specific questions to address:
What should the Contractor do in this situation?

## Validation Results

### Overall — ✅ PASSED  (confidence: 0.9643, iterations used: 1)

> All checks passed (composite confidence 0.96; no per-metric dips; LLM semantic also passed).

### Rule-based Validation (deterministic)

**Track verdict:** ✅ pass

| Metric | Value | Threshold | Status |
|---|---|---|---|
| Citation Accuracy Rate (GCC) | 1.00 | ≥ 0.85 | ✅ pass |
| Citation Accuracy Rate (NEC4) | 1.00 | ≥ 0.85 | ✅ pass |
| Coverage Rate (GCC) | 1.00 | ≥ 0.85 | ✅ pass |
| Coverage Rate (NEC4) | 0.86 | ≥ 0.85 | ✅ pass |
| Composite Confidence | 0.96 | ≥ 0.70 | ✅ pass |
| Clause format | 0 violation(s) | All match regex | ✅ pass |

**GCC anchor coverage:**
  _(no anchors defined for this scenario)_

**NEC4 anchor coverage:**
 ✅ cl. 13.3 ✅ cl. 15.1 ✅ cl. 21.2 ✅ cl. 60.1(6) ✅ cl. 61.3 ✅ cl. 61.4
 ❌ cl. 13.4

### LLM-based Semantic Validation

**Track verdict:** ✅ pass
**Severity:** minor

_No substantive issues raised._

## Comparative Synthesis

> **Executive summary** — GCC bars the Contractor from proceeding without written Engineer approval/order but allows EOT and Cost claims if notices, records and mitigation are maintained; NEC likewise bars proceeding without PM acceptance but gives CE machinery. GCC is claim-protective; NEC is prospective and collaborative.

<details>
<summary><b>1. Spirit / Philosophy</b> — Engineer-led claims vs relational control.</summary>

GCC: The GCC administers a client-initiated floor change through Engineer authority, written approval, variation orders, EOT and Cost claims. Its governance ethos is formal and claims-oriented: the Contractor protects entitlement by notices, contemporary records, particulars, interim accounts and mitigation. In TCE terms, it relies on ex post safeguards and documentary control to manage uncertainty and opportunism.

NEC: NEC4 ECC manages the same facts through a live process of communication, early warning, Scope instruction, compensation-event notification, quotation, programme update and assessed Defined Cost/time effects. Its governance ethos is relational and process-based, underpinned by the spirit of mutual trust and co-operation in cl. 10.2. In TCE terms, it reduces transaction costs by forcing early disclosure, timely replies and prospective assessment.

</details>

<details>
<summary><b>2. GCC Position (Implementation)</b> — Written variation first, then claim protection.</summary>

**Implementation flow:**

1. Contractor specifically applies in writing for instruction/approval, timed neither unreasonably distant nor close to need (Clause 63(a)) →
2. Engineer gives or refuses written approval within a reasonable time (Clause 7(1)) →
3. Contractor does not proceed with varied floor work without written order (Clause 60(2)) →
4. If delay occurs, Contractor gives delay notice within 28 days and Cost-claim notice within 28 days (Clause 50(1)(a); Clause 64(2)) →
5. Contractor mitigates, records, submits particulars/interim account, and updates programme if EOT granted (Clause 50(2); SCC Clause A4(2); Clause 64(3); Clause 50(3); Clause 64(4); Clause 50(4)).

A client’s changed floor requirement is a variation which the Engineer may order under Clause 60(1). However, Clause 60(2) states that “No variation shall be made by the Contractor without an order in writing by the Engineer”; if the Contractor proceeds without that written order or response, it acts in breach and without payment entitlement for that varied work.

When revised design drawings or documents are submitted, Clause 7(1) requires the Engineer to “give or refuse his approval in writing to such proposals within a reasonable time”. The standard GCC has no deemed acceptance rule, so explicit written approval remains necessary before the affected varied floor work proceeds.

If the Engineer’s lack of response delays the Works, Clause 50(1)(b)(vii) treats failure to issue decisions, drawings or instructions as a disturbance supporting an EOT. The Contractor must issue written notice of the cause and probable extent of delay within 28 days of the delay arising under Clause 50(1)(a), submit full and detailed particulars under Clause 50(3), and use and continue to use all reasonable endeavours to avoid or reduce the effects of the delay under Clause 50(2) and SCC Clause A4(2). Whenever an EOT is granted, the Contractor must revise the programme accordingly under Clause 50(4).

For Cost, Clause 63(a) permits recovery of actual “Cost incurred” only if the Contractor has specifically applied in writing for the relevant instruction on a date “neither unreasonably distant from nor unreasonably close to” the date when it was necessary to receive it. Clause 64(2) also requires written notice of intention to claim within 28 days after the happening of the event. Clause 64(3) requires contemporary records, including standby time, idle resources and actual costs. Clause 64(4) requires a first interim account for the financial claim. The Engineer then assesses the EOT and ascertains the Cost incurred due to lack of instructions. Clause 61 is the valuation route for ordered varied work; Clause 5 is relevant if the issue is design ambiguity rather than a client change.

</details>

<details>
<summary><b>3. NEC4 Position (Implementation)</b> — Scope instruction, CE notice and quotation.</summary>

**Implementation flow:**

1. PM instructs Scope change and notifies CE with quotation instruction (cl. 14.3; cl. 60.1(1); cl. 61.1) →
2. Contractor submits revised design particulars and does not proceed until PM acceptance (cl. 21.2) →
3. Contractor early warns as soon as aware of delay, Key Date or Price risk (cl. 15.1) →
4. If PM fails to reply within Contract Data period, Contractor notifies CE within 8 weeks (cl. 13.3; cl. 60.1(6); cl. 61.3) →
5. If PM does not reply to CE notice, Contractor issues failure notice; no reply within further two weeks means CE accepted (cl. 61.4) →
6. Contractor updates programme, continues unaffected work, and submits quotation on competent, prompt mitigation basis (cl. 32.1; cl. 27.3; cl. 62.3; cl. 63.9).

NEC4 ECC manages the situation through strict procedural timelines and prospective risk management, underpinned by mutual trust and co-operation under cl. 10.2. When the Client changes the floor requirement, the Project Manager must give an instruction changing the Scope under cl. 14.3. That instruction is a compensation event under cl. 60.1(1), and the Project Manager should notify the CE and instruct quotation at the time of giving the instruction under cl. 61.1.

To comply with the changed Scope, the Contractor prepares and submits revised design particulars to the Project Manager for acceptance under cl. 21.2. The Contractor must not proceed with the relevant work until the Project Manager has accepted the design under cl. 21.2; proceeding without acceptance is at the Contractor’s own risk. The Contractor must nevertheless continue to Provide the Works for unaffected areas and obey Project Manager instructions under cl. 27.3.

The Project Manager must reply to communications within the period for reply stated in the Contract Data under cl. 13.3. All communications must be readable, copied and recorded under cl. 13.1, and notifications must be communicated separately under cl. 13.7. If the Project Manager fails to reply to the design submission within that period, the failure is itself a compensation event under cl. 60.1(6).

The Contractor must give an early warning as soon as it becomes aware that the lack of response could delay Completion, delay meeting a Key Date, or increase the total of the Prices under cl. 15.1. If the Project Manager has not notified the CE for the Scope change or failure to reply, the Contractor must notify the CE within 8 weeks of becoming aware under cl. 61.3; failure means loss of entitlement to a change in the Prices or Completion Date. If the Project Manager fails to reply to that CE notification, the Contractor may notify the failure; if there is no reply within a further two weeks, the CE notification is treated as accepted under cl. 61.4. Each revised programme submitted for acceptance must show how delays will be dealt with under cl. 32.1. On instruction, the Contractor submits a quotation under cl. 62.3, assessed on the assumption that it reacts competently and promptly and that time and Defined Cost are reasonably incurred under cl. 63.9.

</details>

<details>
<summary><b>4. Behavioural Implications</b> — Do not proceed at risk; notify early.</summary>

Under GCC, the Contractor behaves defensively and sequentially. It should not execute the changed floor work without the Engineer’s written order under Clause 60(2), even if the client requirement is known. It should make a specific written application for the required instruction/approval under Clause 63(a), press for the Clause 7(1) written response, and then protect EOT and Cost through separate 28-day notices under Clause 50(1)(a) and Clause 64(2). Evidence is retrospective but must be contemporary: standby labour, idle plant, delayed design-team activity, correspondence, actual cost and programme impact. The incentive is to avoid waiver or breach while proving actual loss.

Under NEC, the Contractor acts earlier and more openly. It should request or prompt the cl. 14.3 Scope instruction, submit revised design particulars under cl. 21.2, and avoid affected work until accepted. At the same time, it should early warn as soon as the no-response risk is apparent under cl. 15.1, maintain formal recordable communications under cl. 13.1 and separate notifications under cl. 13.7, and use cl. 61.3 within 8 weeks if the PM has not notified the CE. Evidence is not only claim proof but quotation support: forecast delay, Defined Cost, mitigation steps and revised programme logic. The incentive is to convert uncertainty into a managed CE and keep unaffected work moving under cl. 27.3.

**Implementation comparison (GCC vs NEC4):**

| Aspect | GCC | NEC4 |
|---|---|---|
| Authority to change | Engineer orders variation in writing (Clause 60(1); Clause 60(2)). | PM instructs Scope change (cl. 14.3; cl. 60.1(1)). |
| Design review | Engineer approves/refuses in writing within reasonable time (Clause 7(1)). | PM accepts design before affected work proceeds (cl. 21.2). |
| No response | No deemed acceptance; claim delay/Cost if conditions met. | Failure to reply is CE (cl. 60.1(6)). |
| Notice deadline | Delay and Cost notices each within 28 days. | CE notice within 8 weeks of awareness (cl. 61.3). |
| Mitigation/programme | Reasonable endeavours; revise programme after EOT (Clause 50). | Continue unaffected work; revise programme with delay plan. |
| Cost evidence | Contemporary records and first interim account (Clause 64). | Quotation and reasonable Defined Cost (cl. 62.3; cl. 63.9). |


</details>

<details>
<summary><b>5. GCC Lessons for NEC Adoption</b> — GCC claim routines become NEC controls.</summary>

Start with the GCC discipline of not proceeding without authority. Clause 60(2) teaches Hong Kong practitioners to separate the changed floor work from the rest of the Works until there is written authority; under NEC this transfers to cl. 21.2, where the Contractor must not proceed with the relevant work until the PM has accepted the design. The behavioural adjustment is not to wait passively: prompt the cl. 14.3 Scope instruction, submit the revised design particulars, and keep unaffected work moving under cl. 27.3.

The GCC habit of formal written applications under Clause 63(a) transfers to NEC’s communication structure in cl. 13.1, cl. 13.3 and cl. 13.7. The adjustment is timing and purpose: the written request is not only a later claim foundation but also a trigger for the Contract Data reply period and, if unanswered, a potential cl. 60.1(6) compensation event.

GCC notice routines under Clause 50(1)(a) and Clause 64(2) transfer to NEC early warning and CE notification. The adjustment is sharper front-end management: warn as soon as the no-response risk could affect Completion, a Key Date or Prices under cl. 15.1, then notify the CE within 8 weeks of becoming aware under cl. 61.3 if the PM has not done so.

GCC particulars, records and accounts under Clause 50(3), Clause 64(3) and Clause 64(4) transfer to NEC quotations under cl. 62.3 and assessment under cl. 63.9. Clause 61 variation-valuation experience helps price NEC cl. 60.1(1) Scope changes, while Clause 50(4) programme-update habits support cl. 32.1 revised programmes. In practice, GCC claim, record, variation and delay-analysis habits should be used earlier under NEC as live risk, quotation and programme-management tools.

| GCC practice / experience | → How it transfers to NEC implementation |
|---|---|
| Do not vary without written order (Clause 60(2)). | Use cl. 21.2: wait for PM design acceptance before affected work. |
| Specific written application for instruction (Clause 63(a)). | Use cl. 13.3 reply period; create cl. 60.1(6) trigger. |
| Delay and Cost notices within 28 days. | Give cl. 15.1 early warning; notify CE within 8 weeks. |
| Contemporary records and interim account (Clause 64). | Support cl. 62.3 quotation and cl. 63.9 reasonable Defined Cost. |
| EOT particulars and programme revision (Clause 50). | Show delay-management plan in revised programme under cl. 32.1. |

</details>

<details>
<summary><b>6. HK-Specific Notes</b> — HK approvals can explain response delay.</summary>

For GCC Hong Kong public works, the raw guidance identifies Works Bureau Technical Circular WB1900 Appendix A and the Project Administration Handbook (PAH) Chapter 5 as a likely practical explanation for the Engineer’s lack of response. The Architect/Engineer is constrained from ordering any variation committing the Employer to additional expenditure exceeding HK$300,000 for Building Works or HK$1,400,000 for Civil Works without first obtaining “confirmation of no objection” from the Employer. This can structurally delay a formal variation order or written approval even though Clause 7(1) requires a written approval/refusal within a reasonable time and Clause 60(2) prevents the Contractor from proceeding without a written order.

WB1900 Appendix B is also relevant on the GCC side. It requires the Architect/Engineer to report all claims and delays to the Employer and refer the principles underlying their assessment to the Employer for views before reaching a decision. Practically, the Contractor should understand that the contract administrator may be awaiting Employer review of funding and assessment principles; that does not remove the Contractor’s need to make the Clause 63(a) written application, Clause 50(1)(a) delay notice, Clause 64(2) cost-claim notice, Clause 64(3) records, Clause 50(3) particulars and Clause 64(4) first interim account.

For NEC4 Hong Kong practice, the raw guidance refers to DEVB Practice Notes and the CEDD Playbook. In CEDD projects, an instruction to change the Scope under cl. 60.1(1) is administratively categorised strictly as a “Variation”, whereas a failure to reply under cl. 60.1(6) is categorised as a “Claim”. This distinction matters for how the event is logged and administered, even though both are processed through NEC compensation-event mechanisms.

DEVB PN Section A6.3.1.27 expressly states that “Late acceptance of the Contractor’s design which prohibit the Contractor to proceed with the relevant work will constitute a compensation event” under cl. 60.1(6). This directly fits a no-response-to-design-submission scenario where cl. 21.2 prevents the Contractor from proceeding with the affected work until design acceptance.

DEVB PN Section A6.1.1.1(b) warns that although Mobile Instant Messaging such as WhatsApp is common, the policy intent is not to accept MIM as a valid form of communication. Therefore, all critical notifications, design submissions, early warnings, CE notifications and failure notices should be made through formal written records satisfying cl. 13.1, with notifications sent separately under cl. 13.7, to avoid unnecessary disputes. No additional NEC4 Hong Kong Edition specifics such as W4, Z-clauses or tender-closing-date baseline were identified in the supplied expert responses for this topic.

</details>

## Clause Map (extracted by CM-A)

Structured index of every clause cited by the expert agents, with its taxonomy category and a verbatim quote / paraphrase.

- **GCC · Clause 7(1)** — _uncategorised_ · obligation: **process** · party: **Engineer** · timeline: **within a reasonable time** · condition: **When the Contractor submits revised design drawings or documents to the Engineer**
  > Clause 7(1) requires that the Engineer "shall give or refuse his approval in writing to such proposals within a reasonable time"
- **GCC · Clause 50(1)(a)** — _early_warning_risk_ · obligation: **process** · party: **Contractor** · timeline: **within 28 days of the delay arising** · condition: **delay arising**
  > The Contractor must issue a written notice of the cause and probable extent of the delay within 28 days of the delay arising (Clause 50(1)(a))
- **GCC · Clause 50(1)(b)** — _extension_of_time_ · obligation: **remedy** · party: **Contractor** · condition: **delay caused by the Engineer's failure to issue decisions, drawings, or instructions**
  > a delay caused by the Engineer's failure to issue decisions, drawings, or instructions constitutes a disturbance to the progress of the Works, entitling the Contractor to an Extension of Time (EOT) under Clause 50(1)(b)(vii)
- **GCC · Clause 50(2)** — _extension_of_time_ · obligation: **duty** · party: **Contractor** · condition: **a cause of delay**
  > Under Clause 50(2) and SCC Clause A4(2), the Contractor must "use and continue to use all reasonable endeavours to avoid or reduce the effects of a cause of delay"
- **GCC · Clause 50(3)** — _extension_of_time_ · obligation: **process** · party: **Contractor** · condition: **delay**
  > must submit full and detailed particulars of the delay (Clause 50(3))
- **GCC · Clause 50(4)** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **whenever an EOT is granted** · condition: **an EOT is granted**
  > whenever an EOT is granted, the Contractor must revise the programme accordingly (Clause 50(4))
- **GCC · Clause 60(1)** — _change_management_ · obligation: **right** · party: **Engineer** · condition: **A client's change to a floor requirement constitutes a variation**
  > A client's change to a floor requirement constitutes a variation, which the Engineer has the power to order
- **GCC · Clause 60(2)** — _change_management_ · obligation: **condition** · party: **Contractor** · condition: **without an order in writing by the Engineer**
  > under Clause 60(2), "No variation shall be made by the Contractor without an order in writing by the Engineer"
- **GCC · Clause 63(a)** — _extension_of_time_ · obligation: **remedy** · party: **Contractor** · timeline: **on a date which... was neither unreasonably distant from nor unreasonably close to the date on which it was necessary for the Contractor to receive the same** · condition: **If the Engineer's lack of response delays the Works**
  > the Contractor is entitled to claim actual "Cost incurred" under Clause 63(a) . This cost entitlement is strictly conditioned on the Contractor having "specifically applied in writing on a date which... was neither unreasonably distant from nor unreasonably close to the date on which it was necessary
- **GCC · Clause 64(2)** — _dispute_resolution_ · obligation: **process** · party: **Contractor** · timeline: **within 28 days after the happening of the event** · condition: **To claim additional Cost**
  > To claim additional Cost, the Contractor must serve a written notice of intention to claim within 28 days after the happening of the event (Clause 64(2))
- **GCC · Clause 64(3)** — _dispute_resolution_ · obligation: **duty** · party: **Contractor** · condition: **to support any claim**
  > The Contractor is obligated to keep contemporary records to support any claim (Clause 64(3))
- **GCC · Clause 64(4)** — _dispute_resolution_ · obligation: **process** · party: **Contractor** · condition: **financial claim**
  > a first interim account for the financial claim (Clause 64(4))
- **GCC · Clause 61** — _change_management_ · obligation: **process** · party: **n/a**
  > What are the rules for valuing varied work under Clause 61?
- **GCC · Clause 5** — _change_management_ · obligation: **duty** · party: **Engineer** · condition: **design ambiguities**
  > Explain the Engineer's duty to clarify design ambiguities under Clause 5.
- **NEC4 · cl. 10.2** — _mutual_trust_ · obligation: **duty** · party: **both**
  > underpinned by the spirit of mutual trust and co-operation (cl. 10.2)
- **NEC4 · cl. 13.1** — _mutual_trust_ · obligation: **duty** · party: **both**
  > All communications must be in a form that can be read, copied, and recorded (cl. 13.1)
- **NEC4 · cl. 13.3** — _uncategorised_ · obligation: **duty** · party: **PM** · timeline: **within the period for reply stated in the Contract Data** · condition: **Contractor's communication**
  > The Project Manager is contractually obligated to reply to the Contractor's communication within the period for reply stated in the Contract Data (cl. 13.3)
- **NEC4 · cl. 13.7** — _uncategorised_ · obligation: **duty** · party: **both** · condition: **Any notification**
  > Any notification must be communicated separately from other communications to ensure it is not overlooked (cl. 13.7)
- **NEC4 · cl. 14.3** — _change_management_ · obligation: **duty** · party: **PM** · condition: **When the Client changes the floor requirement**
  > When the Client changes the floor requirement, the Project Manager must give an instruction changing the Scope (cl. 14.3)
- **NEC4 · cl. 15.1** — _early_warning_risk_ · obligation: **duty** · party: **Contractor** · timeline: **as soon as they become aware** · condition: **the lack of response could delay Completion, delay meeting a Key Date, or increase the total of the Prices**
  > The Contractor must give an early warning as soon as they become aware that the lack of response could delay Completion, delay meeting a Key Date, or increase the total of the Prices (cl. 15.1)
- **NEC4 · cl. 21.2** — _quality_management_ · obligation: **duty** · party: **Contractor** · timeline: **until the Project Manager has accepted the design** · condition: **To comply with the changed Scope**
  > The Contractor must prepare and submit revised design particulars to the Project Manager for acceptance (cl. 21.2) . The Contractor must not proceed with the relevant work until the Project Manager has accepted the design (cl. 21.2)
- **NEC4 · cl. 27.3** — _change_management_ · obligation: **duty** · party: **Contractor**
  > the Contractor must continue to Provide the Works for all unaffected areas and obey the Project Manager's instructions (cl. 27.3)
- **NEC4 · cl. 32.1** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **in each revised programme submitted for acceptance** · condition: **any delays**
  > The Contractor must show how they plan to deal with any delays in each revised programme submitted for acceptance (cl. 32.1)
- **NEC4 · cl. 60.1(1)** — _change_management_ · obligation: **definition** · party: **n/a** · condition: **Such an instruction**
  > Such an instruction is a compensation event under cl. 60.1(1)
- **NEC4 · cl. 60.1(6)** — _compensation_event_notification_quotation_assessment_ · obligation: **condition** · party: **PM** · timeline: **within this timeframe** · condition: **Project Manager fails to reply to the design submission**
  > If the Project Manager fails to reply to the design submission within this timeframe, this failure is itself a compensation event under cl. 60.1(6)
- **NEC4 · cl. 61.1** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · timeline: **at the time of giving the instruction** · condition: **giving the instruction**
  > The Project Manager should notify the Contractor of the compensation event at the time of giving the instruction and instruct the Contractor to submit quotations (cl. 61.1)
- **NEC4 · cl. 61.3** — _compensation_event_notification_quotation_assessment_ · obligation: **duty** · party: **Contractor** · timeline: **within 8 weeks of becoming aware** · condition: **If the Project Manager did not formally notify the CE**
  > the Contractor must notify the Project Manager of the compensation event(s) within 8 weeks of becoming aware (cl. 61.3)
- **NEC4 · cl. 61.4** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **Contractor** · timeline: **within a further two weeks** · condition: **If the Project Manager fails to reply to the Contractor's CE notification**
  > If the Project Manager fails to reply to the Contractor's CE notification, the Contractor may notify the Project Manager of this failure. If the Project Manager does not reply within a further two weeks, the Contractor's notification is treated as acceptance
- **NEC4 · cl. 62.3** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **Contractor** · condition: **upon instruction**
  > Contractor (upon instruction) submits a quotation for the compensation event, ensuring all proposed costs and delays are reasonably incurred and demonstrate competent mitigation (cl. 62.3, cl. 63.9).
- **NEC4 · cl. 63.9** — _compensation_event_notification_quotation_assessment_ · obligation: **condition** · party: **Contractor** · timeline: **promptly** · condition: **The assessment of a compensation event**
  > The assessment of a compensation event assumes that the Contractor reacts competently and promptly, and that any time and Defined Cost are reasonably incurred (cl. 63.9)

## Raw Expert Evidence (NotebookLM responses)

The full unmodified responses from the GCC and NEC4 expert agents are reproduced below for traceability.

<details>
<summary>GCC expert response (1 iteration(s), 5,515 chars)</summary>

[CLAUSE REFERENCES] Clause 7(1), Clause 50(1)(a), Clause 50(1)(b)(vii), Clause 50(2), Clause 50(3), Clause 50(4), Clause 60(1), Clause 60(2), Clause 63(a), Clause 64(2), Clause 64(3), Clause 64(4), Special Conditions of Contract (SCC) Clause A4(2).
[GCC POSITION] Requirement for an Instruction and Proceeding with Work The GCC corpus does not use the terms "compensation events" or "quotations"; rather, it addresses these circumstances through "variations", "extensions of time", and "claims"
. A client's change to a floor requirement constitutes a variation, which the Engineer has the power to order
. However, under Clause 60(2), "No variation shall be made by the Contractor without an order in writing by the Engineer"
. If the Contractor proceeds with the varied work without the required written response or variation order, they do so in breach of the contract and without entitlement to payment
Review of Design Submissions and Duty to Respond When the Contractor submits revised design drawings or documents to the Engineer, Clause 7(1) requires that the Engineer "shall give or refuse his approval in writing to such proposals within a reasonable time"
. The standard GCC contains no "deemed acceptance" rules for design submissions, meaning the Contractor must secure explicit written approval
Delayed Response and Entitlement to Relief If the Engineer's lack of response delays the Works, the Contractor is entitled to claim actual "Cost incurred" under Clause 63(a)
. This cost entitlement is strictly conditioned on the Contractor having "specifically applied in writing on a date which... was neither unreasonably distant from nor unreasonably close to the date on which it was necessary for the Contractor to receive the same"
. Furthermore, a delay caused by the Engineer's failure to issue decisions, drawings, or instructions constitutes a disturbance to the progress of the Works, entitling the Contractor to an Extension of Time (EOT) under Clause 50(1)(b)(vii)
Notice Obligations, Mitigation, and Programme Updates The Contractor must issue a written notice of the cause and probable extent of the delay within 28 days of the delay arising (Clause 50(1)(a))
. To claim additional Cost, the Contractor must serve a written notice of intention to claim within 28 days after the happening of the event (Clause 64(2))
. The Contractor is obligated to keep contemporary records to support any claim (Clause 64(3)) and must submit full and detailed particulars of the delay (Clause 50(3)) along with a first interim account for the financial claim (Clause 64(4))
more_horiz
The Contractor has a strict obligation to mitigate the delay, meaning they should proceed with unaffected work where possible
more_horiz
. Under Clause 50(2) and SCC Clause A4(2), the Contractor must "use and continue to use all reasonable endeavours to avoid or reduce the effects of a cause of delay"
. Finally, whenever an EOT is granted, the Contractor must revise the programme accordingly (Clause 50(4))
[PROCEDURAL IMPLICATION]
Contractor specifically applies in writing to the Engineer for the necessary instruction and approval of the revised floor design, doing so on a date neither unreasonably distant nor unreasonably close to when the approval is needed (Clause 63(a))
Engineer gives or refuses approval in writing within a reasonable time (Clause 7(1))
Contractor does not proceed with the varied floor work until an order in writing is issued by the Engineer (Clause 60(2))
If no response is received and delay occurs, Contractor serves written notice to the Engineer of the probable extent of the delay within 28 days (Clause 50(1)(a))
Contractor serves written notice of intention to claim additional Cost due to the lack of instruction within 28 days of the event (Clause 64(2))
Contractor mitigates the delay by proceeding with unaffected work, using all reasonable endeavours to reduce the effects (Clause 50(2) / SCC A4(2))
Contractor maintains contemporary records of the standby time, idle resources, and actual costs incurred due to the delay (Clause 64(3))
Contractor submits full and detailed particulars for the EOT (Clause 50(3)) and a first interim account for the Cost claim (Clause 64(4))
Engineer assesses the EOT (Clause 50(2)) and ascertains the Cost incurred due to the lack of instructions (Clause 63(a))
Contractor revises and submits an updated Works programme upon the granting of any EOT (Clause 50(4))
[HK CONTEXT] A likely practical reason for the lack of response from the Engineer is governed by Works Bureau Technical Circular WB1900 (Appendix A) and the Project Administration Handbook (PAH) Chapter 5
. The Architect/Engineer is constrained from ordering any variation committing the Employer to additional expenditure exceeding HK$300,000 (for Building Works) or HK$1,400,000 (for Civil Works) without first obtaining "confirmation of no objection" from the Employer
more_horiz
Additionally, under WB1900 Appendix B, the Architect/Engineer must report all claims and delays to the Employer and refer the principles underlying their assessment to the Employer for views before reaching a decision
. Consequently, the contract administrator is structurally delayed from formally responding or instructing the change until the Employer has reviewed the proposal and funding implications
What are the rules for valuing varied work under Clause 61?
Explain the Engineer's duty to clarify design ambiguities under Clause 5.
How does the SMM define inclusive items in unit rates?

</details>

<details>
<summary>NEC4 expert response (1 iteration(s), 6,017 chars)</summary>

[CLAUSE REFERENCES] cl. 10.2, cl. 13.1, cl. 13.3, cl. 13.7, cl. 14.3, cl. 15.1, cl. 21.2, cl. 27.3, cl. 32.1, cl. 60.1(1), cl. 60.1(6), cl. 61.1, cl. 61.3, cl. 61.4, cl. 62.3, cl. 63.9
[NEC POSITION] The NEC4 ECC manages changes and unresolved communications through strict procedural timelines and a prospective risk management regime, underpinned by the spirit of mutual trust and co-operation (cl. 10.2)
The Client-Initiated Change: When the Client changes the floor requirement, the Project Manager must give an instruction changing the Scope (cl. 14.3)
. Such an instruction is a compensation event under cl. 60.1(1)
. The Project Manager should notify the Contractor of the compensation event at the time of giving the instruction and instruct the Contractor to submit quotations (cl. 61.1)
Design Submission and Proceeding with Work: To comply with the changed Scope, the Contractor must prepare and submit revised design particulars to the Project Manager for acceptance (cl. 21.2)
. The Contractor must not proceed with the relevant work until the Project Manager has accepted the design (cl. 21.2)
. If the Contractor proceeds without the required response, they do so at their own risk. Meanwhile, the Contractor must continue to Provide the Works for all unaffected areas and obey the Project Manager's instructions (cl. 27.3)
Failure to Reply and Associated Actions: The Project Manager is contractually obligated to reply to the Contractor's communication within the period for reply stated in the Contract Data (cl. 13.3)
more_horiz
. If the Project Manager fails to reply to the design submission within this timeframe, this failure is itself a compensation event under cl. 60.1(6)
more_horiz
To preserve entitlement and manage the delay collaboratively, the Contractor must take the following actions:
Early Warning: The Contractor must give an early warning as soon as they become aware that the lack of response could delay Completion, delay meeting a Key Date, or increase the total of the Prices (cl. 15.1)
more_horiz
Notification of Compensation Event: If the Project Manager did not formally notify the CE for the changed floor requirement (cl. 61.1), or for the failure to reply (cl. 60.1(6)), the Contractor must notify the Project Manager of the compensation event(s) within 8 weeks of becoming aware (cl. 61.3)
more_horiz
. Failure to do so means the Contractor loses entitlement to a change in the Prices or Completion Date
Programme Update: The Contractor must show how they plan to deal with any delays in each revised programme submitted for acceptance (cl. 32.1)
Mitigation: The assessment of a compensation event assumes that the Contractor reacts competently and promptly, and that any time and Defined Cost are reasonably incurred (cl. 63.9)
Deemed Acceptance of CE Notification: If the Project Manager fails to reply to the Contractor's CE notification, the Contractor may notify the Project Manager of this failure. If the Project Manager does not reply within a further two weeks, the Contractor's notification is treated as acceptance by the Project Manager that the event is a compensation event (cl. 61.4)
more_horiz
Records and Communications: All communications must be in a form that can be read, copied, and recorded (cl. 13.1)
. Any notification must be communicated separately from other communications to ensure it is not overlooked (cl. 13.7)
[PROCEDURAL IMPLICATION]
Project Manager gives an instruction changing the Scope regarding the floor requirement (cl. 14.3) and notifies the compensation event (cl. 61.1).
Contractor submits particulars of the revised floor design to the Project Manager for acceptance (cl. 21.2) and does not proceed with the affected work until accepted.
Contractor gives an early warning to the Project Manager stating that the lack of a timely decision on the design could delay Completion or increase the Prices (cl. 15.1).
Contractor (if the Project Manager fails to reply to the design submission within the period for reply) notifies a compensation event for the Project Manager's failure to reply (cl. 60.1(6)) within 8 weeks of becoming aware (cl. 61.3).
Contractor includes the delay and their plans for dealing with it on the next revised programme submitted for acceptance (cl. 32.1).
Contractor (if the Project Manager fails to reply to the CE notification) notifies the Project Manager of the failure (cl. 61.4).
Project Manager must reply within a further two weeks; if they do not, the compensation event is treated as accepted by default (cl. 61.4).
Contractor (upon instruction) submits a quotation for the compensation event, ensuring all proposed costs and delays are reasonably incurred and demonstrate competent mitigation (cl. 62.3, cl. 63.9).
[HK CONTEXT] The DEVB Practice Notes and CEDD Playbook provide specific guidance regarding delayed responses and changes in Hong Kong public works:
Variation vs. Claim Categorisation: In CEDD projects, an instruction to change the Scope under cl. 60.1(1) is administratively categorised strictly as a "Variation", whereas a failure to reply under cl. 60.1(6) is categorised as a "Claim"
Late Acceptance of Design: DEVB PN Section A6.3.1.27 explicitly identifies that "Late acceptance of the Contractor’s design which prohibit the Contractor to proceed with the relevant work will constitute a compensation event" under cl. 60.1(6)
Formal Communication: DEVB PN Section A6.1.1.1(b) warns that while Mobile Instant Messaging (MIM) like WhatsApp is common, the policy intent is not to accept MIM as a valid form of communication. The Contractor must ensure that all critical notifications, submissions, and early warnings regarding the lack of response are made through formal written records to prevent unnecessary disputes
What happens if the Project Manager fails to respond to my revised design particulars?
Does the contract have a deemed acceptance rule for delayed design reviews?
How should I record additional costs while waiting for the floor requirement instruction?

</details>

## SYN-A Chain-of-Thought Reasoning

<details>
<summary>Three-level reasoning trace (L1 → L2 → L3)</summary>

[L1 — Spirit/Philosophy] GCC treats the problem as an Engineer-administered variation/approval and claims situation: the Contractor must obtain written authority, protect time and money by notices, and mitigate while preserving records. In Transaction Cost Economics terms, it relies on formal safeguards and ex post claim substantiation to control opportunism and uncertainty. NEC4 ECC frames the same issue as a managed change and communication-risk process under mutual trust and co-operation (cl. 10.2), using early warning, reply periods, compensation-event notification, quotations, programme updates, and deemed acceptance of CE notification to reduce coordination costs prospectively.

[L2 — Clause-level Comparison] Under GCC, the changed floor requirement is a variation ordered by the Engineer under Clause 60(1), but Clause 60(2) bars the Contractor from making it without a written Engineer’s order. If revised design drawings or documents are submitted, Clause 7(1) requires the Engineer to “give or refuse his approval in writing” within “a reasonable time”; there is no deemed acceptance. If delay results, Clause 50(1)(a) requires notice within 28 days of the delay arising, Clause 50(1)(b)(vii) treats failure to issue decisions, drawings, or instructions as a disturbance supporting EOT, Clause 50(3) requires full and detailed particulars, Clause 50(2) and SCC Clause A4(2) require continuing reasonable endeavours to reduce delay, and Clause 50(4) requires programme revision whenever an EOT is granted. Cost recovery depends on Clause 63(a), including a specific written application made neither unreasonably distant from nor unreasonably close to when the instruction was needed, plus Clause 64(2) notice within 28 days, Clause 64(3) contemporary records, and Clause 64(4) a first interim account. Clause 61 is the GCC valuation route for varied work, while Clause 5 is relevant where the problem is design ambiguity rather than a client change. Under NEC4, the PM must instruct the Scope change under cl. 14.3; that instruction is a CE under cl. 60.1(1), notified with quotation instruction under cl. 61.1. The Contractor submits design particulars under cl. 21.2 and must not proceed until accepted. Communications must be recordable (cl. 13.1), notifications separate (cl. 13.7), and PM replies due within the Contract Data period (cl. 13.3). Failure to reply is itself a CE under cl. 60.1(6), to be notified within 8 weeks under cl. 61.3 if not notified by the PM; failure loses entitlement. If the PM does not reply to the CE notice, cl. 61.4 allows a failure notice and, after a further two weeks without reply, the CE is treated as accepted. The Contractor must early warn as soon as aware under cl. 15.1, continue unaffected work under cl. 27.3, show delay-management plans in revised programmes under cl. 32.1, and submit quotations under cl. 62.3 assessed on competent, prompt, reasonable reaction under cl. 63.9.

[L3 — Practice/Behavioural Implications + GCC-to-NEC Transfer] A GCC-trained Contractor should first separate the affected changed-floor work from unaffected works: under Clause 60(2), do not proceed without written order; under NEC cl. 21.2, do not proceed without PM acceptance. The familiar GCC habit of making a specific written application under Clause 63(a) transfers directly into NEC’s formal, recordable communication discipline under cl. 13.1, cl. 13.3, and cl. 13.7, but the timing changes from protecting a later claim to triggering managed response periods. GCC delay notice practice under Clause 50(1)(a) and cost notice practice under Clause 64(2) transfer to NEC early warning under cl. 15.1 and CE notification under cl. 61.3; the behavioural adjustment is to notify as soon as the risk is known and, for CE entitlement, within 8 weeks of becoming aware. GCC detailed particulars under Clause 50(3), contemporary records under Clause 64(3), and first interim account under Clause 64(4) become NEC quotation and assessment evidence under cl. 62.3 and cl. 63.9; the adjustment is that records must support a prospective quotation showing competent mitigation, not merely a retrospective account. GCC mitigation under Clause 50(2)/SCC A4(2) and programme revision under Clause 50(4) support NEC’s requirements to continue unaffected works under cl. 27.3 and show delay-management plans in revised programmes under cl. 32.1. GCC variation valuation awareness under Clause 61 transfers to NEC CE pricing for cl. 60.1(1) Scope changes, while Clause 5 clarification practice is useful only if the issue is ambiguity rather than a client-driven change.

</details>

---

### Query Plan (QP-A)
- **L1 (spirit):**     How does the contract allocate responsibility for administering client-initiated design changes while preserving cooperation, timely decision-making, and orderly project governance?
- **L2 (clauses):**    What clauses define the Contractor’s duties and rights when a changed floor requirement requires design submission, review, instruction, acceptance, quotation, programme update, notice, or claim, and the Employer’s or Project Manager’s response is delayed or absent?
- **L3 (practice):**   In practice, what steps should the Contractor take to protect time and cost entitlement, avoid proceeding at risk, maintain records, prompt a decision, and keep the works progressing where possible?
- **canonical_topic:** `change_management`

### Anchor Clauses (scenario ground-truth, used for CR)
- **GCC anchors:**  (none)
- **NEC4 anchors:** cl. 13.3, cl. 13.4, cl. 15.1, cl. 21.2, cl. 60.1(6), cl. 61.3, cl. 61.4

*Generated by MAS v2.2 — LangGraph orchestrator (6 agents + 3 rule modules).*