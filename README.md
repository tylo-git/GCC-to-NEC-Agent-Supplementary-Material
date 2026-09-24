# Supplementary Material — NEC vs GCC Comparative Contract Analytics

Supplementary material for the manuscript *"From Adversarial to Collaborative: AI Agent–Enabled Comparative Contract Analytics between NEC and GCC"* (submitted to *Automation in Construction*).

This repository is provided for reviewers. It contains the full system outputs, clause taxonomies and detailed evaluation tables that support the results reported in the paper but could not be included in the main text due to length.

## Directory

```
.
├── README.md
├── taxonomy_gcc.md        # Clause taxonomy of HK GCC (Civil Engineering Works, 1999 Edition)
├── taxonomy_nec.md        # Clause taxonomy of NEC4 ECC Hong Kong Edition (July 2023)
├── Appendix_5_Clause_Level_Metrics_with_Cross_LLM_Agreement_and_Pairwise_FINAL.docx
│                          # Appendix 5: Table A5 clause-level metrics across scenarios and LLMs;
│                          # Table A6 cross-LLM section agreement; Table A7 cross-LLM pairwise agreement
├── Appendix_ContractLens_Comparative_Synthesis_Report_TableFrame.docx
│                          # Table frame of the ContractLens MAS comparative synthesis report
└── ABC_D1-10/             # Full MAS outputs for all 13 test scenarios (.md and .pdf of each)
    ├── scenario_A         # Unforeseen physical conditions — remnant piles
    ├── scenario_B         # Instructed design change mid-construction
    ├── scenario_C         # Programme non-compliance without early warning
    ├── scenario_D01       # Missing first programme and first payment assessment
    ├── scenario_D02       # Submitted programme without time risk allowance
    ├── scenario_D03       # Coordination with a separately engaged specialist contractor
    ├── scenario_D04       # Compensation event assessment when the latest programme is not accepted
    ├── scenario_D05       # Broad Activity Schedule and first payment assessment under Options A and C
    ├── scenario_D06       # Revised Activity Schedule after first programme submission
    ├── scenario_D07       # Alternative lift in an accepted revised Activity Schedule
    ├── scenario_D08       # No response to design submission after Client changes floor requirement
    ├── scenario_D09       # Blue paint Defect despite accepted design and programme
    └── scenario_D10       # Security fencing omitted from the Activity Schedule and programme
```

## Notes

- **Taxonomies** (`taxonomy_*.md`) are the rule-based Clause Taxonomy Engine files used by the Clause Mapper agent. They map each GCC / NEC4 clause to canonical categories (payment, change, time, disputes, etc.) and give source page references.
- **Scenario outputs** (`ABC_D1-10/`) are the comparative reports produced by the multi-agent system for each scenario, with GCC and NEC positions and clause references. The `.md` and `.pdf` files have the same content.
- **Appendix 5** gives the detailed evaluation results summarised in the evaluation section of the paper.
- Contract texts themselves (GCC 1999, NEC4 HK Edition) are not included, as they are copyrighted documents.
