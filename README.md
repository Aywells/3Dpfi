# 3Dpfi
# Data for "Unavailability of experimental 3D structural data on protein folding dynamics and necessity for a new generation of structure prediction methods in this context"

**Aydin Wells¹**, **Khalique Newaz²**, **Jennifer Morones¹**, **Jianlin Cheng³**, **Tijana Milenković¹\***

¹ Department of Computer Science and Engineering, University of Notre Dame, USA  
² Institute for Computational Systems Biology, University of Hamburg, Germany  
³ Department of Electrical Engineering and Computer Science, University of Missouri, Columbia, USA  
\* Corresponding author: tmilenko@nd.edu

---

## 1. Studies with experimentally determined 3D structures of protein folding intermediates

This section lists studies reporting experimentally determined post-translational or co-translational folding intermediates, along with the PDB IDs used in our analyses.

### Post-translational intermediates (Section 2.1 in the main paper)

- **Neudecker et al. (2012)** — Fyn SH3 domain  
  https://www.science.org/doi/full/10.1126/science.1214203  
  - PDB:  
    - https://www.rcsb.org/structure/2L2P (intermediate 1)  
    - https://www.rcsb.org/structure/2L25 (intermediate 2)

- **Zhou et al. (2008)** — RNase H  
  https://www.sciencedirect.com/science/article/pii/S002228360801190X  
  - PDB:  
    - https://www.rcsb.org/structure/2RPI (intermediate 1)  
    - https://www.rcsb.org/structure/1RIL (intermediate 2)

### Co-translational intermediates (Section 2.2 in the main paper)

- **Agirrezabala et al. (2022)** — CspA  
  https://pubmed.ncbi.nlm.nih.gov/34994471/  
  - PDB:  
    - 7NWW: https://www.rcsb.org/structure/7NWW  
    - 7OIF: https://www.rcsb.org/structure/7OIF  
    - 7OIG: https://www.rcsb.org/structure/7OIG  
    - 7OT5: https://www.rcsb.org/structure/7OT5  
    - 7OII: https://www.rcsb.org/structure/7OII  
    - 1MJC: https://www.rcsb.org/structure/1MJC

- **Hanazono et al. (2018)** — Lambda repressor  
  https://pmc.ncbi.nlm.nih.gov/articles/PMC6070647/  
  - PDB:  
    - https://www.rcsb.org/structure/5ZCA  
    - https://www.rcsb.org/structure/3WOA  
    - https://www.rcsb.org/structure/1LMB

- **Hanazono et al. (2016)** — WW-domain  
  https://www.nature.com/articles/srep34654  
  - PDB:  
    - https://www.rcsb.org/structure/5B3X  
    - https://www.rcsb.org/structure/5BMY  
    - https://www.rcsb.org/structure/5B3Y  
    - https://www.rcsb.org/structure/5B3Z

- **Cabrita et al. (2016)** — FLN5+FLN6  
  https://pubmed.ncbi.nlm.nih.gov/26926436/  
  - PDB:  
    - https://www.rcsb.org/structure/6G4A  
    - https://www.rcsb.org/structure/2N62

---

## 2. Computational studies on 3D prediction of protein folding intermediates

These are the computational approaches discussed in our paper:

- Outeiral et al. (2023):  
  https://academic.oup.com/bioinformatics/article/38/7/1881/6517779#394300307

- Huang et al. (2023):  
  https://pmc.ncbi.nlm.nih.gov/articles/PMC10513300/

- Wang et al. (2025):  
  https://www.biorxiv.org/content/10.1101/2025.04.09.648002v1

---

## 3. External software used in our analyses

- TM-score web server:  
  https://zhanggroup.org/TM-score/

- AlphaFold2 (ColabFold):  
  https://github.com/sokrypton/ColabFold

- "Proxy" intermediates (DynamicPSN):  
  https://github.com/KhaliqueN/DynamicPSN  
  - Original paper: Newaz et al. (2022):  
    https://pubmed.ncbi.nlm.nih.gov/35441395/

---

## 4. Download our predicted 3D structures

Download the AlphaFold2-predicted co-translational intermediates (all four proteins) and the “proxy” intermediates (two proteins):

**Download:** `our_predicted_structures.zip`
