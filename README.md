# Lysosomal Enzyme Sequence Analysis: CTSK (Cathepsin K)

* **Gene Symbol:** CTSK
* **Enzyme Name:** Cathepsin K
* **NCBI Protein Accession:** [NP_000387.1](https://www.ncbi.nlm.nih.gov/protein/NP_000387.1)
* **What it breaks down:** Extracellular matrix proteins, primarily **type I collagen**, type II collagen, and gelatin
* **Normal Cellular Function:** Cathepsin K is a lysosomal cysteine protease predominantly expressed in osteoclasts (bone-resorbing cells). It plays a vital role in bone remodeling, skeletal development, and the breakdown of bone collagen matrices

----
## Figures and Interpretation

### Figure 1: Amino Acid Composition
![Figure 1: Amino Acid Composition](figures/CTSK_amino_acid_composition.png)

If you look at Figure 1, we can get a really clear picture of how all 20 standard amino acids are distributed across Cathepsin K's 329-amino-acid sequence[cite: 2, 3]. The chart maps out each amino acid's one-letter code against its total count, showing right away that certain building blocks—like leucine, lysine, and glycine—show up much more frequently than others. This makes a lot of biological sense when you think about its role as a lysosomal protease, since these hydrophobic and charged residues work together to keep the protein stable and help it function smoothly in a tough, acidic environment[cite: 2].

### Figure 2: Potential N-Glycosylation Motifs
![Figure 2: Potential N-Glycosylation Motifs](figures/CTSK_potential_N_glycosylation.png)

Figure 2 maps out the linear backbone of the Cathepsin K protein to show where potential N-glycosylation sites are hiding. The analysis flags two specific $N-X-S/T$ motifs (excluding proline) along the sequence, which are marked by the orange points. It is definitely worth keeping in mind that these markers are just computational predictions from the code. They show us where sugar chains *could* theoretically attach, but they don't give us hard proof that the protein is actually glycosylated inside a living cell[cite: 3]. Even so, these predicted spots usually play a big role in helping the protein fold right and get routed safely to the lysosome
---

## Laboratory Questions & Answers

1. **What does your enzyme normally break down inside lysosomes?**
   * Cathepsin K normally breaks down structural extracellular matrix proteins inside lysosomes and resorption zones, most notably **type I collagen**, type II collagen, and gelatin[cite: 2].

2. **What is the total length of your protein, and which amino acids are most common?**
   * The precursor protein length comes out to **329 amino acids** (based on RefSeq accession `NP_000387.1`)[cite: 2, 3]. You can see the exact frequency and ranking of the most common amino acids by checking your generated `results/CTSK_amino_acid_counts.csv` file[cite: 3].

3. **How many potential N-glycosylation motifs did you find? Where are they located?**
   * The exact count is safely stored in `results/CTSK_summary.csv`, and the exact positions along the 329-amino-acid chain are laid out in `results/CTSK_motif_positions.csv` (and visualized as those orange dots in Figure 2)[cite: 1, 3].

4. **Why can glycosylation matter for lysosomal proteins? Does finding a motif prove the protein is glycosylated?**
   * Glycosylation is super important for proper protein folding, structural stability, and acting as a scaffold for trafficking tags (like the mannose-6-phosphate tag that guides enzymes right where they need to go)[cite: 3]. That said, just finding an $N-X-S/T$ sequence motif *doesn't* prove the protein is actually glycosylated in real life; it's just a potential spot where it could happen[cite: 3].

5. **What could happen in the cell if your enzyme did not work properly?**
   * If `CTSK` breaks down or stops functioning correctly, osteoclasts can't break down bone collagen the way they're supposed to during remodeling[cite: 2]. This leads to **Pycnodysostosis**, a rare genetic condition marked by dense, brittle bones and skeletal malformations[cite: 3].
