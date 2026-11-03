# Scenario D01: NEC Douglas D01 - Missing first programme and first payment assessment

**Generated:** 2026-07-07 14:59

## Context
The first programme is to be submitted within four weeks of the starting date on an ECC Option C contract for a new asset. No programme is identified in the Contract Data. The Contractor has not submitted a programme within the time allowed, and the Project Manager is assessing the amount due at the first assessment date.

## MAS Query Topic
> Missing first programme and first payment assessment.

Specific questions to address:
Outline the importance of the programme and how its absence affects the Project Manager's assessment of the amount due?

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
 ✅ cl. 31 ✅ cl. 31.3 ✅ cl. 50.5

### LLM-based Semantic Validation

**Track verdict:** ✅ pass
**Severity:** minor

_No substantive issues raised._

## Comparative Synthesis

> **Executive summary** — Standard GCC does not automatically bar first payment for a missing programme, though it weakens progress, EOT and claim assessment; NEC4 retains 25% of PWDD until a compliant first programme is submitted. GCC is Engineer-led and retrospective, while NEC makes the programme a live collaborative cash-flow and entitlement tool.

<details>
<summary><b>1. Spirit / Philosophy</b> — Engineer-led records vs live collaboration.</summary>

GCC: The programme is an important management baseline, but the standard payment mechanism remains Engineer-led, measurement-based, and claims-oriented. The Contractor submits the programme for review, yet Clause 16(2) preserves full Contractor responsibility and the absence of the programme mainly affects proof, progress control, EOT analysis, and claims records. In TCE terms, GCC relies on hierarchical administration and ex post verification to control opportunism and uncertainty.

NEC: NEC4 ECC treats the programme as the cornerstone of transparent project management under mutual trust and co-operation (cl. 10.2). It is not merely a record; it is the common prospective baseline for monitoring progress, assessing compensation events, managing time and cost, and administering payment. In TCE terms, NEC shifts toward relational governance, reducing transaction costs through early information exchange, shared forecasting, and structured collaboration.

</details>

<details>
<summary><b>2. GCC Position (Implementation)</b> — Measured payment, programme as baseline.</summary>

**Implementation flow:**

1. Contractor submits initial programme within 14 days of Tender acceptance (Clause 16(1)) →
2. Engineer reviews sequence, method, timing, realism and sufficiency; may seek written explanation/revision (Clause 16(1)) →
3. Contractor submits interim statement at end of first monthly period (Clause 78(1)) →
4. Engineer values permanent work/materials based on Contract rates and may omit dissatisfied items (Clause 79(1), Clause 79(5)) →
5. Engineer certifies amount due within 21 days of receiving the interim statement (Clause 79(1)) →
6. Engineer assesses progress/EOT/claims on available information if programme is absent (Clause 51(1), Clause 50(1)(b), Clause 50(2), Clause 50(3), Clause 64(3)).

Under Clause 16(1), the Contractor’s first programme is a baseline for planning, progress monitoring, and later time/cost assessment. It must be submitted to the Engineer within 14 days of Tender acceptance and clearly show the “sequence, method and timing” proposed for the Works, including due allowance for Specialist Works and work by utility undertakings; for complex contracts it identifies critical activities and the critical path.

The Engineer reviews the programme for conformity with the Contract’s sequence, method and timing requirements, whether it is “over-optimistic in respect of any critical activity or the Works as a whole”, and whether the information is sufficient for contract management. If over-optimistic or unsatisfactory, the Engineer asks the Contractor to explain the programming basis in writing; if still unconvinced, the Engineer notifies dissatisfaction and requests a revised programme, but must not advise or instruct how it should be revised. Clause 16(2) states that submission or approval does not relieve the Contractor of any duty or responsibility.

For first payment, standard GCC decouples programme submission from valuation of physical work. Clause 78(1) requires the Contractor’s interim statement at the end of the first monthly period, showing the estimated contract value of work done. Clause 79(1) requires the Engineer to evaluate permanent work executed and materials on Site “based on the rates in the Contract” and to certify within 21 days of receiving the interim statement. There is no express automatic withholding, deferral, or reduction solely because the first programme is missing or unaccepted, although Clause 79(5) allows the Engineer to “omit from any certificate the value of any work done, materials supplied or services rendered with which the Engineer may for the time being be dissatisfied”.

