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

## Candidate ligand and evidence for sender-cell expression

| Item | Information |
|---|---|
| Sender cell | BAFF-producing immune cell (e.g., monocyte) |
| Candidate ligand | BAFF |
| Candidate gene | `TNFSF13B` |
| Protein name | B-cell activating factor (BAFF) |
| Expression evidence | The Human Protein Atlas provides TNFSF13B expression data for monocytes, supporting the choice of a BAFF-producing immune cell as the sender. |
| Functional evidence | BAFF is a cytokine involved in B-cell and T-cell function and humoral immunity. |
| UniProt | https://www.uniprot.org/uniprotkb/Q9Y275/entry |

## Receptor and receiver cell with supporting evidence

| Item | Information |
|---|---|
| Ligand | BAFF (B-cell activating factor), encoded by *TNFSF13B* |
| Receptor | BAFF-R (BAFF receptor/CD268), encoded by *TNFRSF13C* |
| Receiver cell | B cell |
| Signaling context | Immune signaling and B-cell homeostasis; BAFF–BAFF-R signaling promotes the survival, maturation, and maintenance of mature B cells and supports B-cell responses. |
| Supporting source Omnipath | https://explore.omnipathdb.org/search?q=TNFSF13B%2C&tab=intercell&species=9606&parents=ligand https://explore.omnipathdb.org/search?q=TNFSF13B%2C+TNFRSF13C%2C&tab=intercell&species=9606&parents=receptor |
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


## Questions and Answers

**1. What sender cell did you choose, and in what tissue or biological context does it act?**

I chose a **BAFF-producing immune cell, such as a monocyte**, as the sender cell. It acts in the **immune system**, where it can send signals that help regulate B-cell survival and function.

---

**2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?**

The signaling molecule I identified is **BAFF (`TNFSF13B`)**. The Human Protein Atlas shows `TNFSF13B` expression in immune cells, including monocytes. This supports the idea that the sender cell can produce BAFF.

---

**3. What receptor receives the signal, and which receiver cell did you select?**

The receptor is **BAFF-R (`TNFRSF13C`)**, and I selected the **B cell** as the receiver. The Human Protein Atlas shows that `TNFRSF13C` is expressed in B-cell populations.

---

**4. What type of cell-to-cell signaling is represented?**

The signaling type is **paracrine signaling** because BAFF is produced by one cell and acts on another nearby cell, which is the B cell.

---

**5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.**

The most relevant proteins are **TNFSF13B, TNFRSF13C, TNFRSF13B, and TNFRSF17**. `TNFSF13B` is BAFF, while `TNFRSF13C` is BAFF-R, which is the main receptor in our model. `TNFRSF13B` and `TNFRSF17` are also related to BAFF signaling and B-cell functions.

---

**6. What enriched pathway or biological process is consistent with your proposed mechanism?**

The STRING results showed processes related to **TNF-mediated signaling, B-cell proliferation, lymphocyte homeostasis, and B-cell costimulation**. These processes fit our proposed BAFF signaling because BAFF helps B cells survive and function properly.

---

**7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?**

IntAct showed a **direct interaction between BAFF (`TNFSF13B`) and BAFF-R (`TNFRSF13C`)**. The record is **EBI-64072608**. The interaction was detected using a **solid phase assay** under **in vitro conditions** in humans, and the result was positive.

---

**8. Which parts of your final model are strongly supported, and which parts remain an inference?**

The **BAFF–BAFF-R interaction** is strongly supported by the IntAct experimental evidence. The expression of BAFF in immune cells and BAFF-R in B cells is also supported by the Human Protein Atlas. The STRING results support their connection to B-cell-related functions.

The **TRAF3 → NFKB2 → RELB** part of the diagram is a simplified representation of the downstream pathway, so this part is more of an inference for our model.

---

**9. What cellular response is expected in the receiver cell, and why?**

The expected response is **B-cell survival, activation, and proliferation**. When BAFF binds to BAFF-R, it sends a signal into the B cell that can affect gene expression. This helps the B cell survive and maintain its normal function.

## References and database links

HPA :  https://www.proteinatlas.org/ENSG00000159958-TNFRSF13C

https://www.proteinatlas.org/ENSG00000102524-TNFSF13B

STRING: https://m.string-db.org/cgi/network/bUIGLXy5mzOc/bdEZgp9HUIFH

IntAct: https://www.ebi.ac.uk/intact/details/interaction/EBI-64072608

OmniPath: https://explore.omnipathdb.org/search?q=TNFSF13B%2C+TNFRSF13C%2C&tab=intercell&species=9606&parents=receptor%2Cligand
