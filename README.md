# Reader-Centric Requirements Engineering (RCRE) - Supplementary Materials
This repository provides the supplementary materials for the IST Short Communications submission.
The materials are intended to support reuse and reproducibility of the proposed framework in industrial documentation workflows.

# How to use (practical workflow)
## Step 1 — Define the target readers and workflow
Identify the reader roles that must consume the requirements (e.g., designers, supplier developers, service engineers) and the actual artifacts they can access in routine work.

## Step 2 — Apply the RP checklist
Use the RP checklist to review whether the requirement set includes the minimum information required for consumption.  
- SHALL items must be satisfied to count as RP-satisfied.  
- SHOULD/MAY items improve clarity and usefulness but do not necessarily gate satisfaction.

### RP checklist
- RP consists of **11 evaluation items** with SHALL/SHOULD/MAY criteria.
- The full RP checklist and ECU-level decision rule are provided in: `RCRE_Checklist_v01.pdf`.

### Assessment scope
- ECU-level fulfillment was assessed via **full coverage review** across all ECUs in the study.

### Improvement rounds
- Round 1: Apply the RP checklist to identify missing/underspecified items and rewrite representative requirements with explicit meaning + local mappings.
- Round 2: Re-audit with the same checklist to address remaining gaps and reduce interpretation steps.

## Step 3 — Rewrite using the templates
If an RP item is missing or unclear, rewrite the requirement using the minimal templates:
- state operational meaning in reader-accessible language
- provide identifier mappings locally (instead of “search the DBC/document”)
- place next-action hooks near the requirement

# ECU-level RP satisfaction
The paper reports ECU-level RP satisfaction, assessed via full coverage review:
- An ECU is counted as RP-satisfied if its diagnostic requirement set satisfies all RP items at the level required by the SHALL criteria.
- Item-level satisfaction may be supported by an explicitly provided local mapping/link that is practical to use in routine work.
- If an item is not applicable, it must be explicitly stated (e.g., “No warning lamp”) to avoid implicit omissions.

# Data availability and anonymization
This repository does not include proprietary diagnostic requirement documents, raw DBC files, or any industrial artifacts that would enable identification of specific products, projects, or organizations beyond what is publicly disclosed in the paper.
Before/after examples are anonymized and simplified to preserve confidentiality while illustrating the framework.