Absence of the baseline severely affects administration. Under Clause 51(1), the Engineer uses the programme to judge whether progress is “too slow to ensure completion by the prescribed time”. Clause 50(1)(b) requires EOT analysis of whether delay was detrimental to “critical areas of the works programme”; without it, Clause 50(2) requires reliance on circumstances known at that time and Clause 50(3) limits consideration “only to the extent that the Engineer is able on the information available”. Clause 64(3) recognises the “initial plan working sequence and the subsequent changes due to the delaying event” as essential contemporary records, so no baseline compromises proof of delay and loss.

</details>

<details>
<summary><b>3. NEC4 Position (Implementation)</b> — Programme-linked assessment and retention.</summary>

**Implementation flow:**

1. Contractor submits first programme within the Contract Data period if none is identified (cl. 31.1) →
2. Programme shows all required information, including dates, operations, float, time risk allowances, resources and method statements (cl. 31.2) →
3. Project Manager replies within two weeks: accept or give permitted reasons for non-acceptance (cl. 31.3) →
4. Project Manager assesses amount due at each assessment date (cl. 50.1) →
5. If no compliant first programme is submitted, PM retains one quarter of Price for Work Done to Date until compliant submission (cl. 50.5) →
6. If programme is absent/rejected for stated reason, PM assesses compensation events using own programme assessment (cl. 64.1, cl. 64.2).

The programme is the NEC4 ECC’s core management instrument, providing a dynamic and transparent baseline for progress monitoring, change evaluation, and time/cost management under mutual trust and co-operation (cl. 10.2). The Accepted Programme is defined at cl. 11.2(1) and is essential for prospective compensation-event assessment.

If an Accepted Programme is not identified in the Contract Data, cl. 31.1 requires the Contractor to submit a first programme to the Project Manager for acceptance within the period stated in the Contract Data. cl. 31.2 strictly defines the required content: starting date, access dates, Key Dates, Completion Date, planned Completion, order and timing of operations, float, time risk allowances, health and safety requirements, and method statements identifying principal Equipment and resources.

When the Contractor submits a programme, cl. 31.3 requires the Project Manager to reply within two weeks, either accepting it or giving reasons for non-acceptance. Acceptance may be withheld only for four permitted reasons: the plans are not practicable; the programme does not show the information required by the contract; it does not represent the Contractor’s plans realistically; or it does not comply with the Scope.

For payment, cl. 50.1 requires the Project Manager to assess the amount due at each assessment date. If the Contractor fails to submit the first programme, NEC imposes a specific financial sanction: “one quarter of the Price for Work Done to Date is retained in assessments of the amount due until the Contractor has submitted a first programme to the Project Manager for acceptance showing the information which this contract requires” (cl. 50.5). The PM does not defer the whole payment or value work differently. The 25% retention is triggered by failure to submit a first programme showing the required information, not by lack of formal acceptance. If the programme contains all required details but is rejected because the plans are not practicable under cl. 31.3, the 25% withholding does not apply. Once the Contractor submits or resubmits a compliant first programme, the PM ceases retaining the 25% and releases previously retained funds in the subsequent payment assessment/certificate (cl. 50.5).

If the Contractor has not submitted a required programme, or the latest programme is not accepted for a stated contractual reason, cl. 64.1 removes the Contractor’s right to assess the compensation event. The Project Manager then assesses progress, planned completion and entitlement using the PM’s own assessment of the programme for remaining work (cl. 64.2).

</details>

<details>
<summary><b>4. Behavioural Implications</b> — Retrospective proof vs proactive control.</summary>

Under standard GCC, the Contractor’s immediate behavioural risk is evidential rather than automatic cash-flow forfeiture. The Contractor must submit the Clause 16(1) programme within 14 days of Tender acceptance, but first interim payment still proceeds through a Clause 78(1) statement and Clause 79(1) Engineer certification based on measured work and Contract rates. The incentive is therefore often defensive: preserve programme records, substantiate critical path impact, and protect later EOT and loss claims under Clause 50(1)(b), Clause 50(2), Clause 50(3), and Clause 64(3). The Engineer can still use Clause 79(5) to omit dissatisfied work/services, but the missing programme does not itself create a standard automatic 25% deduction.

Under NEC4, the missing first programme has immediate commercial consequences. The Contractor must submit the programme within the Contract Data period, with all cl. 31.2 content, because the Project Manager assesses payment at each assessment date under cl. 50.1 and must retain one quarter of Price for Work Done to Date under cl. 50.5 until compliant submission. The programme also determines who controls compensation-event assessment: without the required or accepted programme, the Contractor loses the right to assess the CE under cl. 64.1 and the PM uses the PM’s own programme assessment under cl. 64.2. NEC therefore rewards early, transparent, evidence-backed planning and penalises informational opacity.

**Implementation comparison (GCC vs NEC4):**

