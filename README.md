# Exploring Lysosomal Enzymes Using NCBI and R

## Protein overview
* **Gene Symbol:** GLB1
* **Enzyme Name:** Galactosidase beta 1
* **NCBI Protein Record:** [NP_000395.3](https://www.ncbi.nlm.nih.gov/protein/NP_000395.3)
* **Brief Function Description:** Galactosidase beta 1 is a lysosomal enzyme responsible for hydrolyzing terminal beta-galactose residues in beta-galactosides, including GM1 ganglioside and keratan sulfate, playing an essential role in the degradation of complex carbohydrates, glycolipids, and glycoproteins.

## Figures and Descriptions

### Amino Acid Composition
* **Figure 1:** [View Amino Acid Composition Plot](figures/GLB1_amino_acid_composition.png)
* **Description:** A bar plot illustrating the distribution and frequency of each amino acid (represented by one-letter codes) across the 677 amino acid sequence of the GLB1 protein. Leucine (L) shows the highest abundance in the primary structure.

### Potential N-Glycosylation Motifs
* **Figure 2:** [View N-Glycosylation Motifs Plot](figures/GLB1_potential_N_glycosylation.png)
* **Description:** A linear coordinate plot mapping the positions of 7 predicted N-glycosylation motifs ($\text{N-X-S/T}$, where $\text{X} \neq \text{P}$) along the length of the GLB1 polypeptide chain.

  ## Questions

1. **What does your enzyme normally break down inside lysosomes?**
   * GLB1 normally hydrolyzes terminal beta-galactose residues from beta-galactosides, including glycosphingolipids (such as GM1 ganglioside), glycoproteins, and keratan sulfate.

2. **What is the total length of your protein, and which amino acids are most common?**
   * The total length of the MANE Select GLB1 protein  is 677 amino acids. Based on the amino acid composition analysis, Leucine (L) is the most abundant amino acid, followed by other residues like Proline (P) and Glycine (G).

3. **How many potential N-glycosylation motifs did you find? Where are they located?**
   * The analysis identified 7 potential N-glycosylation motifs ($\text{N-X-S/T}$, where $\text{X} \neq \text{P}$). Their exact residue positions are recorded in results/GLB1_motif_positions.csv and mapped across the sequence length as visualized in the N-glycosylation plot.

4. **Why can glycosylation matter for lysosomal proteins? Does finding a motif prove the protein is glycosylated?**
   * Glycosylation supports proper protein folding, structural stability, protection against proteases, and targeted intracellular transport. However, identifying a consensus motif (`N-X-S/T`) only highlights a potential site rather than confirming actual in vivo glycosylation, which requires experimental validation.
5. **What could happen in the cell if your enzyme did not work properly?**
   * If GLB1 is deficient or dysfunctional, its target substrates (such as GM1 ganglioside and keratan sulfate) cannot be degraded and instead accumulate progressively inside the lysosomes. This leads to lysosomal storage disorder(such as GM1-gangliosidosis), causing cellular engorgement, progressive organelle dysfunction, and eventual cell death.

  
