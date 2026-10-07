# Cell-to-Cell-Communication

## BAFF–BAFF-R Signaling Between Immune Cells and B Cells

## Biological question:

How does BAFF signaling through BAFF-R affect the survival, activation, and proliferation of B cells?

## Chosen sender cell and biological context

| Item | Answer |
|---|---|
| **Sender cell** | BAFF-producing immune cell (e.g., monocyte) |
| **Biological context** | Immune-cell communication |
| **Main purpose** | Provides signals that support B-cell survival and activation |

## Receptor and receiver cell with supporting evidence

| Item | Information |
|---|---|
| Ligand | BAFF (B-cell activating factor), encoded by `TNFSF13B` |
| Receptor | BAFF-R (BAFF receptor/CD268), encoded by `TNFRSF13C` |
| Receiver cell | B cell |
| Signaling context | BAFF–BAFF-R signaling is involved in B-cell survival, maturation, maintenance, and immune responses. |
| Expression evidence | The Human Protein Atlas shows TNFRSF13C enrichment in B-cell populations, including naive and memory B cells. |
| Supporting source | https://www.proteinatlas.org/ENSG00000159958-TNFRSF13C |
| HPA | https://www.proteinatlas.org/ENSG00000159958-TNFRSF13C https://www.proteinatlas.org/ENSG00000102524-TNFSF13B |
| OmniPath | https://explore.omnipathdb.org/search?q=TNFSF13B%2C+TNFRSF13C%2C&tab=intercell&species=9606&parents=receptor%2Cligand |

## Receptor and receiver cell with supporting evidence

| Item | Information |
|---|---|
| Ligand | BAFF (B-cell activating factor), encoded by *TNFSF13B* |
| Receptor | BAFF-R (BAFF receptor/CD268), encoded by *TNFRSF13C* |
| Receiver cell | B cell |
| Signaling context | Immune signaling and B-cell homeostasis; BAFF–BAFF-R signaling promotes the survival, maturation, and maintenance of mature B cells and supports B-cell responses. |
| Supporting source Omnipath https://explore.omnipathdb.org/search?q=TNFSF13B%2C&tab=intercell&species=9606&parents=ligand https://explore.omnipathdb.org/search?q=TNFSF13B%2C+TNFRSF13C%2C&tab=intercell&species=9606&parents=receptor |
| Supporting source Uniprot | https://www.uniprot.org/uniprotkb/Q96RJ3/entry  |


## OmniPath Findings

| Component | Gene | Role |
|---|---|---|
| BAFF | `TNFSF13B` | Ligand/signal |
| BAFF-R | `TNFRSF13C` | Receptor on B cells |


## STRING Network Interpretation

| STRING Result | Value |
|---|---:|
| **Number of proteins** | 11 |
| **Observed edges** | 31 |
| **Expected edges** | 12 |
| **PPI enrichment p-value** | 1.78 × 10⁻⁶ |
| **Average node degree** | 5.64 |
| **Local clustering coefficient** | 0.93 |

The STRING results show that the 11 proteins are strongly connected, with 31 observed interactions compared with only 12 expected interactions. The very small p-value of 1.78 × 10⁻⁶ means that these proteins are more connected than would normally be expected by chance. The enriched processes are also related to the BAFF signaling system. These include TNF-mediated signaling, B-cell proliferation, lymphocyte homeostasis, and B-cell costimulation. This makes sense because BAFF and BAFF-R are important for B-cell survival and immune responses. The STRING results support our BAFF (TNFSF13B) → BAFF-R (TNFRSF13C) pathway and show that it is connected to important B-cell functions. However, STRING only shows that the proteins are related or connected in the network, so it does not prove that all of them directly interact with each other.

| Item | Information |
|---|---|
| Enriched process | Regulation of B-cell proliferation, lymphocyte homeostasis, B-cell costimulation, and TNF receptor-mediated signaling |
| STRING evidence | 11 proteins; 31 observed edges; PPI enrichment p-value = 1.78 × 10⁻⁶ |
| Protein 1 | TNFRSF13C (BAFF-R) – receptor for BAFF that promotes mature B-cell survival |
| Protein 2 | TNFSF13B (BAFF) – ligand for BAFF-R and other BAFF receptors; supports B-cell survival and activation |
| Protein 3 | TNFRSF13B (TACI) – BAFF/APRIL receptor involved in B-cell activation and antibody responses |
| Protein 4 | TNFRSF17 (BCMA) – receptor for BAFF/APRIL involved in B-cell and plasma-cell survival |

## IntAct validation

| Item | Information |
|---|---|
| Protein pair | TNFSF13B (BAFF) – TNFRSF13C (BAFF-R) |
| IntAct record | EBI-64072608 |
| Interaction type | Direct interaction |
| Experimental detection method | Solid phase assay |
| Organism | Homo sapiens (human) |
| Host organism | In vitro |
| Positive interaction | Yes |
| Publication | Shilts et al. (2022), "A physical wiring diagram for the human immune system" |
| Journal | Nature |
| Publication reference | PMID: 35922511; DOI: 10.1038/s41586-022-05028-x |
| Evidence conclusion | Supports a direct physical interaction between BAFF (TNFSF13B) and BAFF-R (TNFRSF13C). |

I selected BAFF (TNFSF13B) and BAFF-R (TNFRSF13C) because they are part of the proposed BAFF signaling system. The pair has a curated record in IntAct. The interaction was tested using a solid phase assay in humans under in vitro conditions. Since IntAct lists it as a direct interaction with a positive experimental result, the evidence supports that BAFF can physically interact with BAFF-R. This supports the proposed BAFF → BAFF-R signaling pathway in B cells. Since a useful experimental record was found for this pair, there is no need to test another pair.

## Final model and 150–250 word interpretation

<img width="640" height="387" alt="Screenshot 2026-10-07 114239" src="https://github.com/user-attachments/assets/99e1b9dd-d3fc-49de-9d9c-165265fbb86f" />

This model shows how BAFF signaling allows communication between a sender cell and a B cell. The sender cell produces BAFF (TNFSF13B), which is released into the extracellular space. BAFF then moves toward the B cell and binds to BAFF-R (TNFRSF13C) on the surface of the receiver cell. After BAFF binds to BAFF-R, the signal is passed inside the B cell through TRAF3, followed by NFKB2 and RELB. These components help control gene expression inside the B cell. The changes in gene expression can support important B-cell functions such as survival, activation, and proliferation. This pathway is an example of cell-to-cell communication because a signal produced by one cell affects the activity of another cell. The BAFF–BAFF-R interaction allows the B cell to receive signals that help maintain its survival and function. The pathway also shows how an outside signal can be passed through several intracellular components before producing a response in the cell.

## References and database links

HPA :  https://www.proteinatlas.org/ENSG00000159958-TNFRSF13C

https://www.proteinatlas.org/ENSG00000102524-TNFSF13B

STRING: https://m.string-db.org/cgi/network/bUIGLXy5mzOc/bdEZgp9HUIFH

IntAct: https://www.ebi.ac.uk/intact/details/interaction/EBI-64072608

OmniPath: https://explore.omnipathdb.org/search?q=TNFSF13B%2C+TNFRSF13C%2C&tab=intercell&species=9606&parents=receptor%2Cligand