| Aspect | GCC | NEC4 |
|---|---|---|
| First programme deadline | Within 14 days of Tender acceptance (Clause 16(1)). | Within Contract Data period if none identified (cl. 31.1). |
| Required content | “Sequence, method and timing” of Works (Clause 16(1)). | Dates, operations, float, risk allowances, resources (cl. 31.2). |
| Review response | Engineer seeks explanation/revision if unsatisfactory (Clause 16(1)). | PM replies within two weeks with reasons (cl. 31.3). |
| First payment effect | No automatic standard withholding; measured valuation (Clauses 78(1), 79(1)). | 25% PWDD retained until compliant submission (cl. 50.5). |
| Delay/progress assessment | Critical areas and available information (Clauses 50(1)(b), 50(3)). | PM uses own programme assessment if absent (cl. 64.2). |
| Administrator’s discretion | May omit dissatisfied work/services (Clause 79(5)). | Only permitted rejection reasons for programme (cl. 31.3). |


</details>

<details>
<summary><b>5. GCC Lessons for NEC Adoption</b> — GCC routines become NEC management tools.</summary>

GCC practitioners already know the Clause 16(1) discipline of preparing an early programme showing “sequence, method and timing”. Under NEC, that same skill transfers to cl. 31.1 and cl. 31.2, but the behavioural adjustment is timing and completeness: the first programme must be submitted within the Contract Data period and must contain the NEC-specific dates, float, time risk allowances, health and safety requirements, resources and method statements needed to avoid cl. 50.5 retention.

The GCC habit of supporting delay claims with an “initial plan working sequence and the subsequent changes due to the delaying event” under Clause 64(3) transfers directly into NEC compensation-event administration. The adjustment is purpose: records are not only retrospective claim evidence; they support prospective CE assessment, Accepted Programme logic under cl. 11.2(1), and avoidance of the PM’s unilateral assessment under cl. 64.1 and cl. 64.2.

GCC payment teams familiar with Clause 78(1) interim statements and Clause 79(1) Engineer certification should keep their measurement discipline, but must add an NEC cash-flow control step. Under NEC cl. 50.1 and cl. 50.5, the amount due is still assessed at assessment dates, yet one quarter of Price for Work Done to Date is retained until the first programme showing required information is submitted.

GCC Clause 50(1)(b), Clause 50(2), Clause 50(3), and Clause 51(1) delay/progress analysis also transfers, but NEC requires earlier forecasting. In practice, GCC claim, record, variation, and delay-analysis habits should be used before the assessment date and before compensation-event pricing, not only after dispute positions have formed.

| GCC practice / experience | → How it transfers to NEC implementation |
|---|---|
| Clause 16(1) first programme preparation. | cl. 31.1/cl. 31.2 submission; add NEC dates, float and resources. |
| Clause 64(3) contemporary delay records. | cl. 64.1/cl. 64.2 CE assessment; support prospective entitlement. |
| Clause 78(1)/79(1) interim-payment workflow. | cl. 50.1/cl. 50.5; protect cash flow by compliant programme submission. |
| Clause 50 critical-area EOT analysis. | cl. 11.2(1) Accepted Programme; forecast Completion effects earlier. |
| Clause 51(1) monitoring rate of progress. | cl. 31.2 programme updates; evidence realistic planned Completion. |

</details>

<details>
<summary><b>6. HK-Specific Notes</b> — PAH and DEVB guidance modify practice.</summary>

For GCC Hong Kong practice, the Project Administration Handbook (PAH) Chapter 9 confirms that interim measurements are conducted by recording the quantity of each completed item in the Bills of Quantities into an Interim Payments Record Book. This supports the conclusion that, under standard GCC, interim payment is tied to physical measurement rather than programme acceptance.

For GCC Mega Project Contracts, PAH Chapter 5 Appendix 5.36 prescribes Special Conditions of Contract Clause A1, including SCC Clause A1(2), SCC Clause A1(10), and SCC A1(3) amending Clause 78. The initial Works Programme must be submitted within 7 days of Tender acceptance. The Engineer has exactly 30 days to formally approve or reject the programme with reasons. SCC A1(10) requires a Monthly Progress Report highlighting actual or potential departures from the Works Programme. SCC A1(3) amending Clause 78 creates a strict condition precedent to payment: “As a condition precedent to consideration by the Engineer of any sums due to the Contractor, each of such statement shall be accompanied by the Monthly Progress Report”. On Mega Projects, therefore, absence of an accepted first programme restricts preparation of the required Monthly Progress Report and creates a direct contractual barrier preventing the Engineer from even considering the interim payment application. Works Bureau Technical Circular WB1900 does not address this specific aspect.

