# Lysosomal Enzyme Sequence Analysis: CTSK (Cathepsin K)

* **Student Name:** Gregorio, Richelle
* **Gene Symbol:** CTSK
* **Enzyme Name:** Cathepsin K
* **NCBI Protein Accession:** [NP_000387.1](https://www.ncbi.nlm.nih.gov/protein/NP_000387.1)
* **What it breaks down:** Extracellular matrix proteins, primarily **type I collagen**, type II collagen, and gelatin
* **Normal Cellular Function:** Cathepsin K is a lysosomal cysteine protease predominantly expressed in osteoclasts (bone-resorbing cells). It plays a vital role in bone remodeling, skeletal development, and the breakdown of bone collagen matrices

----
## Figures and Interpretation

![Figure 1: Amino Acid Composition](Figures/CTSK_amino_acid_composition.png)
*Figure 1: Amino Acid Composition Of CTSK Gene*

In Figure 1, we can observe the overall amino acid composition of the Cathepsin K protein across its 329-amino-acid sequence. The chart clearly maps out the frequency of all 20 standard amino acids, showing that certain residues—such as leucine, lysine, and glycine appear much more prominently than others. This distribution makes a lot of biological sense when we consider the protein's role as a lysosomal protease, since hydrophobic and charged residues work together to maintain structural stability and support its function within an acidic environment

----

![Figure 2: Potential N-Glycosylation Motifs](Figures/CTSK_potential_N_glycosylation.png)
*Figure 2: Potential N-Glycosylation Motifs Of CTSK Gene*

Figure 2 presents a linear sequence map displaying the predicted locations of potential N-glycosylation sites along the Cathepsin K protein backbone. The horizontal axis represents the amino acid positions across the complete 329-residue polypeptide chain. The computational analysis identified two potential N-glycosylation motifs adhering to the consensus sequence $N-X-S/T$ (where $X$ excludes proline), which are denoted by the orange markers. These indicators represent sequence-based computational predictions of putative carbohydrate attachment sites rather than empirical verification of in enzymatic activity. However, physiological glycosylation at conserved motifs frequently contributes to proper protein folding, structural stability, and appropriate lysosomal trafficking.

----

## Questions & Answers

1. **What does your enzyme normally break down inside lysosomes?**
   * Cathepsin K normally breaks down structural extracellular matrix proteins inside lysosomes and resorption lacunae, most notably **type I collagen**, type II collagen, and gelatin.

2. **What is the total length of your protein, and which amino acids are most common?**
   * The precursor protein length is **329 amino acids** (based on RefSeq accession `NP_000387.1`) and the most common amino acid is the *Glycine* where the exact frequency and ranking of the most common amino acids can be verified directly in the generated `results/CTSK_amino_acid_counts.csv` file.

3. **How many potential N-glycosylation motifs did you find? Where are they located?**
   * The RStudio analysis identified 2 potential N-glycosylation motifs in the CTSK protein (accession NP_000387.1), which contains 329 amino acids. The motifs were located at amino acid position 103 (NDT) and position 161 (NLS). These are potential N-glycosylation motifs identified through sequence analysis.

4. **Why can glycosylation matter for lysosomal proteins? Does finding a motif prove the protein is glycosylated?**
   * Glycosylation is crucial for proper protein folding, structural stability, and acting as a scaffold for trafficking tags (such as the mannose-6-phosphate tag required to target and route enzymes into lysosomes)[cite: 3]. However, finding an $N-X-S/T$ sequence motif *does not* prove the protein is actually glycosylated *in vivo*; it only indicates a *potential* physical site where a glycan could be attached.

5. **What could happen in the cell if your enzyme did not work properly?**
   * If `CTSK` fails to function properly, osteoclasts cannot effectively degrade the bone collagen matrix during bone remodeling[cite: 2]. This results in **Pycnodysostosis**, a rare lysosomal storage and bone disorder characterized by dense, brittle bones (osteosclerosis).
  
----

## References

* **NCBI Protein Database:** [Human Cathepsin K (CTSK) RefSeq Record - NP_000387.1](https://www.ncbi.nlm.nih.gov/protein/NP_000387.1)
* **NCBI Gene Database:** [Human CTSK Gene Entry - Gene ID: 1513](https://www.ncbi.nlm.nih.gov/gene/1513)