For NEC4 ECC Hong Kong Edition practice, the DEVB Practice Notes state that a programme submitted at tender stage is normally not regarded as the Accepted Programme under cl. 11.2(1). DEVB advises that the standard provision in Contract Data Part two identifying a programme is usually deleted, thereby requiring the Contractor to submit the first programme for acceptance after contract commencement.

DEVB guidance also emphasises that the 25% retention under cl. 50.5 applies only to the first programme. Because the sanction significantly affects cash flow, Project Managers must exercise great care and must not accept a substandard programme simply to avoid applying the retention.

DEVB further recommends a pragmatic approach, recognising the difficulty of realistically detailing the entire project early. The Project Manager may conditionally accept a detailed sub-programme for the upcoming 3 to 12 months with minimum required details for later activities. If programmes are repeatedly rejected, the Project Manager is advised to hold joint workshops with the Contractor to ensure mutual understanding of terms such as “float” and “time risk allowances”.

Finally, DEVB identifies the absence of an Accepted Programme as a common pitfall because it forces the Project Manager to assess compensation events under cl. 64.2. DEVB discourages this outcome because it deprives the Contractor of the opportunity to agree the effects of change prospectively and undermines NEC’s collaborative intent. No DEVB Practice Note section numbers, W4 provisions, or Z-clause details were provided in the expert response.

</details>

## Clause Map (extracted by CM-A)

Structured index of every clause cited by the expert agents, with its taxonomy category and a verbatim quote / paraphrase.

- **GCC · Clause 16(1)** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **within 14 days of Tender acceptance** · condition: **Tender acceptance**
  > Contractor submits the initial programme showing sequence, method, and timing within 14 days of Tender acceptance (Clause 16(1))
- **GCC · Clause 16(2)** — _programme_obligations_ · obligation: **condition** · party: **Contractor** · condition: **submission or approval of the programme**
  > Under Clause 16(2), the submission or approval of the programme does not relieve the Contractor of any duty or responsibility under the Contract
- **GCC · Clause 50(1)(b)** — _extension_of_time_ · obligation: **condition** · party: **n/a** · condition: **delay was detrimental to critical areas of the works programme**
  > Evaluating an Extension of Time (EOT) requires assessing whether a delay (e.g., inclement weather) was detrimental to "critical areas of the works programme" under Clause 50(1)(b)
- **GCC · Clause 50(2)** — _extension_of_time_ · obligation: **process** · party: **Engineer** · timeline: **at that time** · condition: **Evaluating an Extension of Time (EOT)**
  > the Engineer evaluates EOT taking into account all circumstances known to him at that time (Clause 50(2))
- **GCC · Clause 50(3)** — _extension_of_time_ · obligation: **process** · party: **Engineer** · condition: **only to the extent that the Engineer is able on the information available**
  > may consider the extension "only to the extent that the Engineer is able on the information available" (Clause 50(3))
- **GCC · Clause 51(1)** — _programme_obligations_ · obligation: **process** · party: **Engineer** · timeline: **by the prescribed time** · condition: **rate of progress is too slow to ensure completion by the prescribed time**
  > The Engineer relies on the programme to determine if the rate of progress is "too slow to ensure completion by the prescribed time" under Clause 51(1)
- **GCC · Clause 64(3)** — _dispute_resolution_ · obligation: **process** · party: **Contractor** · condition: **delaying event**
  > maintaining an "initial plan working sequence and the subsequent changes due to the delaying event" is recognized as an essential contemporary record under Clause 64(3)
- **GCC · Clause 78(1)** — _payment_mechanism_ · obligation: **duty** · party: **Contractor** · timeline: **at the end of the first monthly period**
  > Under Clause 78(1), the Contractor submits an interim statement at the end of the first monthly period showing the estimated contract value of the work done
- **GCC · Clause 79(1)** — _payment_mechanism_ · obligation: **process** · party: **Engineer** · timeline: **within 21 days of receiving the interim statement** · condition: **receiving the interim statement**
  > Engineer certifies the amount due within 21 days of receiving the interim statement (Clause 79(1))
- **GCC · Clause 79(5)** — _payment_mechanism_ · obligation: **right** · party: **Engineer** · condition: **Engineer may for the time being be dissatisfied**
  > the Engineer possesses a broad discretionary power under Clause 79(5) to "omit from any certificate the value of any work done, materials supplied or services rendered with which the Engineer may for the time being be dissatisfied"
- **GCC · Clause 78** — _payment_mechanism_ · obligation: **condition** · party: **n/a** · condition: **condition precedent to payment**
  > SCC A1(3) amending Clause 78 introduces a strict condition precedent to payment: "As a condition precedent to consideration by t
- **NEC4 · cl. 10.2** — _mutual_trust_ · obligation: **duty** · party: **both**
  > The programme is the cornerstone of project management under the NEC4 ECC, providing a dynamic and transparent baseline for monitoring progress, evaluating change, and managing time and cost in a spirit of mutual trust and co-operation (cl. 10.2).
- **NEC4 · cl. 11.2(1)** — _uncategorised_ · obligation: **definition** · party: **n/a**
  > The Accepted Programme (cl. 11.2(1)) is essential for the prospective assessment of compensation events.
- **NEC4 · cl. 31.1** — _programme_obligations_ · obligation: **duty** · party: **Contractor** · timeline: **within the period stated in the Contract Data** · condition: **If an Accepted Programme is not identified in the Contract Data**
  > If an Accepted Programme is not identified in the Contract Data, the Contractor is obligated to submit a first programme to the Project Manager for acceptance within the period stated in the Contract Data (cl. 31.1).
- **NEC4 · cl. 31.2** — _programme_obligations_ · obligation: **duty** · party: **Contractor**
  > The programme must show the starting date, access dates, Key Dates, Completion Date, planned Completion, the order and timing of operations, provisions for float and time risk allowances, health and safety requirements, and method statements identifying the principal Equipment and resources the Contractor plans to use.
- **NEC4 · cl. 31.3** — _programme_obligations_ · obligation: **process** · party: **PM** · timeline: **within two weeks** · condition: **When the Contractor submits a programme**
  > When the Contractor submits a programme, the Project Manager must reply within two weeks, either accepting it or giving reasons for not accepting it (cl. 31.3).
- **NEC4 · cl. 50.1** — _payment_mechanism_ · obligation: **process** · party: **PM** · timeline: **at each assessment date**
  > The Project Manager assesses the amount due at each assessment date (cl. 50.1).
- **NEC4 · cl. 50.5** — _payment_mechanism_ · obligation: **duty** · party: **PM** · timeline: **until the Contractor has submitted a first programme to the Project Manager for acceptance showing the information which this contract requires** · condition: **if the Contractor has failed to submit a first programme showing the information which the contract requires**
  > one quarter of the Price for Work Done to Date is retained in assessments of the amount due until the Contractor has submitted a first programme to the Project Manager for acceptance showing the information which this contract requires
- **NEC4 · cl. 64.1** — _compensation_event_notification_quotation_assessment_ · obligation: **right** · party: **Contractor** · condition: **If the Contractor has not submitted a required programme, or if the Project Manager has not accepted the Contractor's latest programme for a reason stated in the contract**
  > If the Contractor has not submitted a required programme, or if the Project Manager has not accepted the Contractor's latest programme for a reason stated in the contract, the Contractor loses the right to assess the compensation event (cl. 64.1).
- **NEC4 · cl. 64.2** — _compensation_event_notification_quotation_assessment_ · obligation: **process** · party: **PM** · condition: **if the Contractor fails to submit a required programme or the latest programme is rejected for a stated reason**
  > Instead, the Project Manager evaluates progress, planned completion, and entitlement by making their own assessment of the compensation event using their own assessment of the programme for the remaining work (cl. 64.2).

## Raw Expert Evidence (NotebookLM responses)

The full unmodified responses from the GCC and NEC4 expert agents are reproduced below for traceability.

<details>
<summary>GCC expert response (1 iteration(s), 6,639 chars)</summary>

[CLAUSE REFERENCES] Clause 16(1), Clause 16(2), Clause 50(1)(b), Clause 50(2), Clause 50(3), Clause 51(1), Clause 64(3), Clause 78(1), Clause 79(1), Clause 79(5), Special Conditions of Contract (SCC) Clause A1(2), SCC Clause A1(10).
[GCC POSITION] Contractual Importance of the Programme The Contractor's first programme is an essential baseline for project management, planning, and assessing time and cost effects. Under Clause 16(1), the programme must clearly show the "sequence, method and timing" proposed to carry out the Works, including due allowance for carrying out Specialist Works and work by utility undertakings
. For complex contracts, it identifies the critical activities and the critical path
Submission, Required Contents, and Review Process The Contractor is required to submit this initial programme to the Engineer within 14 days of the acceptance of the Tender
. The Engineer analyzes the submitted programme based on three criteria: (a) Conformity with the requirements of the Contract regarding sequence, method, and timing; (b) Whether the programme is "over-optimistic in respect of any critical activity or the Works as a whole"; and (c) Whether the information provided is sufficient for the management of the Contract
. If the programme is deemed over-optimistic or unsatisfactory, the Engineer asks the Contractor to explain the basis of their programming in writing
. If still not convinced, the Engineer informs the Contractor of his dissatisfaction and requests a revised programme, but the Engineer must not advise or instruct the Contractor on how the programme should be revised
. Under Clause 16(2), the submission or approval of the programme does not relieve the Contractor of any duty or responsibility under the Contract
Consequences of Non-Submission on First Payment Assessment The standard GCC corpus decouples the administrative duty of programme submission from the valuation of physical work done, meaning there is no explicit contractual sanction that automatically withholds, defers, or reduces the first payment solely because the first programme is missing or not accepted. Under Clause 78(1), the Contractor submits an interim statement at the end of the first monthly period showing the estimated contract value of the work done
. Under Clause 79(1), the Engineer evaluates the permanent work executed and materials on Site "based on the rates in the Contract" (i.e., the Bills of Quantities)
. However, the Engineer possesses a broad discretionary power under Clause 79(5) to "omit from any certificate the value of any work done, materials supplied or services rendered with which the Engineer may for the time being be dissatisfied"
Evaluating Progress, Delays, and Entitlement Without an Accepted Programme The absence of a baseline programme severely impacts contract administration:
Progress Monitoring: The Engineer relies on the programme to determine if the rate of progress is "too slow to ensure completion by the prescribed time" under Clause 51(1)
. Without it, measuring true delay against a baseline is impossible.
Delay Assessment: Evaluating an Extension of Time (EOT) requires assessing whether a delay (e.g., inclement weather) was detrimental to "critical areas of the works programme" under Clause 50(1)(b)
. Without an accepted programme, the Engineer evaluates EOT taking into account all circumstances known to him at that time (Clause 50(2)) and may consider the extension "only to the extent that the Engineer is able on the information available" (Clause 50(3))
Claims and Supporting Records: To evaluate prolongation or disruption costs, maintaining an "initial plan working sequence and the subsequent changes due to the delaying event" is recognized as an essential contemporary record under Clause 64(3)
. The lack of a baseline fundamentally compromises the Contractor's ability to prove actual delay and loss.
[PROCEDURAL IMPLICATION]
Contractor submits the initial programme showing sequence, method, and timing within 14 days of Tender acceptance (Clause 16(1))
Engineer analyzes the programme for conformity, realism (checking if over-optimistic), and sufficiency of information (Contract Administration guidelines)
Contractor submits an interim statement at the end of the first monthly period detailing the estimated contract value of work done and materials on Site (Clause 78(1))
Engineer measures and values the permanent work executed and materials based strictly on the rates in the Contract, decoupling physical progress valuation from the lack of a programme (Clause 79(1))
Engineer may invoke the power to omit or modify sums for any work or services with which they are dissatisfied due to the administrative failure to submit a compliant programme (Clause 79(5))
Engineer certifies the amount due within 21 days of receiving the interim statement (Clause 79(1))
Engineer evaluates any EOT or claim based only on the limited information available to them, as the absence of a programme prevents proper critical path analysis (Clause 50(3))
[HK CONTEXT] The Project Administration Handbook (PAH) Chapter 9 emphasizes that interim measurements are conducted by recording the quantity of each completed item in the Bills of Quantities into an Interim Payments Record Book, confirming that under the standard GCC, interim payment is tied to physical measurement rather than programme acceptance
However, for "Mega Project Contracts", PAH Chapter 5 (Appendix 5.36) prescribes SCC Clause A1, which fundamentally alters this position by linking payment directly to the programme:
The initial Works Programme must be submitted within 7 days of Tender acceptance
The Engineer has exactly 30 days to formally approve or reject the programme with reasons
SCC A1(10) requires a Monthly Progress Report highlighting actual or potential departures from the Works Programme
Crucially, SCC A1(3) amending Clause 78 introduces a strict condition precedent to payment: "As a condition precedent to consideration by the Engineer of any sums due to the Contractor, each of such statement shall be accompanied by the Monthly Progress Report"
. Therefore, on Mega Projects, the absence of an accepted first programme restricts the formulation of the required Monthly Progress Report, creating a direct contractual barrier that prevents the Engineer from even considering the interim payment application
Works Bureau Technical Circular WB1900 does not address this specific aspect.
What happens if a programme is deemed over-optimistic?
How do Mega Project SCCs change payment condition precedents?
Explain the Engineer's power to omit sums under Clause 79(5).

</details>

<details>
<summary>NEC4 expert response (1 iteration(s), 6,286 chars)</summary>

[CLAUSE REFERENCES] cl. 10.2, cl. 11.2(1), cl. 31.1, cl. 31.2, cl. 31.3, cl. 50.1, cl. 50.5, cl. 64.1, cl. 64.2
[NEC POSITION] The programme is the cornerstone of project management under the NEC4 ECC, providing a dynamic and transparent baseline for monitoring progress, evaluating change, and managing time and cost in a spirit of mutual trust and co-operation (cl. 10.2).
Submission and Content of the First Programme: If an Accepted Programme is not identified in the Contract Data, the Contractor is obligated to submit a first programme to the Project Manager for acceptance within the period stated in the Contract Data (cl. 31.1). The required contents are extensive and strictly defined under cl. 31.2. The programme must show the starting date, access dates, Key Dates, Completion Date, planned Completion, the order and timing of operations, provisions for float and time risk allowances, health and safety requirements, and method statements identifying the principal Equipment and resources the Contractor plans to use.
Acceptance and Review Process: When the Contractor submits a programme, the Project Manager must reply within two weeks, either accepting it or giving reasons for not accepting it (cl. 31.3). The Project Manager may only withhold acceptance for four permitted reasons: the plans are not practicable, the programme does not show the information the contract requires, it does not represent the Contractor's plans realistically, or it does not comply with the Scope.
Consequences of Non-Submission on the First Payment Assessment: The Project Manager assesses the amount due at each assessment date (cl. 50.1). If the Contractor fails to submit the first programme, the contract enforces a specific financial sanction. The Project Manager does not entirely defer or withhold the whole payment, nor do they value the work differently. Instead, "one quarter of the Price for Work Done to Date is retained in assessments of the amount due until the Contractor has submitted a first programme to the Project Manager for acceptance showing the information which this contract requires" (cl. 50.5). Crucially, this 25% retention is linked solely to the submission of a programme containing the required information, not to its formal acceptance. If the Contractor submits a programme showing all required details but the Project Manager rejects it because the plans are not practicable (cl. 31.3), the 25% withholding does not apply.
Evaluating Progress and Entitlement Without an Accepted Programme: The Accepted Programme (cl. 11.2(1)) is essential for the prospective assessment of compensation events. Without it, the collaborative evaluation of time and cost effects breaks down. If the Contractor has not submitted a required programme, or if the Project Manager has not accepted the Contractor's latest programme for a reason stated in the contract, the Contractor loses the right to assess the compensation event (cl. 64.1). Instead, the Project Manager evaluates progress, planned completion, and entitlement by making their own assessment of the compensation event using their own assessment of the programme for the remaining work (cl. 64.2).
[PROCEDURAL IMPLICATION]
Contractor submits a first programme to the Project Manager for acceptance, containing all the information required by cl. 31.2, within the period stated in the Contract Data (cl. 31.1).
Project Manager assesses the submitted programme and replies to the Contractor within two weeks, either accepting it or notifying contractual reasons for non-acceptance (cl. 31.3).
Project Manager assesses the amount due at the first assessment date based on the Price for Work Done to Date (cl. 50.1).
Project Manager retains 25% of the Price for Work Done to Date from the payment assessment if the Contractor has failed to submit a first programme showing the information which the contract requires (cl. 50.5).
Contractor submits (or resubmits) the first programme containing the required information to remedy the deficiency (cl. 50.5).
Project Manager assesses the next amount due and ceases to retain the 25% amount (releasing previously retained funds) in the subsequent payment certificate once the compliant submission is made (cl. 50.5).
Project Manager makes their own assessment of any compensation events, using their own assessment of the programme for the remaining work, if the Contractor fails to submit a required programme or the latest programme is rejected for a stated reason (cl. 64.1, cl. 64.2).
[HK CONTEXT] The DEVB Practice Notes provide explicit guidance on managing the first programme in Hong Kong public works:
Tender Programmes: A programme submitted at the tender stage is normally not regarded as the Accepted Programme under cl. 11.2(1)
. DEVB advises that the standard provision in Contract Data Part two identifying a programme is usually deleted, thereby mandating the Contractor to submit the first programme for acceptance after contract commencement
The 25% Retention Penalty: DEVB emphasizes that the 25% retention under cl. 50.5 applies only to the first programme
. Because it significantly impacts cash flow, Project Managers are warned to exercise great care and must not accept a substandard programme simply to avoid applying the retention
Pragmatic Approach: Recognizing the difficulty of detailing the entire project realistically early on, DEVB advises taking a "pragmatic approach"
. The Project Manager may conditionally accept a detailed sub-programme for the upcoming 3 to 12 months with minimum required details for later activities
. If programmes are repeatedly rejected, the Project Manager is advised to hold joint workshops with the Contractor to ensure mutual understanding of terms like "float" and "time risk allowances"
Avoiding PM's Own Assessment: DEVB identifies the absence of an Accepted Programme as a "common pitfall" that forces the Project Manager to assess compensation events under cl. 64.2
. This is heavily discouraged as it deprives the Contractor of the opportunity to agree on the effects of a change prospectively, defeating the collaborative intent of the NEC
What does a Contractor's share mean in Option C?
How do X12 partnering options change the contract?
What is the role of terminal float for contractors?

</details>

## SYN-A Chain-of-Thought Reasoning

<details>
<summary>Three-level reasoning trace (L1 → L2 → L3)</summary>

[L1 — Spirit/Philosophy]
GCC treats the first programme as an important Engineer-reviewed management baseline, but payment administration remains primarily measurement-and-certification based unless Hong Kong Mega Project SCC A1 applies. In Transaction Cost Economics terms, the standard form relies more on hierarchical/Engineer-led monitoring, contemporary records, and retrospective claims discipline than on an integrated relational payment lever. NEC4 ECC treats the programme as a central relational governance instrument: transparency, forecasting, compensation-event pricing, and payment discipline are tied to the same live management tool under cl. 10.2 mutual trust and co-operation.

[L2 — Clause-level Comparison]
Under GCC Clause 16(1), the Contractor submits the initial programme within 14 days of Tender acceptance, showing “sequence, method and timing”; Clause 16(2) prevents submission or approval from relieving contractual responsibility. The programme then supports Clause 51(1) progress control, Clause 50(1)(b), Clause 50(2), and Clause 50(3) EOT assessment, and Clause 64(3) claims records. For first payment, however, Clause 78(1) requires an interim statement at the end of the first monthly period and Clause 79(1) requires the Engineer to certify within 21 days; Clause 79(5) permits omission of dissatisfied work/services, but standard GCC has no automatic programme-linked first-payment sanction. NEC4 is more direct: cl. 31.1 requires the first programme within the Contract Data period; cl. 31.2 defines its contents; cl. 31.3 requires the PM’s reply within two weeks. cl. 50.1 requires amount-due assessment at each assessment date, and cl. 50.5 mandates retention of one quarter of Price for Work Done to Date until a compliant first programme is submitted. cl. 64.1 and cl. 64.2 also shift compensation-event assessment to the PM if the required programme is absent or not accepted for a stated reason.

[L3 — Practice/Behavioural Implications + GCC-to-NEC Transfer]
For Hong Kong GCC practitioners, the familiar Clause 16(1) programme workflow transfers directly into NEC cl. 31.1 and cl. 31.2, but timing and purpose change: the programme is no longer only an Engineer-reviewed planning baseline supporting later EOT/claims analysis; it is also a condition affecting cash flow under cl. 50.5 and the Contractor’s ability to assess compensation events under cl. 64.1. GCC Clause 64(3) habits—preserving the “initial plan working sequence and the subsequent changes due to the delaying event”—become NEC evidence for Accepted Programme updates, quotations, and prospective CE assessment. GCC Clause 78(1)/79(1) payment routines based on measured work remain useful, but NEC requires the Contractor to protect payment by submitting a compliant first programme before or by the relevant assessment cycle. GCC Clause 50(1)(b), Clause 50(2), and Clause 50(3) critical-path delay analysis transfers to NEC programme-based forecasting, but the behavioural adjustment is to use the programme earlier, collaboratively, and prospectively rather than retrospectively after delay has crystallised.

</details>

---

### Query Plan (QP-A)
- **L1 (spirit):**     How does the contract’s governance philosophy treat the programme as a core management tool for transparency, collaboration, and orderly payment administration?
- **L2 (clauses):**    What clauses require submission of the first programme, define its required content and acceptance process, and regulate how the amount due is assessed when that programme is missing?
- **L3 (practice):**   In practice, how does failure to provide the first programme affect the contract administrator’s ability to assess progress, forecast completion, evaluate entitlement, and certify or assess payment?
- **canonical_topic:** `programme_obligations`

### Anchor Clauses (scenario ground-truth, used for CR)
- **GCC anchors:**  (none)
- **NEC4 anchors:** cl. 31, cl. 31.3, cl. 50.5

*Generated by MAS v2.2 — LangGraph orchestrator (6 agents + 3 rule modules).*